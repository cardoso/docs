---
permalink: /contributing/google-summer-of-code-2020/

redirect_from:
  - /contributing/google-summer-of-code/
---

[![Google Summer of Code 2020](https://github.com/Sing-Li/bbug/raw/master/images/gsoclogo.jpg)](https://summerofcode.withgoogle.com/)

# Google Summer of Code 2020

## How to apply

Rocket.Chat will be applying to become a mentoring organization for Google Summer of Code in 2020.

For students, application for the GSoC 2020 season opens on March 16, 2020.   Please see [GSoC timeline](#timeline) for more details.

### About Rocket.Chat GSoC 2020

For ideas, check out our growing [list of ideas](#project-ideas) for some inspiration.

Come meet our global community of 350+ mentors and students for GSoC 2019 and get some real-time help on next steps, please visit our 24 x 7 community server channel:

<https://open.rocket.chat/channel/gsoc2020>

For offline discussions, we have a discussion forum:

<https://forums.rocket.chat/c/gsoc/gsoc2020/70>

If you have ideas and proposals that are not on our ideas list, or if a mentor is not available, please email to:

   gsoc@rocket.chat

Interested students are also encouraged to interact with our contributor community on GitHub:

<https://github.com/RocketChat/Rocket.Chat>

Enthusiasm and interest are extremely high this year; over 25 candidate students have already started to interact with our community and contributing to the repositories!  Together, they have already contributed over 100 issues and over 18 merged PRs to our various projects.  We are maintaining a real-time updated leaderboard for at-a-glance student (candidates) contribution here:

<https://gsoc.rocket.chat/>

The leaderboard project **itself** is open source, created and maintained by our student (candidates).  All potential GSoC organizations are welcome to use and deploy it (the project has a super friendly MIT license - just like Rocket.Chat).

<https://github.com/lolimay/GSoC-Contribution-Leaderboard-Node>

## Project Ideas

### Improve Documentation Framework (Versioning)

- **Mentors**: [@martin.scholeler](https://open.rocket.chat/direct/martin.schoeler), [@guilherme.cruz](https://open.rocket.chat/direct/guilherme.cruz)
- **Description**: The main objective of this project is to add a versioning capacity to the documentation, while maintaining a relatively simple file structure and ease of use. In addition, add support for multi-lingual documentation and increase the ease of use of the documentation generation and hosting framework to ease the barrier of entry for contributors trying to run the environment on their own machines, making it more contributor friendly.
- **Desirable Skills**: Familiarity with Ruby on Rails development. Working knowledge of Jekyll and documentation generation framework highly useful.

### Omnichannel: Support for Voice and Video Calls

- **Mentors**: @gazzo, @tazzo
- **Description**: We've been working on our new Omnichannel solution and it's time to add two great new features that will make Omnichannel even more powerful: voice and video calls! The idea is to integrate Omnichannel with the providers already supported in Rocket.Chat, such as Jitsi, WebRTC, BigBlueButton and so on. With these two new features, Omnichannel users will be able to initiate video and audio calls between them and Omnichannel agents.
- **Desirable Skills**: Familiarity with Rocket.Chat/Omnichannel development, ReactJS/PreactJS, Voice and Video communication

### Alexa Skill(s) Improvement

- **Mentors**: @ashish.jha @prajval.raval1
- **Project repository**: <https://github.com/RocketChat/alexa-rocketchat>
- **Description**: Bring access of Rocket.Chat into the world of 100 million+ Alexa enabled devices. The project should aim beyond the obvious TTS <-> STT "Rocket.Chat bridging" of intelligent VUI terminal devices and create innovative, high valued user experiences to the Alexa ecosystem - powered by open source Rocket.Chat. Google Home/Assistant devices support, if possible, should also be considered concurrently. The focus will be on devoting more time to improve the features which add more advantage and serve a frictionless experience when used via voice compared to features which have a limited use and are better performed using a GUI.
- **Desirable Skills**: Familiarity with Alexa skills development and conversational design. NodeJS Server Development and Rocket.Chat source code. Experience with interfacing external sources and systems into Alexa skills. Passion for global conversational interaction enablement. Familiarity with Google Action development ideal.

### Add Support for Bixby

- **Mentors**: @ashish.jha @prajval.raval1
- **Project repository**: <https://github.com/RocketChat/alexa-rc-multiserver-client>
- **Description**: Last year we explored the possibilities of having a Rocket.Chat Amazon Alexa Skill and a Rocket.Chat Action on Google. This project should aim to explore adding a Samsung Bixby Capsule for Rocket.Chat. Bixby is a next-generation, conversational assistant platform that was created to help users get things done in a more efficient, personalized and natural way. The way Bixby focuses on a multimodal approach from the very start could help eliminate the nuances involved in building an intricate voice-only experience.
- **Desirable Skills**: Familiarity with VUI/Bixby development. Experience with interfacing external sources and systems into Alexa skills. Passion for global conversational interaction enablement. Familiarity with Javascript ideal.

### Google Action Improvement

- **Mentors**: @ashish.jha @prajval.raval1
- **Project repository**: <https://github.com/RocketChat/google-action-rocketchat>
- **Description**: Bring access of Rocket.Chat into the world of 1 Billion+ Google Assistant enabled devices. The project should aim beyond the obvious TTS <-> STT "Rocket.Chat bridging" of intelligent VUI terminal devices and create innovative, high valued user experiences to the Google Assistant ecosystem - powered by open source Rocket.Chat. The project will aim towards making current action compaitable with Multisever proxy and publishing of Google Action of on its store, of course while adding more features to it such as Interactive Canvas, App Actions etc.  This project will also focus on making current documentation more streamlined and "easy to refer" for newcomers.
- **Desirable Skills**: Familiarity with Google Actions development, Dialogflow, NodeJS Server Development and Rocket.Chat source code. Experience with interfacing external sources and systems into Google Action. Passion for global converstational interaction enablement.

### Omnichannel:  Chatbot support for RASA and Dialogflow

- **Mentors**: @renatobecker
- **Description**: The goal of this project would be to chatbot framework support for popular BOT frameworks - RASA and Dialogflow.
- **Desirable Skills**: Experience in working with Dialogflow or RASA desirable.  Ideally an experienced Python developer with some Javascript skills.

### Nextcloud Video Management

- **Mentors**: @guilherme.gazzo
- **Description**: Add the ability to manage and access recorded and previously live streamed video within the Rocket.Chat integrated Nextcloud environment. Similar to Youtube but with a chat-centric access interface.
- **Desirable Skills**: Familiarity with Rocket.Chat and Nextcloud development.  Deep understanding of current digital streaming and recorded media standards a big plus.

### Apple Watch App

- **Mentors**: @djorkaeff.alexandre @diego.mello
- **Description**: Create an Apple Watch application that replicates the most basic features we have in our iOS mobile client, such as viewing the chat rooms and reading the messages. Let the user ask Siri to read the latest messages, send messages or respond to a message.
- **Desirable Skills**: Familiarity with WatchKit development on WatchOS & SiriKit, Familiarity with React Native.

### Target official/experimental Mobile apps using GitHub Actions (CI)

- **Mentors**: @djorkaeff.alexandre @diego.mello
- **Description**: Create build of our 4 apps on GitHubCI, 2 Android Apps and 2 iOS Apps (Official and Experimental).
- **Desirable Skills**: Familiarity with ReactNative, FastLane, Android & iOS build apps.

### Add Analytics to Mobile Apps

- **Mentors**: @djorkaeff.alexandre @diego.mello
- **Description**: We use Firebase to track some analytics, now we want to know data like 'how many people clicked on login?'. You need to add firebase analytics to our app and add track analytics of the most important features and events.
- **Desirable Skills**: Familiarity with ReactNative and Firebase Analytics.

### Share Location on Mobile Apps

- **Mentors**: @djorkaeff.alexandre @diego.mello
- **Description**: We have this feature on our web client, server has an implementation about this, you only need to implement this feature on our Mobile Client and ability to select and share a location (based or not on user's location), custom message to show the location shared and need to be able to open this location on maps apps.
- **Desirable Skills**: Familiarity with ReactNative and Rocket.Chat codebase.

### Mobile Apps Accessibility

- **Mentors:**  @matheus.cardoso
- **Project repository**: <https://github.com/RocketChat/Rocket.Chat.ReactNative>
- **Description:** Android and iOS both support gesture-based screen readers that let you enjoy using the phone even if you don’t see the screen. This is especially important for those with low or no vision. We want to make Rocket.Chat for everyone. A blind user should be able to easily add servers, change servers, read messages and send messages, as well as other additional functions such as editing profile and creating channels. The proposal should contain a per-screen study of the current App's state of accessibility (what is missing and what needs to be improved), and a roadmap to take it to a delightful state.
- **Desirable Skills:** We are looking for a student who is familiar with team work, developing mobile Apps using React Native and JavaScript, as well as writing maintainable code with Unit Tests and having some familiarity with Voice Over (iOS), TalkBack (Android) and Accessibility. Knowledge of Swift/Objective-C and Kotlin/Java might come in handy for some of the trickier tasks.

### Uber Rocket.Chat App

- **Mentors**: [@marcos.defendi](https://open.rocket.chat/direct/marcos.defendi)
- **Description**: The goal of this project is allow users to call their Uber rides directly from Rocket.Chat.
- **Desirable Skills**: Familiarity with Typescript and OOP concepts.

### Vocabulary Booster Rocket.Chat App

- **Mentors**: [@marcos.defendi](https://open.rocket.chat/direct/marcos.defendi)
- **Description**: The goal of this project is to provide the user a way to improve his vocabulary in a certain language (English, for now), by sending him a message with a "new" word in certain periods of time (configurable). After that, the app should validate if the user has learned the meaning of the word, sending the definition and some word options, or some sentence with the word and a gap to fill. Also the app would show the user's performance. There are some API's to get the words and the meanings. e.g ([WordsAPI](https://www.wordsapi.com/), [Datamuse](https://www.datamuse.com/api/), [Oxford](https://developer.oxforddictionaries.com/), etc) (needs to be evaluated deeply)
- **Desirable Skills**: Familiarity with Typescript and OOP concepts.

## Timeline

[GSoC 2020 Timeline](https://developers.google.com/open-source/gsoc/timeline) next due dates:

**Feb 20**
List of accepted mentoring organizations published.

**February 20 - March 16**
Potential student participants discuss application ideas with mentoring organizations

**March 16 18:00 UTC**
Student application period begins - _[How to write a Proposal](https://google.github.io/gsocguides/student/writing-a-proposal.html)_

**March 31st 18:00 UTC**
Student application deadline

**April 27th 18:00 UTC**
Accepted student proposals announced

...
