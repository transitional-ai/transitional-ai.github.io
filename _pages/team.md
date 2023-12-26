---
title: "t~ai Members"
layout: gridlay
excerpt: "Members"
sitemap: false
permalink: /team/
---


## Core Members 
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}




## Ph.D Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!-- <br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Collaborators 

* Prof. Scott Sisson, UNSW Sydney, Australia
* Dr. Sahani Pathiraja, UNSW Sydney, Australia
* Dr Sarat Moka, UNSW Sydney, Australia
* A/Prof Gustavo Batista, UNSW Sydney, Australia
* Dr. William Zhi, Carnegie Mellon University, USA
* Dr. Tom Blau, Data61, CSIRO, Australia
* Dr Laurence Wilson, CSIRO, Australia
* Prof. Dietmar Muller, University of Sydney, Australia
* Prof. Christian Omlin, Agder University, Norway
* Prof. Willem Vervoort, University of Sydney, Australia
* Prof. Jody Webster, University of Sydney, Australia
* Prof. Lucy Marshall, Macquarie University, Australia
* Prof. Giles Hooker, Cornell University, USA
* Dr William Zhi, Robotics Institute, Carnegie Mellon University, USA
* A/Prof. Cedric John, Imperial College London, UK
* Dr Bjarne Wernicke-Olesen, Oxford Centre for Hindu Studies, Oxford University, UK
* A/Prof Cristian Bravo Roman, Western Ontario University, Canada
* Prof. Alok Sharma, RIKEN, Japan
* Dr Abhishek Gupta, Indian Institute of Technology Goa, India
* Prof. Ashish Anand, Indian Institute of Technology Guwahati, India
* Prof. Yew Soon Ong, A* and Nanyang Technological University, Singapore
* Dr Kavitesh Bali, A* and Nanyang Technological University, Singapore
* Dr Anurag Sharma, University of the South Pacific, Fiji 
* A/Prof. Bibhya Sharma, University of the South Pacific, Fiji

## Masters and Honours Research Students

* Xuechun Wang, "Evaluation of Google Translate for selected Chinese texts: sentiment and semantic analysis", Honours in Data Science, from T3 2023
* Qihan Wang, "Detection of political bias in western media", Honours in Data Science, from T3 2023
* Honghui Wang, "Deep learning for instant pedestrian path prediction", Masters by Research, from T2 2022 (Joint supervision with A/Prof Gustavo Batista)
* Shuhao Huang, "Explainable artificial intelligence for drought prediction in Australia", Honours in Computer Engineering, from T3 2023
* Yeshwanth Rayavarapu, "Comparison of GPT and  Google Translate for translation of selected Indian languages", Honours in Computer Engineering, from T3 2023

  
## Research Interns
 
 * Vamshika Sutar, Indian Institute of Technology Bombay, India (January 2024 - present)
 * Zihan Wang, UNSW Sydney, Australia (January 2024 - present)
 * Samiz M. Haghighi,  UNSW Sydney, Australia (January 2024 - present)
 * Sarthak Kapoor, Indian Institute of Technology Guwahati, India (January 2024 - present)


 


## Alumni (research student)

### Ph.D

* Dr Amit Kumar, “Multimodal approach for clustering risk level in pulmonary fibrosis patients using respiratory and EMG data”, Beijing Institute of Technology, 2023 (External supervision by Dr Chandra)
* Dr Ehsan Farahbakhsh, “Machine learning for mineral prospecting”, Amirkabir University of Technology, Tehran, 2020  (External supervision by Dr Chandra)
  
### Honours

* Albert Demskoy, "Bayesian model for high category cyclone forecasting using  sea-surface temperature: four decades ahead", Honours in Data Science, December 2023
* Rahul Ahluwalia, "Data augmentation for extreme value forecasting using deep learning", Honours in Data Science, December 2023
* Sean Luo, Honours in Data Science, from T2 2022  
* George Maksour, Honours in Data Science, from T2 2022  
* Jim Ng, “ Conditional ensemble deep learning for modelling Australian climate extremes: streamflow and floods“, Honours thesis, UNSW Sydney, 2022 
* Eric Chen, “Deep learning for modelling historic ground-water levels via stream-flow and precipitation data”, Honours thesis, UNSW Sydney, 2022  
* Royce Chen, "Pruning Bayesian neural networks with MCMC", Honours thesis, UNSW Sydney, 2022  
* George Bai, "Bayesian neural ensemble learning with parallelized  and tempered Langevin MCMC",  Honours ithesis,  UNSW Sydney, 2021  
* Jodie Pall, “ Bayesreef: Reef evolution using Bayesian inference”, Honours thesis, School of Geosciences, University of Sydney, 2018 (Received University Medal)  

### Masters (coursework - minor thesis)

* Ruoni Wen, "Remote sensing and deep learning for landcover classification in Fiji", Masters in Statistics, August 2023, (Primary Supervisor, Co-supervisor Dr Ehsan Farahbakhsh)
* Alex Bradford,  "Variatianal deep learning for stock price prediction",  Masters in Statistics, August 2023, (Primary Supervisor)
* Mukuan Hsu, "Topic modelling for COVID-19 vaccine-related tweets", Masters in Computing Science,  August 2023, (Primary Supervisor)
* Hamish Haggerty, “Self-supervised deep learning”, Masters in Statistics, May 2023, (Primary Supervisor)
* Tianyi Wang, Revisiting world economic outlook post-COVID-19 with deep learning",     Master of Statistics,  UNSW Sydney, December 2022, (Primary Supervisor) 
* Yuhao Ke, “Machine learning for NBA”,  Master of Statistics, School of Mathematics and Statistics, UNSW Sydney, December 2022 (Primary Supervisor)  
* Mingyue Kang, "COVID-19 mutation over time", Master of Statistics,  UNSW Sydney, May 2022 (Principal Supervisor in collaboration with Prof. Seshadri Vasan (CSIRO)
* Jiaxin Cathy Yu, "COVID-19 diagnosis study with big data", Master of Statistics,  UNSW Sydney, May 2022 (Principal Supervisor in collaboration with Prof. Seshadri Vasan (CSIRO)
* Kelin Liu, "Clustering methods for vessel tracking with satellite data", Master of Statistics,  UNSW Sydney, May 2022 (Principal Supervisor in collaboration with Dr Rodney Beard (FFA)
* Zhilin Wei, "Computer vision for aerial tracking of coastal plastic waste", Master of Statistics, UNSW Sydney, December 2021 (Principal Supervisor) 
* Dizhou Feng, "Graph neural networks for spatiotemporal forecasting", Master of Statistics,  UNSW Sydney, December 2021 (Principal Supervisor) 
* Yueyang Zhang, "Gradient Boosting LSTM for reducing model uncertainty", Master of Statistics,  School of Mathematics and Statistics, December 2021 (Principal Supervisor) 
* Shaodong Lin, "World economic outlook post-COVID-19 with deep learning", Master of Statistics,  School of Mathematics and Statistics, December 2021  (Principal Supervisor) 
* Yixuan He, "Bayesian neural learning for  financial prediction", Master of Financial Mathematics,  UNSW Sydney, August 2020 (Principal Supervisor) 


### Masters by Research (major thesis)

* Chaarvi Bansal, “Machine learning Framework for COVID-19 Drug Repurposing”, M.Sc. Biological Sciences, Birla Institute in Technology and Science Pilani and UNSW Sydney, 2022 (Principal Supervisor with Prof. P. R. Deepa )
* Julian Rodriguez, "Machine learning for spatial-temporal mineral prospecting using plate tectonic models, M.Phil, University of Sydney (External Supervisor with Prof. Dietmar Muller, 2019-2020)
* Ratneel Deo, “Neural network methodologies for cyclone wind intensity and path prediction”, Master of Science in Computing Science, University of the South Pacific, Suva, Fiji, December 2017 Download thesis from USP Library (Primary Supervisor - External Supervisor) (Nominated for Best Thesis - Gold Medal)



## Alumni (research interns)

### 2023
* Mahek Vora, Indian Institute of Technology Guwahati, India (January - May 2023)
* Naman Jain, Indian Institute of Technology Delhi, India (May - July 2023)
* Akshat Shukla, Indian Institute of Technology Guwahati, India (January - April 2023)
* Azal Khan, Indian Institute of Technology Guwahati, India (June 2023 - December 2023) 
* Omkar Chaudhari, Indian Institute of Technology Guwahati, India (June 2023 - December 2023) 
* Siddharth Khedkar, BITS Pilani, Rajistan, India (September 2023 - December 2023)
* Tvisha Malik, Indian Institute of Technology Delhi, India (March 2023 - August 2023) 
  
 
### 2022

* Azal Khan, Indian Institute of Technology, Guwahati, India (January - August 2022)   
* Saharsh Bharve, Manipal Institute of Technology, India (January - May 2022)  
* Shirin Jain,  Indian Institute of Technology, Guwahati, India  (May-August 2022)
* Snigdha Jain, Indian Institute of Technology, Guwahati, India  (May-August 2022)
* Janhavi Lande, Indian Institute of Technology, Guwahati, India (January - March 2022)  
* Chaarvi Bansal, Birla Institute of Technology and Science, Pilani, Rajasthan, India (January - May 2022)  
* Pranjal Singh,  Indian Institute of Technology, Guwahati, India (January - April 2022)  
* Gunjan Dhanuka, Indian Institute of Technology, Guwahati, India (January - April 2022)  
* Suryansh Shrivastava, Indian Institute of Technology, Guwahati, India (January - April 2022)   
* Pranshu  Kandoi,  Indian Institute of Technology, Guwahati, India (January - April 2022)
* Pandaya  Pranshu, Indian Institute of Technology, Guwahati, India (January - April 2022)
* Dhiraj Pimparkar,  Indian Institute of Technology Jammu, India ( May 2022 - September 2022)  
* Dakshi Goel, Indian Institute of Technology Jammu, India ( May 2022 - September 2022)  

### 2021

* Sweta Rathi, Indian Institute of Technology Guwahati, India (June - August 2021)
* Mukul Ranjan, Indian Institute of Technology Guwahati, India (June - August 2021)
* Amandeep Singh, Indian Institute of Technology Bombay, India (June - August 2021)
* Ritam Manabendra, Indian Institute of Technology Guwahati, India (June - August 2021)
* Anshul Negi, Indian Institute of Technology Roorkee, India (June - August 2021)
* Rishabh Sharma, Indian Institute of Technology Guwahati, India (June - August 2021)
* Sahil Bohra, Indian Institute of Technology Delhi, India (June - August 2021)
* Ayush Bhagat, Manipal Institute of Technology, India (April 2021 - June 2021)
* Venkatesh Kulkarni, Indian Institute of Technology Guwahati, India (November 2021 - February 2022)
* Sandeep Nagar, International Institute of Information Technology, Hyderabad, India (November 2021 - February 2022)

### 2020

* Ritij Saini, Indian Institute of Technology Bombay, India (December 2020 - February 2021)
* Aswin Krishna, Indian Institute of Technology Guwahati, India (December 2020 - February 2021)
* Prabhat Singh, Indian Institute of Technology Guwahati, India (December 2020 - February 2021)  
* Jiaxin Yu, School of Mathematics and Statistics, UNSW Sydney, (December 2020 - February 2021)
* Jiaxi Zhao, School of Mathematics and Statistics, UNSW Sydney, (December 2020 - February 2021)
* Animesh Renanse, Indian Institute of Technology Guwahati, India (May 2020 - August 2020)
* Shaurya Goyal, Indian Institute of Technoritamlogy Delhi, India (May 2020 - August 2020)
* Yash Sharma, Indian Institute of Technology Roorkee, India (May 2020 - August 2020)
* Ashish Gupta, Indian Institute of Technology Delhi, India (May 2020 - August 2020)
* Manavendrasinh Maharana, Manipal Institute of Technology, India (Jan 2020 - June 2020)
* Animesh Tiwari, Indian Institute of Technology Guwahati, India (May 2020 - August 2020)
* Eshwar Nukala, Indian Institute of Technology Guwahati, India (May 2020 - August 2020)
* Arya Arya, Indian Institute of Technology Jammu, India ( August 2020 - December 2020)  
* Mahir Jain, Manipal Institute of Technology, India ( August 2020 - December 2020)
* Ayush Bhagat, Manipal Institute of Technology, India ( August 2020 - December 2020)
* Ayush Jain, Indian Institute of Technology Guwahati, India (May 2020 - August 2020)
* Divyanshu Singh, Indian Institute of Technology Guwahati, India ( August 2020 - December 2020)
* Kousik Rajesh, Indian Institute of Technology Guwahati, India (May 2020 - August 2020)

### 2019

* Aakarsh Yadav, Indian Institute of Technology, India (June 2019 - August 2019)
* Ashray Aman, Indian Institute of Technology Delhi, India (June 2019 - August 2019)
* Rishab Gupta, Indian Institute of Technology, India (June 2019 - August 2019)
 

### 2018

 * Konark Jain, Indian Institute of Technology, India (May 2018 - July 2018)
 * Arpit Kapoor, SRM Institute of Technology, India (June 2018 - August 2018)
 * Ratneel Deo, University of the South Pacific, Fiji (December 2017 - February 2018)
 * Wil Grebner, University of Sydney, Australia (February 2018 -  June 2018)




 
 We are  looking for new PhD students, Postdocs, and Master/Honours students to join the team. 
