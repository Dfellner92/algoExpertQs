### General

- AVOID
    + Being too vague!
        - this includes "how you handled a past situation" or "steps you
          took on a certain project"
    + confrontation, disrespect (duh)

- TRY 
    + Striking balance between
        - Highlighting good qualities about yourself (intellectually curious, can lead projects)
        - Ability to work in team (ability to help others)
    + Answer with stories that highlight the two aforementioned (prepare)
    + If you're being asked about an experience but you've never had it, you could 
      say "I've actually never had that experience, but I can tell you how I would have
      handled it had I been in such a situation."
    + You want a balance between specificity and being too vague
    + Don't ramble


### Low Performer

##### Imagine you had a low performer on your team. How would you handle the situation? What would you do to help them?

One of the sprints with the Social App involved implementing video calls. On a team with another entry level engineer and our supervising senior engineer who was our de facto product owner, he wanted us to try integrating webRTC. I was working with our product owner to implement the UI while the other entry level engineer wanted requested to focus on implementing webRTC and any needed middleware  on the app.js component to ensure we wouldn't have issues with our AWS connection. During our morning "standups", this other engineer would ensure us he'd always be able to connect to webRTC with no issues with AWS, but about 3/4ths through the sprint, we realized even though he was submitting PRs, he hadn't added in the WebRTC logic. I asked him if he was having trouble at any level with this, and as it turns out he was having trouble with AWS connectivity at the deployed level. While everything he did was in making a valiant effort, had we learned about this earlier in the sprint it would have given us the time to make changes to finish on time. However, in the background, he was doing research on his own time on websocket as an alternative plan. So we pair programmed to implement web socket and he was able to teach me and our senior dev everything we needed for this. However, we did have to extend the sprint another 2 days. But what we did do was, A) establish better communication as a team in dealing with what was a blind spot and B) we all learned about websocket and how it pairs with AWS amplify

### Team Conflict

##### Describe a time when there was a conflict within your team. How did you help resolve the conflict? Did you do anything to prevent it in the future?

I began my latest freelance position by being onboarded by a senior freelancer to the project I'd be working on. He said I'd be working on the React frontend with another developer, who was primarily a backend guy. I quickly realized that this project had undergone very little modularity and refactoring, and this was something that was making state very difficult to work with. I found out at the next day's morning meeting that the other developer working with me had begun trying to implement redux as fix for the tough to track state. I was now being asked by him to help with this, as he was running into syntax issues. I told him that implementing redux at this point wasn't necessarily prudent. He now felt like I was trying to micromanage the situation but instead I felt the need to firmly say I never suggested redux, and that, given we weren't at the point of this project for user authentication or any complex global state, we could simply build a higher order context component to avoid prop drilling, as this would be quicker than implenting redux's flux pattern and would make our root level components much more manageable. I wanted to make sure he understood I had nothing but good intentions, so I helped with showing him the simplicity of context. By ultimately using context as a stopgap, when it came time to implement user authentication, we were able to move to redux much easier. 