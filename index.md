# Hello World!
Hello testing this coming from new-title-tagline branch

# My Interests
I'm interested in teaching novice coders about computer science!

# My Blog
I'm really excited to blog my journey on Github.com

<ul>
  {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}"> {{ post.title }}</a>
      </li>
  {% endfor %}
</ul>


#Get in touch

<ul>
<li><a href="https://twitter.com/{{site.twitter_username}}">Twitter</a></li>
<li><a href="https://github.com/{{site.github_username}}">Github</a></li>
</ul>
