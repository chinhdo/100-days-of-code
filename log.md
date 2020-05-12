# 100 Days Of Code - [Chinh's Log](https://github.com/chinhdo)

### Day 2: Monday May 11, 2020

**Today's Progress**

Started work on Programmer's Toolbox, a web site with tools/utilities for programmers. The site is done in React - which is pretty much brand new to me. I started a course but did not process too far yet.

* Generated skeleton React site with tooling with [`npx create-react-app`](https://reactjs.org/docs/create-a-new-react-app.html#create-react-app
* Created components for app, header, footer.
* Make some basic CSS adjustments
* Added Bootstrap

**Thoughts:**

I plan to eventually host the site on Azure at https://toolbox.chinhdo.com.

**Link to work:**

[Programmer's Toolbox Github project](https://github.com/chinhdo/programmers-toolbox)

![](assets/day2.png)

### Day 1: Sunday May 10, 2020

**Today's Progress**

* Created from cratch basic Node.js/TypeScript project with Jest, VSCODE debug support.
* Spent countless minutes figuring out some things that should be a lot simpler than they are. Grrr.
* Version 1.0 of the app can now search for tweets, and produce an HTML report with tweets for me to review and like.
* I decided for the bot to recommend tweets instead of liking the tweets itself because:
  * I want to weed out the spam posts.
  * I want to personally view and if appropriate, reply to some of the posts to give encouragement to others also going through the #100DaysOfCode journey.
  * It's also against Twitter TOS to have your bot automatically like tweets - so there's that :)

**Thoughts:**

Took me way more time than I wanted to spend on setting up a basic Node.js/TypeScript project. Still don't have debug support in Visual Studio Code working. Will work on that later. Compared with the .NET ecosystem, I can create a starter .NET console app with all basic tooling support and get up and running in less than 5 minutes.

I ended up spending way more than 1 hour on coding today. I guess I am feeling a little bit of peer pressure - the good kind :)

**Link to work:**

[twitter-bot](https://github.com/chinhdo/twitter-bot)

Generated recommendations: ![report](assets/day0-twitterbot-output.png)