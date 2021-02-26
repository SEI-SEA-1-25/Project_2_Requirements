# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #2: Building Your First Full-stack Application

### Overview

This second project is your first foray into **building a full-stack application.** You'll be **server side rendering app** with *express, node, postgres, and ejs.* This means you'll learn about what it takes to build a functional application from the ground up yourself.

**This is exciting!** And you get to be creative in choosing what sort of application you want to build! [Check out](https://gawdiseattle.gitbook.io/wdi/11-projects/past-projects/project2) some past p2s!

**You will be working individually for this project**, and you'll be designing the app yourself. We hope you'll exercise creativity on this project and have fun! Make sure you run your ideas by your instructors in your pitch to get their feedback before you dive too deep into code! Remember to keep things small and focus on mastering the fundamentals -- scope creep/feature creep is the biggest pitfall for any project!

---

### Technical Requirements

Your app must:

* **Have at _least_ 2 models** (more if they make sense) that represents the main functional idea for your app. _This doesn't include join tables or the user model which is needed for user auth._
    * Note: If your app idea doesn't really call for more models, let your instructors know and they can suggest ideas for other sufficiently difficult replacements for this requirement.
* **Include sign up/log in functionality**, with hashed passwords & an authorization flow
* **Incorporate at least one API.** _a list of useful API resources can be found below, along with advice on choosing a good API for your project_.
* **Have complete RESTful routes** for at least one of your resources with GET, POST, PUT, and DELETE
* **Utilize the sequelize ORM to create a database table structure** and interact with your relationally-stored data
* **Include a readme file** that explains how to use your app
* Have **semantically clean HTML, CSS, and back-end code**
* **Be deployed online** and accessible to the public. _We will have a deployment jam during project week prior to presentations._

---

### Necessary Deliverables

* A **working full-stack application, built by you**, hosted somewhere on the internet
* A **link to your hosted working app** in the URL section of your Github repo
* A **git repository hosted on Github**, with a link to your hosted project,  and frequent commits dating back to the **very beginning** of the project. Commit early, commit often.
* **A ``readme.md`` file** that includes the following:
  * a Descirption of the app
  * a link to the live site
  * installation instructions
  * user stories
  * explanations of the technologies used (including APIs)  
  * wireframes
  * a RESTful routing chart 
  * database ERDs
  * mvp goals
  * stretch goals
  * daily sprints
  * the approach taken
  * unsolved problems
  * sources used 

---

### How to Get Started

* Begin by researching and exploring APIs that you could use in your app for inspiration while you formulate an idea
  * Use **postman** and **axios** to interact with an API before you decide to use it in your app
  * when choosing an API, _make sure it is a suitable for your project,_ consider the following:
    * does the API require any complicated steps to get an API key? _Are they too complex or slow (takes several days or longer to get a key) for your project?_
    * **DO NOT** pick an API that requires OAuth! _APIs that require OAuth will take up too much time to configure for your p2!_
    * Is is API free? _Does it limit the amount of calls that can be made to it?_
    * Is the API reliable? _Are the responses from the API consistent?_
    * When recieving data back from an API explore it and consider how you could your it in your project.
    * You should have successfully gotten an API key and interacted with it before choosing to use it in your project.
  * [Here](https://github.com/public-apis/public-apis) is a list of free APIs to checkout
  * [Here](https://apilist.fun/) is a collection of APIs for projects
  * [Here](https://www.programmableweb.com/) is an website that lets you search APIs by subject
  * The [gitbook](https://gawdiseattle.gitbook.io/wdi/12-resources/apis) has some useful resources as well.
* Create wireframes and go through a project planning process. Consider what are your:
    * Goals for each 'sprint' -- _what you plan on accomplishing on a daily basis between pod standups._
    * MVP -- _your focus should be on making a MVP with a clean codebase before adding stretch goal features._
    * Stretch Goals -- _extra features you would like to include after you hit MVP._
* Map your database relationships in an **ERD**.
* Plan your routes! _Create a RESTful routing chart for your app that you can reference while working._ 
* **Begin with the end in mind.** Know where you want to go by planning with wireframes & user stories, so you don't waste time building things you don't need
* **Don't hesitate to write throwaway code to solve short term problems**
* **Read the docs for whatever technologies you use.** Most of the time, there is a tutorial that you can follow, but not always, and learning to read documentation is crucial to your success as a developer
* **Commit early, commit often.** Don't be afraid to break something because you can always go back in time to a previous version.
* **User stories define what a specific type of user wants to accomplish with your application**. It's tempting to just make them _todo lists_ for what needs to get done, but if you keep them small & focused on what a user cares about from their perspective, it'll help you know what ot build
* **Write pseudocode before you write actual code.** Thinking through the logic of something helps.

---

### Useful Resources

* **[Heroku](http://www.heroku.com)** _(for hosting your back-end)_
* **[Writing Good User Stories](http://www.mariaemerson.com/user-stories/)** _(for a few user story tips)_
* **[Presenting Information Architecture](http://webstyleguide.com/wsg3/3-information-architecture/4-presenting-information.html)** _(for more insight into wireframing)_

---

### Project Feedback + Evaluation

* __Project Workflow__: Did you spend an adequate amount of time on the planning process? Did you use source control as expected? Are your commit messages clear? Do you have a readme file?

* __Technical Requirements__: Did you deliver a project that met all the technical requirements? Given what the class has covered so far, did you build something that was reasonably complex?

* __Creativity__: Did you added a personal spin or creative element into your project submission? Did you deliver something of value to the end user (not just a login button and an index page)?

* __Code Quality__: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code as your instructors as we have in class?

* __Problem Solving__: Are you able to defend why you implemented your solution in a certain way? Can you demonstrated that you thought through alternative implementations? _(Note that this part of your feedback evaluation will take place during your one-on-one code review with your instructors, after you've completed the project.)_

* __Total__: Your instructors will give you a total score on your project between:

| Score | Expectations | Evaluation Criteria |
| ----- | ------------ | ------------------ |
| **3** | _Exceeds expectations, you wonderful creature, you!_ | **Solid MVP + Stretch Goals**
| **2** | _Meets expectations, good job!_ | **Solid MVP -- meets all technical requirements** 
| **1** | _Does not meet expectations._ | **No MVP -- missed some technical requirements**
| **0** | _Incomplete._ | **Not Passing -- missed most or all technical requirments and MVP**

 This will serve as a helpful overall gauge of whether you met the project goals, but __the more important scores are the individual ones__ above, which can help you identify where to focus your efforts for the next project!

