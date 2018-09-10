# Transeo - A Guide

- [Welcome to Transeo](#welcome-to-transeo)
- [Motivation](#motivation)
- [Connective Technology](#connective-technology)
- [What Transeo Expects From You](#what-transeo-expects-from-you)
- [What You Can Expect From Transeo](#what-you-can-expect-from-transeo)
- [Culture](#culture)
  * [Required Reading](#required-reading)
  * [Our 3 Core Principles](#our-3-core-principles)
    + [Work more like a team than a family](#work-more-like-a-team-than-a-family)
    + [Prioritize your mental health](#prioritize-your-mental-health)
    + [Be a lifelong learner](#be-a-lifelong-learner)
  * [Intention](#intention)
- [Workflow](#workflow)
  * [Sprints](#sprints)
  * [Standups](#standups)
  * [Retros](#retros)
- [Development](#development)
  * [Git](#git)
  * [Testing and CI](#testing-and-ci)
  * [Task Management](#task-management)
  * [Architecture](#architecture)
  * [Open Source](#open-source)
  * [Swift](#swift)
  * [Vapor Slack](#vapor-slack)
  * [User Data and Privacy](#user-data-and-privacy)

# Welcome to Transeo
Transeo is the best solution for tracking, verifying, and analyzing students’ impact on communities. We make hour verification, logging, and report generation easy for students and counselors.

# Motivation
This is a living document that serves as the backbone of development culture at Transeo. Everything that we believe in as it relates to coding, product creation, and culture is in this repo. In short, this is a guide on how to work and grow with Transeo.

# Connective Technology 
One of our motivating principles is creating technology that is connective in nature. To us, this means that our products are innovative, intuitive, and most importantly, accessible. 

When designing a product at Transeo, it’s very important to us that the product fits these guidelines. We’ve found this framework to be incredibly successful at conveying our message through tech. As we continue to grow as a company and as a tool used in communities around the country, we have to ensure that the quality of our products stays the same. 

The idea of connective technology sounds great, but where does Transeo fit into this picture? Let’s start with innovative. Most schools are still using pen and paper to track their hours. Think about that - we know that statistically, at least 55% of high school students will volunteer at some point in high school, and that’s not even counting the schools that mandate it for graduation. We also know that students who volunteer are more likely to be successful in school. So, we know that this behavior leads to greater overall success. Why aren’t schools using the best tools available to track and analyze this crucial cultural process?

In terms of intuitive software, we believe strongly that design and UI considerations are not an afterthought. They are an integral part of the system. Our goal from the minute the student starts using the system is to minimize the possibility that they will leave before entering their data. Transeo is intuitive because we focus on the user, and we understand the product. We’re not trying to crowd everything up with little, unfocused tools. It comes down to a simple idea: we believe in 
our mission, and our technology should exist to enable that mission not create it.

Finally, and perhaps the most important, is accessibility. We’re a mobile-first company meaning that every page we design is compatible with all mobile devices available on the market. The biggest struggle that we’ve seen while incorporating our software into school ecosystems is the wide range of socioeconomic ability. Some students have access to multiple different devices in which they can log their community service, while other students may only have an outdated smart device if that. We recognize that our software cannot be successful or impactful with making it accessible for every audience, so we make sure that it can run on every possible device, and as a result, for close to every student.

Here’s the bottom line - we’re working on a product that is meant to be successful in the market. That’s basic business that we’re not trying to hide. However, as we start to explore where we fit into this sphere of ed-tech and innovation, we’re discovering that, perhaps, we represent something much larger. It’s our job, as a team, to work towards finding that “something” together. Welcome to Transeo!

# What Transeo Expects From You

* Hard work
    * We won't to sugar coat it - the work that we're doing at Transeo is not easy. However, we also believe that growth cannot happen when faced with easily surmountable obstacles. We ask that when you encounter a challenge that might be too difficult to handle alone, reach out. There is no shame in asking someone else on the team for help. In fact, we encourage this, as it helps build our team culture and collaboration. You should expect to work hard on this product, but you should also expect that it won't be just you.  
* Honesty and integrity
    * In order for us to successfully craft a solid team culture, all of our employees must be open and honest about their actions. If you make a mistake, own up to it. We're not going to yell at you, we're going to learn from it. We expect that you will abide by this simple rule in all of your Transeo interactions, all the way down to something as simple as needing some time off. That's perfectly reasonable, but we need to know about it, so just be open and up-front. 
* Belief in our mission
    * We're not like other tech companies who say that they are going to "change the world" and then take no actionable steps toward that goal. Our mission is very simple: To bring together students, administrators, and communities to more effectively track and celebrate student service learning achievements. We know that our mission can actually, truly, make the world a better place, but it won't work if you don't buy into it. Every product decision that we make is driven by this mission, from the placement of a button to the name of Transeo, which means "I Transform" in Latin. We're intentional in everything we do because it pushes us to keep making the world a better place. Now, we need you to help us go even further.

# What You Can Expect From Transeo

* Honesty
    * We're all about transparency at Transeo. This stems from our belief that everyone on our team is a part of the greater mission, so if you have a question, just ask us and we'll be 100% open and honest with you.
* Support
    * Transeo wants to support you in as many ways as possible. If you need something, whether it's time off, code help, or support in any other way, please just reach out and ask.
* Flexibility
    * We are understanding and flexible at Transeo. Things come up, calendars change, more important stuff arises, we get it. We'll work with you to make sure that you are comfortable and at your best when it comes to work. 

# Culture

## Required Reading
These articles are at the core of what we believe in. Please read them! 

* https://www.inc.com/david-brown/32-percent-of-entrepreneurs-struggle-with-mental-health-prioritize-your-personal-health-in-2018.html
* https://www.usenix.org/system/files/login/articles/login_winter17_09_looney.pdf
* https://hbr.org/2014/04/creating-a-culture-of-quality
* https://ashfurrow.com/blog/building-compassionate-software/

## Our 3 Core Principles
### Work more like a team than a family
The tech world is plagued with the statement, “come join our family,” which is often used to keep employees working endless hours. We believe in working together as a team, not as a family. This idea manifests in our belief that we don't need to work long hours to make a great product, or abandon the outside world to keep the company alive. Instead, Transeo is all about balance: balance in work, balance in life, and balance in our company. 

We want you to feel a bond with Transeo's mission, and sometimes, that bond can create a family-like vibe. However, this feeling should give you professional meaning and purpose, not force you to work long hours or lose sight of everything else.

This line from Netflix’s culture page (https://jobs.netflix.com/culture) sums it up nicely:

> “We model ourselves on being a team, not a family. A family is about unconditional love, despite your siblings’ unusual behavior. A dream team is about pushing yourself to be the best teammate you can be, caring intensely about your teammates, and knowing that you may not be on the team forever.”

### Prioritize your mental health
This one is so important. We’re all human, and sometimes working in tech can push us to our extremes. Transeo is not like that; we believe in taking time to reflect and breathe. Be careful not to confuse this with a laid back or easy work environment, though. Transeo’s development culture is fast-paced, innovative, exciting, and sometimes demands a lot - but never at the expense of your mental wellbeing. For more on this, check out required reading number 1 and 2. 

### Be a lifelong learner
Transeo is an education company - at the end of the day, we exist to help students across the country realize and act upon their potential. Our technology is not supposed to tell them what their future should look like. Instead, we're here to illuminate the path so that they can make more intelligent, well-informed decisions. We believe that education is a fundamental human right, and that everyone in the world should have the opportunity to learn. As such, a critical part of our culture is utilizing our position of privilege to learn as much as we can. We do this so that we can build better products and better solutions to help others continue their own learning, and their own exploration. We expect that all Transeo team members fearlessly pursue the promise of new knowledge with the understanding that it's not about _how much_ we can learn, but rather, it's about _why_ we choose to continue learning in the first place.

## Intention
Our entire marketing, sales, and product strategy is based around one simple concept: intention. We believe that every action that we take should be calculated and thought over for the maximum effect. This means that as we continue to scale up to schools across the country, every business and tech decision that we make needs to be intentional and in line with our end mission. 

Our philosophy is fairly different from how some companies choose to work because many fail to consider how their every day actions fit into their mission and end goals. This way of thinking applies to everything we do, from the lines of code we write to the schools that we try to add to our platform. 

It sounds intense, and sometimes it can be. This type of thinking requires a lot of time and consideration. In the end, though, it pays off because it gives us the opportunity to think about Transeo's social responsibility, and how our actions contribute to that responsibility. In short, acting intentionally helps us create in a much more rewarding way.

# Workflow

## Sprints
We work in 2 week sprints meaning that at the beginning of each 2 week cycle we define the work that will get completed over the next two weeks. There are a few main benefits to this method, the most importance of which is avoiding [scope creep](https://en.wikipedia.org/wiki/Scope_creep). This helps us focus on what's important for those two weeks, and gives us a hard deadline to work towards in terms of deliverables.

Sprints look different for different products, so the most important thing is to make sure that you are coordinating with your team around scope selection and ensuring that deadlines can be met on all of the items in the sprint. 

Here's the bottom line - although we'd love to pretend that sprints work perfectly and solve all of the problems in development cycles, stuff happens. So if something that was originally in the sprint just can't be done, work with the head of your team to move it into the next sprint as early as possible. 

## Standups
Standups happen every day in our Slack channel. Doing standups asynchronously not only helps with us working remotely, it also allows the standup to be an activity that provides value, rather than a requirement. Take 5 minutes each day to really reflect on what you did the day prior, and what lessons you are going to take into today. We'll all be better for it.

## Retros
Retrospectives, or "retros" for short, happen at the end of the day on Fridays at the end of a 2 week sprint. This is an opportunity for all of Transeo development to get together and share what went well, what went wrong, and what we can do to improve going forward. This helps focus us for the future while also acknowledging the lessons we learned from the previous sprint, with the goal being to make development more efficient and productive going forward.

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
