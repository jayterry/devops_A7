layout: default title: Home | DevOps Activity Log

<!-- 鏈接到 style.css 樣式表 -->

<link rel="stylesheet" href="style.css">

<div class="markdown-body">
<!-- 關鍵修正：使用 'capture' 和 'markdownify' 濾鏡來強制 Jekyll 將 README.md 的內容渲染為 Markdown -->
{% capture readme_content %}
{% include_relative README.md %}
{% endcapture %}

{{ readme_content | markdownify }}


</div>
