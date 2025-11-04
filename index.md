
<link rel="stylesheet" href="style.css">

<div class="markdown-body">
{% capture readme_content %}
{% include_relative README.md %}
{% endcapture %}

{{ readme_content | markdownify }}


</div>
