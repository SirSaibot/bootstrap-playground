# Bootstrap Playground

## Host the Webpage locally
Inorder to see the webpage working and with all function skip the *Getting started* part and go to the [*local Hosting*](#local-hosting) part and download this current or this [sample repository](https://github.com/SirSaibot/bootstrap-playground) and use it instead of forking your own repository. 

## Getting started <a name="gettingstarted"></a>
### Installing needed programms

First of you need to install some programms incase you don't already have them:
- NodeJS (https://nodejs.org/en/download)
- Github Desktop (https://desktop.github.com) or Git (https://git-scm.com/downloads)

Other optional programms I recommend:
- VisualStudio Code (https://code.visualstudio.com/download)
- a nice Browser (not Internet Explorer or Microsoft Edge)

After downloading and installing everything, you want to go to the [boostrap-playground repository](https://github.com/stetsche/bootstrap-playground) (https://github.com/stetsche/bootstrap-playground) and in the top-right click on the Fork button.
![image of button](readme-img/Fork.png)

On the page that opens you can change the owner, name and description but it's recommended to leave everything as it is and press *create fork*.
After a few seconds it should be done, now you can look at your own repositories and there should be a new one named *bootstrap-tutorial* (if you didn't change the name).

This tutorial is for GithubDesktop only. It is very much possible archive the same with Git or similar options but this guide focuses on GithubDesktop.

### GithubDesktop
Once you have opened GithubDesktop, there should be the option to open one of your repositories. Choose the just forked repository. After a couple of seconds everything should be ready. 

If you did not install Visual Studio you can skip the next step and open the files index.html and style.css manually in other programms like notepad.

### Visual Studio
Open VisualStudio and on the top left click on *Explorer*. There should be the option to open a folder. Click on that and the navigate towards the local path of the just created repository. Afterwards you should see some files and folders coming up on the left side. Open index.html and style.css by simply clicking on them. 
Now you can freely edit the html and css file towards your liking. Inorder to see your work displayed as if it was a real webpage proceed to the next step.

## local Hosting <a name="localhosting"></a>
### Configure node.js
Navigate towards the repository and copy its path (e.g: "C:\Users\User\Documents\GitHub\bootstrap-playground"). Open cmd by pressing Win + r, typing `cmd` and pressing enter. In the just opend window type `cd ` followed by the just copied path.
Example:

![image of cmd](readme-img/cmd.png)

Press Enter and then type:

`npm install`

and press Enter. After a few minutes the installation should be complete. You can do the next step in the same window. From now on just do the next step, you don't need to do this step again.

### Start local hosting
In the cmd window with the path of your folder (where the index.html file is located), type:

`npm run dev`

and press Enter. Now there should be a URL with localhost like this:

![image of npm](readme-img/npm.png)

Press on the *o* -key and a window in your default browser should open displaying your index.html page. The page automatically refreshes everytime you save some changes to any of your files.