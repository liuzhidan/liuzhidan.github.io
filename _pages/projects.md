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
  .proj-list { display: grid; grid-template-columns: 1fr; gap: 14px; margin-top: 1.1rem; }
  .proj-card {
    border: 1px solid #e6e6e6;
    border-left: 3px solid #8a1c1c;
    border-radius: 8px;
    padding: 14px 18px;
    background: #fff;
  }
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
---

Our research is supported by the National Natural Science Foundation of China, the Natural Science Foundation of Guangdong, HKUST (GZ), Shenzhen University and industry partners.

{::nomarkdown}
{% include projects.liquid %}
{:/}
