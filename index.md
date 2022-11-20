---
layout: splash
permalink: /
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/splash.png
  actions:
    - label: "點擊前往"
      url: "/interactive-map/"
excerpt: "以視覺化互動式地圖概括呈現新竹城市功能資訊分析結果，包含POI點分析、Google評論情緒與動態分析、輔助資料等"
research_method:
  - title: "研究方法"
    excerpt: "以POI點、Google Map評論之時態變化、情緒分析等輔以輔助資料，<br>解析新竹各行政區之城市功能<br>請點入觀看研究方法細節與使用資料"
    url: "ResearchMethod"
    btn_label: "Read More"
    btn_class: "btn--primary"
POI_features:
    # image_path: /assets/images/Entropy_placeholder.png
    # image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    # alt: "POIEntropy"
  - title: "POI點分析"
    excerpt: "透過Google Map API進行POI點抓取、計算PIO Entropy等分析"
    url: "POI"
    btn_label: "Read More"
    btn_class: "btn--primary"
comments_features:
  - image_path: /assets/images/Sentiment_placeholder.png
    alt: "placeholder image 2"
    title: "情緒值分析"
    excerpt: '對各POI點之Google Map評論進行情緒值之正負向分析'
    url: "SentimentalScore"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/Sentiment_placeholder2.jpeg
    alt: "placeholder image 2"
    title: "情緒多樣性分析"
    excerpt: '對評論進行情緒分類，並計算情緒多樣性'
    url: "SentimentalDiversity"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/dynamic_placeholder.png
    title: "動態分析"
    excerpt: "根據評論之年、日、時進行地點的動態分析"
    url: "Dynamic"
    btn_label: "Read More"
    btn_class: "btn--primary"
other_features:
  - image_path: /assets/images/road_placeholder.png
    alt: "placeholder image 2"
    title: "路網密度"
    excerpt: '根據open street map資料庫計算各行政區之路網密度'
    url: "StreetDensity"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/shopping_placeholder.jpg
    alt: "placeholder image 2"
    title: "消費熱度"
    excerpt: '根據發票統計資料計算各區消費熱度'
    url: "Consumption"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/population_placeholder.png
    alt: "placeholder image 2"
    title: "城市活力"
    excerpt: '根據電信信令資料分析人口資訊'
    url: "Population"
    btn_label: "Read More"
    btn_class: "btn--primary"
research_conclusion:
  - title: "資料統整 & 總結"
    excerpt: '根據上述所有資料進行相關性分析與統整結論'
    url: "Conclusion"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="research_method" type="center" %}

<!-- <div style="text-align:center;"><h1>POI點分析</h1></div> -->
{% include feature_row id="POI_features" type="center" %}

<div style="text-align:center;"><h1>Google評論分析</h1></div>
{% include feature_row id="comments_features" %}

<div style="text-align:center;"><h1>獨立資料</h1></div>
{% include feature_row id="other_features" %}

{% include feature_row id="research_conclusion" type="center" %}