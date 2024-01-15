+++ 
draft = false
date = 2024-01-15T16:14:51-06:00
title = "Edit Test 01"
description = "Test editing"
slug = "edit-test-01"
authors = []
tags = []
categories = []
externalLink = ""
series = []
+++

This is a quick post to test posting from the GitHub mobile app.

Though not my routine view, I enjoyed the view below while working from Colorado a few days last summer.

{{ with .Resources.GetMatch "*.jpeg" }}
  {{ with .Resize "800x" }}
    <img src="{{ .RelPermalink }}" width="{{ .Width }}" height="{{ .Height }}" />
  {{ end }}
{{ end }}