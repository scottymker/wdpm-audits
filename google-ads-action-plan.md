# Google Ads Action Plan for Wall Decor Plus More

## Overview

Your current Google Ads setup is losing money. This document provides step-by-step instructions to fix it.

**Current State:**
- Spending ~$6.18/day ($185/month)
- ROAS: 1.41x (losing money after product costs)
- Cost per conversion: $24.84 (too high)

**Goal:**
- ROAS: 2.5x+ (profitable after costs)
- Cost per conversion: <$15
- Only advertise products that actually sell

---

## PART 1: CAMPAIGNS TO STOP

### Campaign to Pause: Performance Max | Category A Products

**Location:** Google Ads > Campaigns

**Steps:**
1. Log into Google Ads at https://ads.google.com
2. Click "Campaigns" in the left sidebar
3. Find "Contrarian Path | United States | Performance Max | Bottom Funnel | Category A Products | Mc"
4. Click the green dot under "Status"
5. Select "Pause"
6. Confirm the pause

**Why we're pausing:**
- 1.41x ROAS means you get $1.41 back for every $1 spent
- After product costs (~40%), shipping, and fees, you're losing ~$0.35 per dollar spent
- "Some asset groups limited by policy" flag indicates issues
- 53.74% optimization score means Google sees problems
- Performance Max gives you no control over which products get shown

---

## PART 2: CAMPAIGNS TO FIX

### Campaign to Investigate: Brand Search

**Campaign Name:** Contrarian Path | United States | Search | Middle Funnel | Brand

**Problem:** This campaign is enabled with $2/day budget but has 0 impressions. Something is broken.

**Steps to Diagnose:**

1. Log into Google Ads
2. Click "Campaigns" > Find the Brand campaign
3. Click into the campaign
4. Check "Ad groups" - is there at least one enabled?
5. Check "Ads & assets" - are ads approved or disapproved?
6. Check "Keywords" - are there keywords added?

**Common Fixes:**

| Issue | Solution |
|-------|----------|
| No keywords | Add keywords: "wall decor plus more", "walldecorplusmore", "wdpm" |
| Ads disapproved | Review disapproval reason, fix ad copy, resubmit |
| Bid too low | Increase bid to $1.00-$2.00 per click |
| Location targeting wrong | Ensure targeting United States |

**Why this matters:** Brand searches (people searching your company name) typically have 5-10x ROAS because they already know you. This should be your cheapest, best-converting traffic.

---

## PART 3: NEW CAMPAIGNS TO CREATE

### New Campaign #1: Shopping - Mailbox Decals

This is your #1 priority. Mailbox decals have a 3.9% conversion rate - your best performing product.

#### Step-by-Step Setup:

**Step 1: Verify Google Merchant Center**
1. Go to https://merchants.google.com
2. Confirm your product feed is active and approved
3. Make sure mailbox decal products are listed and approved

**Step 2: Create the Campaign**
1. In Google Ads, click the blue "+" button
2. Select "New campaign"
3. Choose goal: "Sales"
4. Select "Shopping" as campaign type
5. Select your Merchant Center account
6. Choose "Standard Shopping campaign" (NOT Performance Max)

**Step 3: Campaign Settings**
```
Campaign name: Shopping | Mailbox Decals Only
Budget: $5.00 per day
Bidding: Manual CPC (start with $0.50 max CPC)
Networks: Uncheck "Search partners" and "Display Network"
Locations: United States
```

**Step 4: Create Ad Group**
```
Ad group name: Mailbox Decals
Max CPC bid: $0.50
```

**Step 5: Filter Products**
1. In the ad group, click "Product groups"
2. Click the pencil icon to edit
3. Subdivide by "Product type" or "Item ID"
4. ONLY include mailbox decal products
5. Exclude everything else by setting bid to "Excluded"

**Products to Include:**
- Decorative Mailbox Decals Custom Address Stickers
- Custom Elegant Mailbox Vinyl Sticker Decals with Swirls
- Any other mailbox-related products

**Step 6: Add Negative Keywords**
1. Click "Keywords" > "Negative keywords"
2. Add these negative keywords:

```
wall quotes
inspirational decals
vinyl lettering
wall stickers quotes
family quotes
kitchen quotes
bathroom decals
nursery decals
classroom decals
quote decals
saying decals
```

**Step 7: Launch**
1. Review all settings
2. Click "Publish campaign"

---

### New Campaign #2: Shopping - Growth Charts (Start Week 3)

Only create this after the mailbox campaign is running profitably for 2 weeks.

#### Step-by-Step Setup:

**Step 1: Create Campaign**
1. Click "+" > "New campaign"
2. Goal: "Sales"
3. Type: "Shopping"
4. Select "Standard Shopping campaign"

**Step 2: Campaign Settings**
```
Campaign name: Shopping | Growth Charts
Budget: $3.00 per day
Bidding: Manual CPC ($0.40 max CPC)
Locations: United States
```

**Step 3: Filter Products**
Only include:
- Woodlands Moose Canvas Growth Chart
- Lavender Canvas Growth Chart
- Any other growth chart products

**Step 4: Add Same Negative Keywords**
Copy the negative keyword list from Campaign #1.

---

### New Campaign #3: Shopping - Sensory Paths (Start Week 4)

Only create this after growth charts campaign is running.

#### Setup:
```
Campaign name: Shopping | Sensory Paths
Budget: $3.00 per day
Bidding: Manual CPC ($0.40 max CPC)
```

**Products to Include:**
- Sensory Path Floor Decals School Hallway Hopscotch
- Sunflower Numbers Playground Stencil Sensory Path
- Other sensory path products

---

## PART 4: NEGATIVE KEYWORDS MASTER LIST

Add these to ALL campaigns to prevent wasted spend on non-converting searches:

```
wall quotes
inspirational quotes
inspirational decals
vinyl lettering
wall stickers quotes
family quotes
kitchen quotes
bathroom decals
nursery quotes
classroom quotes
quote decals
saying decals
word decals
text decals
lettering decals
scripture decals
bible verse decals
free
cheap
DIY
template
printable
how to make
```

**How to Add Negative Keywords:**
1. Go to campaign
2. Click "Keywords" in left menu
3. Click "Negative keywords"
4. Click blue "+" button
5. Select "Add negative keywords"
6. Paste the list above
7. Save

---

## PART 5: WEEKLY MONITORING CHECKLIST

### Every Monday, Check:

#### 1. Campaign Performance
Go to Campaigns > Look at last 7 days:

| Metric | Target | Action if Below Target |
|--------|--------|------------------------|
| ROAS | 2.5x+ | Lower bids or pause poor products |
| Cost/conversion | <$15 | Add negative keywords |
| CTR | >1% | Improve product images/titles |

#### 2. Search Terms Report
1. Click campaign > Keywords > Search terms
2. Look for irrelevant searches
3. Add irrelevant terms as negative keywords

#### 3. Product Performance
1. Click campaign > Product groups
2. Sort by cost (highest first)
3. If any product has high cost + low conversions, exclude it

---

## PART 6: IMPLEMENTATION TIMELINE

### Week 1: Stop the Bleeding
- [ ] Day 1: Pause Performance Max campaign
- [ ] Day 1: Investigate Brand Search campaign (fix if possible)
- [ ] Day 2: Verify Merchant Center product feed is healthy
- [ ] Day 3: Create "Shopping | Mailbox Decals Only" campaign
- [ ] Day 3: Add all negative keywords
- [ ] Day 4-7: Monitor daily, don't make changes yet

### Week 2: Optimize
- [ ] Review search terms report
- [ ] Add any new negative keywords found
- [ ] Check which mailbox products are getting clicks
- [ ] Exclude any non-mailbox products sneaking in
- [ ] Adjust bids if needed (up if ROAS >3x, down if <2x)

### Week 3: Expand if Profitable
- [ ] Check mailbox campaign ROAS
- [ ] If ROAS >2.5x: Increase budget to $10/day
- [ ] If ROAS >2.5x: Create Growth Charts campaign
- [ ] If ROAS <2.0x: Add more negative keywords, lower bids

### Week 4: Scale What Works
- [ ] Review all campaign performance
- [ ] Create Sensory Paths campaign if others are profitable
- [ ] Consider increasing budgets on winners
- [ ] Pause anything under 2.0x ROAS

---

## PART 7: EXPECTED RESULTS

### Before (Current State)
| Metric | Value |
|--------|-------|
| Monthly spend | ~$185 |
| Monthly revenue from ads | ~$260 |
| ROAS | 1.41x |
| Profit after costs | **-$65/month (LOSS)** |

### After (Target State - 30 Days)
| Metric | Value |
|--------|-------|
| Monthly spend | ~$300 |
| Monthly revenue from ads | ~$750+ |
| ROAS | 2.5x+ |
| Profit after costs | **+$150/month (PROFIT)** |

---

## PART 8: QUICK REFERENCE

### Campaigns to PAUSE
1. ~~Contrarian Path | United States | Performance Max | Bottom Funnel | Category A Products | Mc~~

### Campaigns to FIX
1. Contrarian Path | United States | Search | Middle Funnel | Brand (0 impressions - diagnose why)

### Campaigns to CREATE
1. Shopping | Mailbox Decals Only ($5/day) - START IMMEDIATELY
2. Shopping | Growth Charts ($3/day) - START WEEK 3
3. Shopping | Sensory Paths ($3/day) - START WEEK 4

### Products to Advertise
- Mailbox decals (all varieties)
- Canvas growth charts
- Sensory path floor decals

### Products to NEVER Advertise
- Wall quotes / inspirational quotes
- Vinyl lettering
- Generic wall decals
- Any product with 50+ views and 0 sales

---

## Need Help?

If you get stuck on any step:
1. Google Ads Help: https://support.google.com/google-ads
2. Google Merchant Center Help: https://support.google.com/merchants

---

*Document created: December 2025*
*Based on data analysis: September 10 - December 8, 2025*
