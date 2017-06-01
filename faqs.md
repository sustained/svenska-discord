---
layout: svenska
title: Svenska Discord
subtitle: Vanliga frågor.
show_downloads: false
---

<hr />

{% for faq in site.data.faqs %}

<h1>Fråga: <span style="font-size: 0.6em; line-height: 1.0em;">{{ faq.question_sv }}</span></h1>

<h4>{{ faq.question_en }}

<br />

<div>
    <h3>Svenska</h3>
    {{ faq.answer_sv | markdownify }}

    <h3>Engelska</h3>
    {{ faq.answer_en | markdownify }}
</div>

<hr />

{% endfor %}