# Hello World!

# My Projects

# My Interests
I'm interested in music and coding
# My Blog
I'm really excited to blog my journey on GitHub.com.

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

# Get in Touch
<ul>
<li><a href="https://github.com/{{ site.github_username
}}">GitHub</a></li>
</ul>
