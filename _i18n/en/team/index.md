
# {% include icon.html icon="fa-solid fa-users" %}Team

🚧 Under construction. This section will be available soon. Thank you for your patience!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, lang: en, alumni: false" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$), lang: en, alumni: false" %}

{% include section.html background="images/levadura.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
