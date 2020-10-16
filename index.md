## Welcome to BowfolioApp

# TABLE OF CONTENTS
***
* [OVERVIEW](#overview)
* [PROGRESS + DEVELOPMENT](#progress--development)
* [USER GUIDE](#user-guide)
* [DEVELOPER GUIDE](#developer-guide)

<br/>

# OVERVIEW
***
The native mobile app that reimplements the functionality of the <a href="https://bowfolios.github.io/">BowFolios</a> application. Users can modify profiles, projects, and interests and they can also browse other's profile and project to see if they have the same interests with users. This App is build with Swift and firebase. It is for IOS platform only.

# PROGRESS + DEVELOPMENT
***

Track the team's progress via Milestones:
* <a href="https://github.com/trigeeks/bowfoliosApp/projects/1">M1</a>
* <a href="https://github.com/trigeeks/bowfoliosApp/projects/2">M2</a>
* M3 (We finished implementation of our app in M2)

<br/>

# USER GUIDE
***
This section provides a brief walkthrough of the Bowfilios App user interface and its functionality.

## Sign In View
sign in with your email, users can tap the Eye Button to control of showing the password or not. If you do not have an account, you can press "Register" Button down below.

<img src="doc/signin.png" width="40%" alt="Sign In View">

## Sign Up View
If you do not have an account, you can click sign up to register. Same as Sign In View, you can tap the Eye Button to control of showing the password or not. After sign up, you will be directly send to our home view.

<img src="doc/signUpView.png" width="40%" alt="Sign Up View">

## Home View
There are four views inside Home View, users can slide left or right to switch view or just click the menu button to switch the views. The user button on the top right can trigger a sub-menu which will lead to Edit Profile View and Add Project View.

![homeView](https://media.giphy.com/media/bI8FrAHDv9cZDz36Hj/giphy.gif)

### Profiles View
Users can see other people's profile which shows name, title, bio, interests and projects they participate in. Users can taped on the projects' image to browse the detail of that particular project.

<img src="doc/profileView.png" width="40%" alt="Profiles View">

### Projects View
Users can see all the exist projects, which show name, description, interests and participants. Users can taped on the participants' image to browse the detail of that particular user's profile.

<img src="doc/projectView.png" width="40%" alt="Projects View">

### Interests View
Users can see all the interests with users and projects under that interest. Users can taped on the project's image or profile's image to browse the detail of that particular project or profile.

![interestView](https://media.giphy.com/media/T9PiTTL7740eeoUJFx/giphy.gif)

### Filter View
Users can user filter to choose interests to show and see who has that interest. Users can tap that right arrow button to open the selection. after selecting interest, users should tap onthe arrow button again to close the selection list and the profiles of users under that interest will be show. Users can also quick select all or clear all by tapping the buttons.

![filterView](https://media.giphy.com/media/zuIr6ckfeJu41ZL18E/giphy.gif)

### Edit Profile View
User can edit their own profile by tap the button on the top right, then tap My profile. Users can change their picture, name, bio, interests and projects.

<img src="doc/editProfileView.png" width="40%" alt="Edit Profile View">

### Add Project View
User can add a new project to the database and they must input enough information to create a new project.

<img src="doc/addProjectView.png" width="40%" alt="Add Project View">

# DEVELOPER GUIDE

First, install the latest version of XCode.

Second, clone the <a href="https://github.com/trigeeks/bowfoliosApp">repo</a> to your local computer. You can run the app by using either the XCode Simulator or an iPhone with the latest version. (Caution: Using the camera function on a simulator will cause a crash.)





