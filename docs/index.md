---
layout: default
title: Python & Developer Course
description: A comprehensive course covering Python programming and developer tools
permalink: /
---

# Welcome to the Python & Developer Course

## About This Course
This course provides a comprehensive introduction to Python programming and developer tools. We'll cover:

- Python fundamentals
- Web development with Python
- Version control with Git
- And much more!

## Course Modules
{% for module in site.course_modules %}
- [{{ module.title }}]({{ module.url }})
{% endfor %}

## Get Started
[Download the course materials](#) or [browse the course content](#).

<button class="btn" onclick="alert('Welcome to the course!')">Click Me</button>

## About the Instructor
{{ site.author.name }} is a Python developer and educator with over 10 years of experience in software development.
```

### Key Elements Explained:

1. **Front Matter Section** (between `---`):
   ```yaml
   ---
   layout: default
   title: Python & Developer Course
   description: A comprehensive course covering Python programming and developer tools
   permalink: /
   ---
