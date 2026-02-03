# Sprint 2 Retrospective

Name: Zachary Lam

Student #: 0393618

Date: February, 2, 2026

## 1. What went well in the previous sprint?

- Using hooks, more specifically useState when passing them down as props was easier than expected. Prior to the sprint, I was incorporating useState (in the lab) into a single component that had no shared access and it initially troubled me on how I could share it with other components in order to keep the UI in sync. This transitioned well into implementing it into the project once I knew how to pass them down properly.

- The pagination component turned out well. I had actually played around with it in Javascript from an Udemy course I took in the past and it was familiar for me to incorporate it. I was initially curious how it would fair in React, but it was actually a lot easier using React and hooks. When incorporating pagination with vanilla JS, I had to update the DOM manually which resulted in long lines of code but in React, the logic was more concise and additionally, can scale better.

- During the lab, I had spent extra time refactoring and addressing separation of concerns with my files and directories. This transitioned well into the project as I was able to keep most helper functions contained in a separate source file, keeping the main components and their respective logic clean and solely focusing on the state the component should take in the application.

## 2. What could have gone better in the previous sprint, or went poorly?

- I should've enforced type checking more rather than declaring typeof any. Especially when it came to my mapping functions, since I was getting imperative/type errors and just gave them type any for convenience. I slightly went off track to how I approached it in the lab, especially towards type checking states when they were pass down as props. In the lab, I created types for the state props to give them a shape but failed to fully incorporate that into the project. I will have to go back and refactor in types so that the proper data is passed through and the states maintain their intended shape.

- The aside is hard to access the further you scroll down the page. This makes it a pain point for accessibility as users who add ROMs to the aside won't be able to view what they've added unless they're at the top of the application. Reflecting on it now, I should've designed the aside in a way that it remains sticky and as you scroll the contents of the aside are always in view.

- I didn't add a reset button to my form component. Initially, I had refreshed the browser to reset form inputs to quickly test out the filtering, so I overlooked the idea to add one. Users should be able to reset the filter through a button instead, as refreshing is impractical under most use cases. 

## 3. What can be done in the next sprint to improve my process?

For the next sprint, I will focus on improving the accessibility and user friendliness of newly added components. Whenever I push changes that introduce a new component or feature, I will ask both Dean and Efe to test the application and provide specific feedback on the UI/UX or accessibility. Before the next sprint review, I will address at least one pain point identified from their feedback. I will consider this goal achieved when the changes are implemented, committed, and both peers confirm the issues have been resolved.

Since this project is done as a group, I will focus on improving my GitHub collaboration and conflict management process. For the next sprint, I will review all pull requests submitted by Dean and Efe before merging into develop, even if another peer has already reviewed it. For each PR, I will leave at least one comment or question highlighting potential conflicts or implications for my branch. To meet the milestone for this, I will have to review all PRs for the next sprint, leave a meaningful comment or question by the time all of the sprint 3 requirements are moved to the done column on our Kanban.