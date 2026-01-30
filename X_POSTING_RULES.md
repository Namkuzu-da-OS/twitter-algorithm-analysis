# X Algorithm Posting Rules
## Optimized for Maximum Reach

Based on analysis of the open-sourced X algorithm codebase.

---

## THE SCORING FORMULA

Your post's reach is determined by:

```
Final Score = (favorite × W1) + (reply × W2) + (retweet × W3) + (quote × W4)
            + (share × W5) + (share_dm × W6) + (share_link × W7) + (dwell × W8)
            + (dwell_time × W9) + (click × W10) + (profile_click × W11)
            + (photo_expand × W12) + (video_view × W13) + (follow × W14)
            - (not_interested × W15) - (block × W16) - (mute × W17) - (report × W18)
```

The weights (W1-W18) are hidden, but the signals are clear.

---

## RULE 1: OPTIMIZE FOR REPLIES (Highest Impact)

Replies signal genuine engagement. The algorithm heavily weights them.

**DO:**
- End posts with open-ended questions
- Make controversial (not offensive) statements that invite debate
- Use "fill in the blank" formats: "The biggest risk in 2026 is ___"
- Create "hot take" posts people feel compelled to respond to
- Reply to your own post early to seed the conversation

**DON'T:**
- Ask yes/no questions (low reply quality)
- Make statements so obvious no one needs to add anything

---

## RULE 2: OPTIMIZE FOR REPOSTS + QUOTES

Reposts = distribution. Quotes = distribution + engagement.

**DO:**
- Create "save this" content (lists, frameworks, insights)
- Include one highly quotable line per post
- Share novel information people can't find elsewhere
- Make screenshot-worthy posts (clean formatting)
- Post contrarian takes that invite "here's my take" quote tweets

**DON'T:**
- Post generic takes everyone agrees with (nothing to add)
- Make posts that only make sense in your voice (hard to RT)

---

## RULE 3: MAXIMIZE DWELL TIME

Time spent on your post = signal of quality.

**DO:**
- Use line breaks for scannable formatting
- Write longer posts when you have substance
- Open with a hook that creates curiosity
- Include images (triggers photo_expand_score)
- Post videos >X seconds (unlocks vqv_score)
- Create information density (reward for reading)

**DON'T:**
- Write walls of text with no breaks
- Front-load everything (no reason to keep reading)
- Post single-sentence takes (low dwell)

---

## RULE 4: TRIGGER DM SHARES (Hidden Viral Mechanic)

DM shares are weighted in the algorithm (share_via_dm_score).

**Content that gets DM'd:**
- Insider knowledge ("you need to see this")
- Relatable content ("this is SO [friend's name]")
- Controversial opinions people agree with privately but won't share publicly
- Actionable alpha (financial, career, etc.)

---

## RULE 5: DRIVE PROFILE CLICKS + FOLLOWS

These signals tell the algorithm you're worth distributing.

**DO:**
- Demonstrate unique expertise in posts
- Create curiosity about who you are
- Post thread series ("Part 1 of my...")
- Show results/proof without being braggy
- Have an incomplete but intriguing bio

**DON'T:**
- Be a faceless account with no identity
- Post generic content anyone could write

---

## RULE 6: AVOID NEGATIVE SIGNALS (Critical)

These SUBTRACT from your score and tank reach:

| Signal | Trigger | How to Avoid |
|--------|---------|--------------|
| `not_interested` | Spammy, irrelevant, engagement bait | Don't be annoying |
| `mute_author` | Posting too much, repetitive content | Quality > quantity |
| `block_author` | Offensive, harassing, unwanted tags | Don't tag strangers |
| `report` | Violating rules, spam, abuse | Stay within guidelines |

**One block or mute hurts more than one like helps.**

---

## RULE 7: AUTHOR DIVERSITY PENALTY

The algorithm penalizes posting too frequently:

| Post # | Score Multiplier |
|--------|------------------|
| 1st | 100% |
| 2nd | ~73% |
| 3rd | ~54% |
| 4th | ~40% |
| 5th+ | Approaching floor (~10%) |

**Optimal posting frequency: 2-3 quality posts per day, spaced out.**

---

## RULE 8: IN-NETWORK vs OUT-OF-NETWORK

- **In-network** (your followers): Full score (1.0x)
- **Out-of-network** (non-followers): Reduced score (~0.5-0.8x)

**Implication:** Your followers are your most valuable audience. A post that resonates with your followers gets shown to more non-followers via the retrieval model.

**Strategy:** Build genuine follower relationships. Don't chase virality with randos.

---

## RULE 9: THE 24-HOUR WINDOW

Posts older than ~24 hours are filtered out of "For You."

**Implication:**
- Early engagement matters most
- Post when your audience is active
- A post that flops in hour 1 rarely recovers

---

## RULE 10: TRENDING TOPICS (The Truth)

**There is NO trending topic boost in the algorithm.**

The algorithm eliminated all hand-engineered features. No hashtag boost. No keyword boost. No trending boost.

**However, trending topics help indirectly:**
- Larger active audience = more potential engagers
- Early engagement from trending audience = positive signal
- Retrieval model matches you to users engaging with similar content

**Strategy:** If you can authentically tie your content to a trending topic, do it—but for the audience, not the algorithm.

---

## RULE 11: WHAT DOESN'T MATTER

Based on the code, these are NOT direct ranking factors:

| Myth | Reality |
|------|---------|
| Blue checkmark | No direct boost in ranking code |
| Follower count | Not a score multiplier |
| Account age | No explicit boost |
| Posting time | No time-of-day boost |
| Specific hashtags | No hashtag-specific boosts |
| Keyword stuffing | No keyword boosts |

The ML model learns from **actual engagement**, not surface features.

---

## RULE 12: AVOID MUTED KEYWORDS

If your post contains a keyword the viewer has muted, it's **completely filtered out**—not just down-ranked, but invisible.

**Common muted terms to avoid:**
- Political trigger words (unless that's your niche)
- Spam indicators ("link in bio", "DM me", "giveaway")
- Overused engagement bait ("like if you agree")

---

## POST TEMPLATE

```
[HOOK - 1 line that stops the scroll]
Pattern interrupt, contrarian take, or curiosity gap

[CONTEXT - 2-3 lines]
Set up the situation or problem

[INSIGHT - 2-4 lines]
Your unique take, data, or framework
Use line breaks for readability

[QUOTABLE - 1 line]
The line people will screenshot or quote-tweet

[CTA - 1 line]
Question or prompt that invites replies
```

---

## PRE-POST CHECKLIST

Before posting, verify:

- [ ] Does this invite replies? (Question, opinion, debate)
- [ ] Is there a quotable/screenshot-worthy line?
- [ ] Would someone DM this to a friend?
- [ ] Is it formatted for easy scanning? (Line breaks)
- [ ] Does it make people curious about me? (Profile click)
- [ ] Have I posted less than 3 times today?
- [ ] Could this trigger mutes/blocks? (Spammy, offensive, repetitive)
- [ ] Am I posting when my audience is active?
- [ ] Is there a curiosity hook in the first line?

---

## QUICK REFERENCE: ENGAGEMENT HIERARCHY

Optimize in this order (based on algorithm structure):

1. **Replies** - Highest signal of genuine engagement
2. **Reposts** - Distribution multiplier
3. **Quotes** - Distribution + engagement
4. **Shares (DM/Link)** - Hidden viral mechanic
5. **Likes** - Common but still weighted
6. **Dwell time** - Quality signal
7. **Profile clicks** - Interest signal
8. **Follows** - Ultimate conversion

**Avoid at all costs:**
- Not interested clicks
- Mutes
- Blocks
- Reports

---

## SOURCES

Analysis based on:
- [home-mixer/scorers/weighted_scorer.rs](x-algorithm-main/home-mixer/scorers/weighted_scorer.rs) - Scoring formula
- [home-mixer/scorers/author_diversity_scorer.rs](x-algorithm-main/home-mixer/scorers/author_diversity_scorer.rs) - Diversity penalty
- [home-mixer/scorers/oon_scorer.rs](x-algorithm-main/home-mixer/scorers/oon_scorer.rs) - Out-of-network penalty
- [home-mixer/filters/](x-algorithm-main/home-mixer/filters/) - Filtering logic
- [phoenix/](x-algorithm-main/phoenix/) - ML ranking model
- [README.md](x-algorithm-main/README.md) - System architecture

Note: Actual weight values are in `params.rs` which is "excluded from open source release for security reasons."
