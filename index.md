---
layout: home
title: Daily Crossover
---

# 🌸 Daily Crossover

매일 아침 9시, 4가지 주제의 순살 브리핑을 전달합니다.

## 📬 구독하기

- **Telegram**: [@ai_cricket_game_brief](https://t.me/ai_cricket_game_brief)
- **RSS**: [feed.xml]({{ "/feed.xml" | relative_url }})

## 📋 브리핑 주제

🤖 **AI** - 글로벌 AI 트렌드와 주요 뉴스  
🏏 **크리켓** - T20 월드컵 2026 + 인도 크리켓 소식  
🎮 **게임** - 크래프톤 중심 한국 게임 산업 동향  
💰 **경제** - 환율, 금리, 주식 시장 요약

## 📝 최근 브리핑

{% for post in site.posts limit:10 %}
- [{{ post.date | date: "%Y년 %m월 %d일" }}]({{ post.url | relative_url }}) - {{ post.title }}
{% endfor %}

---

Made with 🌸 by Nari
