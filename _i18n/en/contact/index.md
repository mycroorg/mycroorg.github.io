# {% include icon.html icon="fa-regular fa-envelope" %}Contact

🚧 Under construction. This section will be available soon. Thank you for your patience!

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
  link="+34-913944969"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
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