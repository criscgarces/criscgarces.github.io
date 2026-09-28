---
layout: archive
title: "Experience"
permalink: /experience/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- **Ph.D., Computer Science**, Tulane University, New Orleans, LA — expected graduation date: Spring 2027
  - Advisor: Dr. Jiang Ming
  - Transferred with advisor from the University of Texas at Arlington (2023)
- **B.S. (Honors), Computer Science and Engineering**, _summa cum laude_, University of Texas at Arlington, Arlington, TX
  - Honors thesis: _Screw It: A Computer Vision Approach to Identify Screws and Fasteners_; advised by Dr. Christopher McMurrough
  - Undergraduate Research Assistant, Department of Physics, UTA HEP; advised by Dr. Jaehoon Yu

# Research Interests

AI-assisted binary analysis · Binary reverse engineering · Vulnerability analysis · Cybersecurity education

# Teaching

**Tulane University**, Department of Computer Science

- CMPS 3300 – Software Studio, Teaching Assistant (Fall 2026)
- CMPS 3510 – Computer Organization, Teaching Assistant (Fall 2026)
- CMPS 2301 – Intro. to Computer Systems and Networking Lab (2 sections), **Instructor of Record**; supervised two undergraduate course assistants (Spring 2026)
- CMPS 2300 – Intro. to Computer Systems and Networking, Teaching Assistant (Spring 2026)
- CMPS 4770 – Operating Systems, Tutor (Spring 2025)
- CMPS 4410/6410 – Information Security, Teaching Assistant (Spring 2023, Fall 2023, Spring 2024, Fall 2024)

**University of Texas at Arlington**, Department of Computer Science and Engineering

- CSE 3315 – Theoretical Concepts, Teaching Assistant
- CSE 2315 – Discrete Structures, Teaching Assistant
- CSE 1325 – Object-Oriented Programming in C++, Teaching Assistant

# Awards

- Outstanding Graduate Teaching Award, Department of Computer Science, Tulane University (2023)
- Outstanding Graduate Teaching Award, Department of Computer Science and Engineering, University of Texas at Arlington (2022)
- Lockheed Martin Missiles and Fire Control Graduate Fellowship, College of Engineering, University of Texas at Arlington

# Publications

{% for category in site.publication_category %}

<h3>{{ category[1].title }}</h3>
<ul>{% for post in site.publications reversed %}{% if post.category == category[0] %}
  {% include archive-single-cv.html %}
{% endif %}{% endfor %}</ul>
{% endfor %}

# Professional Service

- External Reviewer, USENIX Security Symposium (2024, 2025)

# Outreach

- Chapter President, Tau Beta Pi, University of Texas at Arlington (2021 – 2022)
- Organizer, undergraduate CS midterm review sessions, Tau Beta Pi, University of Texas at Arlington — four sessions across two semesters, ~40 students each (2021 – 2022)
- Teaching Assistant, OurCS@DFW (_VIRUS: How to Take Apart a Computer Virus_), K-12 outreach workshop on introductory binary analysis, University of Texas at Arlington (Spring 2022)
- Judge, FIRST Lego League, FIRST Robotics (2024)

# Professional Memberships

- Tau Beta Pi (Engineering Honor Society), 2019 – present
- Upsilon Pi Epsilon (Computing Honor Society), 2022 – present
