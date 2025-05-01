+++
title = "Introduction"
description = ""
date = 2021-05-01T08:00:00+00:00
updated = 2021-05-01T08:00:00+00:00
draft = false
weight = 10
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = ''
toc = true
top = false
+++

## Coming Soon

Need to compose some c sharp stuff in here.

{% admonition(type="info",title="Information") %}
Some information
{% end %}

{% admonition(type="note",title="Note") %}
Some notes
{% end %}

{% admonition(type="tip",title="Tip") %}
A tip
{% end %}

{% admonition(type="warning",title="Warning") %}
Some Warning
{% end %}

{% admonition(type="danger",title="Danger") %}
Danger Robinsons!
{% end %}

{% spoiler() %}
hello hidden secret
{% end %}

{% spoiler(fixed_blur=true) %}
```bash
echo hiddenSecrets
```
{% end %}

## Header 2

### Header 3

#### Header 4

## header 2

> [!NOTE]
> Useful information that users should know, even when skimming content.

some content right above

{{ aside(text="An Aside Here") }}


{% tabs(tabs=["c sharp","two","three"],group="code") %}
{% tab() %}
hello world
this is some text

and a new para
{% end %}
{% tab() %}
```bash
hello world
```
{% end %}
{% tab() %}
```bash
Some cheese in here
```
{% end %}
{% end %}

{% tabs(tabs=["one","two","three"],group="cheese") %}
{% tab() %}
hello world
this is some text

and a new para
{% end %}
{% tab() %}
```bash
hello world
```
{% end %}
{% tab() %}
```c#,linenos,name=src/main.rs
public void main () {};
public void main () {};
public void main () {};
public void main () {};

```
{% end %}
{% end %}
