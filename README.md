# Hosting Flip

## Working with github

### Setup Git and github

1. Open [Github](https://github.com/)
2. Sign up
3. Downloading [Git](https://git-scm.com/downloads)
4. Open *Git Bash* and configure your email and username 
```
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
```

### Upload your code on github

1. Open the folder that you wish to put on github on Git Bash
```py
cd C:\Users\User\Documents\Projects\...
```
2. Initialize a git repository on that file
```
git init
```
3. Create a project on [github](https://github.com/new) and copy the code
4. Add a remote origin to that project
```
git remote add origin "https://github.com/Username/project-name.git"
```
5. Add the files
```
git add .
```
6. Commit the files with a message
```js
git commit -m "Some message"
```
7. Push the files to github
```py
# git push --set-upstream origin master
git push
```
8. Your project should now appear in your github

## Web Hosting

### Hosting static project on github

Static project would be a pure HTML, CSS and JS project, not including any frameworks like react etc.

1. Upload your project to github
2. Open the project on github
3. Go to settings > pages and save it for github pages
4. Your project should be up on github in a few minutes

### Hosting on Vercel

For projects that use a framework like vite, react, nextjs etc. (or you could host static pages as well)

1. Create an account on [vercel](https://vercel.com/) (preferrably with your github account)
2. Add a new project
3. Find the project you want to add from your github
4. Import that project, choose the same framework used for the project and then deploy
5. With no errors, your project should be deployed on vercel
