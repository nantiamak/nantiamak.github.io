---
layout: default
---
<div id="summary">
     <p>I am a PhD student in Computer Science at the <a href="https://www.aueb.gr/en">Athens University of Economics and Business</a> supervised by Professor Vasilis Vassalos. My research focuses on integrating machine learning functionality with relational databases, which aligns with my interests in declarative machine learning (a paradigm well-known from databases applied on the area of machine learning). In the context of this effort, I have also worked with the <a href="https://developer.logicblox.com/">LogicBlox</a> team (later acquired by <a href="https://www.infor.com/">Infor</a>) on expressing and optimising machine learning problems using the company's relational platform.</p>

<p>In the past I did research on the interesting topic of sentiment analysis, which resulted in the development of a related component for a commercialised platform.
</p>

<p>
I hold a BSc in Computer Science from the <a href="http://www.uoi.gr/">University of Ioannina</a> and a MSc in Information Systems from my current University. You can find my (possibly outdated) CV <a href="#">here</a>.
</p>
</div>
<div id="contactAndPhoto">
     <img id="myPicture" src="/assets/images/nantia3.png">
      <ul class="contact-list">
      	  <li class="detail-element">
	      <img src="/assets/images/envelope.svg" id="envelope-image">
	      {%- if site.email -%}
	      <span>{{ site.email }}</span>
	      {%- endif -%}
          </li>
	  <li class="detail-element">
	      <img src="/assets/images/address.svg" id="pin-image">
	      {%- if site.address -%}
	      <span>{{ site.office }}</span>
	      <br>
	      <span>{{ site.address }}</span>
	      <br>
	      <span>{{ site.city_country }}</span>
	      {%- endif -%}
	  </li>
	</ul>
	{%- include social.html -%}
</div>
<div style="clear: both;"></div>
  
  