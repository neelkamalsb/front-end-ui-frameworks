<h2> Git Setup Notes </h2>
<ul>
<li>In this exercise you will learn to install Git on your computer. </li>
<li>Git is required for using all the remaining Node.js and Node based tools that we encounter in the rest of the course.</li>
<li>At the end of this exercise, you would be able to:
    <ol>
    <li>Install Git on your computer</li>
    <li>Ensure that Git can be used from the command-line or command-prompt on your computer</li>
    <li>Set up some of the basic global configuration for Git</li>
    </ol>
 </li></ul>

<h3>Downloading and Installing Git</h3>
<ol>
<li>To install Git on your computer, go to https://git-scm.com/downloads to download the Git installer for your specific computing platform.
<li>Then, follow the installation steps as you install Git using the installer.
<li>You can find more details about installing Git at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git. This document lists several ways of installing Git on various platforms.
<li>Installing some of the GUI tools like GitHub Desktop will also install Git on your computer.
<li>On a Mac, setting up XCode command-line tools also will set up Git on your computer.
<li>You can choose any of the methods that is most convenient for you.


<h3>Some Global Configuration for Git</h3>

* Open a cmd window or terminal on your computer.
---
* Check to make sure that Git is installed and available on the command line, by typing the following at the command prompt:<br>
   ```git --version```
---
* To configure your user name to be used by Git, type the following at the prompt: <br>```git config --global user.name "Your Name"```
---
* To configure your email to be used by Git, type the following at the prompt:<br> ```git config --global user.email <your email address>```
---
* You can check your default Git global configuration, you can type the following at the prompt: <br>
```git config --list```
---
