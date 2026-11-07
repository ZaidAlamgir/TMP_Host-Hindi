---
layout: default
title: Home - The Hindi Post
description: "द हिंदी पोस्ट (TMP News): देश-विदेश की ताज़ा ख़बरें, भारतीय राजनीति, अंतरराष्ट्रीय कूटनीति, अर्थव्यवस्था और विश्लेषण की निष्पक्ष और विश्वसनीय रिपोर्टिंग।"
---
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "The Hindi Post",
  "url": "https://thehindipost.tmpnews.com/",
  "potentialAction": {
    "@type": "SearchAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "https://thehindipost.tmpnews.com/search.html?q={search_term_string}"
    },
    "query-input": "required name=search_term_string"
  }
}
</script>
<style>
.support-cta-banner{display:flex;flex-direction:row;align-items:center;justify-content:center;gap:1rem;background-color:#000 !important;border-bottom:none !important;padding:0.35rem 1.5rem !important;margin:0 auto 1.25rem auto;max-width:fit-content;border-radius:50px;box-shadow:0 4px 6px -1px rgba(0,0,0,0.1)}
.support-cta-banner p{margin:0 !important;font-family:'Mukta','Noto Sans Devanagari',sans-serif;font-size:0.85rem !important;color:#fff !important;font-weight:500}
.support-cta-button{background-color:#facc15 !important;color:#000 !important;padding:0.25rem 0.75rem !important;border-radius:20px !important;font-family:'Mukta','Noto Sans Devanagari',sans-serif;font-size:0.75rem !important;font-weight:800 !important;text-decoration:none !important;text-transform:uppercase;letter-spacing:0.05em;white-space:nowrap;box-shadow:none !important;transition:opacity 0.2s}
.support-cta-button:hover{opacity:0.9;color:#000 !important}
@media (max-width:640px){.support-cta-banner{flex-direction:column;padding:0.6rem 1rem !important;gap:0.4rem;border-radius:0 !important;width:100% !important;max-width:100% !important;margin:0 0 1rem 0 !important;box-sizing:border-box}.support-cta-banner p{font-size:0.75rem !important;line-height:1.3;text-align:center}}

/* Category Filter Navigation Bar Styling */
.category-filters-nav-wrapper {
    position: relative;
    width: 100%;
    margin-bottom: 1.25rem;
    display: flex;
    align-items: center;
}

.category-filters-container {
    width: 100%;
    overflow-x: auto;
    overflow-y: hidden;
    -webkit-overflow-scrolling: touch;
    scroll-behavior: smooth;
    touch-action: pan-x pinch-zoom;
    overscroll-behavior-x: contain;
    scroll-snap-type: x proximity;
    user-select: none;
    -webkit-user-select: none;
    padding: 4px 4px 8px 4px;
    scrollbar-width: none;
    -ms-overflow-style: none;
    cursor: grab;
}

.category-filters-container:active {
    cursor: grabbing;
}

.category-filters-container::-webkit-scrollbar {
    display: none !important;
    width: 0 !important;
    height: 0 !important;
}

.category-filters {
    display: flex;
    gap: 0.55rem;
    padding: 0 4px;
    white-space: nowrap;
    width: max-content;
    position: relative;
}

.filter-btn {
    flex-shrink: 0;
    scroll-snap-align: center;
    user-select: none;
    -webkit-user-select: none;
    background: #f1f5f9 !important;
    border: 1px solid #e2e8f0;
    color: #475569;
    padding: 6px 16px;
    border-radius: 9999px;
    font-family: 'Mukta', 'Noto Sans Devanagari', -apple-system, sans-serif;
    font-size: 0.82rem;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.2s cubic-bezier(0.16, 1, 0.3, 1);
    outline: none;
    -webkit-tap-highlight-color: transparent;
}

.filter-btn:hover {
    background: #e2e8f0 !important;
    color: #0f172a;
    border-color: #cbd5e1;
    transform: translateY(-1px);
}

.filter-btn.active {
    background: #0073e6 !important;
    color: #ffffff !important;
    border-color: #0073e6 !important;
    box-shadow: 0 3px 10px rgba(0, 115, 230, 0.3);
    transform: translateY(-1px);
}

html.dark-mode .filter-btn {
    background: #1e293b !important;
    border-color: #334155;
    color: #94a3b8;
}

html.dark-mode .filter-btn:hover {
    background: #334155 !important;
    color: #ffffff;
    border-color: #475569;
}

html.dark-mode .filter-btn.active {
    background: #0073e6 !important;
    color: #ffffff !important;
    border-color: #0073e6 !important;
    box-shadow: 0 3px 12px rgba(0, 115, 230, 0.45);
}

/* Edge Fade Masks for intuitive swipe cues */
.category-filters-nav-wrapper::before,
.category-filters-nav-wrapper::after {
    content: '';
    position: absolute;
    top: 4px;
    bottom: 8px;
    width: 28px;
    pointer-events: none;
    z-index: 4;
    transition: opacity 0.25s ease;
}

.category-filters-nav-wrapper::before {
    left: 0;
    background: linear-gradient(to right, #ffffff 10%, transparent);
    opacity: 0;
    border-top-left-radius: 9999px;
    border-bottom-left-radius: 9999px;
}

.category-filters-nav-wrapper::after {
    right: 0;
    background: linear-gradient(to left, #ffffff 10%, transparent);
    opacity: 1;
    border-top-right-radius: 9999px;
    border-bottom-right-radius: 9999px;
}

.category-filters-nav-wrapper.can-scroll-left::before { opacity: 1; }
.category-filters-nav-wrapper.at-scroll-end::after { opacity: 0; }

html.dark-mode .category-filters-nav-wrapper::before {
    background: linear-gradient(to right, #111827 10%, transparent);
}
html.dark-mode .category-filters-nav-wrapper::after {
    background: linear-gradient(to left, #111827 10%, transparent);
}

.explore-hub-btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
    background-color: #0073e6;
    color: #ffffff !important;
    padding: 10px 24px;
    border-radius: 9999px;
    font-family: 'Mukta', 'Noto Sans Devanagari', sans-serif;
    font-weight: 700;
    font-size: 0.88rem;
    text-decoration: none;
    letter-spacing: 0.02em;
    box-shadow: 0 4px 12px rgba(0, 115, 230, 0.25);
    transition: all 0.2s ease;
}
.explore-hub-btn:hover {
    background-color: #005bb5;
    transform: translateY(-2px);
    box-shadow: 0 6px 16px rgba(0, 115, 230, 0.35);
}

.loader {
    display: none; margin: 1.5rem auto; 
    border: 3px solid #f3f3f3;
    border-top: 3px solid #0073e6; 
    border-radius: 50%;
    width: 30px; height: 30px; 
    animation: spin 1s linear infinite;
}
.loader.visible { display: block; }
@keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

/* Compact Subheadline container */
.subheadline-container {
    position: relative;
    max-height: 38px;
    overflow: hidden;
    margin-bottom: 0.35rem;
}
.subheadline-container::after {
    content: '';
    position: absolute;
    bottom: 0; left: 0; right: 0;
    height: 16px;
    background: linear-gradient(to bottom, rgba(255,255,255,0), #ffffff);
    pointer-events: none;
    z-index: 1;
}
html.dark-mode .subheadline-container::after {
    background: linear-gradient(to bottom, rgba(31,41,55,0), #1f2937);
}
</style>

{% include live-top-widget.html %}

<div class="support-cta-banner">
    <p>निष्पक्ष और स्वतंत्र पत्रकारिता आज पहले से कहीं अधिक महत्वपूर्ण है। The Hindi Post का सहयोग करें।</p>
    <a href="{{ '/support/' | relative_url }}" class="support-cta-button">सहयोग करें</a>
</div>

{% assign latest_post = site.posts.first %}
<main class="home-main" style="flex-grow: 1;">
    {% if latest_post %}
    <!-- Hero Latest Article Card -->
    <section class="top-story-section">
        <a href="{{ latest_post.url | relative_url }}" class="hero-spotlight-card">
            <div class="hero-image-pane">
                <img src="{{ latest_post.image | default: 'https://placehold.co/1200x800/e2e8f0/64748b?text=Image+Not+Available' }}" alt="{{ latest_post.image_description | default: 'Top story image' | escape }}" class="hero-cover-img" loading="eager" fetchpriority="high" decoding="async">
                <div class="hero-live-badge-tag">
                    <span class="hero-pulse-dot"></span>
                    <span>प्रमुख रिपोर्ट</span>
                </div>
            </div>
            <div class="hero-content-pane">
                <div class="hero-meta-row">
                    {% if latest_post.categories.first %}
                    <span class="hero-cat-tag">{{ latest_post.categories.first | replace: '-', ' ' | capitalize }}</span>
                    {% endif %}
                    <time class="hero-post-date"><i class="far fa-calendar-alt mr-1"></i>{{ latest_post.date | date: "%B %d, %Y" }}</time>
                </div>
                <h2 class="hero-spotlight-title">{{ latest_post.title }}</h2>
                <div class="hero-subheadline-container">
                    <p class="hero-spotlight-desc">{{ latest_post.subheadline | default: latest_post.content | strip_html | truncatewords: 28 }}</p>
                </div>
                <div class="hero-action-bar">
                    <div class="hero-author-line">
                        <span class="hero-author-avatar">{{ latest_post.writer | default: latest_post.author | default: 'TMP' | slice: 0 | upcase }}</span>
                        <div class="hero-author-details">
                            <span class="hero-author-name">{{ latest_post.writer | default: latest_post.author | default: 'TMP Staff' }}</span>
                            {% assign hero_words = latest_post.content | number_of_words %}
                            <span class="hero-read-duration">{{ hero_words | divided_by: 200 | plus: 1 }} मिनट पढ़ें</span>
                        </div>
                    </div>
                    <span class="hero-read-btn">
                        <span>आगे पढ़ें</span> <i class="fas fa-arrow-right ml-1"></i>
                    </span>
                </div>
            </div>
        </a>
    </section>
    {% endif %}

    <div class="content-wrapper">
        <!-- Special Reports 10-Card Random Horizontal Slider (Last 5 Days) -->
        <div class="home-slider-section-wrapper" id="home-slider-section-wrapper">
            <div class="slider-section-header">
                <div class="slider-title-wrapper">
                    <span class="slider-live-dot"></span>
                    <h3 class="slider-section-title">विशेष रिपोर्टें</h3>
                    <span class="slider-fresh-badge"><i class="fas fa-bolt"></i> दैनिक चयन</span>
                </div>
                <div class="slider-nav-controls">
                    <button type="button" class="slider-arrow-btn slider-prev-btn" id="sliderPrevBtn" aria-label="पिछली रिपोर्टें">
                        <i class="fas fa-chevron-left"></i>
                    </button>
                    <button type="button" class="slider-arrow-btn slider-next-btn" id="sliderNextBtn" aria-label="अगली रिपोर्टें">
                        <i class="fas fa-chevron-right"></i>
                    </button>
                </div>
            </div>

            <div class="slider-track-container" id="homeSliderTrackContainer">
                <div class="slider-track" id="homeSliderTrack">
                    {% for post in site.posts limit: 10 %}
                    <a href="{{ post.url | relative_url }}" class="slide-story-card" title="{{ post.title | escape }}">
                        <div class="slide-card-bg">
                            <img src="{{ post.image | default: 'https://placehold.co/800x500/e2e8f0/64748b?text=News' }}" alt="{{ post.title | escape }}" class="slide-card-img" loading="lazy" decoding="async">
                            <div class="slide-card-overlay"></div>
                            <div class="slide-card-top-tag">
                                <span class="slide-card-badge">{{ post.categories.first | default: 'समाचार' | replace: '-', ' ' | capitalize }}</span>
                            </div>
                        </div>
                        <div class="slide-card-content">
                            <h4 class="slide-card-title">{{ post.title }}</h4>
                            <div class="slide-card-footer">
                                <span class="slide-card-date"><i class="far fa-calendar-alt"></i> {{ post.date | date: "%b %d, %Y" }}</span>
                                {% assign s_words = post.content | number_of_words %}
                                <span class="slide-card-read">{{ s_words | divided_by: 200 | plus: 1 }} मिनट</span>
                            </div>
                        </div>
                    </a>
                    {% endfor %}
                </div>
            </div>
        </div>

        <!-- JSON Data Pool for Random 10 Stories Selection (Last 5 Days) -->
        <script id="home-slider-pool-data" type="application/json">
        [
          {% for post in site.posts limit: 80 %}
          {
            "title": {{ post.title | jsonify }},
            "url": {{ post.url | relative_url | jsonify }},
            "date": {{ post.date | date: "%Y-%m-%d" | jsonify }},
            "display_date": {{ post.date | date: "%b %d, %Y" | jsonify }},
            "image": {{ post.image | default: 'https://placehold.co/800x500/e2e8f0/64748b?text=News' | jsonify }},
            "category": {{ post.categories.first | default: 'ताज़ा' | replace: '-', ' ' | capitalize | jsonify }},
            "read_time": {% assign p_words = post.content | number_of_words %}{{ p_words | divided_by: 200 | plus: 1 }}
          }{% unless forloop.last %},{% endunless %}
          {% endfor %}
        ]
        </script>

        <hr class="section-divider">
        
        <!-- Live Filterable Latest Reports Grid -->
        <section class="content-section latest-reports-section">
            <div class="section-header-compact">
                <h2 class="section-title">ताज़ा रिपोर्ट्स</h2>
            </div>
            
            <div class="category-filters-nav-wrapper" id="home-filters-nav-wrapper">
                <div class="category-filters-container" id="home-filters-container">
                    <div class="category-filters" id="home-filters-bar">
                        <button class="filter-btn active" data-tag="">सभी</button>
                        <button class="filter-btn" data-tag="world-politics">विश्व राजनीति</button>
                        <button class="filter-btn" data-tag="indian-politics">भारतीय राजनीति</button>
                        <button class="filter-btn" data-tag="muslim-world">मुस्लिम जगत</button>
                        <button class="filter-btn" data-tag="technology">प्रौद्योगिकी</button>
                        <button class="filter-btn" data-tag="medical-science">चिकित्सा विज्ञान</button>
                        <button class="filter-btn" data-tag="global-economy">वैश्विक अर्थव्यवस्था</button>
                        <button class="filter-btn" data-tag="art-culture">कला एवं संस्कृति</button>
                        <button class="filter-btn" data-tag="weather">मौसम</button>
                        <button class="filter-btn" data-tag="sports">खेल</button>
                        <button class="filter-btn" data-tag="national-news">राष्ट्रीय समाचार</button>
                        <button class="filter-btn" data-tag="international-news">अंतरराष्ट्रीय</button>
                        <button class="filter-btn" data-tag="history">इतिहास</button>
                        <button class="filter-btn" data-tag="indian-muslims">भारतीय मुस्लिम</button>
                        <button class="filter-btn" data-tag="middle-east">मध्य पूर्व</button>
                        <button class="filter-btn" data-tag="climate">जलवायु</button>
                        <button class="filter-btn" data-tag="defense">रक्षा</button>
                        <button class="filter-btn" data-tag="south-asia">दक्षिण एशिया</button>
                        <button class="filter-btn" data-tag="africa">अफ्रीका</button>
                        <button class="filter-btn" data-tag="europe">यूरोप</button>
                        <button class="filter-btn" data-tag="central-asia">मध्य एशिया</button>
                        <button class="filter-btn" data-tag="crime-alert">क्राइम अलर्ट</button>
                        <button class="filter-btn" data-tag="south-east-asia">दक्षिण-पूर्व एशिया</button>
                        <button class="filter-btn" data-tag="east-asia">पूर्वी एशिया</button>
                        <button class="filter-btn" data-tag="north-america">उत्तरी अमेरिका</button>
                        <button class="filter-btn" data-tag="south-america">दक्षिणी अमेरिका</button>
                    </div>
                </div>
            </div>
            
            <!-- Horizontal Article Listing -->
            <div class="news-grid-full" id="home-articles-grid" style="min-height: 150px;">
                {% for post in site.posts limit: 8 offset: 1 %}
                {% assign post_words = post.content | number_of_words %}
                {% assign post_read_time = post_words | divided_by: 200 | plus: 1 %}
                <a href="{{ post.url | relative_url }}" class="news-card horizontal-news-card">
                    <div class="news-card-text">
                        <div class="news-card-top-row">
                            {% if post.categories.first %}
                            <span class="news-card-category-badge">{{ post.categories.first | replace: '-', ' ' | capitalize }}</span>
                            {% endif %}
                            <span class="news-card-date">{{ post.date | date: "%b %d, %Y" }}</span>
                        </div>
                        <h3 class="news-card-headline">{{ post.title }}</h3>
                        <div class="subheadline-container">
                            <p class="news-card-subheadline">{{ post.subheadline | default: post.content | strip_html | truncatewords: 20 }}</p>
                        </div>
                        <div class="news-card-footer-row">
                            <span class="read-more-text">आगे पढ़ें <i class="fas fa-arrow-right ml-1"></i></span>
                            <span class="news-card-read-time">{{ post_read_time }} मिनट पढ़ें</span>
                        </div>
                    </div>
                    <div class="news-card-image-wrapper">
                        <img src="{{ post.image | default: 'https://placehold.co/600x400/e2e8f0/64748b?text=No+Image' }}" alt="{{ post.image_description | default: post.title | escape }}" class="news-card-image" loading="lazy">
                    </div>
                </a>
                {% endfor %}
            </div>
            <div id="home-loader" class="loader"></div>
            
            <div style="text-align: center; margin-top: 2rem;">
                <a href="{{ '/news/hub/' | relative_url }}" class="explore-hub-btn">पूरा समाचार केंद्र देखें <i class="fas fa-arrow-right ml-1.5"></i></a>
            </div>

            <!-- Archive Spotlight 10-Card Random Horizontal Slider (Analysis & History Evergreen Collection) -->
            <div class="home-slider-section-wrapper home-archive-slider-wrapper" id="home-archive-slider-section-wrapper">
                <div class="slider-section-header">
                    <div class="slider-title-wrapper">
                        <span class="slider-live-dot archive-dot"></span>
                        <h3 class="slider-section-title">गहन विश्लेषण और इतिहास</h3>
                        <span class="slider-fresh-badge archive-fresh-badge"><i class="fas fa-landmark"></i> सदाबहार संग्रह</span>
                    </div>
                    <div class="slider-nav-controls">
                        <button type="button" class="slider-arrow-btn slider-prev-btn" id="archiveSliderPrevBtn" aria-label="पिछली आर्काइव रिपोर्टें">
                            <i class="fas fa-chevron-left"></i>
                        </button>
                        <button type="button" class="slider-arrow-btn slider-next-btn" id="archiveSliderNextBtn" aria-label="अगली आर्काइव रिपोर्टें">
                            <i class="fas fa-chevron-right"></i>
                        </button>
                    </div>
                </div>

                <div class="slider-track-container" id="homeArchiveSliderTrackContainer">
                    <div class="slider-track" id="homeArchiveSliderTrack">
                        {% for post in site.posts limit: 10 %}
                        <a href="{{ post.url | relative_url }}" class="slide-story-card" title="{{ post.title | escape }}">
                            <div class="slide-card-bg">
                                <img src="{{ post.image | default: 'https://placehold.co/800x500/e2e8f0/64748b?text=News' }}" alt="{{ post.title | escape }}" class="slide-card-img" loading="lazy" decoding="async">
                                <div class="slide-card-overlay"></div>
                                <div class="slide-card-top-tag">
                                    <span class="slide-card-badge archive-badge">{{ post.categories.first | default: 'विश्लेषण' | replace: '-', ' ' | capitalize }}</span>
                                </div>
                            </div>
                            <div class="slide-card-content">
                                <h4 class="slide-card-title">{{ post.title }}</h4>
                                <div class="slide-card-footer">
                                    <span class="slide-card-date"><i class="fas fa-landmark"></i> {{ post.date | date: "%b %d, %Y" }}</span>
                                    {% assign a_words = post.content | number_of_words %}
                                    <span class="slide-card-read">{{ a_words | divided_by: 200 | plus: 1 }} मिनट</span>
                                </div>
                            </div>
                        </a>
                        {% endfor %}
                    </div>
                </div>
            </div>

            <!-- JSON Data Pool for Random 10 Evergreen Archive Stories (Analysis & History from D1) -->
            <script id="home-archive-slider-pool-data" type="application/json">
[{"title": "भारत के मिसाइल मैन: उनकी जयंती पर डॉ. ए.पी.जे. अब्दुल कलाम को श्रद्धांजलि", "url": "/news/history/missile-man-of-india-remembering-dr-a-p-j-abdul-kalam-on-his-birth-anniversary/", "date": "2026-10-15", "display_date": "2026-10-15", "image": "https://assets1.tmpnews.com/images/apj-abdul-kalam.webp", "category": "इतिहास", "read_time": 5, "is_local": true}, {"title": "WHO ने बचपन के मोटापे में वैश्विक वृद्धि की चेतावनी दी, 1990 के बाद से मामले चार गुना बढ़े", "url": "/news/analysis-in-depth-reports/who-warns-of-global-surge-in-childhood-obesity-as-cases-quadruple-since-1990/", "date": "2026-10-08", "display_date": "2026-10-08", "image": "https://assets1.tmpnews.com/images/obesity.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "शाडियन 1975 नरसंहार: मस्जिदों की रक्षा करने वाले 1,600 हुई (Hui) मुसलमानों को PLA की घेराबंदी ने कैसे मारा", "url": "/news/history/shadian-1975-massacre-how-the-pla-siege-killed-1-600-hui-muslims-defending-mosques/", "date": "2026-10-31", "display_date": "2026-10-31", "image": "https://assets.tmpnews.com/images/shadian-massacre.webp", "category": "इतिहास", "read_time": 5, "is_local": true}, {"title": "भारत में अल्पसंख्यकों पर घृणा अपराध बढ़ने के बीच आदित्यनाथ ने समावेशी होने का दावा किया", "url": "/news/analysis-in-depth-reports/adityanath-touts-inclusivity-as-minority-hate-crimes-surge-in-india/", "date": "2026-10-21", "display_date": "2026-10-21", "image": "https://assets.tmpnews.com/images/ajay-bisht.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "सलाहुद्दीन अय्यूबी ने 2 अक्टूबर 1187 को येरुशलम पर विजय प्राप्त की", "url": "/news/history/salahuddin-ayyubi-conquers-jerusalem-on-october-2-1187/", "date": "2026-10-02", "display_date": "2026-10-02", "image": "https://assets1.tmpnews.com/images/conquest-of-jerusalem.webp", "category": "इतिहास", "read_time": 5, "is_local": true}, {"title": "ग्रंथम अध्ययन: 2026 की लू के कारण यूरोप में 50,000 से अधिक मौतें", "url": "/news/analysis-in-depth-reports/grantham-study-links-over-50-000-european-deaths-to-2026-heatwaves/", "date": "2026-10-23", "display_date": "2026-10-23", "image": "https://assets.tmpnews.com/images/europe-summer-heat-map.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "इजरायली शोधकर्ता ने भारत के आरएसएस (RSS) के साथ", "url": "/news/analysis-in-depth-reports/israeli-researcher-cites-ideological-alliance-with-india-s-rss/", "date": "2026-10-19", "display_date": "2026-10-19", "image": "https://assets.tmpnews.com/images/israeli-researcher-cites-ideological-alliance-with-indias-rss.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "गांधी जयंती: सत्य और अहिंसा को नमन करने का दिन", "url": "/news/history/gandhi-jayanti-a-day-to-honour-truth-and-non-violence/", "date": "2026-10-02", "display_date": "2026-10-02", "image": "https://assets1.tmpnews.com/images/mahatma-gandhi.webp", "category": "इतिहास", "read_time": 5, "is_local": true}, {"title": "वैचारिक राजनीति के चलते दक्षिण एशिया में भारत का घट रहा है रसूख", "url": "/news/analysis-in-depth-reports/india-loses-regional-influence-as-ideology-strains-south-asian-ties/", "date": "2026-10-24", "display_date": "2026-10-24", "image": "https://assets.tmpnews.com/images/narendra-modi.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "गंभीर संकट के बीच उत्तर अफ्रीका और मध्य पूर्व को खेती में तुरंत निवेश की सख्त जरूरत: FAO की चेतावनी", "url": "/news/analysis-in-depth-reports/north-africa-and-the-middle-east-need-urgent-farm-investment-amid-deepening-crises-fao-warns/", "date": "2026-10-08", "display_date": "2026-10-08", "image": "https://assets1.tmpnews.com/images/tmp-collage.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "भारत का रोड नेटवर्क: इंफ्रास्ट्रक्चर की एक विशाल ताकत, जो सुरक्षा के गंभीर संकट से जूझ रही है", "url": "/news/analysis-in-depth-reports/india-s-road-network-a-giant-of-infrastructure-plagued-by-a-crisis-of-safety/", "date": "2026-10-13", "display_date": "2026-10-13", "image": "https://assets1.tmpnews.com/images/road-accident-shows-in-pin-board-style-by-tmpnews.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "उत्तर प्रदेश की मतदाता सूची में जोड़े गए रहस्यमय 16.18 लाख मतदाता", "url": "/news/analysis-depth-report/the-mysterious-16-18-lakh-voters-added-to-uttar-pradesh-s-electoral-roll/", "date": "2026-10-07", "display_date": "2026-10-07", "image": "https://assets1.tmpnews.com/images/uttarpradesh-mysterious-voters-added.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "भारत में वोटर लिस्ट से नाम कटने पर हंगामा, हटाने की वजहें साफ न होने पर उठे सवाल", "url": "/news/analysis-in-depth-reports/india-voter-roll-deletions-spark-outrage-over-lack-of-reasons/", "date": "2026-10-09", "display_date": "2026-10-09", "image": "https://assets1.tmpnews.com/images/sir-irregularities-in-up-sparks-tension-nation-wide.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "जमीन के नीचे रिस चुके क्रोमियम को साफ करना: नासिक और बाल्टीमोर से मिलने वाले सबक", "url": "/news/analysis/cleaning-up-chromium-that-has-seeped-underground-lessons-from-nashik-and-baltimore/", "date": "2026-10-16", "display_date": "2026-10-16", "image": "https://assets1.tmpnews.com/images/chromium.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}, {"title": "अमेरिका ने ईरान के खिलाफ युद्ध के सात महीनों में 19 साल के पेट्रियट मिसाइल भंडार को खर्च किया", "url": "/news/analysis-in-depth-reports/u-s-expends-19-years-of-patriot-missiles-in-seven-months-of-iran-war/", "date": "2026-10-19", "display_date": "2026-10-19", "image": "https://assets.tmpnews.com/images/patriot.webp", "category": "विश्लेषण", "read_time": 5, "is_local": true}]
            </script>
        </section>

        <hr class="section-divider">
        
        <section class="content-section features-section reveal-on-scroll">
            <div class="section-header-compact">
                <h2 class="section-title">हमसे क्यों जुड़ें?</h2>
                <p class="section-subtitle">ज्ञान साझा करने, शोध और निष्पक्ष विश्लेषण के लिए समर्पित मंच।</p>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon-bubble grad-bubble-1">
                        <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20h9"></path><path d="M16.5 3.5a2.121 2.121 0 0 1 3 3L7 19l-4 1 1-4L16.5 3.5z"></path></svg>
                    </div>
                    <h3 class="feature-title">अपनी आवाज़ उठाएं</h3>
                    <p class="feature-text">अपने लेख, गहन शोध और विचार पाठकों तक आसानी से पहुंचाएं।</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon-bubble grad-bubble-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"></path><circle cx="9" cy="7" r="4"></circle><path d="M23 21v-2a4 4 0 0 0-3-3.87"></path><path d="M16 3.13a4 4 0 0 1 0 7.75"></path></svg>
                    </div>
                    <h3 class="feature-title">विशेषज्ञों से जुड़ें</h3>
                    <p class="feature-text">दुनिया भर के विश्लेषकों, विद्वानों और विचारशील पाठकों के समुदाय से जुड़ें।</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon-bubble grad-bubble-3">
                        <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"></path></svg>
                    </div>
                    <h3 class="feature-title">हमेशा आगे रहें</h3>
                    <p class="feature-text">हमारे स्वतंत्र न्यूज़रूम द्वारा प्रस्तुत ताज़ा वैश्विक घटनाक्रमों और रीयल-टाइम रिपोर्टों से अपडेट रहें।</p>
                </div>
            </div>
        </section>
    </div>

    <section class="cta-section">
        <div class="cta-card reveal-on-scroll">
            <span class="cta-pill-badge"><i class="fas fa-feather-pointed mr-1.5"></i>टीएमपी में योगदान दें</span>
            <h2 class="cta-heading">अपना ज्ञान और विचार साझा करें</h2>
            <p class="cta-subheading">वैश्विक संवाददाताओं, शोधकर्ताओं और लेखकों के बढ़ते नेटवर्क से जुड़ें। अपने दृष्टिकोण को साझा करें और सार्थक चर्चा को प्रेरित करें।</p>
            <a id="cta-get-started" href="{{ '/post/' | relative_url }}" class="cta-button">
                <span>लिखना शुरू करें</span> <i class="fas fa-arrow-right ml-2"></i>
            </a>
        </div>
    </section>
</main>

<script>
    (function() {
        function initHomePage() {
            const getStartedBtn = document.getElementById('cta-get-started');
            if (getStartedBtn) {
                let cachedUser = null;
                try {
                    cachedUser = localStorage.getItem('cachedUser');
                } catch (e) {
                    console.warn("localStorage is disabled or not accessible:", e);
                }
                if (!cachedUser) {
                    getStartedBtn.href = "{{ 'auth.html' | relative_url }}";
                }
            }
            
            const revealElements = document.querySelectorAll('.reveal-on-scroll');
            if (revealElements.length > 0) {
                if ('IntersectionObserver' in window) {
                    const observer = new IntersectionObserver((entries) => {
                        entries.forEach(entry => {
                            if (entry.isIntersecting) {
                                entry.target.classList.add('is-visible');
                                observer.unobserve(entry.target);
                            }
                        });
                    }, { threshold: 0.05, rootMargin: "0px 0px 50px 0px" });
                    
                    revealElements.forEach(element => {
                        if (!element.classList.contains('is-visible')) {
                            observer.observe(element);
                        }
                    });
                } else {
                    revealElements.forEach(element => {
                        element.classList.add('is-visible');
                    });
                }
            }

        // Initialize Special Reports 10-Post Random Slider (Fresh Selection < 5 Days)
        initSpotlightSlider();

        // Initialize In-Depth Analysis & History 10-Post Random Slider (D1 Archive Evergreen)
        initArchiveSlider();
    }

    function escapeHtml(str) {
        if (!str) return '';
        return String(str)
            .replace(/&/g, '&amp;')
            .replace(/</g, '&lt;')
            .replace(/>/g, '&gt;')
            .replace(/"/g, '&quot;')
            .replace(/'/g, '&#39;');
    }

    function shuffleArray(arr) {
        const a = arr.slice();
        for (let i = a.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [a[i], a[j]] = [a[j], a[i]];
        }
        return a;
    }

    // Shared smooth swipe & desktop pointer pan interaction handler
    function setupTrackInteractions(track, prevBtnId, nextBtnId) {
        if (track._interactionsSetup) return;
        track._interactionsSetup = true;

        const prevBtn = document.getElementById(prevBtnId);
        const nextBtn = document.getElementById(nextBtnId);
        const isRTL = document.documentElement.dir === 'rtl' || document.dir === 'rtl';

        function updateNavState() {
            if (!prevBtn || !nextBtn) return;
            const maxScroll = track.scrollWidth - track.clientWidth - 5;
            const cur = Math.abs(track.scrollLeft);
            prevBtn.disabled = cur <= 5;
            nextBtn.disabled = cur >= maxScroll;
            prevBtn.style.opacity = prevBtn.disabled ? '0.35' : '1';
            nextBtn.style.opacity = nextBtn.disabled ? '0.35' : '1';
            prevBtn.style.cursor = prevBtn.disabled ? 'not-allowed' : 'pointer';
            nextBtn.style.cursor = nextBtn.disabled ? 'not-allowed' : 'pointer';
        }

        if (prevBtn && nextBtn) {
            prevBtn.onclick = () => {
                const card = track.querySelector('.slide-story-card');
                const step = card ? (card.offsetWidth + 14) * 2 : track.clientWidth * 0.85;
                track.scrollBy({ left: isRTL ? step : -step, behavior: 'smooth' });
            };
            nextBtn.onclick = () => {
                const card = track.querySelector('.slide-story-card');
                const step = card ? (card.offsetWidth + 14) * 2 : track.clientWidth * 0.85;
                track.scrollBy({ left: isRTL ? -step : step, behavior: 'smooth' });
            };
            track.addEventListener('scroll', updateNavState, { passive: true });
            updateNavState();
        }

        // Desktop Mouse Drag Panning (Listeners attached only during active drag to eliminate idle overhead)
        let isDown = false;
        let startX = 0;
        let scrollStart = 0;
        let hasMoved = false;

        function onPointerMove(e) {
            if (!isDown) return;
            const x = e.pageX - track.offsetLeft;
            const walk = (x - startX) * 1.25;
            if (Math.abs(walk) > 5) {
                hasMoved = true;
            }
            track.scrollLeft = scrollStart - (isRTL ? -walk : walk);
        }

        function onPointerUp(e) {
            if (isDown) {
                isDown = false;
                track.classList.remove('is-dragging');
                window.removeEventListener('pointermove', onPointerMove);
                window.removeEventListener('pointerup', onPointerUp);
            }
        }

        track.addEventListener('pointerdown', (e) => {
            if (e.pointerType !== 'mouse' || e.button !== 0) return;
            isDown = true;
            hasMoved = false;
            startX = e.pageX - track.offsetLeft;
            scrollStart = track.scrollLeft;
            track.classList.add('is-dragging');
            window.addEventListener('pointermove', onPointerMove, { passive: true });
            window.addEventListener('pointerup', onPointerUp, { passive: true });
        });

        // Touch Drag Threshold Tracking (Prevents accidental clicks when swiping on mobile)
        let touchStartX = 0;
        let touchStartY = 0;
        track.addEventListener('touchstart', (e) => {
            if (e.touches.length === 1) {
                touchStartX = e.touches[0].clientX;
                touchStartY = e.touches[0].clientY;
                hasMoved = false;
            }
        }, { passive: true });

        track.addEventListener('touchmove', (e) => {
            if (e.touches.length === 1) {
                const diffX = Math.abs(e.touches[0].clientX - touchStartX);
                const diffY = Math.abs(e.touches[0].clientY - touchStartY);
                if (diffX > 8 || diffY > 8) {
                    hasMoved = true;
                }
            }
        }, { passive: true });

        track.addEventListener('click', (e) => {
            if (hasMoved) {
                e.preventDefault();
                e.stopPropagation();
                hasMoved = false;
            }
        }, true);
    }

    // 1. Slider 1: Special Reports (Last 5 Days Selection)
    function initSpotlightSlider() {
        const track = document.getElementById('homeSliderTrack');
        const poolEl = document.getElementById('home-slider-pool-data');
        if (!track || !poolEl) return;

        setupTrackInteractions(track, 'sliderPrevBtn', 'sliderNextBtn');

        let posts = [];
        try {
            posts = JSON.parse(poolEl.textContent || '[]');
        } catch (e) {
            console.error("Failed to parse slider posts pool:", e);
            return;
        }

        if (!Array.isArray(posts) || posts.length === 0) return;

        let maxPostTime = 0;
        posts.forEach(p => {
            if (!p.date) return;
            const t = new Date(p.date + 'T23:59:59Z').getTime();
            if (!isNaN(t) && t > maxPostTime) {
                maxPostTime = t;
            }
        });

        const refTime = Math.max(Date.now(), maxPostTime);
        const fiveDaysMs = 5 * 24 * 60 * 60 * 1000;
        const cutoffTime = refTime - fiveDaysMs;

        let eligible = posts.filter(p => {
            if (!p.date) return false;
            const t = new Date(p.date + 'T23:59:59Z').getTime();
            return !isNaN(t) && t >= cutoffTime;
        });

        if (eligible.length < 10) {
            eligible = posts.slice(0, Math.max(15, eligible.length));
        }

        const selectedPosts = shuffleArray(eligible).slice(0, 10);

        // Avoid flickering: only update innerHTML if URLs changed
        const existingUrls = Array.from(track.querySelectorAll('.slide-story-card')).map(a => a.getAttribute('href'));
        const newUrls = selectedPosts.map(p => p.url);
        const isIdentical = existingUrls.length === newUrls.length && existingUrls.every((u, i) => u === newUrls[i]);

        if (!isIdentical) {
            track.innerHTML = selectedPosts.map(post => `
                <a href="${post.url}" class="slide-story-card" title="${escapeHtml(post.title)}">
                    <div class="slide-card-bg">
                        <img src="${post.image}" alt="${escapeHtml(post.title)}" class="slide-card-img" loading="lazy" decoding="async">
                        <div class="slide-card-overlay"></div>
                        <div class="slide-card-top-tag">
                            <span class="slide-card-badge">${escapeHtml(post.category)}</span>
                        </div>
                    </div>
                    <div class="slide-card-content">
                        <h4 class="slide-card-title">${escapeHtml(post.title)}</h4>
                        <div class="slide-card-footer">
                            <span class="slide-card-date"><i class="far fa-calendar-alt"></i> ${escapeHtml(post.display_date)}</span>
                            <span class="slide-card-read">${post.read_time} मिनट</span>
                        </div>
                    </div>
                </a>
            `).join('');
        }
    }

    // 2. Slider 2: In-Depth Analysis & History (Evergreen D1 Archive Collection)
    function initArchiveSlider() {
        const track = document.getElementById('homeArchiveSliderTrack');
        const poolEl = document.getElementById('home-archive-slider-pool-data');
        if (!track) return;

        setupTrackInteractions(track, 'archiveSliderPrevBtn', 'archiveSliderNextBtn');

        let pool = [];
        if (poolEl) {
            try {
                pool = JSON.parse(poolEl.textContent || '[]');
            } catch (e) {
                console.error("Failed to parse archive pool data:", e);
            }
        }

        const isLocal = typeof window !== 'undefined' && window.location && (
            window.location.hostname === 'localhost' || 
            window.location.hostname === '127.0.0.1' || 
            /^\d+\.\d+\.\d+\.\d+$/.test(window.location.hostname)
        );

        function renderCards(posts) {
            if (!Array.isArray(posts) || posts.length === 0) return;
            const existingUrls = Array.from(track.querySelectorAll('.slide-story-card')).map(a => a.getAttribute('href'));
            const newUrls = posts.map(post => (isLocal && post.is_local === false) ? ('https://thehindipost.tmpnews.com' + post.url) : post.url);
            const isIdentical = existingUrls.length === newUrls.length && existingUrls.every((u, i) => u === newUrls[i]);
            if (isIdentical) return;

            track.innerHTML = posts.map(post => {
                let href = post.url;
                if (isLocal && post.is_local === false) {
                    href = 'https://thehindipost.tmpnews.com' + post.url;
                }
                return `
                <a href="${href}" class="slide-story-card" title="${escapeHtml(post.title)}">
                    <div class="slide-card-bg">
                        <img src="${post.image}" alt="${escapeHtml(post.title)}" class="slide-card-img" loading="lazy" decoding="async">
                        <div class="slide-card-overlay"></div>
                        <div class="slide-card-top-tag">
                            <span class="slide-card-badge archive-badge">${escapeHtml(post.category)}</span>
                        </div>
                    </div>
                    <div class="slide-card-content">
                        <h4 class="slide-card-title">${escapeHtml(post.title)}</h4>
                        <div class="slide-card-footer">
                            <span class="slide-card-date"><i class="fas fa-landmark"></i> ${escapeHtml(post.display_date || post.date)}</span>
                            <span class="slide-card-read">${post.read_time || 5} मिनट</span>
                        </div>
                    </div>
                </a>
            `}).join('');
        }

        // Immediate render: On local dev, prioritize articles that exist locally in _site
        if (Array.isArray(pool) && pool.length > 0) {
            const localPool = isLocal ? pool.filter(p => p.is_local) : pool;
            const poolToUse = (localPool.length >= 10) ? localPool : pool;
            const selected = shuffleArray(poolToUse).slice(0, 10);
            renderCards(selected);
        }

        // Edge dynamic sync: On live Cloudflare Pages, fetch fresh random picks from D1
        if (!isLocal && typeof window !== 'undefined' && window.location && window.location.protocol.startsWith('http')) {
            fetch('/api/archive-spotlight')
                .then(res => res.ok ? res.json() : null)
                .then(data => {
                    if (data && Array.isArray(data.posts) && data.posts.length > 0) {
                        renderCards(data.posts);
                    }
                })
                .catch(() => {});
        }
    }

    document.addEventListener('turbo:load', initHomePage);

        if (document.readyState === 'loading') {
            document.addEventListener('DOMContentLoaded', initHomePage);
        } else {
            initHomePage();
        }
    })();
</script>
