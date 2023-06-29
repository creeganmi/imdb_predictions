# imdb_predictions


<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="300"/>
</div>
 
<div align="center"> 
 <h2> Hi everyone, welcome to a new ML project repo for IMDB movie predictions! <h2>
</div>
 <h3> Objective: Use the publicly available IMDB Datasets located on https://www.imdb.com/interfaces/ to build a model that predicts a movie’s average rating. I am not pull in any outside information (only these files)<h3>
   
<div align="center">
 <h3> If you are interested in collaborating on a project feel free to send me a message <h3>
</div>

<h3> 🤝🏻 &nbsp;Connect with me </h3>

<p align="center">
<a href="https://www.linkedin.com/in/michaelcreegan"><img src="https://img.shields.io/badge/-Michael%20Creegan-0077B5?style=flat-square&logo=Linkedin&logoColor=white"/></a>
<a href="mailto:creegan.mi@gamil.com"><img src="https://img.shields.io/badge/-creegan.mi@gmail.com-D14836?style=flat-square&logo=Gmail&logoColor=white"/></a>

<div id="header" align="center">
 <h3> Getting Started with a virutal environment <h3>
</div>
  
My commands are in linux, for windows instructions, click [here](https://www.geeksforgeeks.org/creating-python-virtual-environment-windows-linux/)
   
 1. Clone repo into IDE
 2. Go into repo folder in your terminal. In VS Code you can hit ctrl + ` to open the terminal and enter 
  ```
  cd /path/to/repo
  ```
 3. Create a virtual environment inside of the repo by running: 
  ```
  python3 -m venv venv
  ```
 4. Install dependencies by running: 
  ```
  pip install -r requirements.txt
  ```
 5. You can activate your virtual environment by running: 
  ```
  source /venv/bin/activate ... on windows I believe the command is \venv\Scripts\activate
  ```
 6. Congrats! You have created and activated your new virtual environment! You should be able to run anything without having differing results/issues due to pacakge versions. 
 7. You can deactivate your virtual environment anytime 

<div id="header" align="center">
 <h2> Getting Started without a virutal environment <h2>
</div>
 1. Clone repo into IDE

<div id="header" align="center">
 <h2> Working branches <h2>
</div>
 <h3> You should create your own branch and work on it before merging into prod if working on open source files (not your own file) <h3>
 <h3> To create a branch you do the steps below. I will follow a convention of feature/{lastname}-{what-im-working-on} for consistency <h3>

 1. Create branch: Open terminal and run 
   ```
   git checkout -b feature/creegan-spotify-analysis
   ```
 2. Track main branch: Run: 
  ```
  git branch --set-upstream-to=origin feature/creegan-neural-network
  ```
 3. Make changes to your file
 4. Save changes
 5. Run 
  ```
  git add /path/to/file(s)
  ```
  or too add everything run
  ```
  git add -A
  ```
 
 6. Run 
  ```
  git commit -m "message explaining your changes"
  ```
 7. git push
 8. You can review your changes in the browser or just run git merge but I highly recommend reviewing in the browser before merging
 9. Merge changes into main
