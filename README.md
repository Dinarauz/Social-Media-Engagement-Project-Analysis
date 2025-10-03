# Social Media Engagement Analysis - Digital Marketing & Social Media Analytics
**Analysis Type:** Engagement Optimization & Content Performance
![photo-1683721003111-070bcc053d8b](https://github.com/user-attachments/assets/8d990732-3762-4c81-9396-a2787be75317)

## Executive Summary
Social media marketers waste budget on low-performing platforms and posting times without data-driven guidance. This analysis reveals that Instagram drives over 2x higher engagement than Twitter, with video and poll formats significantly outperforming static content. Peak engagement occurs during off-peak hours (1 AM, 9 AM, 9 PM), challenging traditional posting schedules. By reallocating budget to Instagram video content posted during these windows on Sundays and Fridays, marketing teams can significantly increase engagement rates.

## Business Problem: 
Social media marketers face limited resources and need to optimize content strategy across multiple platforms. Without data-driven insights on platform performance, content formats, and optimal timing, marketing teams risk wasting budget on low-engagement channels and ineffective posting schedules.

**Key Questions:**
1. Which content formats drive highest engagement?
2. How does engagement vary across platforms?
3. When should posts be scheduled for maximum reach?
4. What characteristics define top-performing content (top 10%)?

## Solution
**Methodology**
1. **Platform Performance Analysis:** Calculated average engagement rates across Instagram, Facebook, and Twitter
2. **Content Format Comparison:** Analyzed engagement by format (videos, polls, carousels, images, text)
3. **Time-Series Analysis:** Identified hourly and daily engagement patterns to optimize posting schedules
4. **Top Performer Profiling:** Isolated top 10% of posts to identify shared characteristics of viral content

## Tools & Skills
**Python:** Pandas (data cleaning), NumPy (statistical calculations), Seaborn/Matplotlib (visualization), Kagglehub (data ingestion)
**Power BI:** Interactive dashboard with drill-down capabilities for stakeholder exploration
**Statistical Analysis:** Comparative analysis, pattern recognition, performance segmentation

**Raw Dataset**: https://www.kaggle.com/datasets/divyaraj2006/social-media-engagement

## Power Bi Dashboard PDF
[Social Media Engagement Analysis.pdf](https://github.com/user-attachments/files/21302376/Social.Media.Engagement.Analysis.pdf)

## Power Bi Dashboard Link 
https://app.powerbi.com/groups/79249d93-89f9-42e7-a5be-f7bd52abace8/reports/812dcbff-c0bd-4e8d-b407-1487fbcedbcf/1af2bc2cc0869c110bee?experience=power-bi

## Key Insights
**Platform Performance**
Instagram leads with 3,700 avg engagement
Facebook delivers 3,400 avg engagement (second strongest platform)
Twitter underperforms at 1,700 avg engagement (lowest across platforms)

**Business Implication:** Instagram delivers over 2x the engagement of Twitter.

**Content Format Effectiveness**
**Polls generate highest engagement:** 3,800 (interactive format advantage)
**Videos close second:** 3,500 (visual storytelling drives interaction)
**Text posts lag significantly:** 2,200 (lowest performer)

**Business Implication:** Video production costs are justified by significantly higher engagement vs text/image alternatives.

**Optimal Posting Times**
**Peak engagement hour:** 1 AM (5,500 avg) - highest engagement window
**Secondary peaks:** 9 AM, 4 AM, 9 PM
**Lowest engagement:** Mid-afternoon hours

**Business Implication:** Traditional 9-5 posting schedules miss the most engaged audience windows.

**Weekly Patterns**
**Top days:** Sunday, Friday, Wednesday
**Lowest days:** Monday, Saturday

**Business Implication:** Reserve high-budget campaign launches for Sundays and Fridays to maximize reach.

**Top 10% Performers**
Videos dominate top-performing content
Polls rank second in high-performer frequency
Carousels show strong presence in top tier

**Business Implication:** Content strategy should prioritize video and interactive formats.

## Business Recommendations
**For Marketing Teams**
1. **Reallocate Budget:** Shift 50% of spend to Instagram, 30% to Facebook, reduce Twitter investment
2. **Content Priority:** Produce 60% video content, 25% polls, 15% carousels/images
3. **Posting Schedule:** Schedule key campaigns for 1 AM, 9 AM, or 9 PM windows
4. **Weekly Calendar:** Reserve Sunday and Friday for highest-priority content launches

**For Content Creators**
1. Focus on interactive formats (polls, Q&A videos) over static images
2. Create carousel content for secondary engagement opportunities
3. Avoid text-only posts unless paired with strong visual elements

## Expected Impact
**Quantified Business Value**
  • Significant engagement increase by switching from text to video format
  • Major engagement boost by moving key posts to 1 AM peak window vs. afternoon lows
  • Over 2x ROI improvement by reallocating budget from Twitter to Instagram
  • Cost savings by eliminating underperforming text-only content production

**How Analysis Connects to Outcomes**
My Python analysis identified the engagement gaps between polls (3,800) and text posts (2,200), directly informing the video/poll content recommendation. The hourly engagement calculations showing 1 AM peak (5,500) vs afternoon lows quantify the lift available through schedule optimization. The platform comparison logic (Instagram 3,700 vs Twitter 1,700) provides the ROI multiplier that justifies budget reallocation decisions.

Power BI dashboard enables marketing teams to explore these patterns interactively, filtering by platform/format/time to validate recommendations against their specific audience data before implementing changes.

## Next Steps
**Future Enhancements**
  • **Demographic Segmentation:** Integrate follower age/location data to refine audience targeting and explain why 1 AM performs well
  • **Predictive Modeling:** Build engagement prediction model using content format, posting time, and platform as features
  • **Conversion Tracking:** Link engagement metrics to downstream conversions (clicks, signups, purchases) for full-funnel ROI
  • **Competitive Benchmarking:** Compare performance against industry averages to identify relative strengths/weaknesses

## Long-Term Opportunities
  • Multi-channel attribution tracking to measure how social engagement influences other marketing channels
  • Automated A/B testing framework for continuous content optimization
  • Real-time alerting system when engagement drops below benchmarks

## Current Limitations
  • Dataset scope limited to select platforms (excludes TikTok, LinkedIn, YouTube)
  • No demographic segmentation of engaged users
  • Lacks campaign-specific ROI attribution
  • Static dataset vs real-time API integration for continuous monitoring

**Technologies:** Python | Pandas | NumPy | Seaborn | Matplotlib | Power BI | Time Series Analysis | Content Analytics
