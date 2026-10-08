# MeterWatch — Business Plan for Approval (clean-sheet idea)

**Prepared:** 8 October 2026
**Brief:** a novel, AI-native, agentic, web-based business with nothing in common with BCS, safety, or anything built before. R50,000 per month recurring. Live in 2 days.
**Status:** Awaiting Michael's approval. Nothing bought, deployed or sent.

---

## 1. The call

**Build MeterWatch: an agent that audits every municipal bill the moment it arrives, flags estimated readings, tariff errors and spikes, drafts the dispute, and runs the 30-day clock, for landlords, managing agents and body corporates. WhatsApp and email in, dashboard and dispute pack out, R99 per property per month.**

The customer forwards the e-bill PDF (or photographs the paper bill and the meter) to a WhatsApp number or an email address. The agent reads it, recalculates every line against the current tariff tables for that metro, compares consumption against the property's history, flags the problems in plain language, and, on a tap, produces the formal dispute in the municipality's own format with the Municipal Systems Act section 102 wording that stops credit control on the disputed amount. It then tracks the 30-day window, reminds the customer when to escalate, and keeps the whole paper trail per property.

Why now and why here: eThekwini estimated 64,147 water meters and 57,024 electricity meters in February 2026 alone. Residential electricity is read quarterly and estimated in between. When the actual reading finally lands, the catch-up is billed at current tariffs. One Durban sectional-title landlord received a backdated R185,000 demand after 18 months of plausible estimates. A Phoenix pensioner was presented with R81,000. Councillors call it a pervasive issue. City Power credited R136 million to overcharged Johannesburg customers. Today the only remedies are attorneys (Schindlers runs a paid adjudication service), OUTA's self-help guides, and the municipality's own form. No self-serve monitoring product exists. The research found none in South Africa.

## 2. What was researched and why this won

Fourteen ideas across three lenses (marketplace apps, global micro-SaaS, South African gaps). The shortlist:

| Candidate | Verdict |
|---|---|
| **MeterWatch (chosen)** | Acute, documented, recurring pain. Zero self-serve competitors. The trigger is monthly by nature, so subscription is natural. WhatsApp and email intake means no app to install. Buyers are concentrated (managing agents hold hundreds of units each), so R50k needs a handful of accounts. Buildable in 48 hours: vision model reads bills, tariff tables are public, dispute format is published. |
| **ShadowShop, AI mystery shopper for multi-location businesses (runner-up, full plan in the appendix file)** | Also novel with no named competitor, sells in dollars, buyers already spend on human mystery shops. Loses on speed to revenue: 25 US multi-location accounts sold from Durban versus 3 to 5 managing agents here. Kept as the second business or the global expansion once MeterWatch cash flows. |
| DutyDrift, weekly tariff-change agent for small cross-border sellers | Loud forum demand, USD, simple build. But Customs Guard launched 27 August 2026 at $24.90 and the demand is tied to a tariff environment that can calm down. Reserve. |
| AI search visibility app for Shopify merchants | Nine new apps already (Kwik GEO, FoundGPT, Visibility Mesh, Mento, SearchMention). Shopify App Store review 2 to 7 weeks. Not novel, not live in 48 hours. |
| Weekly AI CFO memo on Xero; AI debt chasing | Xero's JAX shipped payment follow-ups, reconciliation and anomaly flags natively in 2026. Platform risk. |
| Planning-agenda watcher for US realtors; copycat-listing takedown for Etsy sellers; LRA disciplinary process runner for SA employers | Credible but weaker on willingness to pay or closer to document generation. |
| Self-managing landlord app, AI legal letters, SMB customer-interview tool | Free incumbent (MRI Rentbook), unresolved Legal Practice Act section 33 exposure, and a squeezed price band respectively. |

## 3. Market evidence (today's research)

- eThekwini Finance Committee, February 2026: 64,147 water and 57,024 electricity meters estimated; estimates rising from 55,325 (Nov 2025) to 61,567 (Dec 2025). Punitive tariffs threatened on accounts unread for three months.
- eThekwini confirms residential electricity is read quarterly and estimated in between; business meters monthly with estimates on an average when no reading is available. Large catch-up adjustments are a known, acknowledged pattern.
- Section 102(2) of the Municipal Systems Act stops credit control on a specific disputed amount once a valid dispute is lodged. eThekwini's own form requires the dispute within 30 days of the account, tied to a specific amount, with undisputed amounts paid. Croftdene Mall v eThekwini sets what counts as a valid dispute: specific amounts, specific grounds, not a bare denial. That is precisely a job for a document-reading agent.
- Johannesburg: City Power credited R136 million to overcharged customers. Tshwane, Cape Town and Ekurhuleni carry the same dispute machinery. Phase 2 metros.
- Buyers: landlords, managing agents and body corporates. Trafalgar alone manages about 85,000 residential units; National Real Estate 10,000 units across 300 schemes. A mid-sized Durban managing agent holds 300 to 2,000 units. Municipal accounts for sectional title schemes are the single largest recurring cost line after levies.
- Tariff changes feed the product: eThekwini 1 July 2026 increases of 12% water, 8% sanitation, 9% electricity, 9.5% refuse, plus the R1.50 per kilolitre infrastructure surcharge to 2029. Every tariff change is a reason to re-check the bill, and most residents cannot.

## 4. Offer and pricing (ZAR, VAT inclusive, Paystack with EFT fallback)

| Plan | Price | Who | Includes |
|---|---|---|---|
| Home | R99/property/month | Homeowners and small landlords | Bill audit every month, estimate and spike alerts, one-tap dispute pack, 30-day tracker, meter-photo reading log |
| Portfolio | R59/unit/month, minimum 10 units | Landlords and body corporates | Everything in Home, portfolio dashboard, bulk forwarding address, scheme-level and bulk-meter reconciliation |
| Agent | R39/unit/month, minimum 100 units, white-label | Managing agents | Everything in Portfolio, their branding on dispute packs and client reports, client-facing summary per owner, API or CSV export |
| Single Dispute | R349 once | Anyone with one bad bill | One audit and dispute pack with the 30-day tracker. The lead magnet |

**Path to R50,000 MRR:** 2 managing agents at 400 units (R31,200) + 6 portfolio clients averaging 30 units (R10,620) + 85 Home subscribers (R8,415) = R50,235. Or 1,282 Home subscribers. Or 3 agents at 430 units. A handful of agent conversations decides it.

**Unit economics:** reading one bill with Claude vision and recalculating is about R1.50 in model cost. A dispute pack is about R3. WhatsApp utility messages cost about $0.0076 each. Paystack 2.9% + R1. Gross margin above 90% at every tier. The free "check one bill" audit on the landing page costs us under R2 per lead.

## 5. Why the subscription sticks

The bill arrives every month whether or not the customer thinks about it. The property's consumption history, meter-photo log and dispute trail live in MeterWatch, and that history is what wins the next dispute. Managing agents bill the service on to owners and sell it as a differentiator at the next AGM. Churn happens if bills are consistently correct, and in eThekwini that is not the case.

## 6. Product scope for the 48 hours

**Hours 0 to 24: the auditor**
1. Next.js on Vercel, Supabase (auth, Postgres, Storage, row-level security). Repo mbullardct-svg/AIBusiness.
2. Intake: email forwarding address per account (Resend inbound) and web upload on day 1; WhatsApp via 360dialog as soon as the number is verified (partner-led verification is quoted at minutes to 48 hours; unverified numbers can send to 250 unique recipients a day, which is enough for launch).
3. Bill reader: Claude Opus 5.5 vision on the PDF or photo, structured output: account, property, period, each service line, reading type (actual or estimated), previous and current readings, consumption, tariff applied, charges, totals. A confidence score per field; low confidence routes to a quick confirm screen.
4. Tariff engine: eThekwini 2026/27 tables for domestic and business water (stepped), sanitation, electricity (blocks), refuse and rates as versioned data, with the R1.50 surcharge. Recalculate each line and compare to the billed amount. Johannesburg and Cape Town tables load in week 2.
5. Anomaly rules: estimated reading flag; consumption more than 1.5x the property's 6-month median; catch-up adjustment detected; tariff step mismatch; interest or penalty lines; duplicate charges; VAT errors; reading sequence errors (current lower than previous).
6. Dispute pack generator: the municipality's dispute form fields completed, a covering letter with the specific amounts and grounds, section 102(2) wording, the evidence list (meter photo with date stamp, prior bills), and the undisputed amount to pay. PDF.
7. Property timeline: every bill, reading, photo and dispute per property, with the 30-day clock and reminders at day 20, 28 and on expiry, plus the escalation step to the Municipal Manager.
8. First real audits on hour 12 using our own eThekwini bills and three volunteer properties.

**Hours 24 to 48: the business**
9. Paystack plans in test mode (card, 3D Secure), entitlements per plan, EFT invoice path with manual mark-paid for agents and body corporates.
10. Portfolio and Agent workspaces: multi-property, bulk forwarding address, per-owner summary, white-label logo.
11. Landing page with the free "check one bill" audit (upload a PDF, get the flags, pay R349 for the dispute pack or subscribe), pricing, sample dispute pack, terms, privacy.
12. Weekly digest email and WhatsApp alert templates (bill received, problems found, dispute due, response overdue).
13. Custom domain, rate limits, Supabase security advisor pass, end-to-end test as a fresh user.
14. Outreach drafts for managing agents and body corporate trustees in eThekwini, ready for approval.

**Deferred to week 2:** Johannesburg and Cape Town tariffs, smart-meter and prepaid cases, bulk-meter apportionment for schemes, automatic submission of self-readings to eThekwini eServices, API, Afrikaans and isiZulu alert text.

## 7. Stack and running cost

| Layer | Choice | Monthly cost |
|---|---|---|
| App | Next.js on Vercel Pro | ~R370 |
| Data | Supabase (new project, London region) | ~R190 |
| AI | Anthropic API: Opus 5.5 vision for bills, Haiku 5.5 for alerts and classification | ~R1.50 per bill |
| Messaging | 360dialog WhatsApp Business API | ~R950 base plus per-message |
| Email | Resend (inbound forwarding and digests) | R0 to R370 |
| Billing | Paystack | 2.9% + R1 per transaction |
| Domain | meterwatch.co.za via Vercel | once-off |

## 8. Go-to-market (first 30 days)

1. **Free bill check (days 1 to 30):** upload one bill, get the audit. Shareable result card ("Your February bill was estimated. The catch-up could be R4,200 at July tariffs."). Posted into the Durban ratepayer and community Facebook groups where this is the daily topic, and into the comment threads of every billing story in The Mercury, IOL and Daily News.
2. **Managing agents (week 1):** a list of eThekwini managing agents from the NAMA and PPRA registers. The pitch is a free audit of 20 of their units' latest bills. Every flagged estimate is a reason to sign the portfolio.
3. **Body corporate trustees (week 2):** CSOS-registered schemes in eThekwini. Trustees are volunteers who get blamed for the municipal account. R59 a unit beats one bad month.
4. **Search (week 2 onward):** "ethekwini account query", "estimated reading dispute", "municipal bill too high", "section 102 dispute". South African CPCs average about R9. Content pages per metro and per error type.
5. **Partners:** attorneys who run municipal disputes (referral for the cases that need court), levy-finance companies, rental-deposit insurers, estate agents' rental divisions.

## 9. What I need from you (permissions only)

| # | Item | Why | Your time |
|---|---|---|---|
| 1 | Approve the plan, the name MeterWatch and the domain meterwatch.co.za | Nothing starts without it | 5 min |
| 2 | Anthropic API key with billing | Bill reading and dispute drafting | 10 min |
| 3 | 360dialog account with a new WhatsApp number (not one in use on the WhatsApp app) and your Meta Business Manager login | WhatsApp intake and alerts. Start today; verification can take up to 48 hours | 20 min |
| 4 | Paystack account under the entity you choose | Subscriptions. KYC 1 to 5 days; EFT fallback meanwhile | 20 min |
| 5 | Resend account and two DNS records | Inbound bill forwarding and digests | 10 min |
| 6 | Allow durban.gov.za, bylaws.durban.gov.za, joburg.org.za, capetown.gov.za, api.paystack.co, api.resend.com, waba-v2.360dialog.io in this cloud environment's network settings | Tariff tables, dispute forms and API tests from here. These are blocked today | 5 min |
| 7 | Your own eThekwini bills (home and any other accounts you hold) as PDFs or photos, 6 months if you have them | Real test data on hour 1 | 10 min |
| 8 | Three friends or neighbours with eThekwini accounts who will forward a bill | Volunteer audits for the sample results | 20 min |
| 9 | Confirm Vercel is on Pro | Cron and inbound processing | 5 min |

## 10. Legal position

- **Not legal practice:** a municipal dispute is an administrative process under the Municipal Systems Act and the municipality's own by-law, not court proceedings, so Legal Practice Act section 33(1)(b) is not engaged. The customer lodges the dispute in their own name. Court matters are referred to partner attorneys.
- **POPIA:** account numbers, addresses, consumption data and ID numbers on bills are personal information. Row-level security, encrypted storage, signed expiring links, retention policy, operator clauses for Supabase, Vercel, Anthropic and 360dialog. Bills are processed by the model to extract line items; no special personal information is involved. Information Officer registration and PAIA manual in the first 30 days.
- **WhatsApp:** utility and service messages only to customers who opted in by messaging us first; marketing templates only with consent. Meta's per-message charging from 1 October 2026 is in the cost model.
- **Consumer Protection Act:** monthly plans cancel on notice; no lock-ins for individuals.
- **Claims:** we say "flags likely errors and prepares your dispute", never "guarantees a refund". The municipality decides the dispute.

## 11. Honest view on the timeline

- **48 hours:** live site, free bill check running, Single Dispute and Home plans purchasable, email intake live, WhatsApp live if Meta verifies in time, sample audits published.
- **Day 14:** 50 to 150 free checks from the Facebook groups and news threads, 10 to 25 Single Dispute sales, 10 to 20 Home subscribers, two managing agents in audit. MRR R1k to R3k, cash R5k to R10k.
- **Day 45:** first managing agent live at 200 to 400 units. MRR R10k to R20k.
- **Day 90:** R35k to R50k MRR if two agents are live, which is the base case. Stretch at day 60 if a single large agent signs.
- **Kill criteria:** free check to paid conversion under 3% by day 30, or no managing agent beyond audit by day 45, or audits finding actionable errors in under 20% of eThekwini bills (in which case the problem is smaller than the press says).

R50,000 in two days is not a real number for a new business with real customers. Live and selling in two days is. The difference from the first plan: this one needs about three managing-agent decisions, in your own city, on a problem that is in the newspaper every week, and nothing about it touches BCS.

## 12. Risks

| Risk | Handling |
|---|---|
| eThekwini tariff tables are wrong or out of date in our engine | Versioned tables with effective dates, sourced from the published tariff booklet; each recalculation shows its working; a flag is "probable", never "certain" |
| Bill formats vary (paper, e-bill PDF, eServices screenshot, Johannesburg and Cape Town formats) | Vision model with per-field confidence and a confirm screen; format library grows with every bill; eThekwini-only on day 1 |
| Municipality ignores disputes | The product's value is also protection: a lodged section 102 dispute stops credit control on that amount, and the paper trail is what wins at escalation and in court. We say so plainly |
| WhatsApp verification slips past 48 hours | Email forwarding and web upload carry launch; WhatsApp joins when approved |
| Paystack KYC slips | EFT invoicing from day 1 for agents and body corporates; Single Dispute by EFT or Paystack test-to-live switch |
| Municipality fixes estimated billing (automated meter reading rollout announced) | Rollout is years out; even with smart meters, tariff errors, catch-ups, interest and rates disputes persist; expansion to Johannesburg and Cape Town diversifies |
| A copycat from an attorney firm or OUTA | Our moat is the per-property history and the tariff engine across metros; we move first and partner with the attorneys |

## 13. Decision requested

Approve the name, the domain, the stack and the pricing. Reply "go" and send items 2 to 7 in section 9 as you get to them. Build starts with the bill reader and the eThekwini tariff engine, because the first audit has to be right.

---

## Appendix A: sources used today

- eThekwini estimated billing figures: https://iol.co.za/mercury/news/2026-02-27-ethekwini-working-to-reduce-estimated-billing-announces-plan-for-automated-meter-reading/ and https://themercury.co.za/2025-12-12-ethekwini-councillors-raise-alarm-on-billing-inaccuracies-and-grossly-inflated-bills/ and https://iol.co.za/news/south-africa/kwazulu-natal/2026-04-15-ethekwini-billing-crisis-residents-short-changed-by-estimated-bills-as-faulty-meters-and-errors-spark-outrage/
- Quarterly reading and estimation practice: https://roads.durban.gov.za/press-statement/EThekwini+Municipality+Clarifies+Billing+Accuracy
- Section 102 and what counts as a dispute: https://www.golegal.co.za/disputing-municipal-accounts/ and https://www.schindlers.co.za/what-counts-as-a-dispute-with-a-municipality/ and https://saflii.org/za/cases/ZASCA/2024/101.html
- eThekwini dispute form, 30-day rule: https://bylaws.durban.gov.za/uploads/0000/6/2025/10/09/dispute-complaints-appeals-initiation-form-revenue-unit.pdf
- 2026/27 tariff increases: https://iol.co.za/mercury/news/2026-05-31-ethekwini-ratepayers-here-are-the-new-july-1-tariff-hikes/
- Landlord R185,000 backdated demand: https://www.mikebolhuis.co.za/post/project-faulty-municipal-metering-and-billing-irregularities-a-financial-threat-to-landlords-and
- City Power R136m credits: https://allafrica.com/stories/202603100368.html
- Managing agent scale: https://www.pnet.co.za/cmp/en/Trafalgar-Property-Management-Cape-Town-33557/work.html and https://www.nationalre.co.za/sectional-title/
- WhatsApp API timing and pricing: https://docs.360dialog.com/docs/resources/meta-business-verification/plbv and https://chatmaxima.com/whatsapp-api-pricing/south-africa/
- Competitive scans for the rejected ideas: https://apps.shopify.com/kwik-geo-1 , https://www.xero.com/media-releases/xero-announces-new-ai-innovations-xerocon-london/ , https://pickyourapp.com/products/customs-guard , https://www.mrisoftware.com/za/products/rentbook/

## Appendix B: the runner-up

The full ShadowShop plan (AI mystery shopper for multi-location businesses, USD, US-first) is in `docs/PLAN-2-APPENDIX-SHADOWSHOP.md`. It is the second business to build, or the first if you prefer a dollar-denominated, global product over a faster local one.
