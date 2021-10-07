---
layout: default
---

<div id="news" style="font">
I'm co-organizing DBAI - Workshop on Databases and AI - @ NeurIPS2021. Check out our exciting program at <a href="https://dbai-workshop.github.io/">
</div>

<div id="summary">
     <p>I am a postdoc researcher with the <a href="https://www.cwi.nl/research/groups/database-architectures">Database Architectures group at CWI (Centrum Wiskunde & Informatica)</a> working on the area of exploratory data analysis.

Prior to that I earned my PhD in Computer Science from the <a href="https://www.aueb.gr/en">Athens University of Economics and Business</a>, supervised by Professor Vasilis Vassalos. My PhD thesis focused on integrating machine learning (ML) functionality with relational databases and expressing ML algorithms in declarative programming languages. In the context of this effort, I have also worked with the <a href="https://developer.logicblox.com/">LogicBlox</a> team (later acquired by <a href="https://www.infor.com/">Infor</a>) on expressing and optimising machine learning problems using the company's relational platform.</p>

<p>In the past I did research on the interesting topic of sentiment analysis, which resulted in the development of a related component for a Greek brand monitoring platform.
</p>

<p>
I hold a BSc in Computer Science from the <a href="http://www.uoi.gr/">University of Ioannina</a> and a MSc in Information Systems from Athens University of Economics and Business. You can find my (possibly outdated) CV <a href="/assets/papers/Nantia_Makrynioti_CV.pdf">here</a>.
</p>
</div>
<div id="contactAndPhoto">
     <img id="myPicture" src="/assets/images/nantia_japan.jpg">
      <ul class="contact-list">
      	  <li class="detail-element">
	      <img src="/assets/images/envelope.svg" id="envelope-image">
	      {%- if site.email -%}
	      <span>{{ site.email }}</span>
	      {%- endif -%}
          </li>
	  <li class="detail-element">
	      <div id="pin-div">
	      <img src="/assets/images/address.svg" id="pin-image">
	      </div>
	      {%- if site.address -%}
	      <div id="address-div">
	      <span>{{ site.office }}</span>
	      <br>
	      <span>{{ site.address }}</span>
	      <br>
	      <span>{{ site.city_country }}</span></div>
	      <div style="clear: both;"></div>
	      {%- endif -%}
	  </li>
	</ul>
	{%- include social.html -%}
</div>
<div style="clear: both;"></div>
