---
layout: default
---
{% include vapi-widget.html %}


<center>
  <h1>Die Welt neu entdecken: Fundiertes Wissen, inspiriert durch Natur und Wissenschaft.</h1>
</center>

![Alt text](/assets/img/MoskauShrooms.jpg)
### Im Herbst 2025 gibt's wieder Pilztouren im Süden von Hamburg!
### 👉 [Anmeldung hier](https://forms.gle/JvqXBEnY9zq2iczn6) 👈

<!-- The blog posts will automatically appear below, because the layout injects them here -->








<!-- ...existing code... -->



<h2>Themen</h2>
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <div>
    {% for post in category[1] %}
      <div style="margin-bottom: 1.2em;">
        <span style="color: #666; font-size: 0.95em;">
          {{ post.date | date: "%b %d, %Y" }}
          {% if post.lang %}
            •
            {% case post.lang %}
              {% when "en" %} 🇬🇧 English
              {% when "de" %} 🇩🇪 Deutsch
              {% when "ru" %} 🇷🇺 Русский
              {% else %} {{ post.lang | upcase }}
            {% endcase %}
          {% endif %}
        </span><br>
        <a href="{{ post.url }}" style="font-size: 1.25em; color: #1976d2;">
          {{ post.title }}
        </a>
      </div>
    {% endfor %}
  </div>
{% endfor %}
<!-- ...existing code... -->