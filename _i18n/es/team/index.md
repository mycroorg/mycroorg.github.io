
# {% include icon.html icon="fa-solid fa-users" %}Equipo

En esta sección encontrarás información sobre los miembros de MYCROORG. Haz click en los perfiles para ver más detalles. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ip, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: pt, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ayudoctor, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ^(pdesf|pdesm)$, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ^(phdesf|phdesm)$, lang: es,  alumni: false" %}


{% include section.html %}

## {% include icon.html icon="fa-solid fa-timeline" %}Antiguos miembros

Aquí encontrarás a los antiguos miembros de MYCROORG. Actualmente continúan destacando en la academia, la industria y más allá.

{% include list.html data="members" component="portrait" filters="lang: es, alumni: true" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-school" %}Estudiantes y más

MYCROORG también está formado por estudiantes de Grado, Máster, técnicos de laboratorio, alumnos de prácticas y muchos más. Aquí encontraras una lista de todos ellos.

{% capture col1 %}
#### {% include icon.html icon="fa-solid fa-book" %}TFG

###### 24/25
- Marta Sánchez López-Varela
- Laura Rodríguez Cerrajero

###### 23/24
- Luis Javier Romero García

###### 22/23
- Nadia León Recio
- Raquel Márquez Martín-Tesorero

###### 21/22

- Sara Berguices Miguel

###### 20/21

- Paula de la Huerta Bengoechea

###### 19/20
- Alba Sáez Matía

###### 17/18
- Alejandro García López
{% endcapture %}

{% capture col2 %}
#### {% include icon.html icon="fa-solid fa-building-columns" %}TFM

###### 23/24
- Tomás Sierra Gil
- [Nuria García de la Camacha Selgas](/members/es_nuria.html)

###### 22/23
- Marta Chaumel Matellanes

###### 20/21
- [Clara Melguizo Ávila](/members/es_clara.html)

###### 19/20

- Cristina Alonso García
- [Carolina Gómez-Albarrán](/members/es_carolina.html)

###### 18/19

- Alejandro García López
- Ana Soriano Martín-Nieto

###### 17/18

- Eduardo Sánchez Sánchez
{% endcapture %}

{% capture col3 %}
#### {% include icon.html icon="fa-solid fa-users" %}Otros integrantes previos

- Sofía Almodóvar Montero
- Paula Hernández
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}
