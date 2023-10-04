# README REQUIREMENTS :

- [README formatter](https://stackedit.io/app#) : very useful tool

## ALL READMES :
- [ ] Written with [markdown](https://www.markdownguide.org/cheat-sheet/)
- [ ] Commit the README the same way you commit your project : "feat(readme): added testing steps"
- [ ] Screenshot of finished site from [AM I RESPONSIVE](http://ami.responsivedesign.is/)
- [ ] Explanation of the site's purpose - key project goals, target audience
- [ ] Screenshots of all site features (Nav bar | footer | tables | etc...) accompanied by an explanation of what each feature does. ***NOT FOR PP3***
- [ ] Thorough testing steps & screenshots of validator testing
- [ ] All deployment steps (cloning repo | git add/commit/push | deploy to github pages)
- [ ] Credit code & media sources
- [ ] Pass README through a spell checker!

--- 

## PP1 | PP2 | PP3 : [C.I. Template](https://github.com/Code-Institute-Solutions/readme-template)
#### View the CI README in [Markdown](https://raw.githubusercontent.com/Code-Institute-Solutions/readme-template/master/README.md)
***Additional Content :***
- [ ] Wireframes - [Balsamiq](https://balsamiq.com/) / Data schema - [Lucid chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign=_chart_en_tier3_mixed_search_brand_exact_&km_CPC_CampaignId=1484560207&km_CPC_AdGroupID=60168114191&km_CPC_Keyword=lucid%20chart&km_CPC_MatchType=e&km_CPC_ExtensionID=&km_CPC_Network=g&km_CPC_AdPosition=&km_CPC_Creative=354596054350&km_CPC_TargetID=kwd-55720648523&km_CPC_Country=9061582&km_CPC_Device=c&km_CPC_placement=&km_CPC_target=&gclid=Cj0KCQjw06OTBhC_ARIsAAU1yOWd-aAfWgTzdJakjoJHLkdNiAJMRGWM6YcYIJWJl9zKQhzKJIGfYaQaAluFEALw_wcB) : a pen/paper sketch will suffice
- [ ] User stories: e.g. :
- As a **user** I want to **fill out the contact form** so that I can **contact the company**
- As a **user** I want to **view the about page** so that I can **learn more about the company**
- [ ] Design choices & the reason behind them : colour schemes | font selection | features added

--- 

## PP3 :
Testing for this project is limited as it is restricted to your user interactions that come in the form of inputs. Please document each & every input in the following manner:

**TEST** | **ACTION** | **EXPECTATION** | **RESULT** 
----------|----------|----------|----------
Input - User name - Invalid data	| Entered in : blank space, return key, symbols, numbers	| app informs user of invalid data & prompts the user to try again | Works as expected
Input - User name - Valid data	| Entered in : characters in scope | app proceeds to next function | Works as expected

--- 

Alternatively, create it in google sheets / excel with the above headers. Copy the cells and paste into https://tabletomarkdown.com/ - This will generate the markdown for you.

## PP4 :
- [ ] Wireframes
- [ ] Design choices & the reason behind them : colour schemes | font selection | features added
- [ ] User stories : either in an Agile tool & linked in the README, or directly in the README

***Additional Content :***
- [ ] Detailed explanation of data schema
- [ ] Combine ***User stories*** into ***Epics*** : e.g. the user stories for `sign-up`, `login`, `logout` can be grouped into a single epic as they are related features.
- [ ] Document all bugs & their fixes + an explanation of any bugs left unfixed & why

--- 

## PP5 - ADVFE :

If your backend & frontend are in separate repos, !! TWO READMES ARE REQUIRED !!
If you have combined BE & FE into a single repo, you may combine the README.

### BACKEND :
- [ ] All deployment steps
- [ ] Thoroughly document manual testing
- [ ] Backend User stories in an Agile tool - link to stories & Kanban board in README (no need to repeat the individual stories again)
- [ ] Data schema

### FRONTEND :
- [ ] All deployment steps
- [ ] Document reuse of React components to demonstrate understanding
- [ ] Wireframes
- [ ] Project goals
- [ ] Frontend User stories in an Agile tool - link to stories & Kanban board in README (no need to repeat the individual stories again)
- [ ] Thoroughly document manual testing

--- 

## PP5 - ECOMM :
- [ ] Wireframes
- [ ] Colour Scheme - & why you chose this palette
- [ ] Typography choice - & why you chose these fonts
- [ ] Frontend User stories in an Agile tool - link to stories & Kanban board in README (no need to repeat the individual stories again)
- [ ] Thoroughly document manual testing as a table
- [ ] All deployment steps so good your mother could follow them
- [ ] A list of all installed packages & the purpose of each one
- [ ] Screenshots of your dummy-Facebook page (FB often deletes the page, screenshots are a failsafe if this is to occur)
- [ ] Screenshots of your Database Schema generated either by [Lucid chart](https://www.lucidchart.com) or [Django database extension](https://medium.com/@yathomasi1/1-using-django-extensions-to-visualize-the-database-diagram-in-django-application-c5fa7e710e16)
- [ ] Present a clear rationale for the development of the project - Who your target audience is, what are their needs, why would they choose your site
- [ ] Document your marketing strategy
- [ ] Provide your business model & clarify if you are a B2B or B2C company
- [ ] SEO section that includes sub-sections for : Keywords | Page titles | Robots.txt & sitemap.xml | Content | Surface

--- 

## TESTING AS A TABLE :
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


