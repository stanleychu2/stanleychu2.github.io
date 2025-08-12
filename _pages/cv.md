---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Networking and Multimedia, National Taiwan University, Jul. 2022
  * GPA: 4.11 / 4.3
  * TA experience: Applied Deep Learning (2022 Spring)

* B.S. in Computer Science, National Chengchi University, Jul. 2020
  * GPA: 4.19 / 4.3
  * Double Major in Digital Content & Technologies
  * TA experience: Programming 101 (2020 Spring), Computer Programming (2020 Spring)

Work experience
======
* Jul. 2023 – Present: Algorithm Engineer
  * Taboola
  * Deploy and fine-tune LLM to support several tasks, NLU, rephrasing and summary
  * Develop productivity improvement tools like campaign optimization suggestions and cold email service for account managers
  * Build an agent system from scratch (Abby) to help customers to follow Taboola's policy

* Sep. 2022 – Jun. 2023: Machine Learning Engineer
  * LINE+ (LINE TODAY department - a news media platform)
  * Smart crop: enhances thumbnail image cropping by saliency detection, significantly reducing the incidence of miscrops
  * Article clustering: analyze keywords and trends for recommending personalized news

* Mar. 2021 – May. 2022: Alexa Prize Taskbot Challenge
  * National Taiwan University Team Miutsu
  * Developed a highly interactive Alexa skill for the U.S. market, which assists users in performing complex cooking and DIY tasks
  * Selected as one of the top ten innovations globally in the Alexa Prize Taskbot Challenge

* Jul. 2019 – Feb. 2020: Research Fellow
  * Ministry of Science and Technology
  * CutMat: Analyze the Practicability of Long Read Overlapping based on Integer Interval
  * Investigate the probability of integrating integer interval and Hi-C information
  * Undergraduate research fellowship, Ministry of Science and Technology (MOST)

* Jul. 2018 – Jun. 2019: Software Engineer Intern
  * NCCU Computer Center
  * Spearheaded the development and ongoing enhancement of the mobile application, significantly improving user interface
  * Including weather (forecast, air quality), YouBike, bus, map, and food
  * Integrate Elasticsearch to improve the course search system

Skills
======
* Programming Languages
  * Python (Primary)
  * Ruby, JavaScript, C/C++, Shell Script, Swift

* Deep Learning & AI
  * PyTorch
  * Transformers
  * Natural Language Processing (NLP)
  * Dialogue Systems

* Web Development
  * FastAPI
  * jQuery, Node.js, Rails
  * Nginx

* Cloud & DevOps
  * Azure (AZ-900 Certified)
  * AWS
  * Kubernetes
  * Docker
  * Linux
  * Airflow

* Development Tools
  * Sublime, Xcode, ITerm, Vim, PyCharm

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **Careerhack | TSMC × Microsoft**
  * Anomaly Detection, Labeling with AI, Automated Optical Inspection (AOI)
  * Binarize images and build a VGG16, ResNet50 model to detect defective cloth

* **Accounting Application**
  * Develop an iPad application on Xcode with Swift and SQLite as the database
  * Application to deal with accounting management and generate vegetable delivery orders

* **[I'mpression Stamp](https://www.youtube.com/watch?v=nXGQdNKvgHU)**
  * Develop a custom backend using Node.js, leveraging Pixi.js for interactive graphics, and JSFeat for real-time image processing
  * Build a device with NodeMCU to transport button data to the website deploying on Azure VM
  * Provide an iPad and several buttons for users to design unique paintings

* **[Bus Tracker](https://sgnweb.nccu.edu.tw/nccubus/home/index)**
  * Backend: ASP.net
  * Process the data fetched from Public Transport Data eXchange (PTX)
  * Apply jQuery Ajax to the real-time bus information

Certifications
======
* AZ-900 Microsoft Azure Fundamentals