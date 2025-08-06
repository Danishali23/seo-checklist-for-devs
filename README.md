# SEO Checklist for Devs

A practical, no-fluff SEO checklist built for developers. Whether you're building a blog, web app, or job site — this repo outlines core technical SEO practices that make websites search-engine-friendly from day one.

> 💡 Maintained by [Danish Ali](https://github.com/Danishali23) | Based on real-world SEO used on [247CareersinGulf.org](https://247careersingulf.org/)

---

## ✅ Core HTML Markup

- [ ] Use one `<h1>` per page  
- [ ] Title tag ≤ 60 characters  
- [ ] Meta description ≤ 160 characters  
- [ ] Canonical URL tag on every page  
- [ ] Language attribute in `<html lang="en">`  
- [ ] OpenGraph + Twitter tags for share previews

---

## 📊 Structured Data (JSON-LD)

- [ ] `WebSite`, `Organization`, `BreadcrumbList` on all pages  
- [ ] `Article` or `BlogPosting` for blogs  
- [ ] `JobPosting` for job boards (see `structured-data-examples.json`)  
- [ ] Validate with [Google's Rich Results Tool](https://search.google.com/test/rich-results)

---

## 🔍 Crawlability

- [ ] `robots.txt` allows crawling of main sections  
- [ ] `sitemap.xml` is auto-generated and submitted to Google  
- [ ] No unnecessary `noindex` or `nofollow` unless intentional  
- [ ] Pages load without JS blockers (especially for SPAs)

---

## 🚀 Performance (PageSpeed Matters)

- [ ] Core Web Vitals pass (LCP < 2.5s, CLS < 0.1, INP < 200ms)  
- [ ] Lazy-load images  
- [ ] Compress CSS/JS/images  
- [ ] Use responsive images (`srcset`)  
- [ ] Server response time < 600ms

---

## 🗺 Site Architecture

- [ ] Clean, readable URLs (no query mess)  
- [ ] Internal linking structure supports crawling  
- [ ] Mobile-first design  
- [ ] Avoid duplicate content (canonicalize where needed)

---

## 🧩 Extras for Developers

- [ ] Deploy sitemap & robots.txt automatically with builds  
- [ ] Add preloading for fonts and critical JS/CSS  
- [ ] Use semantic HTML5 elements (`<main>`, `<nav>`, `<article>`, etc.)  
- [ ] Set meaningful `alt` text for all images  

---

## 📌 Resources

- [Google SEO Starter Guide](https://developers.google.com/search/docs/fundamentals/seo-starter-guide)  
- [PageSpeed Insights](https://pagespeed.web.dev/)  
- [Schema.org Markup](https://schema.org/)  
- [robots.txt tester](https://www.robotstxt.org/robotstxt.html)

---

### 💬 Contributions Welcome

Have tips to add for React, Next.js, or Jamstack SEO? Open a pull request or drop an issue.

---

📍 **Repo by [Danish Ali](https://github.com/Danishali23)** — focused on helping devs build SEO-friendly experiences from day one.
