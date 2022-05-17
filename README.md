# Wild Life

An app that attempts to recognize possibly poisonous plants that are in your area from a photo the user takes.

## UX Team Members

* **[Nolan Brady](https://usabilityengineering.github.io/ux-portfolio-somehobo/)** - Methods, Findings, Conclusions
* **[Madison Fong](https://usabilityengineering.github.io/ux-portfolio-mnfong/)** - Personas, Scenarios, and Supplementary Materials

# User-Centered Design Artifacts
 
* [Personas and Scenarios](Personas_and_Scenarios.pdf)
* [Wireframes](Wild-Life.pdf)
* [Prototype](https://xd.adobe.com/view/b8ee1f5e-e196-4611-aeef-e87c900d5699-edbd/?fullscreen&hints=off)

# Phase 1: Requirements Gathering

**Executive Summary**

The project’s goal is to help determine if a plant is poisonous in the wild using a picture taken by a phone and a machine learning model. Current methods of categorizing a plant are cumbersome and rely on personal knowledge. In this requirements gathering phase we asked college students about the tools they would need to use this application effectively.

We interviewed college students to understand their needs better:
- **Students (n=2)** participated in 1-on-1 interviews
- **Narrow Use Cases**: We discovered that there aren't many use cases on a day to day basis for when a user would need to determine if a plant is poisonous.
- **Photo Confirmation**: Because of distrust of AI in a potentially dangerous scenario, users require a photo of the given plant to confirm, as well as percentage confidence.
- **False-Positives**: Because user safety is our number one concern, we need to gear the model towards false positives rather than false negatives.

We surveyed college students to better understand their thoughts about the app:
**Online survey received (n = 13)** responses
- **80% Trust**: students were inclined to trust an AI to tell them if a plant is poisonous or not
- **76.9% Poisonous Encounters**: students who spent time outdoors frequently encountered poisonous plants
- **50% Internet access**: of respondents were not sure they had internet access.


[Full phase 1 report](requirements/)

# Phase 2: Interaction Design

**Executive Summary**

The goal of this phase was to create a mock up of the app through the creation of wireframes. To do this, we used the original goal of the project and the information we learned from Phase One to display an accurate represention of what app aspires to do. 

The wireframe includes **6 Total Pages** that demonstrate what we gathered from Phase One:
- **Home Page** that opens to the camera for the user to be able to easily take a picture of the plant they want identified. It also includes buttons that will take the user to either their camera roll to upload a picture or to their past uploads to see if the plant has already been identified.
- **Information Page** that is shown when a plant is identified. It contains a known picture of the plant as well as the user's picture with information about the plant in a dragable text box at the bottom of the page.
- **More Information** from the original Information Page, the user is able to go into another view that contains more pictures of the identified plant to increase their confidence about the match.
- **More Matches**  from the original Information Page, if the user doesn't think the plants match, they are able to search other matches from a button at the bottom right. 
- **Previous Uploads** from the Home Page, the user is able to go into their local history and see the past pictures and matches that they had made in the app.

[Full phase 2 report](design/)

# Phase 3: Usability Evaluation

**Executive Summary**

The goal of this phase was to create a workable prototype and to collect data on users using the prototype in two different scenarios. We aim to use this information to imporve the prototype and further the usability of the overall app
- Users don't understand that our app **works offline**
- **Comparing** two plant images increases user confidence in the result
- Users find that the **more possible matches** button is not visible enough
- **Home page icons** confused a couple users, specifically they want to see them switched around to match snapchat's UI

[Full phase 3 report](evaluation/)
