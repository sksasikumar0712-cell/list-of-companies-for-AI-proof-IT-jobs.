# Beyond IT — productwithsasi

A mobile-friendly static directory of technology careers outside traditional IT and SaaS employers, inspired by the visual style of [Paytm Careers & Hackathons](https://github.com/sksasikumar0712-cell/PaytmaihackthonAI).

## Part 1 (November 17, 2026)

Ten featured companies: Agnikul Cosmos, The ePlane Company, Data Patterns, Boeing, KLA, Microchip Technology, pSemi, Shell, Vestas, Hitachi Energy.

### Features
- Search across company names, industries, locations, technologies and skills
- Industry chip filters and role dropdown
- Company-specific official careers pages, including Chennai-filtered links when available
- Two actions per company: **Careers** (official employer portal) and **HR LinkedIn** (company-specific people search)
- **HR LinkedIn** searches for recruiter/HR profiles using the company name and Chennai; it does **not** scrape, identify, or guarantee any HR employee
- Compact sticky directory title and search bar on mobile and desktop; industry and role filters scroll normally
- Header LinkedIn icon and fixed personal LinkedIn follow link
- Responsive cards for mobile and desktop
- Permanent **Part 2 Coming Soon** teaser for later releases

### Run locally

No build step or dependencies.

```sh
python3 -m http.server 8000
```

Open http://localhost:8000

You may also open `index.html` directly in your browser.

### Deploy

Deploy this static repository through Vercel, Netlify or GitHub Pages. Vercel: import the repository, use the Other framework preset, leave build command empty, and use the repository root as output.

The GitHub repository is **not automatically a published website** merely because the HTML was committed. After deployment, use the published URL for Instagram DM replies.

### Add companies in Part 2

Edit the `companies` array in `index.html`. Each object has `name`, `industry`, `builds`, `location`, `roles`, `careers`, `linkedin`, and `hr`. Check official career links and tech-office location before publishing.

Do not claim a company is hiring based on its presence in this directory. Role tags identify possible technology functions, not verified live vacancies. No IT job or employer is AI-proof.

### Content notes

Locations reflect the provided research snapshot, and exact current addresses for Boeing and Microchip are unconfirmed. LinkedIn searches may require sign-in and results depend on the LinkedIn account and its search algorithm. No candidate or recruiter personal data is stored by this website.

Independent site by @productwithsasi; not affiliated with any listed employer.
