+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'

nopostheader = true
layout = "single"

date = {{ .Date }}
tags = [  ]
author = "Me"
showToc = true
TocOpen = false
draft = false
hidemeta = false
comments = false
description = "Desc Text."
canonicalURL = "https://canonical.url/to/page"
disableHLJS = true
disableShare = false
hideSummary = false
searchHidden = false
ShowReadingTime = true
ShowBreadCrumbs = true
ShowPostNavLinks = true
ShowWordCount = true
ShowRssButtonInSectionTermList = true
UseHugoToc = true

[cover]
image = "<image path/url>"
alt = "<alt text>"
caption = "<text>"
relative = false
hidden = true

# [editPost]
URL = "https://github.com/<path_to_repo>/content"
Text = "Suggest Changes"
appendFilePath = true
+++
