# Adam Juhasz

Full stack developer with experience in the finance, machine learning, and bio-medical device industries. Worked the stack from custom silicon chips to Kubernetes clusters.

## Contact

- [hi@ajuhasz.io](mailto:hi@ajuhasz.io)
- [https://ajuhasz.io](https://ajuhasz.io)
- [LinkedIn](https://www.linkedin.com/in/ajuhasz/)

## Work preferences

- Strongly & statically typed codebases
- Engineering teams with close relationships with adjacent teams (design, product, etc)

## Skills

### Significant language experience

- Typescript
- Haskell
- C

## Work

### Pay Tgthr — 2018 - 2022

_Pay Tgthr is a fintech that issued debit cards to couples to split shared expenses like groceries, utilities, and dinner out._

### Founder & CTO

Developed both the backend and mobile app for the card program that used no SDKs or libraries from partners.

### Engineering-related experience

### Backend

- Developed a Haskell based platform that had hard limits around request latency, data security, and correctness.
- Developed a purchase authorization engine that processed 99% of purchases within 1.2 seconds (we had a limit of 5 seconds from Mastercard) and handled more than $2 million in purchases.
- Developed a fraud risk engine that had a loss ratio of 3%, industry baseline is 7%. It was able to risk couples by combining each individual’s risk based on previous purchases, linked external account balances, in-app behavior (such as time to tap buttons and move between screens), network behavior, and real-time editable business rules.
- Developed an in-house ledger system that kept track of users’ and the business’s balances. It was an append-only double entry ledger that supported multiple account types such as account balance or rewards balance while linking each entry to any number of external objects link users, group, purchases, or ACH transfers.
- Designed our backend infrastructure to be completely self hosted on GKE. Hosted components included Cockroach DB, RabbitMQ, Hashicorp Vault, and Metabase.
- Developed a GitHub Actions & GCP Cloud Build based CI/CD pipeline for automatic deployment of our micro services into both our staging and production.

### Frontend

- Developed a multi-platform React Native mobile application that was rated 4.8 stars and loved by many of our users.
- Worked with an external design agency to develop the screens, design language, pattern library, and App Store listings.
- Developed an Expo based pipeline for automatic updating of the app using over-the-air instant releases.
- Developed the marking pages for the Pay Tgthr website.

### Business experience

- Worked with banks, card issuing partners, Mastercard, and legal counsel to get the card program approved, card design approved, and fund flow approval.

### Ask me about

- Interesting fraud patterns scammers tried on us
- How Haskell and extensive use of algebraic data types allowed us to move faster than both of our competitors
- How we increased our NPS from the 40s to the 90s

---

### Figure Eight (previously known as CrowdFlower) — 2017 - 2018

_Figure Eight helps machine learning startups run annotation workflows to annotate text, images, video._

### Senior Software Engineer

- Full stack development of the customer facing part of the Figure Eight platform

### Backend

- Worked on hardening, optimizing, and re-architecting a Node.js based middleware that sat between the front end and multiple backend APIs. The middleware was responsible for authorization, request collation and caching. We increased front end development velocity by decoupling front end and back end development and being able to provide novel or optimized API endpoints by re-using different backend micro services.

### Frontend

- Worked on effort to investigate adding types to the React frontend to increase reliability and developer velocity. Investigated using Typescript, Reason, and Flow. Team settled on Typescript and began effort to slowly add 100% types to code base. Led effort to enforce Typescript best practices on code reviews.
- Worked on upgrading the front end codebase to current framework releases without breaking current development.

---

### UC Berkeley Extension — 2017 - 2018

_University of California, Berkeley provides continuing education programs_

### Instructor

Was the lead instructor of a bootcamp for adults to learn software development skills around full stack web development. Students had a range of skills from none to previous bootcamp experience. Had 2 TAs help grade and provide in-class help.

### Taught the filling technologies/frameworks

- Basic development skills like Git, CLI usage, commit messages, code review etiquette
- Basic javascript/HTML5/CSS3 skills
- Basic Node.js skills
- React, including how to use there framework and best practices
- MongoDB and MySQL as databases, including Bookshelf.js as an ORM
- Express (node.js web framework)

---

### Alana.cloud (Fynd.me pivot) — 2014 - 2017

_Alana.cloud is a chatbot development and hosting platform. It’s a technology spinout from , a visual search engine and shopping portal for fashion_ [Fynd.me](http://Fynd.me)

### Chief Product Officer & Technical Co-Founder — Alana.cloud

- Spun out the NLP and chat bot technologies developers for the Fynd platform into a Chatbot development and hosting SaaS.
- Developed a novel open source JavaScript batteries-included framework that handled NLP of the user’s input, intent generation from current state and user input, and workflow execution as the chatbot processed input. Supported multiple deployment platform such as web based widgets, Facebook messenger, and raw HTTP access.
- Developed a web-based IDE that supported development of chat bots with custom interfaces for intent generation, writing javascript workflow code, and testing the Chatbot without public deployment, and saving changes to a hosted Git system.
- Developed a system to host and execute developer’s chatbots in a secure environment where developer’s code could be malicious or error prone.

### CTO — Fynd.me

- Developed a search engine for fashion that allowed users to search for pieces not by text by by selecting pieces similar to their desired look. The platform then used graph database to find similar garments by looking at the distance from the selected garments.
- Developed an annotation platform so our fashion experts could categorize and tag garments to train machine learning models to auto-tag garments.
- Piloted with a top 3 fashion retailer to replace their in-house e-commerce search engine with our own technology.

---

### Cutera — 2012 - 2014

_Cutera develops medical lasers for aesthetic procedures_

### Senior Software Engineer

- Porting embedded software running on ARM7 processor from SMX Realtime OS to embOS realtime OS. Responsibilities include porting middleware for USB, Flash, and TCP/IP stack with an embedded web server.
- Porting and writing software for new hand pieces including using I²C, SPI, and internal ARM chipset features in C.
- Maintaining custom Windows software used during development and build.

---

### Lensx Inc (acquired by Alcon Inc) — 2008 - 2012

_Lensx developed a cataract surgery system and was acquired by Alcon Inc_

### Software Engineer (2008 - 2012)

- Part of a team of two engineers that developed the imaging module to capture and analyze three-dimensional images of the human eye for the LenSx laser system in C. Quick development allowed our system to be first-to-market of an image-guided surgery system with realtime OCT (optical coherence tomography) imaging.
- Single-handedly responsible for the hardware control of the imaging system; development included interfacing with multiple hardware components include digital-to-analog boards to control galvanometer scanners, interfacing with frame grabber boards and controlling camera firmware.
- Resource constraints required interfacing with high-performance libraries such as Intel Performance Primitives (IPP) and efficient programming technique to meet doctor’s expectations for imaging time. Patent pending on innovative techniques used to speed-up imaging.
- Due to success with hardware control code, responsibilities expanded to include improving image quality, decreasing imaging processing time and increasing the detection quality of the image analysis.
- Wrote extensive documentation and test cases to support FDA-regulated industry standards.
- Prototyped wireless iPad interface for doctor training using Objective-C and Cocoa touch.
- Four pending patents, lead inventor on two.

### Alcon Inc — 2006 - 2008

_Alcon is the leading bio-medical device manufacturer_

### Associate Engineer (2006 - 2008)

- Developed an audio output engine for tone warnings and speech feedback by hacking an ethernet chip to output sound.
- Converted terminal-based service interface to web-based interface to lower both training and in-field errors; developed in C running on the Enea OSE realtime OS. Responsibilities included modifying and enhancing a lightweight http engine written in C, designing the inter-process communication between the http engine and application software, and developing and designing an html based front-end.
- Developed a browser based collaborative application for foreign Alcon affiliates to develop in-house translations for the purepoint system’s interface using python and google app engine. Architected and wrote a plan to transition from isolated local installations on Windows to a company-wide collaborative intranet based installation. Allowed Alcon to no longer require hiring translators

## Education

### University of Michigan

#### Computer Engineering
