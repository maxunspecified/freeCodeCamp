![freeCodeCamp.org Social Banner](https://s3.amazonaws.com/freecodecamp/wide-social-banner.png)

[![Pull Requests Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![first-timers-only Friendly](https://img.shields.io/badge/first--timers--only-friendly-blue.svg)](http://www.firsttimersonly.com/)
[![Open Source Helpers](https://www.codetriage.com/freecodecamp/freecodecamp/badges/users.svg)](https://www.codetriage.com/freecodecamp/freecodecamp)
[![Setup Automated](https://img.shields.io/badge/setup-automated-blue?logo=gitpod)](https://gitpod.io/from-referrer/)

## freeCodeCamp.org's open-source codebase and curriculum

[freeCodeCamp.org](https://www.freecodecamp.org) is a friendly community where you can learn to code for free. It is run by a [donor-supported 501(c)(3) nonprofit](https://donate.freecodecamp.org) to help millions of busy adults transition into tech. Our community has already helped more than 10,000 people get their first developer job.

Our full-stack web development and machine learning curriculum is completely free and self-paced. We have thousands of interactive coding challenges to help you expand your skills.

## Table of Contents

- [Certifications](#certifications)
- [The Learning Platform](#the-learning-platform)
- [Reporting Bugs and Issues](#reporting-bugs-and-issues)
- [Reporting Security Issues and Responsible Disclosure](#reporting-security-issues-and-responsible-disclosure)
- [Contributing](#contributing)
- [Platform, Build and Deployment Status](#platform-build-and-deployment-status)
- [License](#license)

### Certifications

freeCodeCamp.org offers several free developer certifications. Each of these certifications involves building 5 required web app projects, along with hundreds of optional coding challenges to help you prepare for those projects. We estimate that each certification will take a beginner programmer around 300 hours to earn.

Each of these 50 projects in the freeCodeCamp.org curriculum has its own agile user stories and automated tests. These help you build up your project incrementally and ensure you've fulfilled all the user stories before you submit it.

You can pull in these test suites through [freeCodeCamp's CDN](https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js). This means you can build these projects on websites like CodePen and Glitch - or even on your local computer's development environment.

Once you???ve earned a certification, you will always have it. You will always be able to link to it from your LinkedIn or r??sum??. And when your prospective employers or freelance clients click that link, they???ll see a verified certification specific to you.

The one exception to this is if we discover violations of our [Academic Honesty Policy](https://www.freecodecamp.org/academic-honesty). When we catch people unambiguously plagiarizing (submitting other people's code or projects as their own without citation), we do what all rigorous institutions of learning should do - we revoke their certifications and ban those people.

Here are our ten core certifications:

#### 1. Responsive Web Design Certification

- [Basic HTML and HTML5](https://learn.freecodecamp.org/responsive-web-design/basic-html-and-html5)
- [Basic CSS](https://learn.freecodecamp.org/responsive-web-design/basic-css)
- [Applied Visual Design](https://learn.freecodecamp.org/responsive-web-design/applied-visual-design)
- [Applied Accessibility](https://learn.freecodecamp.org/responsive-web-design/applied-accessibility)
- [Responsive Web Design Principles](https://learn.freecodecamp.org/responsive-web-design/responsive-web-design-principles)
- [CSS Flexbox](https://learn.freecodecamp.org/responsive-web-design/css-flexbox)
- [CSS Grid](https://learn.freecodecamp.org/responsive-web-design/css-grid)
  <br />
  <br />
  **Projects**: Tribute Page, Survey Form, Product Landing Page, Technical Documentation Page, Personal Portfolio Webpage

#### 2. JavaScript Algorithms and Data Structures Certification

- [Basic JavaScript](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript)
- [ES6](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/es6)
- [Regular Expressions](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/regular-expressions)
- [Debugging](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/debugging)
- [Basic Data Structures](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-data-structures)
- [Algorithm Scripting](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-algorithm-scripting)
- [Object-Oriented Programming](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/object-oriented-programming)
- [Functional Programming](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/functional-programming)
- [Intermediate Algorithm Scripting](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/intermediate-algorithm-scripting)
  <br />
  <br />
  **Projects**: Palindrome Checker, Roman Numeral Converter, Caesar's Cipher, Telephone Number Validator, Cash Register

#### 3. Front End Libraries Certification

- [Bootstrap](https://learn.freecodecamp.org/front-end-libraries/bootstrap)
- [jQuery](https://learn.freecodecamp.org/front-end-libraries/jquery)
- [Sass](https://learn.freecodecamp.org/front-end-libraries/sass)
- [React](https://learn.freecodecamp.org/front-end-libraries/react)
- [Redux](https://learn.freecodecamp.org/front-end-libraries/redux)
- [React and Redux](https://learn.freecodecamp.org/front-end-libraries/react-and-redux)
  <br />
  <br />
  **Projects**: Random Quote Machine, Markdown Previewer, Drum Machine, JavaScript Calculator, Pomodoro Clock

#### 4. Data Visualization Certification

- [Data Visualization with D3](https://learn.freecodecamp.org/data-visualization/data-visualization-with-d3)
- [JSON APIs and Ajax](https://learn.freecodecamp.org/data-visualization/json-apis-and-ajax)
  <br />
  <br />
  **Projects**: Bar Chart, Scatterplot Graph, Heat Map, Choropleth Map, Treemap Diagram

#### 5. APIs and Microservices Certification

- [Managing Packages with Npm](https://learn.freecodecamp.org/apis-and-microservices/managing-packages-with-npm)
- [Basic Node and Express](https://learn.freecodecamp.org/apis-and-microservices/basic-node-and-express)
- [MongoDB and Mongoose](https://learn.freecodecamp.org/apis-and-microservices/mongodb-and-mongoose)
  <br />
  <br />
  **Projects**: Timestamp Microservice, Request Header Parser, URL Shortener, Exercise Tracker, File Metadata Microservice

#### 6. Quality Assurance Certification

- [Quality Assurance and Testing with Chai](https://learn.freecodecamp.org/information-security-and-quality-assurance/quality-assurance-and-testing-with-chai)
- [Advanced Node and Express](https://learn.freecodecamp.org/information-security-and-quality-assurance/advanced-node-and-express)
  <br />
  <br />
  **Projects**: Metric-Imperial Converter, Issue Tracker, Personal Library, Sudoku Solver, American British Translator
   
#### 7. Scientific Computing with Python Certification

- [Introduction to Python for Everybody](https://learn.freecodecamp.org/scientific-computing-with-python/python-for-everybody)
  <br />
  <br />
  **Projects**: Arithmetic Formatter, Time Calculator, Budget App, Polygon Area Calculator, Probability Calculator

#### 8. Data Analysis with Python Certification

- [Data Analysis with Python Course](https://learn.freecodecamp.org/data-analysis-with-python/data-analysis-with-python-course)
- [NumPy](https://learn.freecodecamp.org/data-analysis-with-python/numpy)
  <br />
  <br />
  **Projects**: Mean-Variance-Standard Deviation Calculator, Demographic Data Analyzer, Medical Data Visualizer, Page View Time Series Visualizer, Sea Level Predictor
  
#### 9. Information Security Certification

- [Information Security with HelmetJS](https://learn.freecodecamp.org/information-security/information-security-with-helmetjs)
- [Python for Penetration Testing](https://learn.freecodecamp.org/information-security/python-for-penetration-testing)
  <br />
  <br />
  **Projects**: Stock Price Checker, Anonymous Message Board, Port Scanner, SHA-1 Password Cracker, Secure Real Time Multiplayer Game 
  
#### 10. Machine Learning with Python Certification

- [TensorFlow](https://learn.freecodecamp.org/machine-learning-with-python/tensorflow)
- [How Neural Networks Work](https://learn.freecodecamp.org/machine-learning-with-python/how-neural-networks-work)
  <br />
  <br />
  **Projects**: Rock Paper Scissors, Cat and Dog Image Classifier, Book Recommendation Engine using KNN, Linear Regression Health Costs Calculator, Neural Network SMS Text Classifier
  
#### Legacy Full Stack Development Certification

Once you have earned the Responsive Web Design, Algorithms and Data Structures, Front End Libraries, Data Visualization, APIs and Microservices, and Legacy Information Security and Quality Assurance certifications, you'll be able to claim your freeCodeCamp.org Full Stack Development Certification. This distinction signifies that you've completed around 1,800 hours of coding with a wide range of web development tools.

#### Legacy Certifications

We also have 4 legacy certifications dating back to our 2015 curriculum, which are still available. All of the required projects for these legacy certifications will remain available on freeCodeCamp.org.

- Legacy Front End Development Certification
- Legacy Data Visualization Certification
- Legacy Back End Development Certification
- Legacy Information Security and Quality Assurance Certification

### The Learning Platform

This code is running live at [freeCodeCamp.org](https://www.freecodecamp.org).

Our community also has:

- A [forum](https://forum.freecodecamp.org) where you can usually get programming help or project feedback within hours.
- A [YouTube channel](https://youtube.com/freecodecamp) with free courses on Python, SQL, Android, and a wide variety of other technologies.
- A [podcast](https://podcast.freecodecamp.org/) with technology insights and inspiring stories from developers.
- A [Developer News](https://www.freecodecamp.org/news) publication, a free, open source, no-ads place to cross-post your blog articles.

> #### [Join our community here](https://www.freecodecamp.org/signin).

### Reporting Bugs and Issues

If you think you've found a bug, first read the [how to report a bug](https://forum.freecodecamp.org/t/how-to-report-a-bug/19543) article and follow its instructions.

If you're confident it's a new bug and have confirmed that someone else is facing the same issue, go ahead and create a new GitHub issue. Be sure to include as much information as possible so we can reproduce the bug.

### Reporting Security Issues and Responsible Disclosure

If you think you have found a vulnerability, _please report responsibly_. Don't create GitHub issues for security issues. Instead, please send an email to `security@freecodecamp.org` and we'll look into it immediately.

We appreciate any responsible disclosure of vulnerabilities that might impact the integrity of our platforms and users. While we do not offer any bounties or swags at the moment, we'll be happy to list your name in our [Hall of Fame](HoF.md) for security researchers.

### Contributing

The freeCodeCamp.org community is possible thanks to thousands of kind volunteers like you. We welcome any and all contributions to the community and are excited to welcome you aboard.

> #### [Please follow these steps to contribute](https://contribute.freecodecamp.org).

### Platform, Build and Deployment Status

The general platform status for all our applications is available at [`status.freecodecamp.org`](https://status.freecodecamp.org). The build and deployment status for the code is available in [our DevOps Guide](/docs/devops.md).

### License

Copyright ?? 2020 freeCodeCamp.org

The content of this repository is bound by the following licenses:

- The computer software is licensed under the [BSD-3-Clause](LICENSE.md) license.
- The learning resources in the [`/curriculum`](/curriculum) directory including their subdirectories thereon are licensed under the [CC-BY-SA-4.0](/curriculum/LICENSE.md) license.