---
title: test-file
meta_title: ''
description: ''
date: '2022-04-04T05:00:00.000Z'
image: ''
categories: []
author: ''
tags: []
draft: false
---
## Why Sitepins?

Sitepins is built for teams who want **simplicity**, **control**, and **clean Git history**.

### Key benefits

* Visual editor on top of Git
* Works with Markdown, JSON, YAML, TOML
* No lock-in
* Developer-friendly diffs

​

> "Editing content should feel boring. That’s how you know it works."

### Try formatting

**Bold text** _Italic text_ ~~Strikethrough~~

### Links

​[Visit Sitepins](https://sitepins.com)​

### Code block

```js
export default function Sitepins() {
  return "Git-first CMS";
}
```

✅ Tests: long content, headings, lists, readability, save performance

***

### 3. Custom Schema Fields (Create These)

Create a content type called **“Case Study”**

Add these fields:

| Field Name   | Type    | Test Value          |
| ------------ | ------- | ------------------- |
| client\_name | Text    | Acme Corp           |
| industry     | Select  | SaaS                |
| launch\_year | Number  | 2024                |
| featured     | Boolean | true                |
| website      | URL     | ​​                  |
| rating       | Number  | 4.5                 |
| tags         | List    | cms, git, marketing |

**Edge tests**

* Put text inside `launch_year`
* Leave `client_name` empty if required
* Use decimals in `rating`

### 4. JSON Content (Git Safety Test)

Paste this into a JSON-based collection:

```json
{
  "title": "Git-Safe Editing",
  "published": true,
  "order": 3,
  "meta": {
    "seo_title": "Git-Based CMS for Static Sites",
    "seo_description": "Edit content visually while keeping Git clean."
  }
}

```

​<script>alert("test")</script>​

​

“Create a new blog post called **‘Why Git-Based CMS Matters’**, add a paragraph, save it, and tell me when you’re done.”
