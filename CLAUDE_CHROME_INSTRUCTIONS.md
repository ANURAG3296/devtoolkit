# Complete Setup & Deployment Instructions for Claude Chrome

## OVERVIEW
I have a folder of digital products ready to sell and deploy. I need help setting up accounts, deploying a website, and listing products for sale. Please follow these instructions step by step. Ask me for login credentials or any personal info when needed — don't skip steps.

---

## PART 1: DEPLOY THE DEVELOPER TOOLKIT WEBSITE

### Goal: Get devtoolkit website live on Vercel with a custom domain

### Step 1: Create a GitHub Repository
1. Go to github.com (I should already be logged in)
2. Create a new repository called "devtoolkit"
3. Make it public
4. Initialize with a README
5. I will upload the HTML files from my devtoolkit folder to this repo (ask me to do this, or help me upload them through the GitHub web interface)

### Step 2: Deploy on Vercel
1. Go to vercel.com
2. Sign up / log in with my GitHub account (ask me for credentials if needed)
3. Click "New Project"
4. Import the "devtoolkit" GitHub repository
5. Framework preset: "Other"
6. Root directory: leave as default
7. Click "Deploy"
8. Wait for deployment to complete
9. Note the deployed URL (e.g., devtoolkit-xxx.vercel.app)

### Step 3: Custom Domain (Optional)
1. Go to namecheap.com
2. Search for a domain like "devtoolkit.app" or "quickdevtools.com" or "freetoolkit.dev"
3. If I approve a domain, help me purchase it (~$10/year)
4. Go back to Vercel → Project Settings → Domains
5. Add the custom domain
6. Update DNS records on Namecheap as Vercel instructs

### Step 4: Submit to Google Search Console
1. Go to search.google.com/search-console
2. Add the property (the Vercel URL or custom domain)
3. Verify ownership (Vercel usually auto-verifies, or use HTML tag method)
4. Submit the sitemap (if we create one) or request indexing for the homepage
5. Request indexing for each individual tool page URL

---

## PART 2: SET UP GOOGLE ADSENSE

### Goal: Get AdSense approved and add ad code to the website

### Step 1: Apply for AdSense
1. Go to adsense.google.com
2. Sign in with my Google account
3. Click "Get Started"
4. Enter the website URL (from Vercel deployment)
5. Select country: United States
6. Accept Terms of Service
7. Complete the setup

### Step 2: After Approval (may take days/weeks)
1. Go to AdSense dashboard → Ads → By ad unit
2. Create two ad units:
   - "DevToolKit Banner" - Display ad, 728x90 (Leaderboard)
   - "DevToolKit Rectangle" - Display ad, 300x250 (Medium Rectangle)
3. Copy the ad code for each unit
4. In each HTML file in the devtoolkit folder, find the comment `<!-- REPLACE WITH ADSENSE CODE -->` and replace the placeholder div with the actual AdSense code
5. Also add the AdSense script tag to the <head> of each HTML file
6. Push the updated files to GitHub (Vercel will auto-deploy)

**Note:** AdSense typically requires the site to have some traffic and content before approval. The 12 tools should be enough content. If rejected initially, wait 2-4 weeks and reapply.

---

## PART 3: SET UP GUMROAD STORE

### Goal: Create a Gumroad account and list digital products

### Step 1: Create Gumroad Account
1. Go to gumroad.com
2. Click "Start Selling"
3. Sign up with email (ask me for details)
4. Complete profile setup

### Step 2: List Product #1 - Tech Resume Template
1. Click "New Product"
2. Product name: "Professional Tech Resume Template - ATS-Friendly | Software Engineer | Modern Design"
3. Price: $8.99 (set as "Pay what you want" with $8.99 minimum)
4. Description:
```
Land your dream tech job with this professionally designed resume template.

What you get:
- Clean, modern DOCX resume template
- ATS-friendly format (passes automated screening systems)
- Pre-filled with sample content for a Software Engineer role
- Sections: Summary, Technical Skills, Experience, Education, Certifications, Projects
- Easy to customize in Microsoft Word, Google Docs, or LibreOffice
- Professional Navy & Blue color scheme

Perfect for: Software Engineers, Full-Stack Developers, Backend/Frontend Engineers, DevOps Engineers, Data Scientists, Product Managers, and other tech professionals.

Why this template works:
- Tested with major ATS systems (Greenhouse, Lever, Workday)
- Clean formatting that recruiters love
- Proper heading hierarchy for easy scanning
- Professional typography (Arial) compatible with all systems

Instant download after purchase. Start customizing in minutes.
```
5. Upload file: Tech_Resume_Template_Modern.docx
6. Tags: resume template, tech resume, software engineer resume, ATS resume, professional resume, job search
7. Publish the product

### Step 3: List Product #2 - Personal Finance Budget Tracker
1. Click "New Product"
2. Product name: "Personal Finance Budget Tracker - Excel Spreadsheet | Monthly Budget Planner"
3. Price: $6.99 (pay what you want, $6.99 minimum)
4. Description:
```
Take control of your finances with this comprehensive Excel budget tracker.

What you get:
- Professional Excel spreadsheet (.xlsx format)
- Monthly Budget sheet with income/expense tracking
- Dashboard with charts and visual summaries
- Annual Overview for year-at-a-glance analysis
- Categories sheet for easy customization
- All formulas built-in — just enter your numbers

Features:
- Pre-built expense categories (Housing, Transportation, Food, etc.)
- Automatic calculations for totals, savings rate, and remaining budget
- Visual charts showing spending breakdown
- Works in Microsoft Excel, Google Sheets, and LibreOffice Calc
- Professional formatting with clean, readable design

Start budgeting in under 5 minutes. Just download, enter your income, and track your spending.
```
5. Upload file: Personal_Finance_Budget_Tracker.xlsx
6. Tags: budget tracker, finance spreadsheet, budget planner, expense tracker, money management, personal finance
7. Publish the product

### Step 4: List Product #3 - Notion Job Application Tracker (Create in Notion First)
**First, build the Notion template:**
1. Go to notion.so (log in to my account)
2. Create a new page titled "Job Application Tracker 2026"
3. Follow the template structure in Notion_Job_Tracker_Template_Guide.md to create:
   - Main database with all properties listed
   - Kanban board view (group by Status)
   - Table view (all applications)
   - Follow-up view (filtered for stale applications)
   - Calendar view
   - Dashboard section with stats
   - Interview Prep sub-page
   - Offer Comparison sub-page
4. Once built, click "Share" → "Share to web" → Enable "Allow duplicate as template"
5. Copy the template URL

**Then list on Gumroad:**
1. New Product on Gumroad
2. Product name: "Job Application Tracker - Notion Template | Job Search Organizer | Interview Prep"
3. Price: $5.99 (pay what you want, $5.99 minimum)
4. Description:
```
Organize your entire job search in one place with this Notion template.

What you get:
- Visual Kanban board to track every application stage
- Database with all the fields you need (company, role, salary, status, etc.)
- Follow-Up view that shows which applications need attention
- Calendar view for timeline tracking
- Interview Prep template with STAR method guide
- Offer Comparison table for evaluating multiple offers
- Pre-built database templates for quick entry

Perfect for tech professionals, new grads, and anyone actively job searching.

How to use:
1. Click the template link after purchase
2. Click "Duplicate" in Notion to copy it to your workspace
3. Start adding your applications

Works with Notion free and paid plans.
```
5. Add the Notion template link as the product file/link
6. Tags: notion template, job tracker, job application tracker, job search, career tracker, interview prep
7. Publish

---

## PART 4: SET UP ETSY SHOP (Optional but recommended)

### Goal: List templates on Etsy for broader reach

### Step 1: Create Etsy Shop
1. Go to etsy.com
2. Click "Sell on Etsy" → "Open your Etsy shop"
3. Shop name: something like "DevToolKitShop" or "TechTemplateHub"
4. Complete shop setup (ask me for payment/billing details)

### Step 2: List Products
List the same Resume Template and Budget Tracker with similar descriptions but optimized for Etsy SEO:
- Use all 13 available tags per listing
- Put keywords in the first few words of the title
- Set as "Digital download" type

Resume Template Etsy Tags: resume template, tech resume, software engineer resume, ATS friendly resume, modern resume, professional resume template, developer resume, job application, career template, resume download, Word resume template, DOCX resume, clean resume

Budget Tracker Etsy Tags: budget tracker, budget spreadsheet, finance planner, expense tracker, monthly budget, personal finance, money tracker, Excel budget, budget template, savings tracker, financial planner, spending tracker, budget planner

---

## PART 5: SEO & MARKETING QUICK WINS

### Google Search Console Indexing
For each tool URL, go to Google Search Console → URL Inspection → paste URL → Request Indexing. Do this for:
- (homepage URL)
- (homepage URL)/json-formatter.html
- (homepage URL)/base64.html
- (homepage URL)/url-encoder.html
- (homepage URL)/hash-generator.html
- (homepage URL)/password-generator.html
- (homepage URL)/lorem-ipsum.html
- (homepage URL)/color-picker.html
- (homepage URL)/markdown-to-html.html
- (homepage URL)/word-counter.html
- (homepage URL)/css-minifier.html
- (homepage URL)/html-minifier.html
- (homepage URL)/regex-tester.html

### Create a Simple Sitemap
Create a sitemap.xml file listing all tool URLs and upload it to the GitHub repo. Then submit it in Google Search Console.

---

## SUMMARY OF ALL PRODUCTS

| # | Product | Platform | Price | File |
|---|---------|----------|-------|------|
| 1 | Tech Resume Template | Gumroad + Etsy | $8.99 | Tech_Resume_Template_Modern.docx |
| 2 | Budget Tracker | Gumroad + Etsy | $6.99 | Personal_Finance_Budget_Tracker.xlsx |
| 3 | Notion Job Tracker | Gumroad | $5.99 | Build in Notion using guide |
| 4 | DevToolKit Website | Vercel (ads) | Free (ad revenue) | devtoolkit/ folder (12 HTML files) |

## WHAT ANURAG NEEDS TO PROVIDE
- GitHub login credentials (for repo creation)
- Google account (for AdSense and Search Console)
- Email for Gumroad account
- Notion account login (for building the template)
- Payment info for Etsy shop setup (Etsy charges $0.20 per listing)
- Domain name preference and payment for custom domain (~$10/year)
