# Study Pilot — SEO, Search Console & AdSense Launch Guide

Domain assumed in this package: https://studypilottool.com/ (confirm it is yours and resolves correctly before submitting).

## 1. Before launch
- Confirm every tool works on desktop and mobile, including errors, empty states and file handling.
- Test all navigation/footer links and remove any placeholder text, broken links, or duplicate content.
- Confirm the canonical domain (HTTPS and either www or non-www) and redirect alternate versions to it.
- Keep `robots.txt` accessible at `/robots.txt` and `sitemap.xml` accessible at `/sitemap.xml`.
- Make About, Contact, Privacy, Terms and Disclaimer accurate and easy to find. Use a genuine contact method and describe data/file handling truthfully.
- Use original screenshots, illustrations and explanatory text. Avoid thin, copied or mass-produced pages.

## 2. Google Search Console setup
1. Visit https://search.google.com/search-console/ and sign in.
2. Add the domain property `studypilottool.com` (Domain property requires DNS verification).
3. Add the TXT record supplied by Google to your domain DNS; do not guess the value. Wait for DNS and verify.
4. Open **Sitemaps** and submit `https://studypilottool.com/sitemap.xml`.
5. Use **URL Inspection** to inspect the homepage and important tool pages; request indexing where appropriate.
6. Review Page indexing, Core Web Vitals and HTTPS reports periodically. Indexing is not guaranteed.

## 3. Google Analytics (optional, useful)
- Create a GA4 property at https://analytics.google.com/ and a web data stream.
- Add the official measurement tag supplied by Google to the site (or use a supported tag manager).
- Configure consent/privacy disclosures appropriate to your audience and jurisdiction. Do not add a fabricated measurement ID.

## 4. AdSense preparation
- Apply at https://adsense.google.com/ using your account and domain.
- Ensure the site has original useful content and functioning tools, clear navigation, genuine About/Contact pages, and accurate Privacy information.
- Review current AdSense policies and publisher restrictions. Do not encourage clicks, place ads where they obscure tools, or use deceptive layouts.
- Once AdSense provides your publisher code, install it exactly as instructed and verify the site. Do not fabricate a publisher ID or an `ads.txt` record.
- If AdSense provides an `ads.txt` line, create `/ads.txt` at the site's root with that exact line. Verify it is reachable.
- Approval is decided by Google; this guide cannot guarantee approval.

## 5. Suggested keyword/page mapping
| Page | Primary topic | Supporting topics |
|---|---|---|
| `/` | free student study tools | online study tools, productivity tools for students |
| `/age-calculator/` | age calculator | calculate age, age in years months days |
| `/percentage-calculator/` | percentage calculator | percentage of a number, percent increase decrease |
| `/gpa-calculator/` | GPA calculator | grade point average, GPA calculation |
| `/pdf-merger/` | merge PDF files | combine PDF online, PDF merger |
| `/pdf-compressor/` | compress PDF | reduce PDF size, compress PDF online |
| `/image-to-pdf/` | image to PDF | convert JPG to PDF, PNG to PDF |
| `/pdf-to-word/` | PDF to Word | convert PDF document, editable Word document |
| `/pdf-summarizer/` | AI PDF summarizer | summarize PDF, document summary |
| `/pdf-question-answering/` | ask questions from PDF | PDF chat, document Q&A |
| `/quiz-generator/` | quiz generator | create quizzes from notes, study quiz |
| `/notes-generator/` | AI notes generator | study notes, notes from text |
| `/mcq-generator/` | MCQ generator | multiple choice questions, practice questions |
| `/essay-outline-generator/` | essay outline generator | essay structure, outline from topic |

Use these as topical direction, not as a keyword-stuffing list. Write for the visitor and validate keyword demand in Search Console after pages begin receiving impressions.

## 6. 30-day content plan
- Week 1: How to calculate GPA; guide to percentage calculations; study planning guide.
- Week 2: How to merge PDFs; how to compress a PDF; image-to-PDF walkthrough.
- Week 3: How to study from a PDF; effective note-making; creating practice MCQs.
- Week 4: Essay outlining guide; active recall and quiz practice; FAQ page improvements based on user questions.

For each article: add a descriptive title, concise meta description, clear headings, examples, original visuals where useful, internal links to relevant tools, and author/editor review. Avoid publishing unreviewed AI-generated filler.

## 7. Ongoing SEO checklist
- [ ] Search Console verified
- [ ] Sitemap submitted
- [ ] Homepage and tool URLs inspectable
- [ ] All pages mobile tested
- [ ] No broken links or console errors
- [ ] Privacy disclosures accurately describe data processing
- [ ] Tool pages explain use cases, limitations and steps
- [ ] Internal links connect related tools and guides
- [ ] Images compressed and have meaningful alt text
- [ ] No fake testimonials, copied content or misleading claims
- [ ] Review Search Console impressions, clicks, queries and page issues monthly
