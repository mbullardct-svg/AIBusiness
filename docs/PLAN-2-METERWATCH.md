# MeterWatch — Business Plan for Approval (clean-sheet idea)

**Prepared:** 8 October 2026
**Brief:** a novel, AI-native, agentic, web-based business with nothing in common with BCS, safety, or anything built before. R50,000 per month recurring. Live in 2 days.
**Status:** Awaiting Michael's approval. Nothing bought, deployed or sent.

---

## 1. The call

**Build MeterWatch: an agent that audits a municipal bill the moment it arrives, flags estimated readings, catch-ups and tariff problems, prepares the dispute pack for the customer to lodge, and runs the 30-day clock. For homeowners, landlords, body corporates and managing agents. WhatsApp and email in, dispute pack out. R299 per audit, R249 per scheme per month, 15% of what we recover.**

The customer forwards the e-bill PDF (or photographs the paper bill and the meter) to a WhatsApp number or an email address. The agent reads it, checks the reading type and the consumption against the property's history, recalculates the lines it can prove, flags the problems in plain language and, on a tap, produces the formal dispute in eThekwini's own form with the Municipal Systems Act section 102 wording that stops credit control on the disputed amount, a one-page authority letter where an agent acts for an owner, and the undisputed amount to pay today. The customer lodges it. MeterWatch tracks the 30-day window, prompts the escalation to the Municipal Manager, and keeps the paper trail per property.

Why now and why here: eThekwini estimated 64,147 water meters and 57,024 electricity meters in February 2026 alone. Residential electricity is read quarterly and estimated in between. When the actual reading finally lands, the catch-up is billed at current tariffs. One Durban sectional-title landlord received a backdated R185,000 demand after 18 months of plausible estimates. A Phoenix pensioner was presented with R81,000. City Power credited R136 million to overcharged Johannesburg customers.

Who does this today: consultancies. AuditCheck reviews a residential account for R1,500. OptiRate audits business electricity, water and rates on a percentage of confirmed savings. Council Solutions and Convexx work Johannesburg accounts. All of them are people reading bills by hand, priced for the few who can afford it, and none of them is instant or self-serve. MeterWatch is the same service at a fifth of the price, in minutes, over WhatsApp, with the history kept so the next dispute is stronger than the last.

## 2. What was researched and why this won

Fourteen ideas across three lenses (marketplace apps, global micro-SaaS, South African gaps). The shortlist:

| Candidate | Verdict |
|---|---|
| **MeterWatch (chosen, narrowly)** | Acute, documented, recurring pain. Incumbents are hand-run consultancies at R1,500 a review or on contingency; no instant, self-serve, WhatsApp-first product exists. The trigger is monthly, so the scheme subscription is natural. Buyers cluster: one managing agent brings 10 to 50 schemes. Cheapest to build and lowest legal risk of the shortlist. Honest ceiling: a R15k to R50k a month business on today's evidence, not a venture. |
| **ShadowShop, AI mystery shopper for multi-location businesses (runner-up, full plan in the appendix file)** | Novel with no named competitor, sells in dollars, bigger ceiling, buyers already spend on human mystery shops. Loses on speed and risk: 25 US multi-location accounts sold from Durban with no network, 65% gross margin on voice, voice-detection risk, and its free audit sends unsolicited enquiries to businesses that did not ask. If you want the venture-scale option and accept a slower first rand, this is the one. |
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
- Buyers: homeowners, landlords, body corporates and managing agents. The unit of account is the municipal account, not the flat: a body corporate usually has one bulk account per scheme. Trafalgar manages about 85,000 units in about 1,400 buildings; National Real Estate 10,000 units across 300 schemes; a mid-sized Durban agent runs 15 to 60 schemes. Municipal charges are the largest line in a scheme's budget after insurance and staff.
- Incumbent pricing: AuditCheck R1,500 per residential review; contingency auditors take a percentage of confirmed savings (industry norm 20% to 30%, exact fees unverified); the CSOS levy itself is capped at R40 per unit per month, which is why any per-unit price for a bill check is dead on arrival.
- Tariff changes feed the product: eThekwini 1 July 2026 increases of 12% water, 8% sanitation, 9% electricity, 9.5% refuse, plus the R1.50 per kilolitre infrastructure surcharge to 2029. Every tariff change is a reason to re-check the bill, and most residents cannot.

## 4. Offer and pricing (ZAR, VAT inclusive, Paystack with EFT fallback)

| Plan | Price | Who | Includes |
|---|---|---|---|
| Single Audit and Dispute Pack | R299 once | Anyone with one bad bill | Full audit, dispute form completed, covering letter, evidence list, undisputed amount to pay, 30-day tracker. The lead product, priced against AuditCheck's R1,500 |
| Home | R49/month or R399/year | Homeowners and small landlords | Every bill audited on arrival, estimate and catch-up alerts, meter-photo log, dispute packs included |
| Scheme | R249 per scheme (municipal account) per month | Body corporates and managing agents | Everything in Home per account, bulk-meter reconciliation against unit sub-meters, trustee report, agent white-label, unlimited units |
| Recovery | 15% of the amount credited, capped at R5,000 per dispute | Any customer who wants us to run the dispute end to end | We prepare, the customer signs, we chase and escalate on the 30-day clock. A service fee for our work, not debt collection |

**Path to R50,000 MRR:** 120 schemes at R249 (R29,880) + 200 Home at R49 (R9,800) + 35 Single Audits a month at R299 (R10,465) = R50,145, with recovery fees as upside. 120 schemes is about eight mid-sized agents' portfolios, or three large ones.

**Unit economics:** reading one bill with Claude vision is about R1.50 in model cost. A dispute pack about R3. WhatsApp utility messages about $0.0076 each. Paystack 2.9% + R1. Gross margin above 90% on every line except Recovery, where our time is the cost.

## 5. Why the subscription sticks, and where it does not

Residents churn when the bills come right for a few months. That is why Home is cheap and the lead product is a once-off. The subscription that holds is the scheme: a body corporate's bulk account is large, estimated often, and reconciled against unit sub-meters nobody has time to check. The scheme's consumption history, meter-photo log and dispute trail live in MeterWatch, and that history wins the next dispute. Agents white-label the trustee report and show it at the AGM.

## 6. Product scope for the 48 hours

**Hours 0 to 24: the auditor**
1. Next.js on Vercel, Supabase (auth, Postgres, Storage, row-level security). Repo mbullardct-svg/AIBusiness.
2. Intake: email forwarding address per account (Resend inbound) and web upload on day 1; WhatsApp via 360dialog as soon as the number is verified (partner-led verification is quoted at minutes to 48 hours; unverified numbers can send to 250 unique recipients a day, which is enough for launch).
3. Bill reader: Claude Opus 5.5 vision on the PDF or photo, structured output: account, property, period, each service line, reading type (actual or estimated), previous and current readings, consumption, tariff applied, charges, totals. A confidence score per field; low confidence routes to a quick confirm screen. eThekwini changed its bill layout on 1 December 2024, so there are at least three formats in circulation (old paper and e-bill, new format, eServices screenshots). We collect samples of each before promising extraction on any of them.
4. Tariff engine: eThekwini 2026/27 tables (one published PDF) as versioned data: stepped domestic water by kilolitre block, sanitation, a flat residential energy charge for electricity, refuse, and rates by valuation category, plus the R1.50 surcharge. Recalculate each line and compare to the billed amount. Tariff-mismatch flags stay behind human review until 100 bills have validated the tables. Johannesburg and Cape Town in week 2.
5. Anomaly rules, day 1: estimated reading; catch-up adjustment after a run of estimates; reading sequence error (current lower than previous); consumption more than 1.5x the 6-month median; interest and penalty lines. Behind review until validated: tariff step mismatch, valuation category, VAT. The big-money errors are estimate chains, catch-ups and meter mix-ups, not arithmetic, and the product says so.
6. Dispute pack generator: eThekwini's dispute form fields completed, a covering letter with the specific amounts and grounds, section 102(2) wording, the evidence list (date-stamped meter photo, prior bills), a one-page authority letter where an agent acts for the owner, and, on the front page, the undisputed amount with the instruction to pay it today. The customer lodges. We never submit in our own name until eThekwini confirms its proof-of-authority rules in writing.
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

## 8. Go-to-market (first 60 days)

1. **Ratepayer associations are the channel (week 1):** Westville, Durban North, the eThekwini Ratepayers Protest Movement and the other associations already collect billing complaints over WhatsApp. We give each one a free, branded audit channel for its members. They get a service for members and data for their fight with the city. We get distribution without buying it.
2. **One press relationship (week 1 to 2):** The Mercury and IOL run this story weekly. We give the journalist the first 100-bill audit as data: how many estimated, how many catch-ups, the rand value. That is a story, and it is our launch.
3. **Managing agents through NAMA KZN, not cold email (week 2 to 6):** a branch talk and a free audit of five schemes per agent. Cold email to agents returns 2% to 5% replies; a room of them returns conversations. Trustees decide at meetings, so the scheme plan sells over weeks, not days.
4. **Attorney and conveyancer referrals (week 3 onward):** firms that run municipal disputes refer the small cases to us and take the ones that need court.
5. **Search (week 4 onward):** "ethekwini account query", "estimated reading dispute", "municipal bill too high". South African CPCs range from about R5 to well over R100 depending on the term; we test with R2,000 before committing. Content pages per error type.
6. **Not doing:** posting into community Facebook groups that ban promotion, or marketing in news comment threads. Both get us banned and screenshotted.

## 9. What I need from you (permissions only)

| # | Item | Why | Your time |
|---|---|---|---|
| 1 | Approve the plan, the name MeterWatch and the domain meterwatch.co.za | Nothing starts without it | 5 min |
| 2 | Anthropic API key with billing | Bill reading and dispute drafting | 10 min |
| 3 | 360dialog account with a new WhatsApp number (not one in use on the WhatsApp app) and your Meta Business Manager login | WhatsApp intake and alerts. Start today; verification can take up to 48 hours | 20 min |
| 4 | Paystack account under the entity you choose | Subscriptions. KYC 1 to 5 days; EFT fallback meanwhile | 20 min |
| 5 | Resend account and two DNS records | Inbound bill forwarding and digests | 10 min |
| 6 | Allow durban.gov.za, bylaws.durban.gov.za, joburg.org.za, capetown.gov.za, auditcheck.net, optirate.co.za, api.paystack.co, api.resend.com, waba-v2.360dialog.io in this cloud environment's network settings | Tariff tables, dispute forms, competitor checks and API tests from here. All blocked today | 5 min |
| 7 | Your own eThekwini bills as PDFs or photos, 6 months if you have them, including at least one from before December 2024 and one after | Real test data on hour 1, both bill formats | 10 min |
| 8 | Three friends or neighbours with eThekwini accounts who will forward a bill | Volunteer audits for the sample results | 20 min |
| 9 | Confirm Vercel is on Pro | Cron and inbound processing | 5 min |

## 10. Legal position

- **The customer lodges, not us.** eThekwini's dispute form asks for the account holder's details and ID, and its credit-control policy recognises an agent only as a person the customer has authorised. The pack is prepared by MeterWatch and signed and lodged by the customer, or by their managing agent under a signed authority letter the pack includes. We submit nothing in our own name until the municipality confirms its proof-of-authority rules in writing.
- **Pay the undisputed amount.** A section 102 dispute protects only the specific disputed amount. Disconnections on short notice still happen. Every pack states the undisputed amount on page one with the instruction to pay it now. This is a product rule, not a footnote, because a customer disconnected on our watch is the one risk that ends the business.
- **Not legal practice.** A municipal dispute is an administrative process under the Municipal Systems Act and the by-law, not court proceedings, so Legal Practice Act section 33(1)(b) is not engaged on its wording. No Legal Practice Council ruling exists either way. Court matters go to partner attorneys.
- **Recovery fee is a service fee.** We charge for preparing and chasing the dispute, not for collecting a debt, so the Debt Collectors Act is not engaged. The fee is invoiced against the credit the municipality passes, capped, and never deducted from money we hold, because we hold none.
- **Defamation.** Municipalities as organs of state cannot sue for defamation (Bitou, following Die Spoorbond). Named officials can. Result cards talk about amounts and readings, never people.
- **POPIA.** Account numbers, addresses, ID numbers and consumption data are personal information. Row-level security, encrypted storage, signed expiring links, retention policy, operator clauses for Supabase, Vercel, Anthropic and 360dialog. Information Officer registration and PAIA manual within 30 days.
- **WhatsApp.** Service messages only to people who messaged us first; marketing templates only with consent. Meta's per-message charging from 1 October 2026 is in the cost model.
- **Consumer Protection Act.** Monthly plans cancel on notice; the annual Home plan carries a clear renewal notice.
- **Claims.** "Flags likely errors and prepares your dispute", never "guarantees a refund". A flag is "probable" with its working shown.

## 11. Honest view on the timeline

- **48 hours:** live site, free bill check running, Single Audit and Home plans purchasable, email intake live, WhatsApp live if Meta verifies in time, first audits of our own and volunteer bills published as the sample.
- **Day 14:** 100 to 150 free checks through the ratepayer associations and the press piece, 10 to 15 Single Audits, the first scheme in trial. Cash R3k to R5k. MRR under R1k.
- **Day 45:** 3 to 5 schemes paid, 30 to 40 Home, Recovery fees starting. MRR R2k to R4k.
- **Day 90:** 20 to 30 schemes, about 100 Home, Single Audits running. MRR R10k to R15k plus recovery fees.
- **R50,000 MRR:** month 6 to 8 if the ratepayer-association and NAMA channels work and bulk-account reconciliation proves itself with trustees. If they do not, this settles as a R15k a month business and we say so at day 60.
- **Kill criteria:** free check to paid conversion under 3% by day 30; fewer than 10 paying schemes by day 60; or actionable findings on under 20% of audited eThekwini bills, in which case the problem is smaller than the press says.

R50,000 in two days is not a real number for a new business with real customers, and neither is 90 days on this one. What is real: live and selling in two days, cash from day one, under R5,000 a month in running cost, the lowest legal risk on the shortlist, and a customer in your own city who is in the newspaper every week. If you want the bigger, slower, dollar-denominated bet instead, it is ShadowShop in the appendix.

## 12. Risks

| Risk | Handling |
|---|---|
| eThekwini tariff tables are wrong or out of date in our engine | Versioned tables with effective dates, sourced from the published tariff booklet; each recalculation shows its working; a flag is "probable", never "certain" |
| Bill formats vary (pre and post December 2024 eThekwini layouts, eServices screenshots, other metros later) | Vision model with per-field confidence and a confirm screen; samples of each format collected before launch; eThekwini-only on day 1 |
| A wrong "you were overcharged" flag gets taken to a Sizakala centre and screenshotted | Day-1 flags limited to the error classes we can prove from the bill itself; tariff recalculation behind human review for the first 100 bills; every flag shows its working and says "probable" |
| A customer withholds payment on our pack and is disconnected | Undisputed amount on page one with "pay this today"; the pack never advises withholding anything but the specific disputed amount |
| Municipality ignores disputes | The product's value is also protection: a lodged section 102 dispute stops credit control on that amount, and the paper trail is what wins at escalation and in court. We say so plainly |
| WhatsApp verification slips past 48 hours | Email forwarding and web upload carry launch; WhatsApp joins when approved |
| Paystack KYC slips | EFT invoicing from day 1 for agents and body corporates; Single Dispute by EFT or Paystack test-to-live switch |
| Municipality fixes estimated billing (automated meter reading rollout announced) | Rollout is years out; even with smart meters, tariff errors, catch-ups, interest and rates disputes persist; expansion to Johannesburg and Cape Town diversifies |
| AuditCheck, OptiRate or an attorney firm ships a self-serve version | They are consultancies priced on labour; our cost per audit is under R5. We move first, partner with the attorneys for the court cases, and hold the per-property history |

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
- Incumbents: https://www.auditcheck.net/ , https://optirate.co.za/ , https://www.councilsolutions.co.za/ , https://www.convexx.co.za/
- Bill format change December 2024: https://iol.co.za/news/south-africa/kwazulu-natal/2025-04-17-new-ethekwini-billing-format-aims-to-simplify-resident-experience/
- 2026/27 tariff tables PDF: https://www.durban.gov.za/uploads/0000/13/2026/06/22/eth-final-2026-2027-tariff-tables.pdf
- Credit control policy (agent definition): https://www.durban.gov.za/uploads/0000/6/2025/09/24/credit-control-and-debt-collection-policy-2023-2024.pdf
- Ratepayer associations collecting billing complaints: https://www.citizen.co.za/north-glen-news/news-headlines/local-news/2025/08/06/durban-north-residents-urged-to-join-forces-on-billing-discrepancies/
- Municipalities and defamation: https://acts.co.za/news/blog/2015/06/free-speech-upheld-in-defamation-case-brought-by-bitou-municipality
- Competitive scans for the rejected ideas: https://apps.shopify.com/kwik-geo-1 , https://www.xero.com/media-releases/xero-announces-new-ai-innovations-xerocon-london/ , https://pickyourapp.com/products/customs-guard , https://www.mrisoftware.com/za/products/rentbook/

## Appendix B: the runner-up

The full ShadowShop plan (AI mystery shopper for multi-location businesses, USD, US-first) is in `docs/PLAN-2-APPENDIX-SHADOWSHOP.md`. It is the second business to build, or the first if you prefer a dollar-denominated, global product over a faster local one.
