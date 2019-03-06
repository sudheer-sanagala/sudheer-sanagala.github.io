# Dev Landing Page

How to create a simple landing page for developers

## Intial setup

- Create a new repo `username.github.io` on github.com

- Create an empty folder on your local machine and name the folder as `username.github.io`

- Clone the contents of this [repo](https://github.com/flexdinesh/dev-landing-page.git) to a different location in your local machine and copy the contents to your `username.github.io` folder

- Modify the contents of `index.html` page to your liking

## Deploy to github pages

- User pages are defaulted to `master` branch in the repo

- Initialize your local folder `username.github.io` using `git init`

- Now commit the changes in `index.html` using `git add .` and `git commit -m "Initial Commit"`

- Now add the remote github url to push the changes using `git remote add origin https://github.com/sudheer-sanagala/sudheer-sanagala.github.io.git`

- Push the changes to github using `git push -u origin/master`

- Github will ask for user credentails of the repo. Once entered the changes will be pushed to remote github repo

## Updating github pages

- Make changes to the files in the `username.github.io` in your local machine

- After making changes, commit all the change locally using `git add .`

- Now commit using `git commit -m "commit message"`

- Now push the changes using `git push` and provide repo credentials
