Portfolio Website

This repository contains the source code for my personal developer portfolio. It showcases selected projects, design philosophy, and a clean, minimal front‑end aesthetic. The site is built with core web technologies and focuses on clarity, accessibility, and thoughtful user experience.

Purpose

The portfolio serves as a central place to highlight my work, technical skills, and background. It is designed to be simple, fast, and easy to navigate, reflecting my preference for clean interfaces and intentional design.

Features

- Minimal, responsive layout
- Clear project organization
- Accessible typography and spacing
- Custom “Selected Work” page
- Tessiel featured prominently on the home and Selected Work pages, with its live hero artwork and React, TypeScript, Supabase, Vite, and Vercel stack badges
- Full-stack skills overview with a front-end specialty
- Home-page “Contact me” button linking to a contact section with a visible, copyable email address and an optional email-app link
- Lightweight HTML and CSS structure
- Tailwind CSS utilities via CDN

Tech Stack

- HTML  
- CSS  
- Tailwind CSS (CDN)

Live Demo

https://badwolfweb.com/

Custom Domain Setup

The root `CNAME` file configures `badwolfweb.com` for GitHub Pages when deployed.
Before switching, verify ownership in GitHub Settings > Pages using GitHub's supplied TXT record.
In Porkbun, disable the existing Link In Bio URL forwarding and replace only conflicting web records:

- Apex A records (leave Host blank): `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `www` CNAME: `badwolf910.github.io`

Keep Porkbun's nameservers and preserve all email-related MX, TXT, and CNAME records.
Remove or replace conflicting apex AAAA/ALIAS records if present; do not leave them pointing at the old host.
After deploying the domain configuration and DNS propagation, confirm the DNS check and certificate in repository Settings > Pages, and enable Enforce HTTPS when available.

Pages Included

- **Home** (`index.html`) – Introduction, featured Tessiel project, skills, about section, and contact section
- **Selected Work** (`fprojects.html`) – Featured Tessiel project followed by a curated list of projects with descriptions and links

Project Goals

- Present my work in a clean, professional format  
- Demonstrate front‑end design fundamentals  
- Build a portfolio that is easy to maintain and expand  
- Provide recruiters and clients with a clear view of my capabilities  

Author

Danielle Smith  
https://github.com/badwolf910
