---
layout: svenska
title: Svenska Discord
subtitle: Vanliga frågor.
show_downloads: false
---

{% for faq in site.data.faqs %}

<h2>Fråga: <span style="font-size: 0.6em; line-height: 1.0em;">{{ faq.question_sv }}</span></h2>

<p><em>({{ faq.question_en }})</em></p>

<div style="margin-top: 20px;">
    <h3>Engelska</h3>
    {{ faq.answer_en | markdownify }}
    
    <h3>Svenska</h3>
    {{ faq.answer_sv | markdownify }}
</div>

<hr />

{% endfor %}