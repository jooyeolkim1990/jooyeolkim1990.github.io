# Moral AI, Gated Access

## Anthropic and the Access Order Behind Safety Rhetoric
**Companion tracking note:** [Anthropic Access-Structure Tracking](../log/2026-04-26-anthropic-access-structure-tracking.md)

---

Anthropic sells a posture.

Claude is not presented as another text box for answers, code, summaries, or drafts. It is presented as a different kind of AI relationship: safer, more careful, more principled, more aligned with the user than with the usual incentives of the consumer internet.

That posture now does operational work.

The cheap critique is hypocrisy. A moral AI company enters the market, needs compute, needs revenue, needs enterprise customers, and eventually compromises. That version is easy because it is already familiar.

The sharper point is different.

Moral language structures access.

Safety language does not only restrain. It justifies controlled release. User-alignment language does not only protect users from bad incentives. It makes opaque rationing easier to trust. A company can speak sincerely and still normalize a new access order.

Sincerity is the wrong test.

The structural question is simpler:

> What kind of AI order does Anthropic’s moral posture help make normal?

The answer is not open or closed.

It is moralized, tiered, throttled, and gated.

---

## Track Choices, Not Motives

Anthropic’s hidden motive is unavailable. Its public structure is not.

Intention remains a black box. Repeated public choices do not.

Track the visible sequence: public claims, usage structures, product-access disputes, postmortems, safety-policy language, and release channels for high-value capability. A confusing pricing page can be an accident. A degraded product release can be a mistake. A revised safety policy can respond to competition. A gated model release can serve a defensive purpose.

One event proves little.

The sequence matters.

The pattern is not hidden. It is visible enough. The problem is that it is usually described in separate languages: product limits, safety policy, cybersecurity partnership, national security, and investor credibility.

Anthropic’s moral branding, usage rationing, product discretion, self-regulation language, and partner-gated access keep reinforcing the same structure: broad trust language at the surface, controlled access beneath it.

That is access-structure tracking, not motive-reading.

Anthropic can genuinely want safer AI. It can genuinely reject advertising incentives. It can genuinely believe restricted access beats broad release.

Those beliefs do not dissolve the access order.

They help build it.

---

## Claude as an Ad-Free, User-Aligned Space

Claude’s consumer brand begins by rejecting the ad market.

Anthropic says Claude will remain ad-free because advertising incentives are incompatible with the assistant it wants Claude to be: useful for work and deep thinking. It also says users will not see sponsored links in Claude conversations, and that Claude’s responses will not be influenced by advertisers or include unrequested third-party placements. ([Anthropic][1])

That is moral positioning.

Claude is framed less as ad inventory than as a thinking environment. The user is addressed as someone whose attention should not be sold, whose work should not be interrupted by sponsored influence, and whose relationship with the assistant should not be redirected toward advertisers.

The user is first protected from the incentives of the market.

Anthropic’s public dispute with the Department of War strengthened that posture. Dario Amodei identified two red lines: mass domestic surveillance and fully autonomous weapons. Anthropic later clarified that those objections concerned high-level usage areas, not ordinary military operational decision-making. ([Anthropic][2]) The Guardian reported that Claude surged in app rankings after the Pentagon dispute, reaching No. 1 on Apple’s U.S. free-app chart. ([The Guardian][3])

Public support does not prove moral superiority. It shows something narrower: Anthropic’s moral posture became a consumer-facing asset.

Claude became readable not only as a capable assistant, but as the assistant that refused certain incentives and certain uses.

That trust posture matters because the next layer is not moral freedom.

It is managed access.

Claude can be ad-free and usage-budgeted. It can reject sponsored links while retaining opaque throttling. It can protect users from one market incentive while placing them inside another access system.

The consumer is morally elevated before the product operationally rations access.

---

## The User as Variable Load

Claude turns access into a managed capacity system.

That system has a technical basis. Frontier models run on scarce compute, fluctuating demand, product experiments, and plan-based access rules. No serious consumer AI service promises infinite use to every user at every moment.

Necessity does not erase the governance problem.

Anthropic asks users to trust Claude as a more aligned, less extractive, more respectful assistant. Claude is framed as an ad-free space for work and thinking, not as another engagement surface built around advertiser incentives.

The operational layer speaks another language.

Claude access is shaped by message length, file size, conversation length, tool use, model choice, artifact use, session windows, weekly limits, and paid-plan settings. Anthropic’s own help material says usage varies by plan and by those additional factors, and that paid users can monitor five-hour session and weekly usage limits in settings. ([Claude Help Center][4]) File creation draws from the same plan limits and uses more of the limit than normal chat. ([Claude Help Center][5])

A user buys a plan without buying a fixed quantity of usable work.

Access is not granted once. It is continuously rationed.

The user is not buying a fixed object. The user is buying entry into a capacity environment whose practical limits move with system cost, product surface, session length, and company discretion.

Peak-hour management makes the elasticity visible. In March 2026, reporting on Claude usage changes said users would move through five-hour session limits faster during weekday peak hours, while weekly limits remained unchanged. The same report said the change surfaced through an engineer’s post on X rather than a formal company announcement, and that about 7 percent of users would hit limits they otherwise would not have hit. ([TechRadar][6])

The product still appears as the same Claude. The plan name remains familiar. The reset window remains recognizable. The usable experience changes underneath.

That is low-legibility access.

Anthropic did not invent this. OpenAI and Google also impose caps, vary access, and adjust limits. The point is not uniqueness. The point is tension. Anthropic’s consumer-facing moral posture is unusually strong, while its access structure remains elastic, complexity-dependent, and only partially legible from the outside.

A user can be promised a cleaner moral relationship with AI while still being placed inside a discretionary capacity-management system. The company can refuse to turn the user into an ad target while still treating the user as a variable unit of demand.

That is why “user-aligned” needs an operational test.

User alignment cannot mean only that Claude avoids sponsored links. It also has to face the terms of access: how much usable work users receive, how stable the plan is, and when the service quietly throttles use.

Flexible limits keep the service usable for more people. They also increase the amount of invisible rationing users must trust.

Anthropic’s moral brand makes that trust easier to ask for.

> Users are morally addressed as persons, but operationally managed as variable load.

Claude can be ad-free. Claude can avoid some of the worst incentives of consumer AI. Claude can be safer than alternatives.

Consumer access is still tiered, throttled, and partly opaque.

That is where the access order begins.

---

## Bugs Can Be Fixed. Business Models Have to Be Defended.

Product incidents make accountability look easier than it is.

Claude Code’s quality degradation became a bounded incident. Anthropic traced the problem to three product-layer changes: a default reasoning-effort change, a cache bug that repeatedly cleared older thinking from idle sessions, and a system-prompt instruction that reduced verbosity but hurt coding quality. The company said the changes had been reverted or fixed by April 20 and that it was resetting usage limits for all subscribers. ([Anthropic][7])

That response worked because the problem could be named.

Anthropic named causes. It named fixes. It made the incident legible.

The postmortem also revealed the deeper lesson. The problems were not random model decay. They came from product decisions around latency, token use, verbosity, and the tradeoff between intelligence and usability. Anthropic said lowering the default reasoning effort reduced latency but was “the wrong tradeoff”; it also said a short-answer prompt caused an outsized quality drop and was later reverted. ([Anthropic][7])

The model did not simply “get worse.” Product optimization changed how intelligence appeared to users.

That kind of failure has a rollback path. Anthropic can say: we changed the default effort, then reverted it; we shipped a cache optimization with a bug, then fixed it; we added a harmful prompt line, then removed it. The incident has a timeline, a cause, and a repair story.

A confusing pricing page works the same way. Copy can be corrected. An experiment can be clarified. A notice can be improved. Users may stay frustrated, but the problem remains bounded.

Usage-cap opacity belongs to another category.

It is not a bad prompt, a cache bug, a confusing page, or a degraded release. It is part of the access model itself. Claude is sold as a service whose value depends on how much usable work a person gets from it. That usable work is shaped by plan limits, model cost, conversation length, file attachments, tool use, feature use, peak-hour management, and company discretion.

There is no clean rollback for that.

A company can apologize for a bug. It can correct a pricing page. It can reset limits after a degraded release.

It cannot easily apologize for retaining discretionary control over access without weakening the subscription model itself.

The Claude Code postmortem therefore sharpens the access-structure issue. The quality incident was legible because Anthropic converted it into an engineering story. Usage caps are less legible because they are not engineering failure. They are how the service is rationed, stabilized, and monetized.

From the outside, users do not always know whether a worse session came from a model problem, a product harness change, a prompt change, a context-management bug, a lower effort setting, a usage-budget interaction, or capacity pressure.

The experience collapses into one sentence:

> The product I paid for no longer behaves the way I expected.

That is where responsibility becomes difficult to recover.

Product incidents can be postmortemed. Access discretion has to be justified again and again.

Or, more sharply:

> Anthropic can say “we fixed the bug.”
> It cannot as easily say “we fixed the business model.”

---

## Self-Regulation Turns Boundaries Into Process

Anthropic’s safety language allocates discretion.

It does not only describe risk. It defines what kinds of continuation remain legitimate: stop, delay, report, restrict, review, gate, or release.

The key question is what kind of constraint the language creates.

A hard self-binding rule limits action. A managed process preserves action under conditions.

That distinction became sharper after Anthropic revised its Responsible Scaling Policy. TIME reported in February 2026 that Anthropic was dropping the central pledge from its earlier RSP: the commitment not to train an AI system unless it could guarantee in advance that safety measures were adequate. The revised framework emphasized transparency, risk reports, safety roadmaps, and competitor-contingent reasoning instead. ([TIME][8])

Anthropic’s argument matters. Unilateral restraint can fail if less cautious developers keep advancing with weaker safeguards. The least restrained firms can set the pace, while more cautious firms lose the ability to do safety work at the frontier.

That argument also changes the constraint.

The older logic was closer to a hard-stop pledge: if adequate mitigations were not in place, the company would not proceed above certain risk levels. The newer logic is closer to managed-delay governance: evaluate, report, compare, mitigate, delay when necessary, and preserve room to continue.

A hard-stop rule creates a bright boundary. A managed-delay framework creates a process.

The process can be serious. It can improve transparency. It can generate useful safety work. It still changes the center of gravity.

The structure moves from:

> We cannot proceed unless the boundary is satisfied.

to:

> We can proceed if risk is assessed, mitigated, reported, and compared.

That is not a small shift.

Policy language defines what remains institutionally possible. It helps determine whether a high-risk capability is stopped, delayed, released, restricted, partner-gated, or folded into a risk-reporting regime.

The key issue is not that Anthropic abandoned safety. The form of safety commitment changed.

Once risk no longer triggers a clean stop, the practical question becomes access: who gets the capability, under what conditions, through which channels, with what reporting, with what review, and with what ability for outsiders to contest the judgment?

The consumer layer already showed elastic access. The product layer showed bounded accountability for incidents. The self-regulation layer adds a higher-level grammar: controlled release remains legitimate if it is wrapped in process.

The revised RSP is therefore not only an internal safety document. It is a governance document. It translates frontier capability from a binary question — stop or proceed — into a procedural question: report, mitigate, review, gate, and continue.

That process moves responsibility into procedure.

The more self-regulation becomes procedural, the more safety depends on whether those procedures are legible, contestable, and binding enough to matter.

The policy language does not merely describe safety. It helps define when controlled release remains available as a legitimate option.

Once a hard stop becomes managed delay, access governance becomes the real safety architecture.

---

## Mythos / Glasswing: Capability Through Partner Gates

Claude Mythos Preview is the operational test case.

Anthropic’s new safety grammar becomes concrete in Project Glasswing.

Anthropic describes Project Glasswing as an effort to secure critical software with early access to Claude Mythos Preview, “our most capable model yet.” The important detail is the gate. Access went to selected cloud, security, enterprise, and infrastructure actors, plus more than 40 additional organizations that build or maintain critical software infrastructure. ([Anthropic][9])

The structure is the story.

Mythos is not withheld in an absolute sense. It is not released to ordinary users either. It is routed into a selected-access channel: defensive security partners, critical infrastructure maintainers, and large organizations with security responsibilities.

Cybersecurity gives that choice its strongest defense. The same capability can help defenders find vulnerabilities before attackers exploit them. Anthropic frames Project Glasswing as defensive: give major infrastructure defenders a head start, help them find and fix vulnerabilities, and share lessons with the broader industry. Partners receive access for vulnerability detection, binary testing, endpoint security, and penetration testing, with Anthropic planning to report publicly within 90 days on lessons and disclosed fixes. ([Anthropic][10])

The affected surface is global. The repair circle is selective. Project Glasswing treats vulnerability as a collective problem while routing high-value defensive capability through a selected circle of trusted partners. Those outside the circle remain part of the risk environment, but not part of the access structure.

Defensive purpose does not remove the governance problem.

It relocates it.

The question is no longer only whether the model is released. It is how the model is released, to whom, under what controls, and with what failure modes.

The sensitivity of Mythos is not speculative. Anthropic’s red-team writeup says non-experts can use Mythos Preview to find and exploit sophisticated vulnerabilities, including cases where Anthropic engineers without formal security training produced complete working exploits overnight. Anthropic also says Mythos Preview is “in a different league” from Opus 4.6 on autonomous exploit development. ([Red Anthropic][11])

External evaluation points the same way. The UK AI Security Institute said Mythos Preview represented a step up over previous frontier models in cyber capability. On expert-level capture-the-flag tasks, Mythos Preview succeeded 73 percent of the time. It also became the first model to solve AISI’s 32-step corporate network attack simulation, “The Last Ones,” from start to finish in 3 out of 10 attempts; AISI estimated that the task would require human professionals about 20 hours. ([AI Security Institute][12])

Mythos matters because release conditions matter directly in this domain. A capability that helps defenders patch critical infrastructure can help attackers discover or exploit weaknesses under other conditions.

Anthropic’s answer is gated access.

That can be the right decision. It is still a gate.

The RSP shift becomes concrete here. Once hard-stop logic gives way to managed delay, risk does not automatically produce non-release. It produces reports, redactions, external review, selected access, vendor environments, and partner channels.

Safety does not stop access. Safety organizes access.

Restricted release does not remove a dangerous capability from the world. It creates a privileged circulation channel around it. The public sees restraint. Selected partners receive access. Safety becomes the language through which circulation is narrowed, not stopped.

Anthropic’s own API documentation says Claude Mythos Preview is offered separately as a research preview for defensive cybersecurity workflows through Project Glasswing, with invitation-only access and no self-serve sign-up. ([Claude API Docs][13]) That is the structure in miniature: not public, not absent, selectively available.

The unauthorized-access reports expose the gate itself. Reuters, citing Bloomberg, reported on April 21, 2026, that a small group of unauthorized users accessed Mythos. Reuters also quoted an Anthropic spokesperson saying the company was investigating a report of unauthorized access through a third-party vendor environment. ([Reuters][14])

That report establishes one point:

Partner-gated release has its own attack surface.

That is the strange politics of the gate. Many legitimate downstream stakeholders remain outside the selected circle, while the gate still creates paths that can fail through vendors, permissions, and contractor environments. Exclusion and leakage are not opposites here. They are two governance failures produced by the same access infrastructure.

A restricted-access model does not only need model safety. It needs access-infrastructure safety: vendor security, permission hygiene, monitoring, revocation, auditability, and responsibility recovery when the gate is bypassed.

The model was not simply released.
The model was not simply withheld.
It was reorganized into a partner-gated access structure.

The safety question changes with it.

> Can Anthropic make the model safe enough?

becomes:

> Can Anthropic make the access order safe enough?

That difference is the essay’s core.

If frontier capability is governed through selected access rather than hard non-release, the gate becomes part of the safety system. Partner lists, vendor environments, permission chains, monitoring tools, redaction decisions, risk reports, and review channels stop being secondary operational details.

They become the governance surface.

Mythos is moralized access governance at the frontier.

The capability is justified through defensive purpose.
The distribution is structured through trusted partners.
The policy language allows managed release.
The unauthorized-access reports show that the gate itself can become a site of risk.

Restricted release is not restraint.

It is action through a narrower channel.

Partner-gated release does not eliminate risk. It relocates risk into the access infrastructure itself.

The national-security sequence makes the point sharper without requiring motive-reading. Anthropic’s dispute with the Department of War showed moral refusal at one gate: mass domestic surveillance and fully autonomous weapons remained red lines. ([Anthropic][15]) The Department of War then designated Anthropic a supply-chain risk. ([Anthropic][16]) After Mythos was announced, Reuters reported that Anthropic was discussing Mythos with the Trump administration; Reuters, citing Axios, later reported that the NSA was using Mythos despite the blacklist; and Trump then said Anthropic was “shaping up” and that a Pentagon deal could be possible. ([Reuters][17]; [Reuters][18]; [Reuters][19]) The confirmed record does not show that Mythos was designed as a route back into government favor. It shows something structurally important: Anthropic could be too restrictive for one military contract and too useful to ignore in another security domain.

---

## IPO Pressure Makes the Access Order Investor-Legible

IPO pressure does not create the access order.

It makes the access order easier to sell.

A possible Anthropic IPO turns the pattern into an investor-readable story: enterprise adoption, infrastructure partnerships, regulatory credibility, durable revenue, security leadership, reputational trust.

Reuters reported in April 2026 that SpaceX, OpenAI, and Anthropic could help produce the largest IPO wave in history, with the three companies potentially adding $3 trillion in combined market value while remaining unprofitable. Reuters also reported that Anthropic had been valued at $380 billion in a February funding round. ([Reuters][20])

That environment rewards a specific frontier-AI story: fast growth, high capability, controlled risk, institutional buyers, and a credible moral brand.

The access logic predates the IPO runway.

Frontier AI already depends on scarce compute, cloud distribution, enterprise integration, safety review, cybersecurity concerns, usage-based economics, and controlled capability channels. These pressures are not cosmetic. They shape what kind of AI business can exist at the frontier.

Anthropic’s expanded AWS relationship shows the material layer. AP reported that Anthropic agreed to commit more than $100 billion to Amazon’s AWS cloud platform over ten years to train and run Claude, while Amazon would invest $5 billion immediately and potentially up to $20 billion more. The partnership gives Anthropic access to up to 5 gigawatts of Amazon Trainium chips, and AWS customers are expected to gain access to Claude through AWS. ([AP News][21])

That is not just financing. It is infrastructure.

Compute dependence, cloud distribution, enterprise access, and platform-mediated scale are the operating conditions of frontier AI.

IPO pressure does not create the access order. It makes the access order more investor-legible.

Capital-market pressure accelerates the pattern.

It does not explain it away.

---

## Not Unique, But Sharper Here

Anthropic did not invent discretionary access.

OpenAI and Google also impose usage limits. They adjust access by plan, model, demand, and product surface. No frontier AI company offers pure transparency over practical access. The industry is built around shifting compute costs, demand management, and product tiers.

The claim is narrower and sharper.

Anthropic places ordinary forms of discretion behind an unusually strong moral posture.

That posture makes the tension visible.

OpenAI often speaks in the language of broad access, agency, productivity, and public benefit. Google has its own history of corporate ethics language. Anthropic’s public identity leans especially hard on safety, restraint, user trust, and moral seriousness.

Those are not decorative values in the brand.

They are the brand.

That is why ordinary discretion matters more here. A usage cap from a standard software platform is one thing. A usage cap from a company asking users to trust it as a safer and more principled AI intermediary carries a different meaning. The same operational tool sits inside a different moral frame.

The same applies to restricted release.

A partner-gated cyber model can be justified as a responsible defensive measure. But when the company’s self-regulation language has shifted from hard-stop pledge toward managed delay, risk reports, review, and selected access, the restricted release becomes more than a product decision.

It becomes the access order taking shape.

Anthropic is not unique in using discretion.

It is distinctive because discretion sits behind an unusually strong moral posture.

“All big tech is the same” is too blunt. The sharper claim is that moral language makes discretionary access feel responsible, even when the practical structure remains tiered, throttled, and gated.

---

## Moralized, Tiered, Throttled, and Gated

The future AI order will not arrive as a simple battle between open and closed.

That binary is too thin. Frontier AI can be closed at the model layer, open at the interface layer, restricted at the partner layer, elastic at the consumer layer, and justified through public safety language at the policy layer.

A system can look accessible while remaining highly managed.

Anthropic’s case shows the structure clearly.

Claude is morally branded as an ad-free, user-aligned assistant. Consumer access is managed through elastic usage budgets and plan boundaries. Product incidents can be bounded through postmortems, but the access model itself remains harder to make fully legible. Self-regulation language has shifted from hard-stop logic toward managed delay and procedural justification. Mythos / Glasswing shows high-value capability moving through selected partner gates rather than simple non-release or broad publication.

This does not require secret bad faith.

Sincerity is the wrong test.

Public moral language becomes consequential when it structures access: who gets throttled, who gets upgraded, who gets selected, who gets reviewed, who gets trusted, and who waits outside the gate.

Controlled release is still release.

A gate can be safer than a floodgate. Once the gate becomes the safety system, the gate itself must be examined. Its partner list matters. Its vendor environments matter. Its permission chains matter. Its monitoring matters. Its redactions, reports, reviews, and accountability channels matter.

Anthropic’s strongest defense makes the access-governance question more central, not less. Some dangerous capabilities should not be thrown into the open. Unilateral hard stops are difficult in a competitive frontier market.

Those claims strengthen the case for scrutinizing the gate.

The issue is not whether Anthropic is secretly insincere.

The issue is that moral AI branding becomes a language for normalizing controlled access. It makes throttling sound like responsibility, gating sound like restraint, and managed release sound like safety.

That is the access order behind safety rhetoric.

Not open.
Not closed.
Moralized, tiered, throttled, and gated.

---

[1]: https://www.anthropic.com/news/claude-is-a-space-to-think "Claude is a space to think | Anthropic"
[2]: https://www.anthropic.com/news/statement-department-of-war "Statement from Dario Amodei on our discussions with the Department of War | Anthropic"
[3]: https://www.theguardian.com/technology/2026/mar/02/claude-anthropic-ai-pentagon "Anthropic’s AI model Claude gets popularity boost after US military feud | The Guardian"
[4]: https://support.anthropic.com/en/articles/9797557-usage-limit-best-practices "Usage limit best practices | Claude Help Center"
[5]: https://support.anthropic.com/en/articles/12111783-create-and-edit-files-with-claude "Create and edit files with Claude | Claude Help Center"
[6]: https://www.techradar.com/ai-platforms-assistants/claude/claude-is-limiting-usage-more-aggressively-during-peak-hours-heres-what-changed "Claude is limiting usage more aggressively during peak hours — here’s what changed | TechRadar"
[7]: https://www.anthropic.com/engineering/april-23-postmortem "An update on recent Claude Code quality reports | Anthropic"
[8]: https://time.com/7380854/exclusive-anthropic-drops-flagship-safety-pledge/ "Exclusive: Anthropic Drops Flagship Safety Pledge | TIME"
[9]: https://www.anthropic.com/project/glasswing "Project Glasswing | Anthropic"
[10]: https://www.anthropic.com/glasswing "Project Glasswing: Securing critical software for the AI era | Anthropic"
[11]: https://red.anthropic.com/2026/mythos-preview/ "Claude Mythos Preview | red.anthropic.com"
[12]: https://www.aisi.gov.uk/blog/our-evaluation-of-claude-mythos-previews-cyber-capabilities "Our evaluation of Claude Mythos Preview’s cyber capabilities | AISI"
[13]: https://docs.anthropic.com/en/docs/about-claude/models "Models overview - Claude API Docs"
[14]: https://www.reuters.com/technology/anthropics-mythos-model-accessed-by-unauthorized-users-bloomberg-news-reports-2026-04-21/ "Anthropic's Mythos model accessed by unauthorized users, Bloomberg News reports | Reuters"
[15]: https://www.anthropic.com/news/statement-comments-secretary-war "Statement on the comments from Secretary of War Pete Hegseth | Anthropic"
[16]: https://www.anthropic.com/news/where-stand-department-war "Where things stand with the Department of War | Anthropic"
[17]: https://www.reuters.com/world/anthropic-talking-trump-administration-about-its-next-ai-model-co-founder-says-2026-04-13/ "Anthropic talking to the Trump administration about its next AI model, co-founder says | Reuters"
[18]: https://www.reuters.com/business/us-security-agency-is-using-anthropics-mythos-despite-blacklist-axios-reports-2026-04-19/ "US security agency is using Anthropic's Mythos despite blacklist, Axios reports | Reuters"
[19]: https://www.reuters.com/legal/government/trump-says-anthropic-is-shaping-up-open-deal-with-pentagon-2026-04-21/ "Trump says Anthropic is 'shaping up,' open to deal with Pentagon | Reuters"
[20]: https://www.reuters.com/business/biggest-ipo-wave-history-promises-3-trillion-value-with-no-profits-2026-04-23/ "Biggest IPO wave in history promises $3 trillion in value – with no profits | Reuters"
[21]: https://apnews.com/article/amazon-anthropic-ai-artificial-intelligence-aws-claude-cffa2cc19f9928d9ac44e44f2d967d36 "AI startup Anthropic commits $100 billion to Amazon's AWS over next 10 years | AP News"

---
