---
layout: page
title: Projects
permalink: /projects/
description: Selected projects and grants of the MobiX group.
nav: true
nav_order: 3

# Presentation lives here; the content itself is in _data/projects.yml.
_styles: |
  .proj-summary {
    margin: 1.5rem 0 0;
    padding: .7rem 1rem;
    background: #f7f7f7;
    border-radius: 8px;
    font-size: .85rem;
    color: #666;
  }
  .proj-summary-num { font-size: 1.1rem; font-weight: 700; color: #222; margin-right: .5rem; }
  .proj-summary-text b { color: #8a1c1c; }
  /* one block per funding level; the colour marks the level */
  .proj-group {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: 1rem;
    margin: 1.7rem 0 .6rem;
    padding-bottom: .45rem;
    border-bottom: 1px solid #ececec;
  }
  .proj-group-text { font-size: .9rem; font-weight: 700; letter-spacing: .01em; }
  .proj-group-meta { font-size: .76rem; color: #8a8a8a; white-space: nowrap; }
  .proj-group-national .proj-group-text { color: #8a1c1c; }
  .proj-group-provincial .proj-group-text { color: #b07a3c; }
  .proj-group-municipal .proj-group-text { color: #3f74ad; }
  .proj-group-industry .proj-group-text { color: #3f9e78; }
  .proj-group-other .proj-group-text { color: #8a8a8a; }
  .proj-list { display: grid; grid-template-columns: 1fr; gap: 14px; margin-top: .2rem; }
  .proj-card {
    border: 1px solid #e6e6e6;
    border-left: 3px solid #8a1c1c;
    border-radius: 8px;
    padding: 14px 18px;
    background: #fff;
  }
  .proj-card-national { border-left-color: #8a1c1c; }
  .proj-card-provincial { border-left-color: #b07a3c; }
  .proj-card-municipal { border-left-color: #4a86c8; }
  .proj-card-industry { border-left-color: #3f9e78; }
  .proj-card-other { border-left-color: #9a9a9a; }
  .proj-card-top { display: flex; align-items: center; justify-content: space-between; gap: 12px; margin-bottom: 7px; }
  .proj-badge {
    font-size: .62rem; font-weight: 700; letter-spacing: .06em;
    padding: .14rem .5rem; border-radius: 4px; text-transform: uppercase;
  }
  .proj-badge-pi { background: #f7e8e8; color: #8a1c1c; border: 1px solid #e5caca; }
  .proj-badge-co { background: #eaf1ea; color: #2c5c3f; border: 1px solid #cfe0d3; }
  .proj-amt { font-size: .82rem; font-weight: 600; color: #8a1c1c; }
  .proj-title { font-weight: 600; font-size: .95rem; line-height: 1.4; margin-bottom: 4px; }
  .proj-funder { font-size: .85rem; color: #555; line-height: 1.5; }
  .proj-funder span { color: #8d8d8d; }
  .proj-meta { font-size: .76rem; color: #8a8a8a; margin-top: 6px; }
  .proj-meta span + span::before { content: "\00B7"; margin: 0 .45rem; color: #c9c9c9; }
  /* Dark theme: al-folio switches `html[data-theme=dark]` via the toggle button,
     so we must NOT use @media (prefers-color-scheme) here. */
  html[data-theme=dark] .proj-summary { background: #232629; color: #9aa0a6; }
  html[data-theme=dark] .proj-summary-num { color: #e8ecf1; }
  html[data-theme=dark] .proj-summary-text b { color: #e57373; }
  html[data-theme=dark] .proj-group { border-bottom-color: #3a3f45; }
  html[data-theme=dark] .proj-group-meta { color: #9aa0a6; }
  html[data-theme=dark] .proj-group-national .proj-group-text { color: #e57373; }
  html[data-theme=dark] .proj-group-provincial .proj-group-text { color: #d4a857; }
  html[data-theme=dark] .proj-group-municipal .proj-group-text { color: #7fa8d8; }
  html[data-theme=dark] .proj-group-industry .proj-group-text { color: #5fc98f; }
  html[data-theme=dark] .proj-group-other .proj-group-text { color: #9aa0a6; }
  html[data-theme=dark] .proj-card { background: #1e2124; border-color: #3a3f45; }
  html[data-theme=dark] .proj-card-national { border-left-color: #b04a4a; }
  html[data-theme=dark] .proj-card-provincial { border-left-color: #c99a5c; }
  html[data-theme=dark] .proj-card-municipal { border-left-color: #6a9fd8; }
  html[data-theme=dark] .proj-card-industry { border-left-color: #5cb894; }
  html[data-theme=dark] .proj-card-other { border-left-color: #7a7a7a; }
  html[data-theme=dark] .proj-badge-pi { background: #3a2226; color: #e57373; border-color: #5a3038; }
  html[data-theme=dark] .proj-badge-co { background: #22322a; color: #7fc79c; border-color: #33513f; }
  html[data-theme=dark] .proj-amt { color: #e57373; }
  html[data-theme=dark] .proj-funder { color: #a8b2bd; }
  html[data-theme=dark] .proj-funder span { color: #7d8792; }
  html[data-theme=dark] .proj-meta { color: #9aa0a6; }
  html[data-theme=dark] .proj-meta span + span::before { color: #4a5158; }
---

Our research is supported by the National Natural Science Foundation of China, the Natural Science Foundation of Guangdong, HKUST (GZ), Shenzhen University and industry partners.

{::nomarkdown}
{% include projects.liquid %}
{:/}
