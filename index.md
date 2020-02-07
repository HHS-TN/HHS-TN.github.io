# Technische Natuurkunde - Haagse Hogeschool

Hier staan de github-repositories van de docenten van TN. 

# Repositories
{% for repository in site.github.public_repositories %}
  {% if repository.name != "HHS-TN.github.io" %}
  * [{{ repository.name }}]({{ repository.html_url }})
  {% endif %}
{% endfor %}

# Docenten
{% for user in site.github.organization_members %}
  * [{{ user.login }}]({{ user.html_url }})
{% endfor %}

# Links
* [Angstrom - studievereniging op Git](https://github.com/Studievereniging-Angstrom)
* [Angstrom - studievereniging op Git (account)](https://github.com/Anders-Jonas-Angstrom)
