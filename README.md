# Welcome to Transeo?
Transeo is the best solution for tracking, verifying, and analyzing students’ impact on communities. We make hour verification, logging, and report generation easy for students and counselors.

# Motivation
This document exists as the backbone of development culture at Transeo. Everything that we believe in as it relates to coding, product creation, and culture is in this repo. In short, this is a guide on how to work and grow with Transeo.

# Connective Technology 
One of our motivating principles is creating technology that is connective in nature. To us, this means that our products are innovative, intuitive, and most importantly, accessible. 

When designing a product at Transeo, it’s very important to us that the product fits these guidelines. We’ve found this framework to be incredibly successful at conveying our message through tech. As we continue to grow as a company and as a tool used in communities around the country, we have to ensure that the quality of our products stays the same. 

The idea of connective technology sounds great, but where does Transeo fit into this picture? Let’s start with innovative. Most schools are still using pen and paper to track their hours. Think about that - we know that statistically, at least 55% of high school students will volunteer at some point in high school, and that’s not even counting the schools that mandate it for graduation. We also know that students who volunteer are more likely to be successful in school. So, we know that this behavior leads to greater overall success. Why aren’t schools using the best tools available to track and analyze this crucial cultural process?

In terms of intuitive software, we believe strongly that design and UI considerations are not an afterthought. They are an integral part of the system. Our goal from the minute the student starts using the system is to minimize the possibility that they will leave before entering their data. Because if they do that, we’ve lost a whole realm of opportunity. Transeo is intuitive because we focus on the user, and we understand the product. We’re not trying to crowd everything up with little, unfocused tools. It comes down to a simple idea: we believe in 
our mission, and our technology should exist to enable that mission not create it.

Finally, and perhaps the most important, is accessibility. We’re a mobile-first company meaning that every page we design is compatible with all mobile devices available on the market. The biggest struggle that we’ve seen while incorporating our software into school ecosystems is the wide range of socioeconomic ability. Some students have access to multiple different devices in which they can log their community service, while other students may only have an outdated smart device if that. We recognize that our software cannot be successful or impactful with making it accessible for every audience, so we make sure that it can run on every possible device, and as a result, for close to every student.

Here’s the bottom line - we’re working on a product that is meant to be successful in the market. That’s basic business that we’re not trying to hide. However, as we start to explore where we fit into this sphere of ed-tech and innovation, we’re discovering that, perhaps, we represent something much larger. It’s our job, as a team, to work towards finding that “something” together. 

# Culture

## Required Reading
* https://www.inc.com/david-brown/32-percent-of-entrepreneurs-struggle-with-mental-health-prioritize-your-personal-health-in-2018.html
* https://www.usenix.org/system/files/login/articles/login_winter17_09_looney.pdf
* https://hbr.org/2014/04/creating-a-culture-of-quality

## 3 main ideas we believe in:
### We are a team, not a family
The tech world is plagued with statements like “come join our family.” Transeo is a team, not a family. This is incredibly important to us, as we believe it sets the theme for all of our work. This idea is taken from Reed Hastings and Netflix. This line from Netflix’s culture page (https://jobs.netflix.com/culture) sums it up nicely:

> “We model ourselves on being a team, not a family. A family is about unconditional love, despite your siblings’ unusual behavior. A dream team is about pushing yourself to be the best teammate you can be, caring intensely about your teammates, and knowing that you may not be on the team forever.”

### Prioritize your mental health
This one is so important. We’re all human, and sometimes working in tech can push us to our extremes. Transeo is not like that. Be careful not to confuse this with a lazy work environment, though. Transeo’s development culture is fast-paced, innovative, exciting, and sometimes demands a lot - but never at the expense of your mental wellbeing. For more on this, check out required reading #2. 

### Transeo should be a place of growth for you
We want everyone on our team to grow with us. We’re an early stage company - that’s not something we’re trying to hide. Transeo should be a place where you can further explore your own curiosities and feed your intellectual spirit while continuing to contribute to our mission. 

# Development

## Git
Git and GitHub are two incredibly important tools in our company culture. We believe in the power of collaboration, so all projects should live on GitHub. 

When you want to contribute to the project, you should open up a new branch on the respective repo in the format of `feature-_`, replacing `_` with a short description about what you’re doing. For example, `feature-login-page`. This allows collaborators to quickly see what the branch’s purpose is. Note that the `master` branch is protected on all of our repos, preventing contributors from pushing directly to it. 

After completing the feature (and testing the feature!), open up a pull request on the main repo and request a PR review from someone else on the team. Be patient - reviews, when done right, take time. The first time through a review will almost always require changes to be made. You should prioritize making these changes over starting another feature branch. 

When the PR has been approved, your code from the feature branch will be merged into `master` and the branch will be deleted. You should switch back to master, pull the merge into your local folder, and then start a new branch for the new feature. 

## Task Management 
Projects of this magnitude with this many moving pieces often become very complex very fast. To try and combat that, we use Trello to manage projects. 

One of the downfalls of task management as a whole is determining how detailed each task should be. Creating a card in Trello is useless for our purposes if the card content is as broad as “Do the student portal.” Your job as a responsible team member is to try and find the perfect in-between. Find a system that works for you, and then see if it works with the rest of the project’s style, too. 

Card organization in Trello is also very important. Cards should be moved from the appropriate lists at the appropriate times. For example, don’t move a card from `Finished` to `Deployed` if it’s still sitting in a PR. Tagging cards also helps with this as it can provide some broader organization within each list. 

## Architecture 
Transeo’s mobile and server-side swift apps use MVC as the default. However, if there’s a better framework that you think works for the project you should suggest it **when the project is beginning.** It is exhaustingly time-consuming and expensive to switch app architectures in the middle of a project. 

## Open Source
When we create a tool, if it does not contain proprietary information it should be open sourced. This is the default for us - it does not mean that private repos are off the table, but if other developers could benefit from the library, we should make it public. 

## Swift
Our 2 biggest projects, the Transeo backend, and the Transeo iOS app, are built using Apple’s Swift. You should adhere to Ray Wenderlich’s style guide when coding, found here: https://github.com/raywenderlich/swift-style-guide.  

## Vapor Slack
If you are working on the backend server (built using Vapor), you should join the Slack community at http://vapor.team. There is a wealth of knowledge within that channel, and everyone is willing to help.

## User Data and Privacy 
There should be no circumstance in which you attempt to access production databases from the command line or MySQL tools GUIs, unless you have explicit permission from Transeo management. These databases contain critical user data which we must respect from a privacy standpoint. If you’ve been authorized by a user to look into their account to diagnose an issue, use our internal administrator tools to do so - they are built with privacy in mind. 


