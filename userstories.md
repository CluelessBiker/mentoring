#USER STORIES :

- Stories must follow the MoSCoW method & be divided into *Must have*, *Should have*, *Could have* & *Wont have*. This status can be reflected by applying labels to the stories.
- Group stories into [Epics](https://www.atlassian.com/agile/project-management/epics-stories-themes#:~:text=Stories%2C%20also%20called%20%E2%80%9Cuser%20stories,drive%20toward%20a%20common%20goal.) (A combination of stories that relate to one another, example: Signup, Login, Logout). This status can be reflected by applying labels to the stories.
- Divide stories into [Iterations](https://www.productplan.com/glossary/iteration/#:~:text=In%20agile%20software%20development%2C%20an,iteration%2Dby%2Diteration%20basis.) (A group of stories that will take up a pre-determined measure of time). Iterations can be reflected by assigning Milestones to the stories.
- Assign stories [Story Points](https://www.simplilearn.com/story-points-in-agile-article#:~:text=Story%20points%20represent%20the%20complexity,approach%20estimates%20employing%20story%20points.)
- Below is a template that you may use to populate your own user stories in **Github Issues**
```
USER STORY:
As a **role** I can **capability** so that **received benefit**.

Example:
As a [warehouse employee], I can [select paper size for print], so that the [printed label size, matches parcel size].

ACCEPTANCE CRITERIA:
(checklist for items that need to be accomplished)
- criteria one:
- criteria two:
- criteria three:

Example: (login)
- criteria one: user is rerouted to home page upon successful login
- criteria two: UI updates to reflect logged-in status
- criteria three: a warning message is given to display errors should an issue arise during login

TASKS:
(the steps needed to accomplish this story)
- [ ] task 1
- [ ] task 2
- [ ] task 3

Example:
- [ ] Implement login form & html template
- [ ] Install all auth package
- [ ] create URL path

BUG TICKETS:
- [ ] 

Example:
- [ ] User cannot Signup. Issue resolved by renaming form input from password to password1

STORYPOINTS: 3
```
