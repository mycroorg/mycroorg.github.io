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

{%
  include feature.html
  image="images/main_page/aspergillus.jpg"
  link="inevstigacion"
  title="🔬  Investigación"
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

{%
  include feature.html
  image="images/divulgacion.jpeg"
  link="proyectos"
  title="💡  Proyectos y divulgación"
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

{%
  include feature.html
  image="images/mycroorg_team_2.jpg"
  link="equipo"
  title="👩🏻‍🔬  Quiénes somos"
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

{%
  include feature.html
  image="images/main_page/aspergillus.jpg"
  link="research"
  title="🔬  Research"
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

{%
  include feature.html
  image="images/divulgacion.jpeg"
  link="projects"
  title="💡  Projects and Science Communication"
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

{%
  include feature.html
  image="images/mycroorg_team_2.jpg"
  link="team"
  title="👩🏻‍🔬  Our Team"
  text=text
%}

{% endif %}