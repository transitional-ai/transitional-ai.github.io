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


## Masters and Honours Research Students

* Jack Choi, "Transformation of abusive comments using LLMs",  Honours in Quantitative Data science, Since February 2025 (Principal Supervisor)
* Yathin Suresh, "Ananysis of songs on Billboard charts using NLP", Honours in Computational Data Science, Since February  2025 (Principal Supervisor)
* Thoma Duffy, "Analysis of antisemitic trends in media using LLMs", Masters in  Statistics, Since February 2025 (Principal Supervisor)
* Yue Zhang, "Evaluation of LLM-based language translation for Mandarin to English, Masters in Data Science and Decisions, Since May 2025  (Principal Supervisor)
  
## Research Interns
 
 * Vamshika Sutar, Indian Institute of Technology Bombay, India (January 2024 - July 2024) 
 * Samiz M. Haghighi,  UNSW Sydney, Australia (January 2024 - July 2024)
 * Siddharth Khedkar, Indian Institute of Technology Guwahati, India (January 2024 - May 2024)


 


## Research Student Alumni  

### Ph.D

* Dr Saman Forouzandeh, "Recommender systems using graph-based deep learning'', School of Mathematics and Statistics,  UNSW Sydney,  April 2025 (Joint Principal  Supervisor with Dr Pavel Krivitsky)
* Dr Ratneel Deo, ''Deep learning for understanding geo-coastal and reef development``, University of Sydney, April 2025 (External Supervisor   with Prof. Jody Webster and Dr Tristan Salles)
* Dr Nhat Minh Megan Nguyen, "Bayesian Inference for Complex Models", University of Sydney,  September 2024 (External Supervisor with A/Prof. Minh-Ngoc Tran and Dr Tongliang Liu)
* Dr Amit Kumar, "Multimodal approach for clustering risk level in pulmonary fibrosis patients using respiratory and EMG data", Beijing Institute of Technology, April 2023 (External Supervisor)
* Dr Ehsan Farahbakhsh, “Developing a novel method for three-dimensional modelling of ore deposits by integrating data layers”, Amirkabir University of Technology, Tehran, December 2020 (External Supervisor)

### Honours

*  Raine Bianchini, "Languge models for audio transcription analysis in movies", Honours in Quantitative Data science, August 2025 (Principal Supervisor)
* Omkar Chaudhary, "Financial fraud detection in cryptocurrency using graph-based deep learning", Honours thesis in Economics, BITS Pilani -Goa, India, July 2025 (Principal Supervisor)
* Xuechun Wang, "Evaluation of Google Translate for selected Chinese texts: sentiment and semantic analysis", Honours in Quantitative Data Science, August 2024  (Principal Supervisor with Dr Rodney Beard) 
* Shuhao Huang, "Explainable artificial intelligence for drought prediction in Australia", Honours in Computer Engineering, May 2024
* Albert Demskoy, "Bayesian model for high category cyclone forecasting using  sea-surface temperature: four decades ahead", Honours in Data Science, December 2023
* Rahul Ahluwalia, "Data augmentation for extreme value forecasting using deep learning", Honours in Data Science, December 2023
* Sean Luo, "Evaluation of GANs with dimensional reduction approach", Honours in Data Science, May 2022 (Joint supervision with Dr Sahani Pathiraja)
* George Maksour, "Evaluation of deep reinforcement learning models for horse-race betting", Honours in Data Science, May 2022 (Joint supervision with Dr Sahani Pathiraja)
* Jim Ng, “ Conditional ensemble deep learning for modelling Australian climate extremes: streamflow and floods“, Honours thesis, UNSW Sydney, December 2022 (Primary Supervisor with A/Prof Willem Vervoot)
* Eric Chen, “Deep learning for modelling historic ground-water levels via stream-flow and precipitation data”, Honours thesis, UNSW Sydney, December 2022 (Primary Supervisor with A/Prof Martin Anderson)
* Royce Chen, "Pruning Bayesian neural networks with MCMC", Honours thesis, UNSW Sydney, December 2022 (Joint supervision with Dr Sahani Pathiraja)
* George Bai, "Bayesian neural ensemble learning with parallelized  and tempered Langevin MCMC",  Honours thesis,  UNSW Sydney, December 2021 (Principal Supervisor)
 
 ### Masters (coursework - minor thesis)

* Zhenyu Zhu, "Sanskrit optical charator recognisition using advanced deep learning models", Master's in Data Science and Decisions,  August 2025 (Principal Supervisor)
* Ziyu Lei, "Political leaning analysis by large language models", Master's in Statistics, May 2025 (Principal Supervisor)
* Yizhen Fan, "Electric load forecasting using deep learning models", Master's in  Financial Mathematics, August 2025 (Principal Supervisor)
* Junru Hua, "Extreme value forecasting with data augmentation and deep learning ", Master's in  Data Science and Decisions,  August 2025 (Principal Supervisor)
* Chen Wang, "Sinophobia during COVID-19: Twitter ", Master's in Data Science, August 2024 (Principal Supervisor) 
* Tanay Panat, " Global ease of living index with data imputation and dimentionality reduction", Master's in Data Science, December 2024 (Principal Supervisor) 
* Yeshwanth Rayavarapu, "Comparison of GPT and  Google Translate for translation of selected Indian languages", Master's in Data Science, May 2024, (Principal Supervisor) 
* Ruoni Wen, "Remote sensing and deep learning for landcover classification in Fiji", Master's in Statistics, August 2023, (Principal Supervisor) , Co-supervisor Dr Ehsan Farahbakhsh)
* Alex Bradford,  "Variational deep learning for stock price prediction",  Master's in Statistics, August 2023, (Principal Supervisor) 
* Mukuan Hsu, "Topic modelling for COVID-19 vaccine-related tweets", Master's in Computing Science,  August 2023, (Principal Supervisor) 
* Hamish Haggerty, “Self-supervised deep learning”, Master's in Statistics, May 2023, (Principal Supervisor) 
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

* Honghui Wang, "Deep learning for instant pedestrian path prediction", Master's by Research,  2024(Principal Supervisor  with A/Prof Gustavo Batista and Dr William Zhi) 
* Chaarvi Bansal, “Machine learning Framework for COVID-19 Drug Repurposing”, M.Sc. Biological Sciences, Birla Institute of Technology and Science Pilani and UNSW Sydney, 2022 (Principal Supervisor with Prof. P. R. Deepa )
* Julian Rodriguez, "Machine learning for spatial-temporal mineral prospecting using plate tectonic models, M.Phil, University of Sydney (External Supervisor with Prof. Dietmar Muller, 2019-2020)
* Ratneel Deo, “Neural network methodologies for cyclone wind intensity and path prediction”, Master of Science in Computing Science, University of the South Pacific, Suva, Fiji, December 2017  (Primary Supervisor - External Supervisor) (Nominated for Best Thesis - Gold Medal)



## Research Intern Alumni 
### 2025
* Divisha Naharas, University of Nevada - Reno, USA (January -June 2025)
* Fangli Cheng, UNSW (January -June 2025)
* Aditya Pramar,  Pingla Institute (January - June 2025)
* Jiaming Yang, UNSW   (January - June 2025)
* Liang Long, UNSW   (January - June 2025)
* Sungkyun Yoo, Pingla Institute (January - June 2025)
* Viswas Dubey, Vellore Institute of Technology  (January - June 2025)
* Sai  Rugved, Indian Institute of Technology Guwahati, India (April - September 2025)
### 2024

* Aryan Chaudhary, National Institute of Technology Rourkela, India (September 2024- March 2025)
* Vamshika Sutar, Indian Institute of Technology Bombay, India (July 2024 - March 2025)
* Tanuj Chaudrary, Indian Institute of Technology Guwahati, India (July 2024 - November 2024)
* Kartik Disawal, Indian Institute of Technology Goa, India (January - June 2024)
* Omkar Chaudhary, BITS Pilani -Goa, India,  (June-December 2024)

### 2023
* Mahek Vora, Indian Institute of Technology Guwahati, India (January - May 2023)
* Naman Jain, Indian Institute of Technology Delhi, India (May - July 2023)
* Akshat Shukla, Indian Institute of Technology Guwahati, India (January - April 2023)
* Azal Khan, Indian Institute of Technology Guwahati, India (June 2023 - December 2023) 
* Omkar Chaudhari, Indian Institute of Technology Guwahati, India (June 2023 - December 2023) 
* Siddharth Khedkar, BITS Pilani, Rajasthan, India (September 2023 - December 2023)
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



## Collaborators 

* Dr. Eka
* Prof. Scott Sisson, UNSW Sydney, Australia 
* A/Prof Gustavo Batista, UNSW Sydney, Australia
* Dr. William Zhi, Carnegie Mellon University, USA 
* Prof. Dietmar Muller, University of Sydney, Australia
* Prof. Christian Omlin, Agder University, Norway
* Prof. Willem Vervoort, University of Sydney, Australia
* Prof. Jody Webster, University of Sydney, Australia
* Prof. Lucy Marshall, Macquarie University, Australia
* A/Prof. Cedric John, Imperial College London, UK
* A/Prof Cristian Bravo Roman, Western Ontario University, Canada
* Dr. Amit Kumar, Vietnam
* Prof. Alok Sharma, RIKEN, Japan
* Dr Abhishek Gupta, Indian Institute of Technology Goa, India 
* Prof. Yew Soon Ong, A* and Nanyang Technological University, Singapore
* Dr Kavitesh Bali, A* and Nanyang Technological University, Singapore
* Dr Anurag Sharma, University of the South Pacific, Fiji 
* A/Prof. Bibhya Sharma, University of the South Pacific, Fiji

 
 We are  looking for new PhD students, Postdocs, and Master/Honours students to join the team. 


 
<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" >
    <!-- Menu -->
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
        <li data-target="#carousel" data-slide-to="7"></li>
        <li data-target="#carousel" data-slide-to="8"></li>
        <li data-target="#carousel" data-slide-to="9"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">
      <div class="item active">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_0.png" alt="Slide 1" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_1.jpg" alt="Slide 2" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_2.jpg" alt="Slide 3" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_3.jpg" alt="Slide 4" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_4.png" alt="Slide 5" />
      </div>       
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_5.jpeg" alt="Slide 6" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_6.png" alt="Slide 7" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_7.jpg" alt="Slide 8" />
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/slider_8.jpg" alt="Slide 9" />
      </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
