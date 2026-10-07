---
---



## Welcome to ISAS GWave Group! --- 宇宙研重力波グループへようこそ
重力の謎に、光・量子・熱の物理で挑みます。

{% include section.html %}


{% capture text %}

研究内容について一言

{%
  include button.html
  link="research"
  text="Research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Research -- 研究内容"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Members"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Members -- メンバー"
  text=text
%}

{% include section.html %}

{% capture col1 %}
## {% include icon.html icon="fa-solid fa-newspaper" %}Latest NEWS

  {% assign sorted_news = site.posts | sort: "last_modified_at" | reverse %}
    {% for post in sorted_news limit:3 %}
    
  <div class="news-card">
    <div class="news-header">
        <span class="news-title">{{ post.title }}</span>
        <span class="news-date">{% include icon.html icon="fa-regular fa-calendar" %} {{ post.last_modified_at | date: "%Y-%B-%d" }} </span>
    </div>
    <div class="news-description">
        {{ post.description }} 
    </div>
  </div>

    {% endfor %}  
  
{%
  include button.html
  link="news"
  text="Read all news"
  icon="fa-solid fa-arrow-right"
  flip=true
  align=left

%}

{% endcapture %}

