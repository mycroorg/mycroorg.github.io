---
---

#  {% translate mainpage.thetitle %}
{% include section.html %}

{% if site.lang == "es" %}

{% capture text %}

Los hongos son el centro de nuestra investigación. Buscamos comprender la biología y la genética de los hongos filamentosos toxígenos y fitopatógenos, así como de levaduras de interés industrial.

{%
  include button.html
  link="investigacion"
  text="Nuestras publicaciones"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture researchtitlees %}

{% include icon.html icon="fa-solid fa-microscope" %} &nbsp;Investigación

{% endcapture %}

{%
  include feature.html
  image="images/main_page/aspergillus.jpg"
  link="investigacion"
  title=researchtitlees
  text=text
%}

{% capture text %}

Nuestro trabajo incluye artículos científicos, proyectos, contratos con empresas y colaboraciones con otros grupos nacionales e internacionales. Pero no nos quedamos ahí. También somos conscientes de la importancia de la divulgación científica, y trabajamos para hacerla accesible y para todos los públicos.

{%
  include button.html
  link="proyectos"
  text="Echa un vistazo"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture projectstitlees %}

{% include icon.html icon="fa-solid fa-lightbulb" %} &nbsp;Proyectos y divulgación

{% endcapture %}

{%
  include feature.html
  image="images/divulgacion.jpg"
  link="proyectos"
  title=projectstitlees
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Somos un grupo amplio de investigadores, desde estudiantes hasta profesores experimentados, unidos por el fascinante mundo de los hongos. Contribuimos a resolver un reto del mundo real: eliminar las micotoxinas de los alimentos.

{%
  include button.html
  link="equipo"
  text="Conócenos"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture teamtitlees %}

{% include icon.html icon="fa-solid fa-users" %} &nbsp;Quiénes somos

{% endcapture %}

{%
  include feature.html
  image="images/mycroorg_team_2.jpg"
  link="equipo"
  title=teamtitlees
  text=text
%}

{% else %}

{% capture text %}

Fungi constitute the core of our scientific research. We seek to understand the biology and genetics of toxigenic and phytopathogenic filamentous fungi, as well as yeasts of industrial interest.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture researchtitleen %}

{% include icon.html icon="fa-solid fa-microscope" %} &nbsp;Research

{% endcapture %}

{%
  include feature.html
  image="images/main_page/aspergillus.jpg"
  link="research"
  title=researchtitleen
  text=text
%}

{% capture text %}

Our work includes scientific publications, projects, contracts with companies and collaborations with other national and international groups. But we do not stop there. We are also aware of the importance of popular science, and we work to make it accessible to all audiences.

{%
  include button.html
  link="projects"
  text="Check out our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture projectstitleen %}

{% include icon.html icon="fa-solid fa-lightbulb" %} &nbsp;Projects and Science Communication

{% endcapture %}

{%
  include feature.html
  image="images/divulgacion.jpg"
  link="projects"
  title=projectstitleen
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a dynamic group of researchers, ranging from enthusiastic students to experienced full professors, united by the fascinating world of fungi. We contribute to solving a real-world challenge: eliminating mycotoxins from food.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{% capture teamtitleen %}

{% include icon.html icon="fa-solid fa-users" %} &nbsp;Our team

{% endcapture %}

{%
  include feature.html
  image="images/mycroorg_team_2.jpg"
  link="team"
  title=teamtitleen
  text=text
%}

{% endif %}

{% include section.html %}

{% if site.lang == "es" %}

# {% include icon.html icon="fa-brands fa-x-twitter" %}ÚLTIMOS POSTS DE @MYCROORG

{% else %}

# {% include icon.html icon="fa-brands fa-x-twitter" %}LAST POSTS FROM @MYCROORG

{% endif %}

{% capture tweet1 %}

<blockquote class="twitter-tweet"><p lang="es" dir="ltr">¿Quieres saber qué hacemos en <a href="https://twitter.com/mycroorg?ref_src=twsrc%5Etfw">@mycroorg</a>? ¡No te pierdas nuestros vídeos! 📽️<br>Comenzamos con <a href="https://twitter.com/seraliseg?ref_src=twsrc%5Etfw">@seraliseg</a> que explica cómo abordamos uno de los objetivos de su tesis para caracterizar las especies del género &quot;Fusarium&quot; en cereales 🌾🧫🌽 <a href="https://twitter.com/hashtag/bioinform%C3%A1tica?src=hash&amp;ref_src=twsrc%5Etfw">#bioinformática</a> <a href="https://twitter.com/hashtag/micotoxinas?src=hash&amp;ref_src=twsrc%5Etfw">#micotoxinas</a> <a href="https://twitter.com/hashtag/mycroorgmola?src=hash&amp;ref_src=twsrc%5Etfw">#mycroorgmola</a> <a href="https://t.co/1swee4PNds">pic.twitter.com/1swee4PNds</a></p>&mdash; MYCROORG (@mycroorg) <a href="https://twitter.com/mycroorg/status/1917475089026633735?ref_src=twsrc%5Etfw">April 30, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

{% endcapture %}

{% capture tweet2 %}

<blockquote class="twitter-tweet"><p lang="es" dir="ltr">Y como colofón final al “World Mycotoxin Forum”, <a href="https://twitter.com/Marielaar9?ref_src=twsrc%5Etfw">@Marielaar9</a> recogió el premio Naresh Magan otorgado por la <a href="https://twitter.com/ISM_Society?ref_src=twsrc%5Etfw">@ISM_Society</a> 👏🏻👏🏻 ¡Enhorabuena Mariela! Súper orgullosas de ti 😍 <a href="https://t.co/gdMhdIpffm">pic.twitter.com/gdMhdIpffm</a></p>&mdash; MYCROORG (@mycroorg) <a href="https://twitter.com/mycroorg/status/1910230869643510048?ref_src=twsrc%5Etfw">April 10, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

{% endcapture %}

{% capture tweet3 %}

<blockquote class="twitter-tweet"><p lang="es" dir="ltr">En <a href="https://twitter.com/mycroorg?ref_src=twsrc%5Etfw">@mycroorg</a> estudiamos las micotoxinas y sus hongos productores desde muchas perspectivas 👩‍🔬 En este segundo vídeo <a href="https://twitter.com/cerenaortega?ref_src=twsrc%5Etfw">@cerenaortega</a> cuenta cómo analizamos la presencia de micotoxinas en suelo y por qué es importante hacerlo🌾¡Síguenos para no perderte nuestros vídeos! <a href="https://twitter.com/hashtag/mycroorgmola?src=hash&amp;ref_src=twsrc%5Etfw">#mycroorgmola</a> <a href="https://t.co/y8B6vMGJ2d">pic.twitter.com/y8B6vMGJ2d</a></p>&mdash; MYCROORG (@mycroorg) <a href="https://twitter.com/mycroorg/status/1920497983868616920?ref_src=twsrc%5Etfw">May 8, 2025</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 

{% endcapture %}

{%
  include cols.html
  col1=tweet3
  col2=tweet1
  col3=tweet2
%}