# Development

## Git
Git and GitHub are two incredibly important tools in our company culture. We believe in the power of collaboration, so all projects should live on GitHub. 

When you want to contribute to the project, you should open up a new branch on the respective repo in the format of `feature-_`, replacing `_` with a short description about what you’re doing. For example, `feature-login-page`. This allows collaborators to quickly see what the branch’s purpose is. Note that the `master` branch is protected on all of our repos, preventing contributors from pushing directly to it. 

After completing the feature (and testing the feature!), open up a pull request on the main repo and request a PR review from someone else on the team. Be patient - reviews, when done right, take time. The first time through a review will almost always require changes to be made. You should prioritize making these changes over starting another feature branch. 

When the PR has been approved, your code from the feature branch will be merged into `master` and the branch will be deleted. You should switch back to master, pull the merge into your local folder, and then start a new branch for the new feature. 

## Testing and CI
Testing is at the core of our beliefs, but we also believe that **there is a fine line between testing for safety and testing just to write tests.** When a PR is reviewed, the reviewer will take note of whether or not tests are included and if they're applicable in the situation. They might determine that the PR is fine without tests, or they might note that it can't be merged without testing. Either way, testing's purpose at Transeo is to ensure that we don't have regressions as we continue to update and innovate on our existing platform. That should be the guiding principle when writing tests, not the number of tests or whether each individual function has a test.

Continuous integration helps us with our goal of no regressions. On the applicable repos, Circle CI will build and test each PR and block merging if building fails.

## Task Management 
Projects of this magnitude with this many moving pieces often become very complex very fast. To try and combat that, we use Asana to manage projects. 

One of the downfalls of task management as a whole is determining how detailed each task should be. Creating a card in Asana is useless for our purposes if the card content is as broad as “Do the student portal.” Your job as a responsible team member is to try and find the perfect in-between. Find a system that works for you, and then see if it works with the rest of the project’s style, too. 

Card organization in Asana is also very important. Cards should be moved from the appropriate lists at the appropriate times. For example, don’t move a card from `Finished` to `Deployed` if it’s still sitting in a PR. Tagging cards also helps with this as it can provide some broader organization within each list. 

## Architecture 
Transeo’s mobile and server-side swift apps use MVC as the default. However, if there is a better framework that you think works for the project you should suggest it **when the project is beginning.** It is exhaustingly time-consuming and expensive to switch app architectures in the middle of a project. 

## Open Source
When we create a tool, if it does not contain proprietary information it should be open sourced. This is the default for us - it does not mean that private repos are off the table, but if other developers could benefit from the library, we should make it public. 

## Swift
Our 2 biggest projects, the Transeo backend, and the Transeo iOS app, are built using Apple’s Swift. You should adhere to Ray Wenderlich’s style guide when coding, found here: https://github.com/raywenderlich/swift-style-guide.  

## Vapor Slack
If you are working on the backend server (built using Vapor), you should join the Discord community at http://vapor.team. There is a wealth of knowledge within that channel, and everyone is willing to help.

## User Data and Privacy 
There should be no circumstance in which you attempt to access production databases from the command line or MySQL tools GUIs, unless you have explicit permission from Transeo management. These databases contain critical user data which we must respect from a privacy standpoint. If you’ve been authorized by a user to look into their account to diagnose an issue, use our internal administrator tools to do so - they are built with privacy in mind. 
