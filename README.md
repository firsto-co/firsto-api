# 🏁 Firsto API – Ranking Badges Integration Guide

Welcome to the official API and integration guide for [Firsto](https://firsto.co) – the launchpad for standout projects.

This repository provides ready-to-use **ranking badges** for your Firsto project. You can embed these badges into your landing page, GitHub README, or personal website to proudly display your Daily / Weekly / Monthly achievements.

Visit [firsto.co](https://firsto.co) to discover top-performing projects or submit your own.

---

## 🏅 What are Firsto Badges?

Firsto offers three types of badges to celebrate the top-performing projects on its platform:

- 🗓️ Daily Top 1–3  
- 📅 Weekly Top 1–3  
- 📆 Monthly Top 1–3

Each badge can be embedded via HTML and links directly to your project page on Firsto.

---

## 🔧 How to Embed Badges

Replace:
- `{slug}` with your project slug on Firsto  
- `{siteName}` with your project name

Set `siteUrl` to: `https://firsto.co`

---

## 🗓️ Daily Ranking Badge Code

```html
<!-- Daily Top 1 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 1 Daily Winner">
  <img 
    src="https://firsto.co/images/badges/daily-top1.svg" 
    alt="{siteName} Top 1 Daily Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Daily Top 2 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 2 Daily Winner">
  <img 
    src="https://firsto.co/images/badges/daily-top2.svg" 
    alt="{siteName} Top 2 Daily Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Daily Top 3 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 3 Daily Winner">
  <img 
    src="https://firsto.co/images/badges/daily-top3.svg" 
    alt="{siteName} Top 3 Daily Winner" 
    style="width: 195px; height: auto;" 
  />
</a>
````

---

## 📅 Weekly Ranking Badge Code

```html
<!-- Weekly Top 1 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 1 Weekly Winner">
  <img 
    src="https://firsto.co/images/badges/weekly-top1.svg" 
    alt="{siteName} Top 1 Weekly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Weekly Top 2 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 2 Weekly Winner">
  <img 
    src="https://firsto.co/images/badges/weekly-top2.svg" 
    alt="{siteName} Top 2 Weekly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Weekly Top 3 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 3 Weekly Winner">
  <img 
    src="https://firsto.co/images/badges/weekly-top3.svg" 
    alt="{siteName} Top 3 Weekly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>
```

---

## 📆 Monthly Ranking Badge Code

```html
<!-- Monthly Top 1 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 1 Monthly Winner">
  <img 
    src="https://firsto.co/images/badges/monthly-top1.svg" 
    alt="{siteName} Top 1 Monthly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Monthly Top 2 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 2 Monthly Winner">
  <img 
    src="https://firsto.co/images/badges/monthly-top2.svg" 
    alt="{siteName} Top 2 Monthly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>

<!-- Monthly Top 3 -->
<a href="https://firsto.co/projects/{slug}" target="_blank" title="{siteName} Top 3 Monthly Winner">
  <img 
    src="https://firsto.co/images/badges/monthly-top3.svg" 
    alt="{siteName} Top 3 Monthly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>
```

---

## 🧪 Example

Here’s how it looks for a project called `SuperWidget` that ranked 2nd on the weekly leaderboard:

```html
<a href="https://firsto.co/projects/superwidget" target="_blank" title="SuperWidget Top 2 Weekly Winner">
  <img 
    src="https://firsto.co/images/badges/weekly-top2.svg" 
    alt="SuperWidget Top 2 Weekly Winner" 
    style="width: 195px; height: auto;" 
  />
</a>
```

---

## 💡 Tips

* Badges are optimized and hosted via CDN by Firsto.
* You only need to embed once — the badge represents your **highest-ever** ranking.
* Best placed on your GitHub README, site footer, or marketing page.

---

Get your project featured and earn your badge today on [firsto.co](https://firsto.co)!

