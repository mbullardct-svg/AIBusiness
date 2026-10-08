# ShadowShop — Business Plan for Approval (Idea 2, clean sheet)

**Prepared:** 8 October 2026
**Target:** R50,000 per month in recurring revenue from an AI-native, agentic, web-based business with no connection to BCS, safety, or anything we have built before
**Status:** Awaiting Michael's approval. Nothing bought, deployed or sent.

---

## 1. The call

**Build ShadowShop: an AI mystery shopper that tests every location of a multi-site business every week, by phone, web form and email, and scores how each one handles a new customer.**

A franchisor, dental group, law firm, estate agency, gym chain or home-services brand pays today for human mystery shops at roughly $8 to $20 per phone shop for retail and $50 to $200 per shop for professional and compliance work, delivered as a quarterly sample of a few locations. Franchise research shows 35% of brands never respond to a new enquiry at all and the average email response takes nearly nine hours, while the cost of a franchise lead has risen to $271. Nobody is measuring that leak continuously, because humans are expensive and slow.

ShadowShop's agent places a realistic enquiry to each location on a schedule the owner sets. By phone it is a voice agent posing as a prospective customer with a vertical-specific scenario. By web form and email it is a scripted enquiry. Every interaction is transcribed and scored by Claude against the owner's rubric: time to answer, time to respond, greeting, needs discovery, price and availability handling, booking attempt, follow-up, tone. The owner gets a per-location scorecard, the transcript, a coaching note for the manager, and a weekly league table. Because the shopping is recurring by nature, the subscription is natural: cancel and the measurement stops.

Research found no startup that does this end to end. The closest are tools that score a business's own inbound calls after the fact (Call Box, Car Wars, Retell QA, Cresta) and one role-play simulator (FireCoach). Human mystery-shopping firms are a $200-per-shop industry (IBISWorld 2026 benchmark) with no automation of the shop itself.

## 2. Why this and not something else

Fourteen candidates were researched today. The ones that reached a shortlist and why they lost:

| Candidate | Verdict |
|---|---|
| **AI mystery shopper (chosen)** | Novel (no named competitor), agentic and recurring by nature, global in USD, buyers already pay for the human version, buildable in 48 hours on Vapi plus Claude, legal path clear when the buyer owns the locations being tested. |
| AI search visibility app for Shopify merchants | Nine new apps already in the category (Kwik GEO, FoundGPT, Visibility Mesh, Mento, SearchMention and others). Shopify App Store review takes 2 to 7 weeks, so not live in 48 hours. Not novel. |
| Weekly AI CFO memo from Xero | Xero's own JAX agent shipped payment follow-ups, reconciliation and anomaly flags in 2026. Platform risk kills it. |
| AI debt-chasing agent for SMEs | Paidnice, LeanPay, Chaser exist, and Xero JAX now does payment follow-ups natively. |
| Self-managing landlord app for SA | MRI Rentbook is free for independent landlords. Price floor is zero. |
| AI procurement agent that gets three quotes | Genuinely open for very small buyers, but supplier response rates are unproven and the sales cycle is slow. Kept as a reserve idea. |
| AI customer-interview tool for SMBs | Enterprise players (Outset, Listen Labs, Conveo at $1,250/mo) above, Koji at €29 below. Squeezed. |
| AI legal letters for SA consumers | Legal Practice Act section 33 is unresolved for paid non-lawyer drafting. Not a 48-hour risk to take. |
| Agentic synthetic shopper for Shopify checkout QA | Uptime leads with 31 reviews after years; Shopify's SimGym signals native encroachment. Small. |

## 3. Market evidence (today's research)

- Mystery shopping is an established spend: about 4,000 firms worldwide; IBISWorld's 2026 US benchmark price is $209 per shop; phone shops for multi-site retailers run $8 to $20 each before reporting fees; a 200-store brand budgets $80,000 to $180,000 a year.
- The problem is measurable and ugly: 35% of franchise brands never respond to an inquiry; average email response 8.8 hours; best-in-class respond under 60 seconds (FranFunnel Q1 2025). Franchise Update's 2024 mystery shop found half of brands contacted never followed up a lead.
- Lead cost makes the leak expensive: franchise cost per lead rose from $97 (2021) to $271 (2024). Legal intake leads cost $50 to $150 each. A dental new-patient call is widely cited as worth thousands over the patient's lifetime.
- Voice agent costs have collapsed: Vapi and Retell run about $0.10 to $0.30 per minute all-in, with instant US number provisioning via Twilio. A three-minute shop costs under a dollar.
- Buyers already accept AI scoring: Call Box and Car Wars sell AI scorecards of inbound calls to dental practices and dealerships at a premium over human $40 to $50 per-call shops.
- No competitor found that places the shop itself with an agent across phone, form and email and reports continuously.

## 4. Who buys, and the first two beachheads

**Buyer:** the owner, COO or franchise development director of a business with 5 to 200 locations or intake points who is spending on lead generation and cannot see what happens when the phone rings.

**Beachhead 1: US dental groups and DSOs.** 5 to 50 practices, already buying call scoring, obsessed with new-patient conversion. Scenario library: new patient enquiry, insurance question, emergency, price shop.

**Beachhead 2: US and UK home-services and fitness franchises.** Franchisors need brand-standard compliance across franchisees and have no cheap way to measure it. Scenario library: quote request, availability, upsell, membership enquiry.

**South Africa (month 2):** estate agencies, car dealers, medical groups, franchise groups. Needs a South African number via Twilio's regulatory bundle or a local SIP carrier, which takes days, so it is not in the 48 hours.

Law firms are attractive (intake is worth $50 to $150 a lead) but posing as a client may raise professional-conduct questions in some bars; we take advice before opening that vertical.

## 5. Offer and pricing (USD, charged in ZAR equivalent via Paystack until a merchant-of-record is approved)

| Plan | Price | Includes |
|---|---|---|
| Starter | $99/mo | Up to 5 locations, 1 phone shop + 1 form or email shop per location per week, standard scenarios, scorecards, weekly email |
| Growth | $249/mo | Up to 15 locations, 2 phone shops per location per week, custom scenarios and rubric, manager coaching notes, league table, CSV export |
| Brand | $29 per location per month, minimum $499 | Unlimited locations, franchisee-level logins, brand-standard rubric, monthly board report, API |
| One-off Audit | $199 | 10 locations shopped once by phone and form, full report in 48 hours. The lead magnet that converts to a plan |

**Path to R50,000 (about $2,700) MRR:** 6 Growth ($1,494) + 2 Brand at 20 locations ($1,160) + 1 Starter ($99) = $2,753. Or 11 Growth accounts. That is roughly 25 multi-location customers across two verticals.

**Unit economics:** a phone shop costs about $0.60 in voice minutes plus $0.05 in Claude scoring. A Growth account at 15 locations and 2 shops a week is 120 shops, about $80 a month, against $249. Gross margin about 65% on Growth, higher on Brand, above 90% on form and email shops. Twilio numbers $1.15 a month each; we rotate a pool so locations do not learn the number.

## 6. Why the subscription sticks

The shop is a measurement, and measurements only matter as a trend. Week 6 tells you whether the coaching worked. Franchisors tie it to brand-standard compliance. Dental groups tie it to the new-patient number. The moat over time is the scenario and rubric library per vertical, the benchmark data ("you answer in 48 seconds, the top quartile answers in 12"), and the location-level history nobody else holds.

## 7. Product scope for the 48 hours

**Hours 0 to 24: the shopper**
1. Next.js on Vercel, Supabase (auth, Postgres, Storage), repo mbullardct-svg/AIBusiness.
2. Data model: accounts, locations (phone, web form URL, email, timezone, opening hours), scenarios (vertical templates plus custom), rubrics, shops, transcripts, scores, schedules.
3. Phone shops via Vapi: outbound call API, scenario persona prompt, end-of-call webhook delivering transcript and recording URL. Twilio US number pool. Calls land inside the location's opening hours in its timezone.
4. Form and email shops: Playwright fills the location's contact form with a tracked alias; Resend inbound catches replies; time-to-first-response and reply quality are measured over 72 hours.
5. Scoring: Claude Opus 5.5 scores each transcript against the rubric with structured output (per-criterion score, evidence quote, coaching note). A second pass flags anything that looks like the agent was detected or the call failed, so those are excluded from scores.
6. Dashboard: locations, latest scores, trend, transcript viewer, coaching notes.
7. First real shop run against three volunteer businesses by hour 12.

**Hours 24 to 48: the business**
8. Scheduler: weekly cadence per plan, randomised times, Vercel cron plus a job table.
9. Paystack plans in test mode (card, 3D Secure, international cards accepted), plan entitlements, EFT fallback for South African customers. Price display in USD.
10. One-off Audit flow: pay, upload 10 locations, report in 48 hours. This is the self-serve lead magnet.
11. Weekly email report with league table (Resend). Manager-facing coaching note per location.
12. Landing page, pricing, sample report, terms (buyer confirms it owns or controls the locations and has notified staff that calls may be monitored for quality), privacy.
13. Custom domain. Compliance guardrails in code: calls only to numbers the buyer registered, only within opening hours, never to numbers on the buyer's exclusion list, recording off by default in all-party-consent states (transcript only), no voice shops to any business that has not signed up.

**Deferred to week 2:** SA numbers and local-language scenarios, WhatsApp shops, chat-widget shops, franchisee logins, benchmark reports, API, Stripe or Paddle in USD once approved.

## 8. Go-to-market (first 30 days, no personal network required)

1. **Free Response Audit (web form and email only, no calls):** a public page where anyone enters a business name and we submit a tracked enquiry to its public contact form and email, then show response time against the benchmark. Costs us nothing, breaks no law, produces a shareable result. This is the engine.
2. **Benchmark content:** "We enquired at 200 US dental practices. 41% never replied." Published on the site, posted to dental practice-management groups, franchise forums, r/dentistry, LinkedIn. Numbers come from our own audits.
3. **Paid search on buyer intent:** "mystery shopping company", "phone mystery shopping", "secret shopper service for franchises", "dental phone training", "speed to lead". Human mystery-shop firms bid these; we undercut on price and frequency.
4. **Directories:** IFA supplier directory, dental DSO supplier lists, franchise supplier marketplaces. Listings are cheap and buyers search them.
5. **Partners:** dental and franchise consultants who sell phone training. The weekly score is proof their training worked. Revenue share.

## 9. What I need from you (permissions only)

| # | Item | Why | Your time |
|---|---|---|---|
| 1 | Approve the plan, the name ShadowShop and the domain shadowshop.ai ($160 for 2 years) | Nothing starts without it | 5 min |
| 2 | Anthropic API key with billing | Scoring and scenario generation | 10 min |
| 3 | Vapi account (or Retell) with a card on file, and a Twilio account | Voice shops and number pool. Both are instant signups | 20 min |
| 4 | Paystack account under any entity you choose, with international cards enabled | USD-priced subscriptions charged in ZAR until Paddle approves us | 20 min |
| 5 | Resend account and two DNS records | Weekly reports and inbound email shops | 10 min |
| 6 | Allow api.vapi.ai, docs.vapi.ai, api.twilio.com, api.paystack.co, api.resend.com in this cloud environment's network settings | So I can test from here | 5 min |
| 7 | Vercel Pro confirmation | Cron and long functions | 5 min |
| 8 | Three businesses you know (any kind, anywhere) who will let us shop them for free this week | First real calls and the sample report | 30 min |

## 10. Legal position

- **Consent:** the buyer registers the locations, confirms it owns or controls them, and confirms staff have been told calls may be monitored for quality. That is how every human mystery-shopping programme works. We never place a voice call to a business that has not signed up. The free audit uses web forms and email only.
- **Recording:** US all-party-consent states (California, Florida, Illinois and others) get transcript-only mode by default; audio is retained only where the buyer confirms single-party or has a staff notice in place. South Africa's RICA allows a party to the call to record; the buyer is effectively a party through its own line, but we still default to transcript-only.
- **AI disclosure:** US TCPA restricts artificial-voice marketing calls; a quality test commissioned by the business receiving the call is not marketing and is not to a consumer. California's AB 2905 covers prerecorded messages, not live conversational agents. Utah's law is consumer-facing. EU AI Act Article 50 requires disclosure on first interaction; we do not launch in the EU until that flow exists. Counsel reviews the terms before launch.
- **Law firms:** vertical held back until we have bar guidance on simulated client enquiries.

## 11. Honest view on the timeline

- **48 hours:** live site, free Response Audit running, paid Audit and plans purchasable, voice shops working on US numbers, one sample report published.
- **Day 14:** 200-practice benchmark published; first 3 to 5 paying accounts from the audit funnel and paid search. MRR $300 to $1,000.
- **Day 60:** 10 to 15 paying accounts, MRR $1,500 to $2,500, if the free audit converts at 3% to paid audit and paid audits convert at 30% to plans. Those are assumptions, not data.
- **Day 90 to 120:** R50,000 (about $2,700) MRR base case. Stretch at day 60 if one franchisor signs a Brand plan.
- **Kill criteria:** free audit conversion under 1% by day 30, or voice shops detected as AI in more than 15% of calls, or paid audit buyers not converting to any plan by day 45.

R50,000 in two days is not a real number for a new business with real customers. Live and selling in two days is. The difference from the first plan: this one has a zero-cost, legally clean, self-serve acquisition engine that does not depend on your contacts, and it sells in dollars.

## 12. Risks

| Risk | Handling |
|---|---|
| Staff detect the AI voice and the shop is void | Current voice models pass short enquiry calls routinely; we measure detection rate per call and exclude detected calls from scores; form and email shops carry the product if voice underperforms |
| A buyer uses us to harass a competitor | Voice shops only to registered, verified locations; verification by calling the location's listed number with a confirmation code or by email domain match |
| Paystack declines a US card or the ZAR conversion confuses buyers | Show USD, state the ZAR charge on the checkout, apply for Paddle on day 1 so USD billing follows |
| Vapi or Twilio account limits on a new account | Start on form and email shops, scale voice as limits lift; keep Retell as a second provider |
| Mystery-shop incumbents add AI | They are services businesses with human shopper networks; the cannibalisation problem is theirs. We move faster and price per location, not per shop |
| Nobody searches for this because the category does not exist | We sell against the budget that does exist (mystery shopping, phone training, speed-to-lead) and lead with the free audit, not the category name |

## 13. Decision requested

Approve the name, the domain, the stack and the pricing. Reply "go" and supply items 2 to 5 in section 9 as you get to them. Build starts with the voice shop and the scoring engine, because that is the part that has to be convincing by hour 12.

---

## Appendix: sources used today

- Franchise response benchmarks: https://www.franfunnel.com/answers/how-quickly-should-ai-respond-to-franchise-leads and https://www.franchising.com/articles/mystery_shopping_24_researchers_investigate_first_contact_with_potential_fr.html
- Mystery shopping pricing: https://trocglobal.com/mystery-shopping-cost/ , https://www.outsourceaccelerator.com/glossary/mystery-shopping/ , https://www.ibisworld.com/united-states/procurement/mystery-shopping-services/53965161
- AI call scoring incumbents: https://www.callbox.com/resources/dental/a/transform-your-practices-phone-proficiency-with-the-introduction-of-ai-mystery-shop-scorecard.cfm , https://carwars.com/main/resources/elevate-your-teams-phone-performance-with-mystery-shop-scorecard-for-service/ , https://firecoach.ai/tools/ai-mystery-shopper
- Voice agent costs and numbers: https://ainora.lt/blog/ai-voice-agent-cost-per-minute-2026 , https://twilio.com/en-us/phone-numbers
- Legal: https://tcpaworld.com/2023/05/12/b2b-update-here-is-a-quick-tcpa-primer-on-calling-business-phones/ , https://apcp.assembly.ca.gov/system/files/2024-04/ab-2905-low-apcp-analysis.pdf , https://www.dwt.com/blogs/artificial-intelligence-law-advisor/2024/04/utah-enacts-ai-and-bot-business-disclosure-law
- Shopify marketplace timing and GEO competition: https://community.shopify.dev/t/unlisted-shopify-app-review-required-before-installation/33101 , https://apps.shopify.com/kwik-geo-1
- Xero JAX: https://www.xero.com/media-releases/xero-announces-new-ai-innovations-xerocon-london/
