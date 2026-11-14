# Contributing

This list has one job: show a veteran, a survivor, or a family member the exact next step to claim what was earned — the right agency, the right form, the right deadline — with a primary source behind every claim. Contributions are judged against that job, and against one further test most lists never face: **someone may rely on this to file a claim, meet a deadline, or refuse a scammer.** Accuracy is not a style preference here.

## The inclusion bar

An entry gets in only if it clears **all** of these:

1. **Actionable by a non-technical person.** If using it requires a law degree, a developer account, or insider vocabulary, it belongs in a different list.
2. **Primary source only.** Link to the administering agency's own page (va.gov, benefits.va.gov, dol.gov, sba.gov, consumerfinance.gov, archives.gov, dfas.mil), the statute (Cornell LII, govinfo, eCFR), milConnect/DMDC, or the official organization's own site. Never a law-firm marketing page, a news article, a blog post, or a lead-generation "veteran benefits" site *as the authority* for a claim — that last category is a scam genre, not a source.
3. **Verified current.** Benefits are the fastest-rotting facts in public life: rates reset every December 1 (disability compensation) and August 1 (GI Bill), grant maximums every fiscal year, programs end by statute and appropriation. Before adding or citing any program, check its status *today*. An ended, defunded, superseded or merely *proposed* program stated as live is the worst bug this repo can ship.
4. **The lever is named.** One line must say what the entry does *and* what it gives the reader: the deadline, the window, the exemption, the free help. "VA healthcare exists" is not an entry; "enroll with Form 10-10EZ — five ways to file" is.
5. **Honestly priced.** Tag it `Free`, `Freemium` (the free tier must be genuinely usable, not a trial funnel), or `Paid`. Almost everything earned through service is free; a cost tag appears only where a real cost exists. If the price model changed, that's a bug worth a PR.
6. **No affiliate or referral links.** Ever. A recommendation you get paid for is an ad.
7. **It earns its place.** "Also exists" is not a reason.

## What gets rejected

- **Claims sharks and fee-chargers, always.** Anyone charging to file an initial VA claim, charging for a DD214, guaranteeing a rating, or offering to "expedite" VA — rejected on sight. VSO help is free; accredited attorneys/agents may charge only at the stages VA's rules allow.
- **Fabricated-evidence tactics, always.** This list is lawful claiming: documented conditions, honest statements, real deadlines. Anything coaching exaggerated symptoms, manufactured evidence or lying to VA, an examiner or a lender is rejected on sight — and reported if it's a PR pattern.
- Pension-poaching schemes, benefits "buyouts," pension-advance loans, and anyone charging to do what this list teaches free.
- Entries whose authority is a secondary source (law-firm SEO pages, lead-generation guides, AI content farms) even when the underlying claim happens to be true. Re-anchor it to the primary source or it doesn't ship.
- Claims stated more strongly than the source supports: a capped program is not "open to all," a fiscal-year figure is not permanent, an FY-dated dollar amount without its year is a lie by omission, and a state-specific benefit is not national.
- Dead links, and state-specific entries without routing the reader to their own state's agency (see the NASDVA directory in the README).

## Entry format

```markdown
- **[Name](https://primary-source.example)** — What it does, in one plain sentence, ending with the lever it gives the reader (the deadline, the window, the exemption, the free help). `Free`
```

- Plays (actions, deadlines and status checks, not tools) start with 📋 and link only to a primary source.
- Keep the line under ~45 words. If it needs a paragraph, it's two entries or it's out.
- New sections need an issue first — sections are promises, and this list keeps its promises few and kept.

## The border rule

Three sister lists stay in their lanes. If your entry is about *preventing* a scam, verifying something in the moment, or the first 72 hours after one, it belongs in **Awesome Scam Defense**. If it's the long institutional consumer fight — disputes, complaints, opt-outs, rights — it belongs in **Awesome Consumer Revenge Kit**. Veteran-specific benefits, rights and programs — what was earned in service and how to claim it — live here. Cross-list entries live in exactly one home and get linked, not copied.

## Maintenance

Links are checked automatically every week (see `.github/workflows/link-check.yml`), and program claims are re-verified against their sources on a rolling basis — a link that still resolves can still be *wrong* if the program behind it ended, the rate year rolled over, or the authorization lapsed. A dead link or a dead program gets one fix cycle, then the entry is removed — a shorter list that's accurate beats a longer list that isn't.
