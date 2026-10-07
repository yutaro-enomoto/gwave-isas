---
---



## Welcome to ISAS GWave Group! --- 宇宙研重力波グループへようこそ
重力の謎に、光・量子・熱の物理で挑みます。

{% include section.html %}


{% capture text %}

研究内容について一言

{%
  include button.html
  link="projects"
  text="Researches --- 研究内容"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Researches --- 研究内容"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

{%
  include button.html
  link="team"
  text="Member --- メンバー"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Member --- メンバー"
  text=text
%}
