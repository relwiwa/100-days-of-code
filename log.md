# 100 Days Of Code - Log

### Day 9: January 11, 2017, Wednesday: MUC  

**Today's Progress**:  
Continued working on Voting App for Freecodecamp Certification:  
1. Setup a header component
2. Setup frontend part of poll creation functionality, including routes and PollService for managing polls component-wide
3. Got the title and plot for the Voting App: It's going to be called ''Decisions, Decisions''. And the plot will be a voting app for people undecided about something. And asking friends and the world to help them decide by voting. In another step, they could also give suggestions on alternatives to the options listed, but that will be beyond the scope of Freecodecamp's user stories.  

**Resources used**  
Continued to follow the steps shown in: [Angular 2 and NodeJS - The Practical Guide to MEAN Stack 2.0 (Udemy)] (https://www.udemy.com/angular-2-and-nodejs-the-practical-guide/),

**Open Questions**  
What's the difference between [ngModel] and [(ngModel)]?  

**Link(s) to work**  
Today's commits:  
1. [Create AppHeaderComponent] (https://github.com/relwiwa/fcc-voting/commit/897cd9d9bfa10b574f77ba608bcd04a49a9f0222)  
2. [Add frontend part of poll creation functionality, including route] (https://github.com/relwiwa/fcc-voting/commit/01b50b3db27e9031e0a14ddca59b4fa941cd97a3)  

### Day 8: January 10, 2017, Tuesday: ATH - MUC - TXL - MUC  

**Today's Progress**:  
1. Setup client-side components and services via angular-cli for Voting App.  
2. Setup server-side API routes for Voting App.  

**Resources used*  
Following the steps shown in: [Angular 2 and NodeJS - The Practical Guide to MEAN Stack 2.0 (Udemy)] (https://www.udemy.com/angular-2-and-nodejs-the-practical-guide/),

**Link(s) to work**  
Today's commits:  
1. [Create Angular components and services needed for voting app] (https://github.com/relwiwa/fcc-voting/commit/9d1159b39138486328d51ae14e93dda0d992af9d)  
2. [Create poll and user routes with dummy responses] (https://github.com/relwiwa/fcc-voting/commit/8fb4cb3758823ead195f114970dfd2e067e81a8d)  

### Day 7: January 9, 2017, Monday: ARN - MUC - ATH  

**Today's Progress**:  
Setup Mongoose schemas for Voting Aapp.  

**Link(s) to work**  
Today's commit: [Setup Mongoose schemas and export models] (https://github.com/relwiwa/fcc-voting/commit/bf31231e6143028a60cb20725385e7a2ce926189)  

### Day 6: January 8, 2017, Sunday: MUC - ARN

**Today's Progress**:  
1. angular-cli to the rescue: Setup MEAN-stack foundation for Freecodecamp Voting Backend Project using Angular2  
2. Configured deployment to Heroku  

**Thoughts**   
I used angular-cli to setup Angular2. Understanding and using Webpack is among my todos, but for now, using the client is really helpful.  

**Resources used**  
1. [Angular 2 and NodeJS - The Practical Guide to MEAN Stack 2.0 (Udemy)] (https://www.udemy.com/angular-2-and-nodejs-the-practical-guide/), [MEAN App with Angular 2 and the Angular CLI (Tutorial)] (https://scotch.io/tutorials/mean-app-with-angular-2-and-the-angular-cli)  
2. [Angular CLI Deployment: Host Your Angular 2 App on Heroku] (https://medium.com/@ryanchenkie_40935/angular-cli-deployment-host-your-angular-2-app-on-heroku-3f266f13f352#.tjc8rzgtu)

**Link(s) to work**  
1. Today's commits:  
[chore: initial commit from angular-cli] (https://github.com/relwiwa/fcc-voting/commit/ed84f958ae19a464fae408c44211a20e23e3e353)  
[Basic setup of express backend] (https://github.com/relwiwa/fcc-voting/commit/ba52876a186bc8e25a8d91f4d8e5ff1d88d91801)  
2. [Voting app on Heroku] (https://relwiwa-voting.herokuapp.com/abc)  

### Day 5: January 7, 2017, Saturday

**Today's Progress**:  
Finished work on Scatterplot Graph Challenge: Added more story elements to author-driven narrative. Published project on Codepen. 

**Link(s) to work**  
Scatterplot Graph Challenge for FreeCodeCamp:  
[Codepen](http://codepen.io/relwiwa/pen/ZLGKBX)  
[Github commit] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/5bd963319c67867e08cefcb35d943e22a1e8e15b)  

### Day 4: January 6, 2017, Friday

**Today's Progress**:  
Continued work on Scatterplot Graph Challenge: Added tooltips with hover effect to the scatterplot chart. This turned out to be the user-driven narrative of this chart. Also added an animation as author-driven narrative, focusing of high percentage of professional cyclists with doping allegations. 

**Thoughts**   
This time, I did not use intervals to create the animation, but D3's native transition function, that provides transition-specifc events. These enable altering various elements in the chart, not just the one currenty in transition. Took me a while to figure it out.  

**Resources used**  
[D3 transition documentation] (https://github.com/d3/d3-transition)  

**Link(s) to work**  
Today's Scatterplot Graph Commits:  
[Add tooltips and hover effect] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/b1b9764a5216682a0174afe33f0e5424e3c69635)  
[Add author-driven narrative] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/11c49251571e7d5fa9e54e67ebcd444293c219ee)  

### Day 3: January 5, 2017, Thursday

**Today's Progress**:  
Continued work on Scatterplot Graph Challenge: Added x-axis after battling with Dates in Javascript. Also added the data circles to the chart. More tomorrow.  

**Thoughts**   
Today I (again) wrestled with dates and times in Javascript. In order to calculate the difference in minutes and seconds, I set the other date components to a fixed value.  

**Resources used**  
[Mike Bostock on formatting time axis with hours and minutes] (http://stackoverflow.com/questions/11286872/how-do-i-make-a-custom-axis-formatter-for-hours-minutes-in-d3-js)  

**Link(s) to work**  
Today's Scatterplot Graph Commits:  
[Add x-axis and helper functions for time calculations] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/2e6846eedce169330fd9a0808488747dd3edacf1)  
[Add circles to chart] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/6bc20e77930f3a576001d5510f48f96b6146e56f)  


### Day 2: January 4, 2017, Wednesday

**Today's Progress**:  
1. Reorganized Git/Github repository using git's filter-branch functionality and submodules  
2. Setup Gulp to automate tasks during production and creating productive distribution  
3. Started with FreeCodCamp's Scatterplot Graph Challenge, changing from D3's version 3 to version 4  

**Thoughts**   
Today I learned that it's possible to filter commits using Git's filter-branch functionality. I was never really happy with not being able to create a hyrarchical structure using Github in an easy way. So today, I decided to put every single project in its own repository resulting in tons of repositories. But also, to use submodules to organize them a little better.  

**Resources used**  
1. [Git's filter-branch functionality] (https://git-scm.com/docs/git-filter-branch), [Git's submodule functionality] (https://git-scm.com/book/en/v2/Git-Tools-Submodules)  
2. [Udacity's course on Web-Tooling and Automation](https://de.udacity.com/course/web-tooling-automation--ud892)  
3. [What's new in D3 v4] (https://iros.github.io/d3-v4-whats-new)  

**Link(s) to work**  
1. [Re-organized Data Visualization Repo](https://github.com/relwiwa/fcc-data-viz)  
2. [Bar Chart project using Gulp] (https://github.com/relwiwa/fcc-bar-chart/commit/fcdffa3b1c2762e26ea23deb77ae86801ae08959), [Scatterplot Graph project using Gulp] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/186f9492d5e73c2c74d6bbe8431d002324a1f1cf)  
3. [Scatterplot Graph project] (https://github.com/relwiwa/fcc-scatterplot-graph/commit/186f9492d5e73c2c74d6bbe8431d002324a1f1cf)  

### Day 1: January 3, 2017, Tuesday

**Today's Progress**:  
1. Reorganized (spaghetti) code of my first D3 diagram into separate files with reusable objects  
2. Setup 100 Days of Code Repository and re-familiarized myself with Wiki-Markup (two spaces for a new line ;-)

**Thoughts**  
I finished my first chart in pure D3. Before, I worked through Udacity's D3 and Data Visualization course and I'm glad to see that the combination of tutorials and practice works out fine for me - in spite of the mission statement of 100 Days of Code. Nevertheless happy to focus on code practice for the next 100 Days of Code and move on with FreeCodeCamp's Certification.

**Link(s) to work**  
1. Visualize US GDP data with a (D3) bar chart:  
[Codepen](http://codepen.io/relwiwa/full/zoVjxJ)
[First Git Commit]  (https://github.com/relwiwa/fcc-bar-chart/commit/aa560170702602b4dd583957c20a0bc5bf514887)
[Second Git Commit] (https://github.com/relwiwa/fcc-bar-chart/commit/fcb9b0f6b4f5b6dde64700ce630dbd01781800fb)  
2. [My 100 Days of Code Repository] (https://github.com/relwiwa/100-days-of-code)