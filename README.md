# Fork a Repo & Create Your First Blog Challenge

## Fork the repo `HTML-CSS-Template` from the NGEN Room Org
1. __On your github account__ go to this link [HTML-CSS-Template](https://github.com/NGEN-Room/HTML-CSS-Template) 
2. Fork this repo ( click the fork in the top right corner or reserach how to fork )

## Rename your HTML-CSS-Template repo
1. make sure you are in the `HTML-CSS-Template` repo (on github if you click the arrow near your profile find 'your repositories')
2. Go to the settings button 
3. Rename your repo exactly like this `your-user-name.github.io` for example
```
Te-Piha.github.io ( my username is Te-Piha)
``` 
note this is important as the github pages will need this to work.

## BEFORE YOU CLONE YOUR REPO
1. In your command line you must make sure you are accessing `YOUR` email and name when going forward. To make sure you are logged in the command line:
```
1. git config --global user.name Te-Piha
2. git config --global user.email t.niha@ngenroom.co.nz
```
_Note: The reason we are checkon this is because you want to make sure you are the correct person pushing the correct information up to your github_

## Clone Your Repo 
1. __In Your command line__ cd (change directory) into the workspace directory on your desktop. Your command line should look like this:
```
User/Te Puna Marama Trust/Desktop/Workspace
```
__Important!__ Clone your repo into your Workspace folder ( this should have been done yesterday but if it wasnt `make directory` on the Desktop called 'Workspace'. you will be using workspace as your main local hub for coding)

__Also Important!__  
Make sure you never clone into another repo
``` 
For a Good example:
`User/Te Puna Marama Trust/Desktop/Workspace/no-hea-koe`     
`User/Te Puna Marama Trust/Desktop/Workspace/Te-Piha.github.io` 

And a Bad example:
`User/Te Puna Marama Trust/Desktop/Workspace/no-hea-koe/Te.github.io` 
``` 
In the bad example you can see that i have put my `Te-Piha.github.io` repo into my `no-hea-koe` repo versus having a main parent directory `workspace` and storing all my different repos inside that one


2. Clone down your new repo
3. Check that your repo is in the workspace by hitting `ls` in the command line to list out everything in that directory


## Add temporary html to your index.html
1. __In Your command line__ cd into your new repo 
2. Open the code in the repo `code .` ( the `full-stop` in this commmand will open all the files, in the current directory, in VS Code )
3. Add the below text to the index.html file and __save it__

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="this-is-a-css-class"> 
    <h1> Kia ora! This is your first blog page!</h1> 
    <h2> I will use this page to store my technical blogs and Reflection blogs </h2>
  </div>
  <p> I will also be able to use this blog space as a way to show my creativity and build my own blog.
    Chuurrr!
  </p>

</body>
</html>
``` 
## Commit and Push 

1. __In Your command line__ Commit and Push your changes to GitHub

## Connect your repo to github pages
2. __In Your browser__ head to your repositories on github and go into your repo you just pushed to `your-user-name.github.io`
3. Enter the settings menu for that repo and scroll down to the GitHub Pages section
4. Under the `Source` option, select the master branch
5. __Congradulations!__ You can check out your live repo by visiting `your-user-name.github.io`


_Note: There will be a delay from when you push your changes to github and actually showing up on your url_

## Step 5: Technical + Reflection Blog
We will be using everything that you have learn and storing them in a student jounral!
1. clone student journal down to your workspace folder
2. cd into the repo `student-journal`
3. branch the repo naming `your-name-student-journal`
4. open the files in vscode ( in command line hit `code .`)
5. fill out the technical and reflction folders 
6. commit and push your changes up back into github

