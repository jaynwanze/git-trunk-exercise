# 5. Bug fix

| Date | Phase |
| --- | --- |
|  February 5<sup>th</sup> | Bugfix |

This morning the project manager received a frantic call from the EIC of _Flavor_ magazine. The app was so successful that the writers have been inundated with emails from readers submitting their own recipes for consideration. The number of emails has been so great that their inboxes are completely useless. The magazine wants your team to remove the writers' email addresses from the app ASAP.

## :running: Activities


Follow along with the activities below to walk through the process of creating a bugfix branch, then merging the bugfix into both `main` branch.

### 1 - Create the Hotfix Branch

__One Team Member__

Create a branch off of `main` named `bugfix-emails`:
```sh
$ git checkout main
# switch to main branch

$ git checkout -b bugfix-emails
# create & switch to bugfix-emails branch
```

After removing the email addresses from the main page ([/app/index.md](/app/index.md)), stage and commit the change:
```sh
$ git add app/index.md

$ git commit -m "Remove email addresses from app"
```


### 2 - Publish the bugfix Branch and create Pull Request

Push the branch to origin (Github):

```sh
$ git push origin bugfix-emails
```

Navigate to your GitHub fork and open the pull request. On the Pull Request interface, make sure that the base fork is `your-username\git-trunk-exercise` and the base branch is `main`. This means that you are requesting to merge your changes into the `main` branch of your forked copy of the repository. 


### 5 - Accept Pull Requests

Open each Pull Request in the Github interface and click the green "Merge pull request" button. Once the bugfix is merged into `main` we can assume that the app is updated and the issue of writers receiving too much email is resolved.

Fetch the latest changes in main branch to your local device, like you did in [4. Fetching Latest](4-fetching-latest.md).


## Congratulations
You have completed all the steps of the exercise!

## Quick Links

- [Readme](../readme.md)
- [1. Setup](1-setup.md)
- [2. Feature Branches](2-feature-branches.md)
- [3. Code Review](3-code-review.md)
- [4. Fetching Latest](4-fetching-latest.md)