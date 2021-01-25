
---

# Elevator Pitch:

> ### *\"We developers have heard from time to time that documentation is more important than the code itself. So is the documentation for APIs. [Postman provides a markdown editor](https://learning.postman.com/docs/collaborating-in-postman/commenting-on-collections/#commenting-on-a-collection) to document a Workspace, Collection, or even a Request and I have been contemplating for a while on how to integrate version controlling with Postman's Documentation editor. That is where [Github](https://github.com/) comes to play. How about a markdown file in your Github repository that syncs automatically with your Postman workspace leveraging the power of [Postman's monitors](https://learning.postman.com/docs/designing-and-developing-your-api/monitoring-your-api/intro-monitors/).\"* :smiley:

---

![mind blown](https://media.giphy.com/media/pSurYTaFDcY4E/giphy.gif)

  

### *Wait what?? What do you mean by a [markdown file](https://www.markdownguide.org/cheat-sheet/) in Github that syncs with your Postman Workspace?? How could a Workspace in Postman could sync a data between two different platforms?? And even if it did what it claims, What are its benefits?*

  

### *I will try to answer these questions definetively in this documentation.*

---

# Why use this Workspace? What are its benefits??

  

### *Well, There are a couple reasons why using this workspace might boost your productivity in the long run*

  

- ### Github's [version controlling](https://www.google.com/search?channel=fs&client=ubuntu&q=github%20version%20control%20system) features along with Postman Monitor (More on that later).

- ### The comfort of creating a MarkDown file in the text editor of your choice.

- ### Some of the [VSCode, Atom and Sublime Extensions](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor) provide live preview for MarkDown files which will make our lives easier while editing documentation.

- ### Everybody on the team could easily access and collaborate together on editing the documentation in Github.

  

### *If you still aren't sold, Let me elucidate the [power of Postman's monitor](https://learning.postman.com/docs/designing-and-developing-your-api/monitoring-your-api/intro-monitors/) and Github's version controlling which could be applied for API documentation.*

---

# Power of Postman's Monitor and Github's Version Controlling:

  

- ### Most of us know Github for its prowess in source code version controlling and [collaboration](https://code.tutsplus.com/tutorials/how-to-collaborate-on-github--net-34267).

- ### API Documentation changes periodically as new APIs gets added and new versions of APIs get launched.

- ### This forces us to keep a local copy of the previous API documentation in our machine

- ### But with the integration of Github and Postman using Postman Monitor (btw, Monitors are extra-ordinary and makes our lives much easier), We could save all the different versions of API Documentation as it evoles in Github and directly sync in Postman's Documentation editor.

- ### If it requires that you need to revert back to old documentation, you could do that with a press of a key when using this Workspace.

---

# OK, But how does this Workspace sync a Markdown file in Github to Postman??

  

- ### Well first of all, It uses both [Postman's](https://documenter.getpostman.com/view/631643/JsLs/?version=latest) and [Github's API](https://docs.github.com/en/rest) to send and take actions between them.

- ### And for that reason it requires the User's API Key.

- ### This Workspace uses Postman Monitor for constantly checking for new updates in [Github](https://github.com/) file and syncing with Postman.

---

# Workspace Briefing:

  

### This Workspace contains 5 Collections and each of them are explained below.

> ### Workspace Documentation Syncer -> *Used to Document a Workspace in Postman*

> ### Collection Documentation Syncer -> *Used to Document a Collection in Postman*

> ### Request Documentation Syncer -> *Used to Document a Request in Postman (This one quite hacky, for more details look into this Collection Documentation)*

> ### Create Project in One Go -> *Used to create a Postman Workspace and a Github Repo in one go*

> ### Delete Project in One Go -> *Used to delete a Postman Workspace and a Github Repo in one go*

### The Workspace consist of 5 Environment and each of them are explained below.

---
# References:
####  *[Learn MarkDown](https://www.markdownguide.org/cheat-sheet/)*
#### *[Get Github API Token](https://github.com/settings/tokens)*
#### *[Get Postman API Key](https://learning.postman.com/docs/developer/intro-api/)*

