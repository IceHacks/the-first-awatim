# The First AWATIM
Help the AWATIM Project grow with Patreon: [https://www.patreon.com/AWATIM](https://www.patreon.com/AWATIM). Also follow our twitter for occasional updates via <a href="https://twitter.com/thefirstawatim">@thefirstawatim</a>. The First AWATIM (aka AWATIM) is a project to bring better services to the modern world (ex: better **games**, better **websites**, better **makers**, and better **world**). AWATIM is a one man team (so far) if you want to help out the only way right now is through <a href="https://www.patreon.com/AWATIM">Patreon</a>.

## Games
We beleive in free games with no ads and minimal IAP's. That is hard for most developers to conceive but not for us. Being a hardcore programmer myself and an mild gamer I "understand" ads but I disagree with them at the same time. The best way to get rid of ads is through nice people (maybe you) that donate and I realize that struggle.

<br>

## Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      - <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    </li>
  {% endfor %}
</ul>

{% include "footer.html" %}