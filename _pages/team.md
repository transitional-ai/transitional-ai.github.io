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




## Master and Honours Research Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
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


## Research Interns

### 2023



Azal Khan, Indian Institute of Technology, Guwahati, India (January 2023 - current) 

### 2022

* Azal Khan, Indian Institute of Technology, Guwahati, India (January - August 2022)   
* Saharsh Bharve, Manipal Institute of Technology, India (January - May 2022)  
* Shirin Jain,  Indian Institute of Technology, Guwahati, India  (May - August 2022)
* Snigdha Jain, Indian Institute of Technology, Guwahati, India  (May - August 2022)
* Janhavi Lande, Indian Institute of Technology, Guwahati, India (January - March 2022)  
* Chaarvi Bansal, Birla Institute of Technology and Science, Pilani, Rajasthan, India (January - May 2022)  
* Pranjal Singh,  Indian Institute of Technology, Guwahati, India (January - April 2022)  
* Gunjan Dhanuka, Indian Institute of Technology, Guwahati, India (January - April 2022)  
* Suryansh Shrivastava, Indian Institute of Technology, Guwahati, India (January - April 2022)   
* Pranshu  Kandoi,  Indian Institute of Technology, Guwahati, India (January - April 2022)
* Pandaya  Pranshu, Indian Institute of Technology, Guwahati, India (January - April 2022)

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
* Arya Arya Indian Institute of Technology Jammu, India ( August 2020 - December 2020)  
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





## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

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

## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>

 
 We are  looking for new PhD students, Postdocs, and Masters/Honours students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies)  


Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors).


## Administrative Support 
