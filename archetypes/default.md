+++
title = "{{ replace .File.ContentBaseName "-" " " | title }}"

categories = ["default"]

tags = ["blog"]

draft = false
hidden = false
comments = false

image = "https://picsum.photos/seed/{{ substr (md5 (.Date)) 4 8 }}/1000/700"

date = {{ .Date }}
lastmod = {{ .Date }}
expiryDate = {{ .Date }}
# See details front matter: https://stack.jimmycai.com/writing/frontmatter
# See details front matter: https://gohugo.io/content-management/front-matter
+++
