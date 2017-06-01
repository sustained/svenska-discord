---
layout: svenska
title: Svenska Discord
subtitle: Vanliga frågor.
show_downloads: false
---

<hr />

{% for faq in site.data.faqs %}

<h1>Question: <span style="font-size: 0.6em; line-height: 1.0em;">{{ faq.question}}</span></h1>

<br />

<div>
    <h2>Svenska</h2>
    {{ faq.answer_sv | markdownify }}

    <h2>Engelska</h2>
    {{ faq.answer_en | markdownify }}
</div>

<hr />

{% endfor %}