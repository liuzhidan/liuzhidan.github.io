---
layout: page
title: Teaching
permalink: /teaching/
description: Courses taught at HKUST (GZ) and Shenzhen University, and selected student achievements.
nav: true
nav_order: 5

# Presentation lives here; the content itself is in _data/teachings.yml.
_styles: |
  .teach-inst { margin-top: 1.6rem; }
  .teach-inst-head {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: 1rem;
    margin-bottom: .55rem;
    padding-bottom: .45rem;
    border-bottom: 1px solid #ececec;
  }
  .teach-inst-name { font-size: 1.02rem; font-weight: 700; color: #222; }
  .teach-inst-count { font-size: .78rem; color: #8a8a8a; white-space: nowrap; }
  .teach-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  @media (max-width: 720px) { .teach-grid { grid-template-columns: 1fr; } }
  .teach-card {
    border: 1px solid #e6e6e6;
    border-left: 3px solid #8a1c1c;
    border-radius: 8px;
    padding: 12px 16px;
    background: #fff;
  }
  .teach-top { display: flex; align-items: center; flex-wrap: wrap; gap: 6px; margin-bottom: 7px; }
  .teach-code {
    font-size: .72rem; font-weight: 700; letter-spacing: .04em;
    padding: .12rem .5rem; border-radius: 4px;
    background: #f7f7f7; color: #8a1c1c; border: 1px solid #ececec;
  }
  .teach-level {
    font-size: .62rem; font-weight: 700; letter-spacing: .06em;
    padding: .14rem .5rem; border-radius: 4px; text-transform: uppercase;
  }
  .teach-level-ug { background: #eaf1ea; color: #2c5c3f; border: 1px solid #cfe0d3; }
  .teach-level-pg { background: #e8eef7; color: #2c4d7c; border: 1px solid #cfd9e8; }
  .teach-term { margin-left: auto; font-size: .76rem; color: #8a8a8a; white-space: nowrap; }
  .teach-title { font-weight: 600; font-size: .93rem; line-height: 1.4; }
  .teach-zh { font-weight: 400; color: #8d8d8d; font-size: .85em; }
  .teach-achv-title { margin-top: 2.2rem; font-size: 1.15rem; font-weight: 700; }
  ul.teach-achv { list-style: none; padding-left: 0; margin-top: .8rem; }
  ul.teach-achv li {
    display: flex; gap: .9rem; align-items: baseline;
    margin-bottom: .7rem; padding-left: .95rem;
    border-left: 2px solid #e6e6e6; line-height: 1.55; font-size: .92rem;
  }
  ul.teach-achv li b { color: #8a1c1c; font-size: .82rem; white-space: nowrap; flex: 0 0 auto; }

  /* Dark theme: al-folio switches `html[data-theme=dark]` via the toggle button,
     so we must NOT use @media (prefers-color-scheme) here. */
  html[data-theme=dark] .teach-inst-head { border-bottom-color: #3a3f45; }
  html[data-theme=dark] .teach-inst-name { color: #e8ecf1; }
  html[data-theme=dark] .teach-inst-count { color: #9aa0a6; }
  html[data-theme=dark] .teach-card { background: #1e2124; border-color: #3a3f45; border-left-color: #b04a4a; }
  html[data-theme=dark] .teach-code { background: #2a2e33; color: #e57373; border-color: #3a3f45; }
  html[data-theme=dark] .teach-level-ug { background: #22322a; color: #7fc79c; border-color: #33513f; }
  html[data-theme=dark] .teach-level-pg { background: #232c3a; color: #7fa8d8; border-color: #33404f; }
  html[data-theme=dark] .teach-term { color: #9aa0a6; }
  html[data-theme=dark] .teach-zh { color: #8a8f96; }
  html[data-theme=dark] ul.teach-achv li { border-left-color: #3a3f45; }
  html[data-theme=dark] ul.teach-achv li b { color: #e57373; }
---

Courses and selected student achievements at HKUST (GZ) and Shenzhen University.

{::nomarkdown}
{% include teaching.liquid %}
{:/}
