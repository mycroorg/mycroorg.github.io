# {% include icon.html icon="fa-regular fa-envelope" %}Contacto

🚧 En construcción. Esta sección estará lista pronto, ¡gracias por tu paciencia!

{%
  include button.html
  type="email"
  text="jane@smith.com"
  link="jane@smith.com"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
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
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/foto_bio.jpg"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{%
  include figure.html
  image="images/logo_UCM.png"
%}