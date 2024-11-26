# {% include icon.html icon="fa-regular fa-envelope" %}Contacto

Nuestro grupo forma parte del [Departamento de Genética, Fisiología y Microbiología](https://www.ucm.es/gfm/) de la [Universidad Complutense de Madrid](https://www.ucm.es/). Puedes encontrarnos en el Laboratorio 7 de la planta 11 de la [Facultad de Ciencias Biológicas](https://biologicas.ucm.es/).

{%
  include button.html
  type="email"
  text="belenp@ucm.es"
  link="belenp@ucm.es"
%}
{%
  include button.html
  type="phone"
  text="(+34) 91 394 49 69"
  tooltip="Teléfono"
  link="+34-913944969"
%}
{%
  include button.html
  type="address"
  text="Dirección"
  tooltip="Nuestra dirección en Google Maps"
  link="https://maps.app.goo.gl/gThEGgudWjeU9wdC7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/logo_bio.jpg"
  link="https://biologicas.ucm.es/"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/foto_bio.jpg"
  link="https://www.ucm.es/gfm/"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{%
  include figure.html
  image="images/logo_UCM.png"
  link="https://www.ucm.es/"
  width="70%"
%}