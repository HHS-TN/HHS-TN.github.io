# Technische Natuurkunde - Haagse Hogeschool

Hier staan de github-repositories van de docenten van TN. 

# Repositories
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}

# Docenten
{% for user in site.github.organization_members %}
  * [{{ user.login }}]({{ user.url }})
{% endfor %}

# Links
[Angstrom - studievereniging op Git](https://github.com/Studievereniging-Angstrom)
