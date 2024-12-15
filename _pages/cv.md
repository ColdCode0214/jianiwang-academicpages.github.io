---
layout: archive
title: "CV📄"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Worcester Polytechnic institute (WPI), May 2027 [expected]
* M.S. in Computer Science, Worcester Polytechnic institute (WPI), May 2023
* B.S. in Computer Engineering, Hunan University (HNU), June 2020

Research Experience
=====


* [05/2023-Present] NSF National AI Institute for Student-AI Teaming (iSAT) (WPI, USA)
  * Supervisor: Prof.Jacob Richard Whitehill
  *	Project: Speaker Diarization in the classroom.
	* Purpose: Investigating how automatic speaker diarization can be built to handle real-world classroom group discussions.
	* Contributions: 
    * Examined key design considerations such as the level of granularity of speaker assignment, speech enhancement techniques, voice activity detection, and embedding assignment method, so as to find an effective configuration.
    * Build a framework to handle the speaker diarization task for classroom audio.
    * Test if the model’s performance shows bias across different genders and racial groups.
    * Application for estimating how much each student speaks during group discussions.
    * Published the paper “Speaker Diarization in the Classroom: How Much Does Each Student Speak in Group Discussions?” in EDM2024 as the first author and received the Best student Short Paper Award.
    * Published the paper “Optimizing Speaker Diarization for the Classroom: Applications in Timing Student Speech and Distinguishing Teachers from Children” in JEDM.
    * Presented this work in the Collaborative Learning session of EDM Conference. 
    * Be invited by Prof. Neil Heffernan to share this work in the course AI for Adaptive Educational Technology.
    * Be invited to share this work with CU/CMU LEVI Team.
	* Collaborators Institutions: NSF National AI Institute for Student-AI Teaming (iSAT), University of Colorado Boulder, Northeastern University


* [05/2023-02/2024] Computer Science & Learning Science Lab (WPI, USA)
  * Supervisor: Prof.Jacob Richard Whitehill
  * Project: Person Re-ID in the classroom.
  * Purpose: Identify who-is-where-when in classroom videos for classroom analytics
  * Contributions: 
    * Investigating skin tone bias of person re-ID.
    * Published the paper “Tracking Classroom Movement Patterns with Person Re-ID” in EDM2024 as the second author.


* [08/2022-05/2023] Computer Science & Learning Science Lab (WPI, USA)
  * Supervisor: Prof.Jacob Richard Whitehill
  * Project: The fairness, bias, and robustness of machine learning models in learning science and education.
  * Topic: Deep Multiple-Instance Learning for Stable Attribute Classification in Classroom Video.
  *	Contribution: Applied multiple instances learning (MIL) to improve the classification accuracy of ResNet and extend this method to classify other stable attributes of classroom videos.


* [10/2019-06/2020] ML & Nuclear Power Plant Group (Hnu, China)
  * Supervisor: Prof.Jingke She
  * Project: The Intelligent Control of Nuclear Power Plant.
  * Topic: The Design and Implementation of an LSTM-Based Steam Generator Level Prediction Model.
  * Contribution: Applied machine learning method to improve the control speed instead of using physical principles and designed an intelligent control system (led to a conference paper).


Work Experience
======
* 07/2020-08/2021
  * Baidu.com, Inc (Beijing, China)

  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
