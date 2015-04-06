# Pennywhale Workflow

We rely on [Asana](http://asana.com/) and the [git flow branching model](http://nvie.com/posts/a-successful-git-branching-model/) which I'll briefly go over below.

## How we use Asana

We have three types of tasks in Asana, **features, bugs, and hotfixes**. Each tasks is assigned an hourly estimate, which is how long it should take to finish that task. You'll get paid at a set rate based on this hourly estimate.

We'll be creating weekly sprints of 10 hours of work every week. If you want more work, let us know and we'll be happy to increase the size of the sprint. Each task in the sprint will be tagged with the sprint number so it's easy to find all tasks in the sprint.

### Git branches

* The **master** branch is always code that is ready to be deployed
* The **develop** branch is the updated development code
* We create **feature, bug, and hotfix** branches for each individual task

Feature, bug, and hotfix branch names are formatted as follows: `feature/30926900144980-sample-feature-here`. `feature/`will change depending on the type of branch. `30926900144980` is the id of the task, which can be found by clicking on the task and looking at the location bar of your browser. The url will look like `https://app.asana.com/0/30926900144978/30926900144980`, and it's the last digits after / that we need. `sample-feature-here` is just a short description of what the feature/branch/hotfix is for readability.

After completing a task, push that branch to github and open a pull request requesting to merge that branch with **develop**. Once it's merged in, we'll mark that task as complete.


## Payment, what we expect, and what you can expect

We expect you to work at least 10 hours a week. If you want more work, we'll be happy to increase the size of the sprint. You'll be paid once every two weeks for all work completed in the past two weeks (at least 20 hours). 
