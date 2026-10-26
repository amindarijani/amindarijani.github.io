---
layout: page
permalink: /resources/
title: resources
description: Tools and learning material I use and recommend.
nav: false
---

<style>
  .res-list { display: flex; flex-direction: column; gap: 1.25rem; margin-top: 1.5rem; }
  .res-card { display: flex; align-items: stretch; border: 1px solid var(--global-divider-color); border-radius: 14px; overflow: hidden; background: var(--global-card-bg-color); color: var(--global-text-color) !important; text-decoration: none !important; transition: transform .2s ease, border-color .2s ease, box-shadow .2s ease; }
  .res-card:hover { transform: translateY(-2px); border-color: var(--global-theme-color); box-shadow: 0 8px 22px rgba(0,0,0,.08); }
  .res-img { flex: 0 0 38%; min-height: 150px; background: #f7f7f9; display: flex; align-items: center; justify-content: center; padding: 1.25rem; }
  .res-img img { max-width: 80%; max-height: 110px; width: auto; height: auto; display: block; transition: transform .4s ease; }
  .res-img img.wide { max-width: 85%; max-height: 40px; }
  .res-card:hover .res-img img { transform: scale(1.06); }
  .res-body { padding: 1.1rem 1.3rem; display: flex; flex-direction: column; justify-content: center; }
  .res-body h3 { font-size: 1.1rem; margin: 0 0 .35rem; font-weight: 600; color: var(--global-text-color); }
  .res-body p { margin: 0; font-size: .95rem; line-height: 1.5; color: var(--global-text-color-light); }
  .res-tag { display: block; margin-top: .6rem; font-size: .8rem; letter-spacing: .02em; color: var(--global-theme-color); }
  @media (max-width: 576px) { .res-card { flex-direction: column; } .res-img { flex-basis: auto; min-height: 130px; } }
</style>

<div class="res-list">
  <a class="res-card" href="https://fiji.sc/" target="_blank" rel="noopener noreferrer">
    <div class="res-img"><img src="/assets/img/resources/fiji.svg" alt="Fiji logo" style="max-height:90px"></div>
    <div class="res-body">
      <h3>ImageJ / FIJI</h3>
      <p>Image analysis for measuring, counting and quantifying microscopy images, with a plugin for almost everything.</p>
      <span class="res-tag">Free · open source</span>
    </div>
  </a>
  <a class="res-card" href="https://www.protocols.io/" target="_blank" rel="noopener noreferrer">
    <div class="res-img"><img class="wide" src="/assets/img/resources/protocols.svg" alt="protocols.io logo"></div>
    <div class="res-body">
      <h3>protocols.io</h3>
      <p>A platform for sharing, versioning and discovering lab protocols.</p>
      <span class="res-tag">Free for public protocols · paid plans for private and team features</span>
    </div>
  </a>
  <a class="res-card" href="https://www.cochrane.org/learn" target="_blank" rel="noopener noreferrer">
    <div class="res-img"><img src="/assets/img/resources/cochrane.svg" alt="Cochrane logo"></div>
    <div class="res-body">
      <h3>Cochrane Training</h3>
      <p>Learning resources for systematic reviews and meta-analysis.</p>
      <span class="res-tag">Many free · some courses require a subscription</span>
    </div>
  </a>
</div>
