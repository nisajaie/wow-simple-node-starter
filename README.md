@WalmartLabs Node.js Starter Template
===

A simple Node.js + Materialize + Jade template project that is ready to deploy to Heroku. This application is optional to use, but please follow the final submission instructions for all applications.

# Table of Contents
- [Set-Up](#set-up)
- [Usage](#usage)
- [Coding](#coding)
- [Final Submission](#final-submission)
- [Judging Criteria](#judging-criteria)
- [Job Openings](#job-openings)

# Set-Up
- [ ] Create a GitHub Account: https://github.com/
- [ ] Git Set-Up: https://help.github.com/articles/set-up-git/
- [ ] Node and npm Installation: https://www.npmjs.com/get-npm
- [ ] Create Heroku Account: https://signup.heroku.com/dc
- [ ] Download Heroku CLI: https://cli.heroku.com/
- [ ] Download an IDE. Check out the recommended ones: 
    - Sublime Text 3: https://www.sublimetext.com/3
    - Visual Studio Code: https://code.visualstudio.com/

# Usage
1. **Fork your repository** - Have 1 person from your team fork the repository so that you have a copy of the codebase you can freely modify without affecting the original: https://help.github.com/articles/fork-a-repo/. 
    - Note: A forked repository will look like https://github.com/[YOUR_USERNAME_HERE]/wow-simple-node-starter

2. **Clone your repository** - Each team member will clone a copy of this forked repository onto their desktop to work on individually. That way, everyone can work on their project individually and eventually merge: https://help.github.com/articles/cloning-a-repository/
    - Open up a terminal and navigate to the directory where you wanted your cloned directory (folder) to be made: https://www.codecademy.com/articles/command-line-commands
    - `git clone https://github.com/[YOUR_USERNAME_HERE]/wow-simple-node-starter.git`
    - `cd wow-simple-node-starter`

2. **Install** - Verify that you have the correct node version and then install the application. Verify your node version by entering `node -v`. Your node version should be *4.26* or above. Then do a `npm install` to install the app.
  
3. **Start the app** - Once it has finished installing, run the application by entering `node app`. Do a Ctrl+C if you ever want to stop the application.

4. **View the app** - Open up your browser and go to http://localhost:3000. If you can view the app successfully, you're ready to make your own changes and go! Open up your text editor, open up the directory your repository is located, and start coding!     - Try experimenting with the values in the `views`, such as changing the text in `views/index.jade`
    - Don't worry too much about the other folders (`node_modules`, `bin`, `routes`) but don't delete them because they are necessary to deploy to Heroku.
    - Once you've made a change, simply hit save in your text editor. Go back to http://localhost:3000 and your change should be there. Happy coding!
    
# Coding
1. How to use GitHub add, commiting, branching, PRs?
- Get data, the [Walmart way](https://developer.walmartlabs.com/)
- Don't get too deep into the coding and forget one of the biggest parts - presentation. If you are submitting a presentation powerpoint, please use Google Slides rather than a desktop powerpoint application. See below for Final Submission instructions and Judging Criteria.
- Have fun!

# Final Submission
You will be deploying your final base application to Heroku, a platform to host your application. You will be submiting the Heroku application for the final submission. *Please only make 1 submission per team.*
https://devcenter.heroku.com/articles/deploying-nodejs#deploy-your-application-to-heroku

1. Once you're ready to go, do `heroku login` and enter in your credentials.
2. Do a `heroku create` and then a `git push heroku master`
3. Do `heroku open` to open up your application. A browser should open up with your app.
4. Grab the link of your app and submit your app here: https://goo.gl/forms/APIvHIbkVN5ehcOi1
5. Congratulations! You're done!

# Judging Criteria
### Innovation / Ambition
- How unique is it? Is this something that has been done before?
- How well did the developers research potential competitors in order to create a new solution?
- How feasible was the application given the constraints of the hackathon?
- How well did the application fit in the constraints of the given themes?
### User Interface/ User Experience
- Given the time frame of the hackathon, how user friendly is the prototype?
- How intuitive is the application to someone using it for the first time?
- Was there a lot of planning (e.g. wireframes, sketches, etc.) ahead of time?
- Regardless of functionality, was the prototype well-designed and aesthetically pleasing?
### Quality
- How functional is the application given the time frame of the hackathon?
- How well-tested is the code that was written?
- Are there visible bugs or obvious flaws in the presentation of the application?
### Presentation
- How well did the individual or team present the app to the audience?
- Did the presentation involve an introduction, a problem, and a demonstration of the application?
- How well-defined is the problem? How well did they address the prompt?

# Job Openings
Check out our job openings! Feel free to ask any of the @WalmartLabs volunteers questions about what it's like to work at Walmart.
- [**Sr. Backend Software Engineer**](https://careers.walmart.com/us/jobs/816082BR-senior-backend-software-engineer-carlsbad-ca)
- [**Staff Backend Software Engineer**](https://careers.walmart.com/us/jobs/816029BR-staff-software-engineer-be-engineer-carlsbad-ca)
- [**Staff Frontend Tools Engineer**](https://careers.walmart.com/us/jobs/816064BR-staff-fe-tools-engineer-san-bruno-ca)
- [**Staff Mobile Tools Engineer**](https://careers.walmart.com/us/jobs/844209BR-staff-mobile-tools-engineer-carlsbad-ca)
- [**Principal Technical Project Manager**](https://careers.walmart.com/us/jobs/867179BR-principal-technical-project-manager-sunnyvale-ca)
 
# About
This starter was inspired by the [Node.js Material Starter Template](https://github.com/primaryobjects/Node.js-Material-Starter-Template), but updated for Heroku deployment, Materialize + Express routes.
Here is an [example app](https://wow-hackathon-example-app.herokuapp.com/) using this starter + the Walmart Open API. You `may need` this help chrome tool to view the data in this example app - [Allow-Control-Allow-Origin](https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en-US).
