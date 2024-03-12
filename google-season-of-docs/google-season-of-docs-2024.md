# Google Season of Docs 2024

[![Google Season of Docs 2019](https://developers.google.com/static/season-of-docs/images/logo/SeasonOfDocs_Logo_KO.png)](https://developers.google.com/season-of-docs/)

[Rocket.Chat](https://github.com/Rocket.Chat/Rocket.Chat) is applying to participate in [Google Season of Docs 2024](https://developers.google.com/season-of-docs).

[Google Season of Docs](https://g.co/seasonofdocs) provides support for open source projects to improve their documentation and gives professional technical writers an opportunity to gain experience in open source. Together we raise awareness of open source, of docs, and of technical writing. The GSoD 2024 grants range from $5,000 to $15,000 USD depending on the project's budget.

## Summary

1. [How to apply](#how-to-apply)
2. [About our organization](#about-our-organization)
3. [Project Idea: Main Project Developer Documentation Audit and update](#main-project-developer-documentation-audit-and-update)
4. [Project Idea: Apps development Documentation Audit and update](#apps-development-documentation-audit-and-update)
5. [Timeline](#timeline)
6. [Budget](#budget)

## How to apply

Rocket.Chat has a community server at [http://open.rocket.chat](http://open.rocket.chat)

Interested technical writers, please contact us through the Google Seasons of Docs 2024 channel at [https://open.rocket.chat/channel/gsod2024](https://open.rocket.chat/channel/gsod2024)

See the [official technical writer guide](https://developers.google.com/season-of-docs/docs/tech-writer-guide) for more information.

## About our organization

Rocket.Chat is one of the largest active open source **(permissive MIT source license)** communications platform on GitHub, connecting thousands global community contributors (across projects) from 30+ countries, with 38,500+ GitHub stars, 9800 forks, 875+ total releases and 15,000+ issues since inception in 2015.

We are the ultimate Free Open Source Solution for team communications, enabling real-time conversations between colleagues, with other companies or with your customers, regardless of how they connect with you. The result is an increase in productivity and customer satisfaction rates.

Every day, tens of millions of users in over 150 countries and in organizations such as Deutsche Bahn, The US Navy, and Credit Suisse trust Rocket.Chat to keep their communications completely private and secure.

## Project ideas

### Main Project Developer Documentation Audit and update  

#### The Problem

Rocket.Chat, as an open-source communication platform, faces unique challenges in maintaining and enhancing its documentation to meet the dynamic needs of its diverse developer community. The existing documentation, while comprehensive, has been identified to have several areas needing improvement to better serve the project’s contributors, developer experience, and the community’s growing demands.
Every day new contributors post questions about Development setup, contribution, and project best practices and this could lead some of them to give up contributing due to the lack of documentation in certain areas.

**Existing documentation page:** [https://developer.rocket.chat](https://developer.rocket.chat)

### Project scope

* Check and analyze main project [GitHub issues](https://github.com/RocketChat/Rocket.Chat/issues), [Rocket.Chat forum](https://forums.rocket.chat/), and [community channels](https://open.rocket.chat) data to find the areas to improve the main project documentation
* Update [main project documentation](https://developer.rocket.chat) homepage with resources and fast links for most visited pages
* Reorganize documentation structure to better-fit contributor needs and interests
* Rewrite and improve [Contribution guidelines](https://developer.rocket.chat/contribute-to-rocket.chat/modes-of-contribution) and How to start contributing
* Update the [Server (main project) Repository Structure](https://developer.rocket.chat/open-source-projects/server/repository-structure) documentation with current structure and packages explanations
* Improve and update the [troubleshooting page](https://developer.rocket.chat/contribute-to-rocket.chat/modes-of-contribution/participate-in-rocket.chat-development/troubleshooting) for the most common scenarios and systems that are reported in the community channels (GitHub, forum, and community channels)
* Create a HowTo guides for:
  * Write unit and end-to-end test
  * Write front-end code
  * Write back-end code
  * Contribute to Internationalization/translations
  * Deploy Rocket.Chat with different methods (Docker, snap, etc...)

### Out of scope

* Tech writers won't develop and change the github project structure
* Tech writers won't be implementing new tools

### How would we measure success?

* Reduction in github issues related to contributor onboarding and environment setup issues
* Reduction in the number of open questions found in our public channels
* Increase in pull request numbers to the main project
* Increased coverage of well-known contributor pain points

---

### Apps development Documentation Audit and update  

#### The Problem

Developing apps to enhance Rocket.Chat's functionality offers a more straightforward approach than delving into its extensive code base. However, there's a noticeable gap in the documentation available for app developers.

Navigating our current documentation proves challenging for newcomers to app development. The available information lacks the necessary detail and clarity, turning what could be an efficient development process into a protracted and sometimes discouraging experience. This scenario often leads to developers feeling overwhelmed, potentially causing them to abandon their projects entirely.

Presently, app development for Rocket.Chat can be daunting without direct assistance from seasoned app developers or our internal team, due to outdated informations.

**Existing documentation page:** [https://developer.rocket.chat/apps-engine/rocket.chat-apps-engine](https://developer.rocket.chat/apps-engine/rocket.chat-apps-engine)

### Project scope

* Check and analyze main project [GitHub issues](https://github.com/RocketChat/Rocket.Chat/issues), [Rocket.Chat forum](https://forums.rocket.chat/), and [community channels](https://open.rocket.chat) data to find the areas to improve the main project documentation
* Update outdated information about the [Apps.Engine documentation](https://developer.rocket.chat/apps-engine/rocket.chat-apps-engine)
* Create or improve/update HowTo guides for:
  * Create a slash command app ([existing doc](https://developer.rocket.chat/apps-engine/extend-app-capabilities/slash-commands/slash-command-examples))
  * Call external APIs ([existing doc](https://developer.rocket.chat/apps-engine/extend-app-capabilities/http-requests))
  * Use UI elements to interact with the user or app ([existing doc](https://developer.rocket.chat/apps-engine/extend-app-capabilities/apps-engine-user-interface))
  * Handle permissions ([existing doc](https://developer.rocket.chat/apps-engine/app-permission-system))
  * Add a configurations page to your app ([existing doc](https://developer.rocket.chat/apps-engine/app-configuration))
  * Persist data ([existing doc](https://developer.rocket.chat/apps-engine/app-data-persistence))
  * Add internationalization to your app ([existing doc](https://developer.rocket.chat/apps-engine/app-internationalization))
  * Register API endpoint ([existing doc](https://developer.rocket.chat/apps-engine/adding-features/registering-api-endpoints))
  * OAuth with external applications ([existing doc](https://developer.rocket.chat/apps-engine/adding-features/oauth2-client))
  * Schedule tasks that run in a defined period ([existing doc](https://developer.rocket.chat/apps-engine/adding-features/scheduler-api))
  * Debug your app
  * Publish the app in the Rocket.Chat marketplace ([existing doc](https://developer.rocket.chat/apps-engine/app-submission-to-the-marketplace))

### Out of scope

* Tech writers won't develop and change the github project structure
* Tech writers won't be implementing new tools

### How would we measure success?

* Reduction in github issues related app develpoment
* Reduction in the number of open questions found in our public community server and Forum
* Increased apps published in the marketplace
* Increased documentation visits

---

### What skills would a technical writer need to work on this project?

**Must have:**

* Demonstrated experience working with large and complex structured docs for developers.
* Basic technical understanding of modern web and CS concepts.

**Nice to have:** Ability to read Javascript/Typescript code is nice to have but not a must.

### Timeline

The project will take approximately six months. Here's a timeline approximation of the deliverables.

| Date             | Action                           |
| ---------------- | -------------------------------- |
| May              | Writer orientation               |
| June             | Project ramp-up                  |
| July             | Re-organizing and re-structuring |
| August - November| Wriritng documentation           |
| December         | Feedbacks and adjustments        |

### Budget

Budget consists of tech writer payment, swags, subscriptions, and up to 3 volunteers who would help us with testing and providing feedback over the timeline on the produced content.

| Type                                | Amount   | Running total | Notes                 |
| ----------------------------------- | -------- | ------------- | --------------------- |
| Tech writer payment                 | 12000USD | 12000USD      |                       |
| T-shirt swags                       | 250USD   | 13000USD      | Writer + 3 volunteers |
| Documentation Tool subscription     | 300USD   | 13300USD      | Writer + Administrator|
| **TOTAL**                           |          | 13300USD      |                       |
