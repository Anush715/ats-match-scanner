# ATS Match Scanner

See your resume the way a hiring bot does.

## Why I built this

Tailoring a resume to a specific job description usually means manually comparing the two and guessing which keywords matter. This tool automates that comparison: it scores the keyword overlap, highlights matched terms directly within your resume text, and lists the terms that are missing so you can decide which ones genuinely apply.

## How it works

- Pulls significant keywords out of the job description (filters common stopwords, ranks by frequency)
- Checks your resume for each keyword, handling basic singular/plural variants
- Scores the overlap as a percentage
- Highlights matched terms inline on your own resume text, so you can see exactly where you're already covered
- Lists the missing terms so you can decide which ones genuinely apply to you

Everything runs client-side in the browser. No backend, no database, nothing is uploaded or stored anywhere.

## Tech

Plain HTML, CSS, and JavaScript — no framework, no build step. Deployed on Vercel's free Hobby plan.

## Live demo

[Add your live Vercel URL here after deploying]

## Run locally

Just open `index.html` in a browser. No install needed.

---
Built by Anushka Bansal — anush50217@gmail.com
