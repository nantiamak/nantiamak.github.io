---
layout: default
---
<div id="summary">
<p>Welcome to my website! I am a software engineer at <a href="https://www.relational.ai/">RelationalAI</a> working on core components of the company's relational knowledge graph system.
Prior to that, I was a postdoc researcher with the <a href="https://www.cwi.nl/research/groups/database-architectures">Database Architectures group at CWI (Centrum Wiskunde & Informatica)</a> doing research on the area of exploratory data analysis.</p>

<p>I earned my PhD in Computer Science from the <a href="https://www.aueb.gr/en">Athens University of Economics and Business</a>, supervised by Professor Vasilis Vassalos. My PhD thesis focused on integrating machine learning (ML) functionality with relational databases and expressing ML algorithms in declarative programming languages. In the context of this effort, I have also worked with the <a href="https://developer.logicblox.com/">LogicBlox</a> team (later acquired by <a href="https://www.infor.com/">Infor</a>) on expressing and optimising machine learning problems using the company's relational platform.</p>

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
	</ul>
	{%- include social.html -%}
</div>
<div style="clear: both;"></div>
