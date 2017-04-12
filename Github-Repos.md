---
layout: page
title: repos
color: indigo
cover: "https://camo.githubusercontent.com/fb782da4019ab66eeea35cc9b9ce73b2438b1688/687474703a2f2f646f632e72756c746f722e636f6d2f696d616765732f6769746875622d6c6f676f2e706e67"
permalink: /repos/		
---

<h1>Github Repositories</h1>
Here you can find links to all my public git repositories. I am currently in the process of adding details to each of the README.md's of these projects, simple details like project start date, weather it was a college project or not. If any further information is need as regards my repositories feel free to email me and I can answer any questions you might have.

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
