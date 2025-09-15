# ActomeAI Portal Website (Static Site)

This branch (**gh-pages**) contains the **compiled static files** of the ActomeAI portal website.  
It is automatically generated and deployed by [Hexo](https://hexo.io/).  

👉 The live site is served directly from this branch:  
**https://username.github.io**

---

## ⚠️ Important

- Do **not** edit files in this branch manually.  
- All changes to the website should be made in the **main branch** (Hexo source code).  
- To update the site:  
  1. Modify content or configuration in `main`.  
  2. Generate and deploy via Hexo (`hexo clean && hexo generate && hexo deploy`).  
  3. Hexo will overwrite this branch with the new static files.  

---

## Branch Structure

- **main** → Hexo source code (development happens here).  
- **gh-pages** → Static site generated from `public/` (used by GitHub Pages).  

---

© 2025 ActomeAI. All rights reserved.  
Open Science × Responsible AI
