---
---

# Welcome to the H2DesignLab at HCI@Stevens!

{% capture text %}

We believe multidisciplinarity and creativity are the keys to strong HCI, social computing, and health informatics research. We consist of individuals with various backgrounds—art and design, information and computer sciences, psychology, and statistics (and more coming)—and we collaborate with people with a wide array of interests and expertise in medicine, nursing, clinical psychology, and public health with the same aim: How can we use advancing technology to support health? 

{% endcapture %}

{%
  include feature.html
  image="images/h2_social.jpg"
  text=text
%}

{% include section.html %}

## Highlights

{% capture text %}

Every year, we have multiple papers and work-in-progress presentations at ACM CHI and CSCW and related SIGCHI conferences (and sometimes AMIA).

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/pubs.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

We develop and evaluate design solutions for multiple health spaces, spanning from youth and young adult mental health to parenting of young children, social isolation of older adults, and to informal caregivers of chronically ill individuals. We study how emerging technology (e.g., large language models, mobile and wireless technology) can contribute to those solutions.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our lab consists of people from diverse backgrounds, all fascinated by the idea that technology can play a positive role in solving the world's important problems.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/chi24.jpg"
  link="team"
  title="Our Team"
  text=text
%}
