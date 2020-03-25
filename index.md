# Hello World!

# My Projects
<ul>
<li><a href="https://finedjentleman.github.io/Helloworld/">Hello
World Project</a></li>
<li><a href="https://github.com/thewecanzone/
GitHubForDummiesReaders">GitHub For Dummies Repo</a></li>
</ul>

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
