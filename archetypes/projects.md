+++
title = "{{ replace .TranslationBaseName "-" " " | title }}"
date = {{ .Date }}
class = "projects"
draft = false
status = "1_current/2_completed"
name = "Project name"
short_desc = "one or two line description"
people = ["names", "of", "project", "members", "ensure it matches with the name parameter in the front matter of the associated .md file in people/"]
url = "insert external website here otherwise leave blank"
image = "name of project logo in /static/images/projects/. Remove otherwise"
+++
<!-- Insert description that goes into it's own page here. Stuff like publications should be in here for now. Hopefully we'll figure out a better way to do it later. -->