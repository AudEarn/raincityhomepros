# RainCityHomePros SEO Blog Plan

## Goal
Rank raincityhomepros.vercel.app for high-intent, low-competition Seattle home service keywords. Priority: Vent Cleaning first, then cascade through all 10 categories.

## SEO Strategy

### On-Page Best Practices Applied
- Each post targets ONE primary keyword in: title tag, H1, first 100 words, at least one H2, meta description, canonical URL
- All posts link internally to the relevant service category page (e.g. /vent-cleaning-seattle.html)
- Blog index page at /blog/index.html linked from main nav
- Each post has related articles section (internal links between posts)
- Meta descriptions 150-160 chars, include keyword and CTA
- Canonical tags on every page
- Open Graph tags for social sharing
- Breadcrumb navigation for crawlability

### Target Keyword Framework
Priority: Low competition, local intent, informational + transactional mix
- Informational: "how to", "what is", "signs you need", "how often"
- Transactional: "cost", "price", "near me", "best", "top rated"
- Local: Always include "Seattle" or suburb name

---

## Content Calendar

### Phase 1: Vent Cleaning (Weeks 1-3) - HIGHEST PRIORITY

| Date | Slug | Primary Keyword | Type | Status |
|------|------|----------------|------|--------|
| May 11 | how-often-clean-dryer-vent-seattle | how often clean dryer vent Seattle | Informational | PUBLISHED |
| May 11 | signs-you-need-vent-cleaning-seattle | signs you need vent cleaning Seattle | Informational | PUBLISHED |
| May 11 | air-duct-cleaning-cost-seattle | air duct cleaning cost Seattle | Transactional | PUBLISHED |
| May 12 | dryer-vent-cleaning-vs-air-duct-cleaning | dryer vent vs air duct cleaning Seattle | Informational | SCHEDULED |
| May 13 | nadca-certified-duct-cleaning-seattle | NADCA certified duct cleaning Seattle | Transactional | SCHEDULED |
| May 14 | best-dryer-vent-cleaning-seattle | best dryer vent cleaning Seattle | Transactional | SCHEDULED |
| May 15 | dryer-vent-cleaning-bellevue | dryer vent cleaning Bellevue WA | Local | SCHEDULED |
| May 16 | dryer-vent-cleaning-kirkland | dryer vent cleaning Kirkland WA | Local | SCHEDULED |
| May 17 | dryer-vent-cleaning-renton | dryer vent cleaning Renton WA | Local | SCHEDULED |
| May 18 | air-duct-cleaning-bellevue | air duct cleaning Bellevue WA | Local | SCHEDULED |
| May 19 | mold-in-air-ducts-seattle | mold in air ducts Seattle | Informational | SCHEDULED |
| May 20 | how-long-does-duct-cleaning-take | how long does duct cleaning take | Informational | SCHEDULED |
| May 21 | vent-cleaning-seattle-coupon | vent cleaning Seattle coupon | Transactional | SCHEDULED |

### Phase 2: HVAC (Weeks 4-5)

| Date | Slug | Primary Keyword | Type |
|------|------|----------------|------|
| May 22 | hvac-tune-up-cost-seattle | HVAC tune up cost Seattle | Transactional |
| May 23 | signs-hvac-needs-repair-seattle | signs HVAC needs repair Seattle | Informational |
| May 24 | best-hvac-companies-seattle | best HVAC companies Seattle | Transactional |
| May 25 | heat-pump-vs-furnace-seattle | heat pump vs furnace Seattle | Informational |
| May 26 | hvac-maintenance-checklist-seattle | HVAC maintenance checklist Seattle | Informational |

### Phase 3: Roofing (Week 6)

| Date | Slug | Primary Keyword | Type |
|------|------|----------------|------|
| May 27 | roof-replacement-cost-seattle | roof replacement cost Seattle | Transactional |
| May 28 | signs-need-new-roof-seattle | signs you need a new roof Seattle | Informational |
| May 29 | best-roofing-companies-seattle | best roofing companies Seattle | Transactional |
| May 30 | metal-roof-vs-asphalt-seattle | metal roof vs asphalt Seattle | Informational |

### Phase 4: Plumbing (Week 7)
| Keyword targets: "plumber Seattle cost", "emergency plumber Seattle", "water heater replacement Seattle cost", "best plumbers Seattle" |

### Phase 5: Electrical (Week 8)
| Keyword targets: "electrician Seattle cost", "electrical panel upgrade Seattle", "EV charger installation Seattle", "best electricians Seattle" |

### Phase 6: Remaining Categories (Weeks 9-12)
Landscaping, Gutter Cleaning, Pressure Washing, Concrete, Tree Service - 3-5 posts each

---

## Keyword Research Priorities

### Vent Cleaning - Top Keywords to Target
1. dryer vent cleaning Seattle (est. 320/mo) - MEDIUM competition
2. air duct cleaning Seattle (est. 480/mo) - MEDIUM competition
3. vent cleaning Seattle (est. 260/mo) - LOW competition
4. dryer vent cleaning cost Seattle (est. 140/mo) - LOW competition
5. best air duct cleaning Seattle (est. 90/mo) - LOW competition
6. NADCA certified duct cleaning Seattle (est. 70/mo) - VERY LOW competition
7. dryer vent cleaning Bellevue (est. 90/mo) - LOW competition
8. dryer vent cleaning Kirkland (est. 70/mo) - VERY LOW competition
9. air duct cleaning Renton WA (est. 60/mo) - VERY LOW competition
10. how often clean dryer vent (est. 1,600/mo national) - LOW competition

### Why Vent Cleaning Ranks Fastest
- Lower domain authority competitors in Seattle
- Fewer dedicated local directories
- High mix of informational + local intent queries
- NADCA certification angle = trust signal content opportunity
- Multiple suburb-specific keywords (Bellevue, Kirkland, Renton, Bothell, Redmond, etc.)

---

## Internal Linking Strategy

### Hub & Spoke Model
- /vent-cleaning-seattle.html = HUB (service page)
- /blog/how-often-clean-dryer-vent-seattle.html = SPOKE
- /blog/signs-you-need-vent-cleaning-seattle.html = SPOKE
- /blog/air-duct-cleaning-cost-seattle.html = SPOKE
- Each SPOKE links back to HUB + to other SPOKEs

### Cross-Category Linking
Once Phase 2+ begins, HVAC posts should mention and link to vent cleaning (related services)

---

## Daily Posting Workflow

1. Claude navigates to github.com/AudEarn/raincityhomepros/upload/main
2. Claude builds the day's blog post HTML using the established template (buildBlogPage function)
3. Claude drops the new .html file to the GitHub upload zone using DragEvent + DataTransfer
4. Claude updates /blog/index.html to add the new post card
5. Claude commits with message: "Blog: [Post Title] - [Date]"
6. Vercel auto-deploys (typically 1-3 minutes)
7. Claude verifies live URL works correctly

## File Structure

```
raincityhomepros/
  index.html
  vent-cleaning-seattle.html
  [other service pages]
  styles.css
  script.js
  blog/
    index.html                              (blog listing page)
    how-often-clean-dryer-vent-seattle.html
    signs-you-need-vent-cleaning-seattle.html
    air-duct-cleaning-cost-seattle.html
    [new posts added daily]
    blog-plan.md                            (this file)
```

---
*Last updated: May 11, 2026*
