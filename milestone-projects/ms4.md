# MILESTONE #4 :

### MANDATORY REQUIREMENTS
1. Django Full Stack Project: Build a Django project backend by a relational database to create a website that allows users to store and manipulate data records about a particular domain.
2. Multiple Apps: The project must be a brand new Django project, composed of multiple apps (an app for each potentially reusable component in your project).
3. Data Modeling: Put some effort into designing a relational database schema well-suited for your domain. Make sure to put some thought into the relationships between entities. Create **at least 2 custom django models** beyond the examples shown on the course (changing the field names of the miniproject models is not customisation)
4. User Authentication: The project should include an authentication mechanism, allowing a user to register and log in, and there should be a good reason as to why the users would need to do so. e.g., a user would have to register to persist their shopping cart between sessions (otherwise it would be lost).
5. User Interaction: Include at least one form with validation that will allow users to create and edit models in the backend (in addition to the authentication mechanism). - FULL CRUD to at least one of the models in the UI
6. Use of Stripe: At least one of your Django apps should contain some e-commerce functionality using Stripe. This may be a shopping cart checkout or single payments, or donations, etc. After paying successfully, the user would then gain access to additional functionality/content on the site. Note that for this project you should use Stripe's test functionality, rather than actual live payments.
7. Structure and Navigation: Incorporate a main navigation menu and structured layout (you might want to use Bootstrap to accomplish this).
8. Use of JavaScript: The frontend should contain some JavaScript logic you have written to enhance the user experience.
9. Documentation: Write a README.md file for your project that explains what the project does and the value that it provides to its users.
10. Version Control: Use Git & GitHub for version control.
11. Attribution: Maintain clear separation between code written by you and code from external sources (e.g. libraries or tutorials). Attribute any code from external sources to its source via comments above the code and (for larger dependencies) in the README.
12. Deployment: Deploy the final version of your code to a hosting platform such as Heroku.
13. Security: Make sure to not include any passwords or secret keys in the project repository. Make sure to turn off the Django DEBUG mode, which could expose secrets.

**This [document](ms4-loa.pdf) contains the full list**

### README :
- [ ] Written with [markdown](https://www.markdownguide.org/cheat-sheet/)
- [ ] Commit the README the same way you commit your project : "doc(readme): added testing steps"
- [ ] Screenshot of the finished site from [AM I RESPONSIVE](http://ami.responsivedesign.is/)
- [ ] Explanation of the site's purpose - key project goals, target audience
- [ ] User stories - As a **user** I want to **fill out the contact form** so that I can **contact the company**
- [ ] Design : Wireframes (sketch is fine), colour palette, typography - & why you chose them
- [ ] Screenshots of all site features (Nav bar | footer | tables | etc...) accompanied by an explanation of what each feature does.
- [ ] Show & explain your ERD model (your database structure & how your models relate to each other : I recommend using [DrawSQL](https://drawsql.app/) for this
- [ ] Thorough testing steps & screenshots of validator testing
- [ ] All deployment steps including initial steps to clone the repo (git add/commit/push | deploy to github pages)
- [ ] Credit code & media sources
- [ ] Pass README through a spell checker!

### TESTING AS A TABLE :
**TEST** | **ACTION** | **EXPECTATION** | **RESULT** 
----------|----------|----------|----------
Home page | Size to 320px using Chrome Dev Tools	| Elements look good @ 320px | Works as expected
Home page | Size to 1920px using Chrome Dev Tools | Elements look good 1920px | Works as expected
Contact form | Click send button without data in form fields | Cannot submit form | Works as expected
Nav bar - home page | Click nav buttons | That each nav element takes me to the correct page site page | Works as expected

- To achieve the above table, this is what the formatting your README will look like :
```
**TEST** | **ACTION** | **EXPECTATION** | **RESULT** 
----------|----------|----------|----------
Home page	| Size to 320px using Chrome Dev Tools	| Elements look good @ 320px | Works as expected
Home page	| Size to 1920px using Chrome Dev Tools | Elements look good 1920px | Works as expected
Contact form | Click send button without data in form fields | Cannot submit form | Works as expected
Nav bar - home page | Click nav buttons | That each nav element takes me to the correct page site page | Works as expected
```

### TESTING / VALIDATORS :
- [W3](https://validator.w3.org/) : HTML validator
- [W3C](https://jigsaw.w3.org/css-validator/) : CSS validator
- [JS Hint](https://jshint.com/) : JavaScript validator
- [PEP8 Lintner : C.I.](https://pep8ci.herokuapp.com)
- Install a python linter directly into your project following [these steps](https://code-institute-room.slack.com/archives/CPCT0MBKL/p1664380977854349) in Slack.

### ADDITIONAL LEARNING : 
- [Securing Django Views from Unauthorized Access](https://www.codu.co/articles/securing-django-views-from-unauthorized-access-npyb3to_) : blog post explaining how to prevent users accessing data through URLs that have not been secured.
- [Django walkthrough series](https://www.youtube.com/watch?v=sBjbty691eI&list=PLXuTq6OsqZjbCSfiLNb2f1FOs8viArjWy) : YouTube
- [Common reasons for failing PP4](https://www.youtube.com/watch?v=Q5cdZXomzVg) : Youtube - an assessor shares common reasons students fail this project, & and has an FAQ.
- [Django database extension](https://medium.com/@yathomasi1/1-using-django-extensions-to-visualize-the-database-diagram-in-django-application-c5fa7e710e16) : Allows you to generate a schema of your database to visually see the connections.
