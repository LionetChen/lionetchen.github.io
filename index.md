# Hello World
Github.io web site home page.

## Languages
<ul>
    <li>C#</li>
    <li>BASIC/VB</li>
    <li>Python</li>
</ul>

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{post.url}}">{{post.title}}</a>
        </li>
    {% endfor %}
</ul>