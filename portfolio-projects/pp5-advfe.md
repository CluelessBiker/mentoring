### README: backend
- document all deployment steps (including but not limited to: creating requirements.txt, procfile, terminal commands to install packages)
- thorough testing of all elements (CRUD)
- ERD that reflects model relations ([Draw SQL](https://drawsql.app/) or [Django database extension](https://medium.com/@yathomasi1/1-using-django-extensions-to-visualize-the-database-diagram-in-django-application-c5fa7e710e16))

### README: frontend
- document all deployment steps
- thorough testing of all elements (CRUD, page sizing, security, filling out forms)
- wireframes
- colour palettes
- explanation of design choices, why you picked this theme, & how the concept is beneficial to others

### [AGILE](https://github.com/CluelessBiker/mentoring/blob/main/userstories.md):
- create user stories for all features
- assign stories to relevant sprints
- record all stories/sprints to **github projects**

### GIT:
- a clean & informative git commit history

### UI:
- design an intuitive, user friendly site, that is relevant to the theme/topic chosen
- UI must be responsive from 320px-1920px (290px if trying to impress assessors)
- all interactive elements must be functional (button clicks, input forms, social links)
- full CRUD must be available via the UI built, **_NOT_** just inside the Django admin panel
- must have user login, that reflects logged-in status to the current user, & restricts the functionality of CRUD for said user)
- provide notifications to reflect that posts have been created/edited/deleted, or that users have successfully signed in
- restrict input fields to only accept relevant data (eg. type='number' or type='phone') & display error messages when incorrectly populated
- TWO forms must be supplied (ed. creating a post form, editing a post form)

### JSX:
- doc strings above functions
- code comments
- properly indented
- files must be PascalCase
- files must have corresponding style sheets
- try to keep components modular & to have a single purpose (eg. assets spinners, avatars, forms)
- project **must** be built in react
- deployed to Heroku
- install & configure [ESLint](https://gist.github.com/ianmeigh/8e603b91a38d7829d959402bfcf29d3d) (a JSX linter)
- remove all dead code (commented out code, or code that is no longer relevant to the project just as components that have not been implemented)

### PYTHON:
- doc strings inside functions & classes
- code comments
- properly indented
- files must be snake_case
- ensure all (secret)keys are saved to the env.py file & are **not** visible in your settings.py
- deployed to Heroku
- a minimum of one **_CUSTOM_** model must be implemented that is relevant to your concept
- all files must pass through [PEP8](https://pep8ci.herokuapp.com/)
- custom python code must be written (CRUD on your custom model, eg: views.py & serializer.py)
- relevant fields inside your model (eg. integer fields for numbers, booleans for true/false, dates for dates, etc)
- ensure DEBUG is set to False before submission
- remove all dead code (commented-out code, or code that is no longer relevant to the project just as models that have not been implemented)


### CSS:
- code comments
- properly indented
- files must be lowercase

### ASSETS/MEDIA:
- files must be kebab-case
