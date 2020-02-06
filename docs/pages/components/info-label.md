---
title: Info Label
id:
keywords: info label, info, label, info-label, counter
sidebar: left-navigation-sidebar
toc: false
permalink: components/info-label.html
folder: components
---

Info Label are used to easily highlight the Information. `fd-info-label`, `fd-info-label--numeric`, `fd-info-label--accentcolor1` and `fd-info-label--icon`
{: .docs-intro}

<br>

# info-label

## info-label Style Options
`info-label` Info Label has three options: `--accentcolor1,accentcolor2...`, `--icon` and `--numeric`
{% capture info-label %}
<span class="fd-info-label fd-info-label--numeric fd-info-label--accentcolor1">6</span>
<span class="fd-info-label fd-info-label--numeric fd-info-label--accentcolor2">6.2</span>
<span class="fd-info-label fd-info-label--numeric fd-info-label--accentcolor3">42k</span>
<span class="fd-info-label fd-info-label--accentcolor3">Info Label </span>
<span class="fd-info-label fd-info-label--accentcolor4">Missing Item</span>
<span class="fd-info-label fd-info-label--accentcolor5 fd-info-label--icon sap-icon--photo-voltaic">Delivered</span>

{% endcapture %}
{% include display-component.html component=info-label %}

<br>

### info-label Color Options
In addition the the default grey, there are additional Semantic color options available `--accentcolor1,accentcolor2...`.
{% capture info-label %}

<span class="fd-info-label fd-info-label--accentcolor1">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor2">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor3">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor4">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor5">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor6">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor7">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor8">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor9">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor10">Info Label</span>

{% endcapture %}
{% include display-component.html component=info-label %}

<hr>


## Status Indicator Label with any icons

In addition the the default grey, there are additional Semantic color options available `--icon`, and Icons placeholder with sap Icon `sap-icon--`.

{% capture info-label %}

<span class="fd-info-label fd-info-label--accentcolor1 fd-info-label--icon sap-icon--future">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor2 fd-info-label--icon sap-icon--add-activity-2">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor3 fd-info-label--icon sap-icon--bar-code">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor4 fd-info-label--icon sap-icon--time-entry-request">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor5 fd-info-label--icon sap-icon--bubble-chart">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor6 fd-info-label--icon sap-icon--hide">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor7 fd-info-label--icon sap-icon--key">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor8 fd-info-label--icon sap-icon--technical-object">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor9 fd-info-label--icon sap-icon--upload-to-cloud">Info Label</span>
<br><br>
<span class="fd-info-label fd-info-label--accentcolor10 fd-info-label--icon sap-icon--upload-to-cloud">Info Label</span>

{% endcapture %}
{% include display-component.html component=info-label %}

<br>

<style>
.fd-info-label{
    margin-right: 20px;
}
</style>
