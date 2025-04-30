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



## Header 2

### Header 3

#### Header 4

## header 2

some content right above

{% tabs(tabs=["one","two","three"],group="code") %}
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
```bash
Some cheese in here
```
{% end %}
{% end %}