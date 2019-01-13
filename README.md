<p align="center">
  <img src="https://i.imgur.com/Xv2xvly.png" alt="npm-stats" title="npm-stats.org" />
</p>

# npm-stats

Dive in to npm-stats, a fully functional graphical interface for interacting with npm package downloads and installs.

## Inspiration
I wanted to truly get a headstart in Javascript, and outside of writing memorized lines of npm init and npm install over and over again, I really didn't have a clue about what npm was. That's where npm-stats came in. The website is fully intended to help users identify key npm-packages and easily visualize npm-package data and download data throughout the years of npm's usage. This provides industry-wide developers of all experience levels with important data analytics, empowering them to make better technology decisions, regardless of whether they use npm to build small, personal-level apps or large CRM tools!

## How I built it
### Vue.js, Node.js, and [npm-api](https://www.npmjs.com/package/npm-api)
npm-stats's creation required building and utilizing functional RESTful APIs and packages to create a responsive site. The site is styled mainly with Charts.js, and a special shoutout goes to @apertureless for creating a Vue.js wrapper for the incredibly versatile Charts.js library. npm-api proved incredibly useful for providing clean, efficient npm-package data, and Node.js gave this project the dedicated back-end it needed.

## Challenges I ran into
In the process of making the site, I ran into several production issues with Vue and yarn. Additionally, I encountered severe difficulties in terms of backend fallacies and package inconsistencies that needed to be updated consistently.

## Accomplishments that I'm proud of
I'm amazed that I was able to complete npm-stats over such a small duration, especially with my serious lack of experience using Vue and Yarn. There were also multiple obstacles with designing user-interaction, so ultimately having a working version of the site pushed into production was extremely fulfilling.

## What I learned
Coming into this project as a Vue.js novice, I had absolutely no experience with anything related to the Vue framework, and minimal experience with npm servers and design. However, I was able to surpass these gaps in knowledge by poring over countless web pages of documentation and taking note of the extremely supportive Node.js community. Ultimately, challenging myself to go into this full-force and learn-by-doing truly allowed me to grow and understand the nuances of Vue.js and Node.js development. Being able to experiment with incredible libraries like D3.js and Processing before creating the final project was also a high note!

## What's next for npm-stats
I hope to expand the site into a truly responsive site complete with providing standardized npm-package documentation. I'm also actively pushing myself to create a React-based app for npm-stats, which I hope to develop in due time!

### Contributing!
If you're interested in contributing, or want to find out more information about the devs, head over to [@apertureless](https://github.com/apertureless).

Made with ♥ in 2019, with special inspiration from Medium and Jakub Juszczak.

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```
