---
title: "~tAI - Blog"
layout: gridlay
excerpt: "~tAI -- Blog."
sitemap: false
permalink: /news/
---

## Latest News

<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="4000" data-pause="hover" style="max-width: 800px; margin: 0 auto;" >
    <!-- Menu -->
    <ol class="carousel-indicators"> 
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li> 
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
    </ol>

    <!-- Items -->
    <div class="carousel-inner" markdown="0">   
      <div class="item active">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/May20_26Rohit.jpeg" alt="Slide 0" style="width: 100%; height: 450px; object-fit: cover;" />
        <div style="padding: 6px 0; color: #666; text-align: left;">
         <small>¹ Assoc.Prof. Rohitash Chandra presenting at the t~AI Seminar series. <i>May 20, 2026</i></small>
        </div> 
      </div>
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/May20_26Sangdeok.jpeg" alt="Slide 1" style="width: 100%; height: 450px; object-fit: cover;" />
        <div style="padding: 6px 0; color: #666; text-align: left;">
         <small>² Welcoming PhD student Sangdeok Lee to our group. <i>May 20, 2026</i></small>
        </div> 
      </div>  
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/1_May6_26John.jpeg" alt="Slide 2" style="width: 100%; height: 450px; object-fit: cover;" />
        <div style="padding: 6px 0; color: #666; text-align: left;">
         <small>³ Dr John Hawkins launched his new book at the UNSW bookstore. <i>May 6, 2026</i></small>
        </div> 
      </div>   
      <div class="item">
        <img src="{{ site.url }}{{ site.baseurl }}/images/slider7001400/2_May6_26John.jpeg" alt="Slide 3" style="width: 100%; height: 450px; object-fit: cover;" />
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


<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

{% for post in site.posts %}
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p>{{ post.summary }}</p>
  <br/>
{% endfor %}


<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
Follow us on <a href='https://www.linkedin.com/company/pinglainstitute/'>LinkedIn</a> or <a href='https://www.facebook.com/pinglainstitute'>Facebook</a> for more.
<br/>
<br/>
<br/>
