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
<li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>

# Other Projects
<ul>
<li><a href="https://github.com/evman421/evman421.github.io">evman421 GitHub Page</a></li>
<li><a href="https://github.com/jasowen6/html5helloworld">HTML5 Hello World</a></li>
</ul>
