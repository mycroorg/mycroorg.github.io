
# {% include icon.html icon="fa-solid fa-users" %}Team

🚧 Under construction. This section will be available soon. Thank you for your patience!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: fp: lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: assprof: lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: phd, lang: en, alumni: false" %}

{% include section.html background="images/levadura.jpg" dark=true %}
{% include section.html %}

## {% include icon.html icon="fa-solid fa-timeline" %}Past members

{% include list.html data="members" component="portrait" style="small" filters="lang: en, alumni: true" %}

{% include section.html background="images/levadura.jpg" dark=true %}

{% include section.html %}

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

- Paula Hernández
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}
