
# {% include icon.html icon="fa-solid fa-users" %}Team

In this section you will find information about MYCROORG members. Click on the profiles to see more details. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: fp: lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: assprof: lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: postdoc: lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: phd, lang: en, alumni: false" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-timeline" %}Past members

Here you will find the past members of MYCROORG. Today, they continue to shine in academia, industry and beyond.

{% include list.html data="members" component="portrait" filters="lang: en, alumni: true" %}

{% include section.html %}

## {% include icon.html icon="fa-solid fa-school" %}Students and more

MYCROORG is also formed by BSc and MSc students, lab technicians, trainees and more. Here you will find a list of all of them.

{% capture col1 %}
#### {% include icon.html icon="fa-solid fa-book" %}BSc thesis

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
#### {% include icon.html icon="fa-solid fa-building-columns" %}MSc thesis

###### 23/24
- Tomás Sierra Gil
- [Nuria García de la Camacha Selgas](/members/nuria.html)

###### 22/23
- Marta Chaumel Matellanes

###### 20/21
- [Clara Melguizo Ávila](/members/clara.html)

###### 19/20

- Cristina Alonso García
- [Carolina Gómez-Albarrán](/members/carolina.html)

###### 18/19

- Alejandro García López
- Ana Soriano Martín-Nieto

###### 17/18

- Eduardo Sánchez Sánchez
{% endcapture %}

{% capture col3 %}
#### {% include icon.html icon="fa-solid fa-users" %}More past members

- Andrea Milena Fontalvo Caballero
- Marta Espinel Colao
- Sofía Almodóvar Montero
- Paula Hernández
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}
