---
layout: default
title: लाइव अपडेट्स
permalink: /live/
description: "द हिंदी पोस्ट लाइव अपडेट्स: देश और दुनिया की बड़ी घटनाओं, ब्रेकिंग न्यूज़, महत्वपूर्ण बयानों और ताज़ा घटनाक्रम का पल-पल का सीधा और विश्वसनीय कवरेज देखें।"
image: /assets/images/live/TMPnewsliveBanner.webp
extra_css:
  - /assets/style/live.css
extra_js:
  - /assets/js/live.js
---
<div id="fb-root"></div>
<div class="live-container">
    <header class="live-header">
        <h1><div class="live-indicator"><div class="dot"></div></div> लाइव अपडेट्स</h1>
    </header>
    <div id="live-feed-persistence-wrapper">
        <div id="pinned-post-container"></div>
        <div id="live-feed">
             <div class="loader"></div>
        </div>
    </div>
    <div id="feed-controls" class="text-center mt-8 px-4">
        <button id="load-more-btn" class="professional-btn" onclick="if(window.triggerLoadMoreLivePosts) window.triggerLoadMoreLivePosts(event)">पिछले अपडेट्स लोड करें</button>
        <a href="https://archive-live.tmpnews.com" id="archive-btn" class="professional-btn" style="display: none;">पुराने अपडेट्स का आर्काइव देखें</a>
        <p id="no-more-posts-msg" class="text-gray-500 font-bold py-4 uppercase text-sm" style="display: none;">लाइव कवरेज समाप्त।</p>
    </div>
</div>
<div id="bottom-nav-placeholder"></div>