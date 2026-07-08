# Operator sheet - perez-gardening

**Tier:** standard ($1000) - **Booking:** REQUIRED
**Business:** Perez Gardening | **Phone:** (714) 932-3724
**City:** Fullerton CA | **Niche:** landscaper

## Evidence (use in OD - do not invent)

### Google Maps (this business)
- [Open Maps listing](https://www.google.com/maps/place/Perez+gardening/@34.2614476,-121.5345415,7z/data=!4m10!1m2!2m1!1sperez+gardening!3m6!1s0x80dd2b7c6fe8c503:0x40d03749469403fb!8m2!3d33.640814!4d-117.7803964!15sCg9wZXJleiBnYXJkZW5pbmdaESIPcGVyZXogZ2FyZGVuaW5nkgEIZ2FyZGVuZXKaASNDaFpEU1VoTk1HOW5TMFZKUTBGblNVUmFPRTl0VlV4M0VBReABAPoBBAhSEB4!16s%2Fg%2F11h7vgpmqj?hl=en-MY&entry=ttu) — operator-verified 2026-07-07 (replaces poisoned g.page pager-seller link)

### Review language (harvested - copy tone only)
- WARN No harvested reviews - use BRIEF facts only; do not invent quotes

### Peer refs (layout research)
- [https://styles.refero.design/](https://styles.refero.design/) - Refero benchmark - synthesize patterns, never copy screens
- [https://www.squarespace.com/templates](https://www.squarespace.com/templates) - Layout archetype inspiration only
- [https://land-book.com/](https://land-book.com/) - Hero/CTA rhythm reference
- (Maps peer ref pending correct Share link)
- [https://styles.refero.design/](https://styles.refero.design/) - peer reference
- [https://www.squarespace.com/templates](https://www.squarespace.com/templates) - peer reference

## Creative angle
landscaper in Fullerton, CA.
Commissioned local brand - distinctive typography and color, not a swapped template.
Local customers; primary CTA tap-to-call (714) 932-3724.

## Starter DNA
- Starter path: tools/od-starters/generic-local - open README before Pass 1

## Design DNA (never a template - your OD seed)
- **OD seed:** `signature grotesque diagonal local drift blueprint moss`
- Full direction + forbidden list: `.rf/design-dna.md`. Reroll: `.\scripts\new-design-dna.ps1 -Slug perez-gardening -Force`

## Money systems (pitch these FIRST - the site second)
- **Foundation (bundled FREE in System tier):** Business Brain (`modules/crm/`) + Owner's
  Control Room (`modules/dashboard/`). One sheet, one login - every system below plugs into it.
- **START: Ghost Lead Catcher** `tools/rf-kit/modules/ghost-lead-catcher/` (+$400) - this niche's sharpest pain. LEAD with it on the call.
- Next sell 2: **We'll Call You Back** `modules/callback-after-hours/` (+$300) - near-zero wiring cost once the Brain is in.
- Next sell 3: **Quote + Deposit Combo** `modules/quote-deposit-combo/` (+$600) - near-zero wiring cost once the Brain is in.
- Next sell 4: **Lost-Quote Win-Back** `modules/lost-quote-winback/` (+$350) - near-zero wiring cost once the Brain is in.
- Next sell 5: **Review Magnet** `modules/review-magnet/` (+$500) - near-zero wiring cost once the Brain is in.
- Next sell 6: **Fresh Work Feed** `modules/fresh-work-feed/` (+$400) - near-zero wiring cost once the Brain is in.
- Next sell 7: **Slow-Season Filler** `modules/slow-season-filler/` (+$350) - near-zero wiring cost once the Brain is in.
- Return-visit motion: come back in 60-90 days and sell the next system on the path - the
  foundation is already installed, so margin RISES with each one.
- Suggested price-add over tier floor (modules + starting system): **+$400**. Stack with rubric (busy/reviews/rush).
- Full path lifetime value on this client: +$2900 across return visits.
- **Command Pack (install footprint day one):** Ghost Lead Catcher + We'll Call You Back + Quote + Deposit Combo = list $1300, **bundled $1170** (save $130). More systems installed now = a richer Path C later.
- **Attach Monthly Wins Report** (+$300, or bundle it FREE on a System build): the monthly proof email is what turns this client into referrals and repeat sales.
- Brand Kit add-on: +$350 (new-brand-kit.ps1).
- Doctrine: pitch the money system first (caught leads, filled slots, reviews), the site second.
- Full spec (modules, placeholders, client setup): `.rf/system-spec.md`

## Showroom inventory (fork candidates)
- None yet for this niche. Unsold builds land here via `.\scripts\mark-unsold.ps1 -Slug <slug>`.

## Pricing (per-deal - never below floor, SOUL sec.3)
- Tier floor: $1000. Anchor high (pitch Website System first), sell down.
- Charge UP for: 100+ reviews/busy, money-moment module, multi-location/menu-heavy, rush.
- Brand Kit add-on: $350+. Log OD minutes at sale: `log-sale.ps1 -DesignMinutes <n>`.

## Booking snippet (Standard / Premium)
- RECOMMENDED: Templates/od-snippets/booking/request-form-formspree.html - Standard default - callback form unless owner prefers calendar | Alternate: Templates/od-snippets/booking/calendly-embed.html
- Replace placeholder **FORM_ID** with client endpoint before handback
- Checklist: `Templates/od-snippets/booking/checklist.md`
- After handback: `.\scripts\qa-standard-ship-bar.ps1 -Slug $Slug`

## Pass 1 - commission (~8 min, structure only)
```powershell
.\scripts\run-od-commission.ps1 -Slug perez-gardening
```

## Pass 2 - polish + mark (~9 min)
- [ ] Hero + phone above fold
- [ ] Callback form pasted from `Templates/od-snippets/booking/request-form-formspree.html` (trades)
- [ ] Placeholder `FORM_ID` replaced (client account)
- [ ] Greeter copy sounds like staff, not generic AI form
- [ ] Proof from Evidence section (no invented reviews)
```powershell
.\scripts\run-od-mark-design-ready.ps1 -Slug perez-gardening
```

## Handback (Grok)
```powershell
.\scripts\run-od-handback.ps1 -Slug perez-gardening -Package -Deploy
```