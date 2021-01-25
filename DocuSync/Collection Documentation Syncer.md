
---

# Elevator Pitch: 💯

> ### *\"We developers have heard from time to time that documentation is more important than the code itself. So is the documentation for APIs. [Postman provides a markdown editor](https://learning.postman.com/docs/collaborating-in-postman/commenting-on-collections/#commenting-on-a-collection) to document a Workspace, Collection, or even a Request and I have been contemplating for a while on how to integrate version controlling with Postman's Documentation editor. That is where [Github](https://github.com/) comes to play. How about a markdown file in your Github repository that syncs automatically with your Postman workspace leveraging the power of [Postman's monitors](https://learning.postman.com/docs/designing-and-developing-your-api/monitoring-your-api/intro-monitors/).\"* 😊😁

---

![mind blown](https://media.giphy.com/media/pSurYTaFDcY4E/giphy.gif)

  

### *Wait what?? What do you mean by a [markdown file](https://www.markdownguide.org/cheat-sheet/) in Github that syncs with your Postman Workspace?? How could a Workspace in Postman could sync a data between two different platforms?? And even if it did what it claims, What are its benefits?*

  

### *I will try to answer these questions definitively in this documentation.*

---

# Why DocuSync? What are its benefits?? 🤔💭

  

### *Well, There are a couple reasons why using DocuSync might boost your productivity in the long run* 🏃🏻🏃🏻‍♀️

  

- ### Github's [version controlling](https://www.google.com/search?channel=fs&client=ubuntu&q=github%20version%20control%20system) features along with Postman Monitor (More on that later).

- ### The comfort of creating a MarkDown file in the text editor of your choice.

- ### Some of the [VSCode, Atom and Sublime Extensions](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.MarkdownEditor) provide live preview for MarkDown files which will make our lives easier while editing documentation.

- ### Everybody on the team could easily access and collaborate together on editing the documentation in Github.

  

### *If you still aren't sold, Let me elucidate the [power of Postman's monitor](https://learning.postman.com/docs/designing-and-developing-your-api/monitoring-your-api/intro-monitors/) and Github's version controlling which could be applied for API documentation.*

---

# Power 💪🏻 of Postman's Monitor 🖥️ and Github's Version Controlling: 

  

- ### Most of us know Github for its prowess in source code version controlling and [collaboration](https://code.tutsplus.com/tutorials/how-to-collaborate-on-github--net-34267).

- ### API Documentation changes periodically as new APIs gets added and new versions of APIs get launched.

- ### This forces us to keep a local copy of the previous API documentation in our machine

- ### But with the integration of Github and Postman using Postman Monitor (btw, Monitors are extra-ordinary and makes our lives much easier), We could save all the different versions of API Documentation as it evoles in Github and directly sync in Postman's Documentation editor.

- ### If it requires that you need to revert back to old documentation, you could do that with a press of a key when using this Workspace.

---

# OK 👌🏻 , But how does DocuSync sync a Markdown file in Github to Postman?? 🤔💭

  

- ### Well first of all, It uses both [Postman's](https://documenter.getpostman.com/view/631643/JsLs/?version=latest) and [Github's API](https://docs.github.com/en/rest) to send and take actions between them.

- ### And for that reason it requires the User's API Key.

- ### Docusync uses Postman Monitor for constantly checking for new updates in [Github](https://github.com/) file and syncing with Postman.

---

# Workspace Briefing: ⏳

### DocuSync contains 5 [Collections](https://learning.postman.com/docs/getting-started/creating-the-first-collection/) and each of them are explained below:

> ### Workspace Documentation Syncer -> *Used to Document a Workspace in Postman*

> ### Collection Documentation Syncer -> *Used to Document a Collection in Postman*

> ### Request Documentation Syncer -> *Used to Document a Request in Postman (This one quite hacky, for more details look into this Collection Documentation)*

> ### Create Project in One Go -> *Used to create a Postman Workspace and a Github Repo in one go*

> ### Delete Project in One Go -> *Used to delete a Postman Workspace and a Github Repo in one go*

### DocuSync consist of 5 [Environment](https://learning.postman.com/docs/sending-requests/managing-environments/) and each of them are explained below:

> ### Workspace Documention Syncer Env -> *Used as an environment for Workspace Documentation Syncer*

> ### Collection Documention Syncer Env -> *Used as an environment for Collection Documentation Syncer*

> ### Request Documention Syncer Env -> *Used as an environment for Request Documentation Syncer*

> ### Create Project in One Go Env -> *Used as an environment for Create Project in One Go*

> ### Delete Project in One Go Env -> *Used as an environment for Delete Project in One Go*


### DocuSync consist of 3 [Monitors](https://learning.postman.com/docs/designing-and-developing-your-api/monitoring-your-api/setting-up-monitor/) and each of them are explained below:

> ### Workspace Documention Syncer Monitors -> *Used as an environment for Workspace Documentation Syncer*

> ### Collection Documention Syncer Monitors -> *Used as an environment for Collection Documentation Syncer*

> ### Request Documention Syncer Monitors -> *Used as an environment for Request Documentation Syncer*

#### *[Note: Since the Create Project in One Go and Delete Project in One Go does not need a Monitor they were not created]*
---
# Points to Note: ❌
- ### Use the right Environment, Mock Server and Monitor for the right Collection. The Pairs are mentioned above.
- ### All the Workspace, Collection and the Request used in Docusync Should be unique as DocuSync searches through your Postman Account and finds the resource manually. So there might occur a concurrency problem if there are two are more Workspace, Collection in your Postman Account with a same name.
- ### Take a look into each environments and fill out according to the instructions provided in the placeholder descriptions of each environmental variables.
---
## ❤️ [If you think DocuSync is useful to you and you found value in it. Contribute to this public workspace]
---
# References: 📄
#### *[Get Github API Token](https://github.com/settings/tokens)*
#### *[Get Postman API Key](https://learning.postman.com/docs/developer/intro-api/)*
####  *[Learn MarkDown](https://www.markdownguide.org/cheat-sheet/)*

#### Made with ❤️
