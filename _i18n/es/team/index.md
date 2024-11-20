
# {% include icon.html icon="fa-solid fa-users" %}Equipo

🚧 En construcción. Esta sección estará lista pronto, ¡gracias por tu paciencia!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: ip, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: pt, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ayudoctor, lang: es,  alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ^(phdesf|phdesm)$, lang: es,  alumni: false" %}

{% include section.html background="images/levadura.jpg" dark=true %}
{% include section.html %}

## {% include icon.html icon="fa-solid fa-timeline" %}Antiguos miembros

{% include list.html data="members" component="portrait" style="small" filters="lang: es, alumni: true" %}

{% include section.html background="images/levadura.jpg" dark=true %}

{% include section.html %}

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

- Paula Hernández
{% endcapture %}

{%
  include cols.html
  col1=col1
  col2=col2
  col3=col3
%}
