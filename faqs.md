---
layout: svenska
title: Svenska Discord
subtitle: Vanliga frågor.
show_downloads: false
---

<hr />

{% for faq in site.data.faqs %}

<h1>Fråga: <span style="font-size: 0.6em; line-height: 1.0em;">{{ faq.question_sv }}</span></h1>

<p><em>({{ faq.question_en }})</em></p>

<div style="margin-top: 20px;">
    <h2>Svenska</h2>
    {{ faq.answer_sv | markdownify }}

    <h2>Engelska</h2>
    {{ faq.answer_en | markdownify }}
</div>

<hr />

{% endfor %}