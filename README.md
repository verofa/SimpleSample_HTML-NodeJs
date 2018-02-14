## How to build a Simple Node.js application using a cloud platform as a Service solution (PaaS)

In this sample we are going to create a simple application to build a project using a particular cloud solution called [Heroku (Saleforce)](https://www.heroku.com/) based on a platform as a services more commonly known as **PaaS**. 

### Prerequisites

To start the exercise you need to have installed/created the following components:

1.- Email account (for linking it with Heroku account)  
2.- Heroku account
3.- If you are using Unix-like platform, a Package Manager and depending of the OS:
3a.- MacOs: Homebrew  
3b.- Linux (Debian/Ubuntu based systems): apt-get/aptitude
4.- Heroku Command Line Interface (CLI)  
5.- Node.js and npm  
6.- Git bash  
7a.- Powershell or cmd (Microsoft Windows Command Prompt) if you are using a windows platform  
7b.- Terminal prompt id you are using a Unix-like platform (MacOs or Linux)  
8.- Simple Text editor (for instance, Notepad, Notepad ++)  


## How to do it ^

1.- **Creating an email account**:  
As a suggestion you can create an [Gmail](https://en.wikipedia.org/wiki/Gmail) account that has a free basic service [here](https://accounts.google.com/SignUp), but feel free to create an email account in your favorite email service
*If you already have an account that you can/want link with the Heroku account, this steps is an alternative one and you do need to create a new one.

2.- **Creating an Heroku account**:  
For creating an Heroku account you just need to have an email account and provide the necessary information as your name, country and the development language (in this case you have to chose node.js) [here](https://signup.heroku.com). 

3.- **Installing the Package Manager**:  
This step only apply if you are using a *MacOS* system since in a Linux platform normally the package manager is already install by default.  
To Install Homebrew, open the Terminal Command Line and run:

```javascript
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
``` 

4.- **Installing Heroku Command Line Interface**:  
Once you have the Heroku account created you have to install the Heroku Command Line tool for creating and managing Heroku applications from the command line / shell.
  
-  For **MacOs** open a terminal command line and run:  

```javascript
brew install heroku/brew/heroku
```

- For **Debian/Ubuntu** run the following to add our apt repository and install the CLI:

```javascript
wget -qO- https://cli-assets.heroku.com/install-ubuntu.sh | sh
```

5.- **Installing Node.js and npm**:  
For the training purpose we are going to use **Node.js** as a program language and **npm** as the package manager that is used by **Node.js**.

- For **Microsoft Windows** platform get the proper installer from https://nodejs.org/en/download/ . Normally the Windows Installer (.msi) 64-bit version

- For **MacOS** platform using Homebrew, open a terminal command line and run: 

```javascript
brew install node
```

Also, as an alternative way you can get the proper installer as well from https://nodejs.org/en/download/ (macOS Installer (.pkg))

- For **Debian/Ubuntu** platform open a terminal command line and run:

```javascript
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```

- To check the installation run in your terminal command line:

```javascript
# Node.js version
node -v
# nmp version
npm -v
```





