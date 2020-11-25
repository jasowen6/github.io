# Hello World!
# My Interests
I'm interested in learning about web development.

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
<li>
<a href="https://twitter.com/{{ site.twitter_jasowen}}"Twitter</a>
</li>
<li>
<a href="https://github.com/{{ site.github_jasowen6}}"GitHub</a>
</li>
</ul>
