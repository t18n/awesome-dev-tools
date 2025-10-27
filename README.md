# Awesome Dev Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of awesome development tools and resources for software developers.

- [Awesome Dev Tools](#awesome-dev-tools)
  - [Introduction](#introduction)
  - [The AWESOME list](#the-awesome-list)
    - [Development Tools](#development-tools)
      - [Integrated Development Environments (IDEs)](#integrated-development-environments-ides)
      - [Version Control Systems:](#version-control-systems)
      - [Build Artifact / Binary Management:](#build-artifact--binary-management)
      - [Testing and Debugging Tools](#testing-and-debugging-tools)
        - [Test runners](#test-runners)
        - [E2E Testing](#e2e-testing)
      - [Issue Tracking and Project Management Tools](#issue-tracking-and-project-management-tools)
    - [Front-end](#front-end)
      - [Web development](#web-development)
        - [Client-side](#client-side)
        - [Full-stack](#full-stack)
      - [Mobile Development](#mobile-development)
      - [Design](#design)
      - [Styling](#styling)
        - [Approaches](#approaches)
        - [Processors](#processors)
        - [Libraries](#libraries)
      - [JavaScript animation frameworks](#javascript-animation-frameworks)
      - [SVG libraries](#svg-libraries)
      - [Editor libraries](#editor-libraries)
      - [Web component libraries](#web-component-libraries)
      - [Cross-platform GUI frameworks](#cross-platform-gui-frameworks)
    - [Database](#database)
      - [Relational databases](#relational-databases)
      - [NoSQL databases:](#nosql-databases)
      - [Others](#others)
    - [Data analytics](#data-analytics)
      - [Data visualization tools](#data-visualization-tools)
    - [Back-end](#back-end)
      - [Headless CMS](#headless-cms)
      - [RESTful API frameworks](#restful-api-frameworks)
      - [WebSocket](#websocket)
    - [AI](#ai)
      - [Machine learning frameworks](#machine-learning-frameworks)
    - [Accessibility](#accessibility)
      - [Accessibility testing tools:](#accessibility-testing-tools)
    - [Cryptography](#cryptography)
      - [Cryptographic libraries:](#cryptographic-libraries)
    - [Workflows](#workflows)
      - [Monorepo](#monorepo)
      - [Continuous Integration (CI) tools:](#continuous-integration-ci-tools)
      - [Continuous Deployment (CD) tools:](#continuous-deployment-cd-tools)
    - [Documentation and knowledge management tools:](#documentation-and-knowledge-management-tools)
      - [Documentation tools:](#documentation-tools)
      - [Knowledge management tools:](#knowledge-management-tools)
    - [CI](#ci)
      - [Cloud-based CI services:](#cloud-based-ci-services)
    - [Benchmarks](#benchmarks)
      - [Benchmarking tools:](#benchmarking-tools)
  - [TODO](#todo)
  - [Contributing](#contributing)
  - [License](#license)

## Introduction

Welcome to Awesome Dev Tools! This repository is a community-driven list of high-quality tools, libraries, and frameworks related to software development. The aim of this repository is to curate and showcase the best tools and resources to help developers be more productive and write better code.

Whether you're a front-end developer, back-end developer, or full-stack developer, this repository has something for you. It includes a wide range of categories, including development tools, front-end and back-end frameworks, testing and debugging tools, and much more.

We encourage contributions from the community, so if you have a favorite development tool or resource that you think should be included in this list, please submit a pull request!

## The AWESOME list

### Development Tools

#### Developer Utilities

  - [ToolHover](https://toolhover.com) - Free online developer utilities including JSON formatter & validator, password generator, hash
  generator, Base64 encoder/decoder, text counter & converter, and QR code generator.

#### Integrated Development Environments (IDEs)

- [Visual Studio Code](https://code.visualstudio.com/): A free, lightweight, cross-platform source code editor by Microsoft for Windows, Linux, and macOS, with support for debugging, syntax highlighting, intelligent code completion, Git integration, and more. Built with Electron and TypeScript.
- [Vim](https://www.vim.org/): a highly customizable text editor that's designed to be used entirely from the keyboard, with a focus on speed and efficiency
- [Neovim](https://neovim.io/): a fork of Vim that provides improved performance and extensibility, while still maintaining compatibility with Vim's core features and workflows
- [Eclipse](https://www.eclipse.org/): An open-source IDE written in Java, mainly used for Java development but also supports other programming languages via plug-ins. Available for Windows, Linux, and macOS.
- [IntelliJ IDEA](https://www.jetbrains.com/idea/): A powerful and customizable IDE for Java, Kotlin, and other programming languages, with advanced code analysis, debugging, and testing tools. Available for Windows, Linux, and macOS.
- [Sublime Text](https://www.sublimetext.com/): A lightweight code editor used to write and edit code in various programming languages. Provides a range of features for code editing and customization. Available for Windows, Linux, and macOS.
- [Android Studio](https://developer.android.com/studio): the official integrated development environment (IDE) for developing Android apps, providing a wide range of tools and features for building and testing Android applications

#### Version Control Systems:

- [Git](https://git-scm.com/): A free and open-source distributed version control system that allows developers to collaborate on projects and track changes to code. Available for Windows, Linux, and macOS.
- [Subversion](https://subversion.apache.org/): A centralized version control system that can be used to track changes to files and directories over time. Available for Windows, Linux, and macOS.

#### Build Artifact / Binary Management:

- [Buildstash](https://buildstash.com): A web-based platform for managing built software binaries, integrating with CI/CD to automate archival, and allowing distribution of binaries to collaborators, testers, and users.

#### Testing and Debugging Tools

##### Test runners

- [Jest](https://jestjs.io/): a popular testing framework for JavaScript that provides a simple and easy-to-use interface for writing and running tests, with built-in support for mocking and code coverage reporting
- [Mocha](https://mochajs.org/): a JavaScript testing framework that provides a flexible and extensible testing interface, allowing developers to choose their own assertion library and mocking tools
- [Xdebug](https://xdebug.org/): A PHP extension for debugging PHP scripts. Available for Windows, Linux, and macOS.
- [JUnit](https://junit.org/junit5/): A popular testing framework for Java programmers. Used for unit testing, integration testing, and more. Can be used with various IDEs and build tools.

##### E2E Testing

- [Cypress](https://www.cypress.io/): a JavaScript end-to-end testing framework that provides an easy-to-use API for writing and running tests, with a focus on fast and reliable test execution and debugging
- [Playwright](https://playwright.dev/): an open-source Node.js library for automating browsers and mobile devices, providing a powerful and flexible API for writing and running end-to-end tests and browser automation scripts
- [Selenium](https://www.selenium.dev/): An open-source tool for automating web browsers to test web applications. Supports a range of programming languages including Java, C#, Python, and more. Works on Windows, Linux, and macOS.
- [Appium](http://appium.io/): an open-source test automation tool for mobile applications that supports a wide range of platforms and devices, allowing developers to write and run tests using a variety of programming languages and testing frameworks
- [Detox](https://github.com/wix/Detox): a gray-box end-to-end testing and automation framework for mobile apps that provides full control over the device and testing environment, with a focus on reliable and maintainable test code

##### API Mocking and Debugging

- [Beeceptor](https://beeceptor.com/): A no-code, cloud based, multi-protocol mock server and debugging tool, used to create custom API endpoints for capturing, inspecting, and mocking HTTP requests and webhooks. Crucial for testing API integrations and frontend development when the backend is unavailable.
- [Microcks](https://microcks.io/): The open source ([CNCF](https://www.cncf.io/projects/microcks/) project), cloud native tool for **API Mocking** and Testing with [GraphQL support](https://microcks.io/blog/graphql-features-what-to-expect/) 🎥 [GraphQL conf 2023](https://youtu.be/UjDnrrTp7uI?si=M6S4l_Bukp9CEYl4)
- [WireMock](https://wiremock.org/):  Open-source, flexible multi-protocol service virtualization tool by which external API dependencies can be reliably simulated and stubbed for testing and isolated development environments.

#### Workflow Monitoring Tools

- [Telert](https://github.com/navig-me/telert) – Lightweight open-source CLI tool to send Telegram, Slack, Desktop, or Audio notifications when terminal commands finish.

#### Issue Tracking and Project Management Tools

- [Jira](https://www.atlassian.com/software/jira): A proprietary issue tracking, bug tracking, and project management tool developed by Atlassian. Used by agile teams to plan, track, and release software. Available on the cloud and on-premise.
- [Asana](https://asana.com/): A web and mobile application designed to help teams organize, track, and manage their work. Available on the web and on mobile devices.
- [Trello](https://trello.com/): A web-based project management tool that allows users to create boards, lists, and cards to organize and prioritize their work. Available on the web and on mobile devices.

### Front-end

#### Web development

##### Client-side

- [React](https://reactjs.org/): a JavaScript library for building user interfaces
- [Vue.js](https://vuejs.org/): a progressive JavaScript framework for building user interfaces
- [Angular](https://angular.io/): a TypeScript-based open-source web application framework
- [Nuxt.js](https://nuxtjs.org/): a higher-level framework based on Vue.js for building server-rendered web applications and static sites
- [Svelte](https://svelte.dev/): a front-end framework that compiles your code to highly efficient JavaScript, with a focus on reactivity and simplicity
- [Solid.js](https://www.solidjs.com/): a fast, reactive JavaScript library for building user interfaces, inspired by React and Vue.js

##### Full-stack

- [Next.js](https://nextjs.org/): a React-based framework for building server-rendered web applications
- [Ruby on Rails](https://rubyonrails.org/): a popular web framework for the Ruby programming language
- [Django](https://www.djangoproject.com/): a high-level Python web framework that encourages rapid development and clean, pragmatic design
- [Express.js](https://expressjs.com/): a fast, unopinionated, minimalist web framework for Node.js
- [Flask](https://flask.palletsprojects.com/): a lightweight Python web framework that's easy to learn and use
- [Spring](https://spring.io/): a Java framework for building web and enterprise applications
- [ASP.NET](https://dotnet.microsoft.com/apps/aspnet): a popular web framework for building web applications with .NET
- [Laravel](https://laravel.com/): a PHP web framework with expressive, elegant syntax and a focus on developer happiness

#### Mobile Development

- [React Native](https://reactnative.dev/): a JavaScript framework for building mobile apps
- [Flutter](https://flutter.dev/): an open-source UI software development kit created by Google
- [Ionic](https://ionicframework.com/): a cross-platform mobile app development framework based on Angular
- [Xamarin](https://dotnet.microsoft.com/apps/xamarin): a Microsoft-owned platform for building native Android, iOS, and Windows apps with .NET and C#
- [NativeScript](https://nativescript.org/): an open-source framework for building native mobile apps with Angular, Vue.js, or TypeScript
- [Retool Mobile](https://retool.com/): Retool Mobile is a no-code tool that makes building native iOS and Android apps faster for developers. Use languages you already know—like JavaScript and SQL—to instantly create and deploy apps for your mobile workforce.

#### Design

- [Figma](https://www.figma.com/): a cloud-based design tool for creating user interfaces, providing a powerful and collaborative interface for designing and prototyping web and mobile applications
- [Sketch](https://www.sketch.com/): a digital design tool for creating user interfaces, providing a range of vector editing tools and a streamlined workflow for creating high-quality designs
- [Adobe XD](https://www.adobe.com/products/xd.html): a vector-based design tool for creating user interfaces and experiences, providing a powerful and flexible interface for designing and prototyping web and mobile applications

#### Styling

##### Approaches

- [CSS Modules](https://github.com/css-modules/css-modules): a CSS methodology and tool for locally-scoped CSS, making it easier to manage styles in large web applications
- [CSS-in-JS](https://github.com/cssinjs/): a technique for writing and managing styles in JavaScript, allowing for dynamic and responsive CSS that's easier to test and maintain

##### Processors

- [Sass](https://sass-lang.com/): a popular CSS preprocessor that provides more advanced features, such as variables, mixins, and nested rules, making it easier to write and maintain large-scale stylesheets
- [SCSS](https://sass-lang.com/documentation/syntax#scss): a more modern version of Sass that uses a syntax that's closer to traditional CSS, making it easier for developers to learn and adopt
- [Less](http://lesscss.org/): a CSS preprocessor that provides a simpler syntax than Sass, but still offers many of the same features and benefits, such as variables and mixins
- [PostCSS](https://postcss.org/): a CSS postprocessor that can transform your CSS in a variety of ways, including adding vendor prefixes, optimizing your CSS, and more

##### Libraries

- [Headless UI](https://headlessui.dev/): a set of completely unstyled, fully accessible UI components for building web applications with Tailwind CSS and more
- [Chakra UI](https://chakra-ui.com/): a popular React component library with a focus on accessibility and ease of use
- [Tailwind CSS](https://tailwindcss.com/): a utility-first CSS framework that provides a set of pre-defined styles and classes, making it easy to build custom designs without writing custom CSS
- [Materialize](https://materializecss.com/): A modern responsive front-end framework based on Google's Material Design. Includes pre-built CSS classes and components for building responsive websites. Available for HTML, CSS, and JavaScript.

#### JavaScript animation frameworks

- [Framer Motion](https://www.framer.com/motion/): a production-ready motion library for React, used to create animations and gestures for your web applications
- [GreenSock Animation Platform (GSAP)](https://greensock.com/gsap/): A high-performance animation library for HTML5 and JavaScript, with support for animating CSS styles, SVG, canvas, and more. Available for HTML, CSS, and JavaScript.
- [Anime.js](https://animejs.com/): A lightweight animation library for JavaScript, with support for CSS properties, SVG, DOM attributes, and more. Available for HTML, CSS, and JavaScript.
- [Three.js](https://threejs.org/): A lightweight 3D animation library for JavaScript, used to create 3D animations and games in the web browser. Available for HTML, CSS, and JavaScript.
- [Lottie](https://airbnb.io/lottie/): an open-source library for rendering After Effects animations in real-time on the web, providing a simple and flexible API for adding animations to your web pages and applications

#### SVG libraries

- [Snap.svg](http://snapsvg.io/): A JavaScript library for creating and animating SVG graphics on the web. Available for HTML, CSS, and JavaScript.
- [D3.js](https://d3js.org/): A JavaScript library for creating dynamic and interactive data visualizations in the web browser. Available for HTML, CSS, and JavaScript.
- [Raphael.js](http://dmitrybaranovskiy.github.io/raphael/): A lightweight JavaScript library for working with vector graphics on the web. Available for HTML, CSS, and JavaScript.
- [SVGO](https://github.com/svg/svgo): an open-source tool for optimizing SVG files, providing a wide range of optimizations and options for reducing file size and improving rendering performance

#### Editor libraries

- [TipTap](https://www.tiptap.dev/): a framework for building rich text editors in Vue.js, providing a powerful and flexible set of tools for creating custom editors and handling user input
- [Draft.js](https://draftjs.org/): an open-source library for building rich text editors in React, providing a powerful and extensible set of tools for handling text input and rendering complex document structures
- [Lexical](https://lexical.ooo/): a JavaScript library for building custom text editors, providing a simple and extensible API for handling text input and rendering formatted text
- [Editor.js](https://editorjs.io/): a block-based editor for creating articles, blog posts, and other rich content, providing a range of blocks for handling text, images, and other media
- [ProseMirror](https://prosemirror.net/): a toolkit for building rich-text editors in the browser, providing a powerful and flexible set of tools for handling text input and rendering complex document structures
- [Slate.js](https://www.slatejs.org/): a completely customizable framework for building rich-text editors, providing a flexible and powerful set of tools for handling user input and rendering complex document structures
- [Editable.js](https://github.com/medialize/Editable.js): a library for creating in-browser WYSIWYG editors, providing a simple and easy-to-use API for adding rich text editing capabilities to your web pages and applications

#### Web component libraries

- [Polymer](https://polymer-library.polymer-project.org/): A JavaScript library for building web components and creating reusable custom elements for web pages. Available for HTML, CSS, and JavaScript.
- [LitElement](https://lit-element.polymer-project.org/): A lightweight web component library built on top of Polymer, used to create and share reusable UI components for web pages. Available for HTML, CSS, and JavaScript.

#### Cross-platform GUI frameworks

- [Tauri](https://tauri.studio/): an open-source framework for building cross-platform desktop applications with web technologies, providing a flexible and powerful API for accessing native functionality and interacting with the operating system
- [Electron](https://www.electronjs.org/): A popular framework for building cross-platform desktop applications using web technologies. Supports HTML, CSS, and JavaScript.
- [Qt](https://www.qt.io/): A comprehensive, cross-platform C++ application development framework used to create native-looking applications with minimal coding. Supports various platforms and programming languages.

### Database

#### Relational databases

- [MySQL](https://www.mysql.com/): An open-source relational database management system that supports SQL queries and can be used with various programming languages. Available on Windows, Linux, and macOS.
- [PostgreSQL](https://www.postgresql.org/): A powerful, open-source object-relational database management system that supports SQL queries and can be used with various programming languages. Available on Windows, Linux, and macOS.

#### NoSQL databases:

- [MongoDB](https://www.mongodb.com/): A document-based NoSQL database that uses JSON-like documents to store data. Supports various programming languages and is available on Windows, Linux, and macOS.
- [Couchbase](https://www.couchbase.com/): A distributed NoSQL database that uses key-value pairs to store and retrieve data. Supports various programming languages and is available on Windows, Linux, and macOS.

#### Others

- [tbls](https://github.com/k1LoW/tbls): tbls is a CI-Friendly tool for document a database, written in Go.

### Data analytics

#### Data visualization tools

- [Tableau](https://www.tableau.com/): A powerful data visualization tool used to explore and analyze data in various formats. Supports various data sources and can be used on Windows, Linux, and macOS.
- [Power BI](https://powerbi.microsoft.com/): A cloud-based business analytics service by Microsoft that provides interactive visualizations and business intelligence capabilities. Can be used on Windows, macOS, and mobile devices.
- [Databricks](https://databricks.com/): A cloud-based data engineering, data science, and analytics platform used to build data-driven applications. Supports various programming languages and data sources.

### Back-end

#### Headless CMS

- [Strapi](https://strapi.io/): an open-source headless CMS that provides a flexible content management system and API for your web applications, with a focus on ease of use and extensibility
- [Contentful](https://www.contentful.com/): a cloud-based headless CMS that offers a variety of content management tools and features, such as versioning and workflows, and supports a wide range of programming languages and frameworks
- [Sanity](https://www.sanity.io/): a headless CMS that provides a real-time collaborative editing environment, as well as powerful content modeling and API capabilities
- [Prismic](https://prismic.io/): a headless CMS that offers a flexible content model and API, with a focus on user experience and content delivery performance
- [Umbraco](https://umbraco.com/): an open-source content management system that provides a flexible and extensible platform for building web applications, with a focus on ease of use and customization
- [WordPress](https://wordpress.org/): a free and open-source content management system that powers over 40% of the web, providing a robust and extensible platform for building blogs, websites, and web applications

#### RESTful API frameworks

- [Express](https://expressjs.com/): A popular Node.js web application framework used to create RESTful APIs and web applications. Supports various middleware and template engines.
- [Flask](https://flask.palletsprojects.com/): A lightweight Python web framework used to create RESTful APIs and web applications. Supports various plugins and extensions.

#### WebSocket

- [Socket.IO](https://socket.io/): A JavaScript library for building real-time, bidirectional, and event-based communication applications on the web. Available for HTML, CSS, and JavaScript.
- [Ratchet](http://socketo.me/): A PHP WebSocket library for building real-time applications and communication channels. Available for PHP.
- [Inquery](https://github.com/inqueryio/inquery): Inquery is a utility for Postgres that triggers webhooks when rows are inserted, updated, or deleted. It uses database triggers that send low-latency websocket messages to a Go application. This application then calls the configured webhook(s) with a JSON payload that includes specified values from the database row.

### AI

#### Machine learning frameworks

- [TensorFlow](https://www.tensorflow.org/): An open-source machine learning framework developed by Google, used to create and train machine learning models. Supports various programming languages and is available on Windows, Linux, and macOS.
- [PyTorch](https://pytorch.org/): An open-source machine learning library developed by Facebook, used to create and train machine learning models. Supports various programming languages and is available on Windows, Linux, and macOS.
- [Scikit-learn](https://scikit-learn.org/stable/): A popular machine learning library for Python, used to build and train machine learning models. Supports various algorithms and data formats.

### Accessibility

#### Accessibility testing tools:

- [axe](https://www.deque.com/axe/): A free and open-source accessibility testing tool used to detect accessibility issues in web applications. Available as a browser extension or command-line tool.
- [Wave](https://wave.webaim.org/): A web accessibility evaluation tool used to check the accessibility of web content. Available as a browser extension or web application.

### Cryptography

#### Cryptographic libraries:

- [OpenSSL](https://www.openssl.org/): A robust, full-featured open-source toolkit for SSL and TLS protocols used to secure communications over the internet. Available for C, C++, and other programming languages.
- [Bouncy Castle](https://www.bouncycastle.org/): A Java cryptographic library that provides various algorithms for encryption, decryption, signing, and verifying digital signatures. Available for Java and .NET.

### Workflows

#### Monorepo

- [Nx](https://nx.dev/): a set of development tools and libraries for building and managing monorepos, with a focus on high performance and extensibility
- [Turborepo](https://turborepo.com/): a new approach to monorepo management that makes it easy to build, test, and deploy multiple projects from a single codebase

#### Continuous Integration (CI) tools:

- [Jenkins](https://www.jenkins.io/): An open-source automation server used to automate building, testing, and deploying software. Available on Windows, Linux, and macOS.
- [Travis CI](https://travis-ci.com/): A cloud-based CI service used to build and test software projects hosted on GitHub. Supports various programming languages and platforms.

#### Continuous Deployment (CD) tools:

- [Ansible](https://www.ansible.com/): An open-source automation tool used to deploy applications and manage IT infrastructure. Available for various platforms and programming languages.
- [AWS CodeDeploy](https://aws.amazon.com/codedeploy/): A cloud-based service used to automate the deployment of applications to Amazon EC2 instances, on-premises instances, or serverless Lambda functions. Supports various platforms and programming languages.

### Documentation and knowledge management tools:

#### Documentation tools:

- [Sphinx](https://www.sphinx-doc.org/): A documentation generator for Python projects. Can be used to create HTML, PDF, and ePub documentation. Available for Python.
- [Docusaurus](https://docusaurus.io/): A documentation generator used to create websites for open-source projects. Provides a range of features for managing and publishing documentation. Available for HTML, CSS, and JavaScript.

#### Knowledge management tools:

- [Confluence](https://www.atlassian.com/software/confluence): A collaboration software used to create, organize, and discuss work with your team. Provides a range of features for managing and sharing knowledge. Available on the cloud and on-premise.
- [Notion](https://www.notion.so/): A powerful productivity and knowledge management tool used to organize and share information with your team. Provides a range of features for taking notes, managing projects, and collaborating on documents. Available on the web and on desktop.

### CI

#### Cloud-based CI services:

- [CircleCI](https://circleci.com/): A cloud-based CI service used to automate building, testing, and deploying software. Supports various programming languages and platforms.
- [GitLab CI/CD](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/): A cloud-based CI/CD service used to automate building, testing, and deploying software projects hosted on GitLab. Supports various programming languages and platforms.

### Benchmarks

#### Benchmarking tools:

- [Geekbench](https://www.geekbench.com/): A cross-platform benchmarking tool used to measure the performance of CPUs and GPUs. Supports various operating systems and hardware configurations.
- [Fio](https://fio.readthedocs.io/en/latest/fio_doc.html): A flexible I/O tester and benchmark tool used to measure the performance of storage systems. Available for Linux and macOS.
- [Apache JMeter](https://jmeter.apache.org/): An open-source load testing tool used to measure the performance and functional behavior of web applications. Available on Windows, Linux, and macOS.
- [AB](https://httpd.apache.org/docs/2.4/programs/ab.html): A command-line tool used to benchmark the performance of web servers by sending a high number of requests. Available for Unix-like systems.

## TODO

- [ ] Filterable list
- [ ] Git hook to update the Table of contents
- [ ] Deployment

## Contributing

We welcome contributions from the community! If you have a favorite development tool or resource that you think should be included in this list, please submit a pull request. We only accept high-quality, useful tools and resources, so please make sure to include a brief description and information on the programming languages, libraries, and platforms the tool is available on.

To contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your contribution
3. Add your contribution to the appropriate category
4. Submit a pull request

Please note that all contributions are subject to review, and we reserve the right to reject any contributions that do not meet our standards.

## License

This repository is released into the public domain under the Creative Commons CC0 1.0 Universal Public Domain Dedication. You can find a copy of the CC0 license in the LICENSE file.
