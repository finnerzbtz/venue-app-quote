# Estimated Running Costs — NYC Venue Discovery App

**Prepared by Grow Smart AI — February 2026**

These are the estimated monthly costs for hosting and running the app post-launch. Most services have generous free tiers that will cover the development and early launch phases.

---

## Development Phase (pre-launch)

| Service | Cost | Notes |
|---------|------|-------|
| Supabase (Database) | **$0** | Free tier: 500MB database, 1GB storage, 50K monthly active users |
| Google Places API | **$0** | $200/month free credit included |
| Transactional Email (Resend) | **$0** | Free tier: 3,000 emails/month |
| Hosting (Vercel/Expo) | **$0** | Free tier covers development |
| Apple Developer Account | **$99/year** | One-time setup, required for App Store |
| Google Play Developer | **$25 one-time** | One-time setup, required for Play Store |

**Development phase total: ~$0/month** (plus ~$124 in one-time store fees)

---

## Early Launch (0–500 users)

| Service | Monthly Cost | Notes |
|---------|-------------|-------|
| Supabase | **$0** | Free tier handles up to ~50K MAU |
| Google Places API | **$0–50** | ~$17 per 1,000 Place Details requests. $200/month free credit covers ~11,700 requests |
| Transactional Email | **$0** | 3,000 emails/month free (Resend) |
| Hosting | **$0–20** | Free tier likely sufficient; Pro ~$20/month if needed |

**Early launch total: ~$0–70/month**

---

## Growth Phase (500–5,000 users)

| Service | Monthly Cost | Notes |
|---------|-------------|-------|
| Supabase Pro | **$25** | 8GB database, 100GB storage, daily backups |
| Google Places API | **$50–200** | Depends on venue page views. Cache aggressively to reduce calls |
| Transactional Email | **$0–20** | Resend free up to 3K/month, then ~$20/month |
| Hosting | **$20** | Vercel Pro or equivalent |
| Error Monitoring (Sentry) | **$0** | Free tier: 5K events/month |

**Growth phase total: ~$95–265/month**

---

## Cost Reduction Strategies

1. **Cache Google data aggressively** — Store venue details locally after first fetch. Reduces API calls by 80%+.
2. **Rate limit API calls** — Only fetch fresh data when a venue hasn't been updated in 24–48 hours.
3. **Google's $200 free credit** — Covers roughly the first 11,700 Place Details calls per month at no cost.
4. **Auto-switch to platform reviews** — After 10+ user reviews, stop pulling Google data for that venue entirely.
5. **Supabase free tier** — Handles significant traffic before needing to upgrade.

---

## Summary

| Phase | Users | Est. Monthly Cost |
|-------|-------|-------------------|
| Development | 0 | $0 |
| Early launch | 0–500 | $0–70 |
| Growth | 500–5,000 | $95–265 |
| Scale | 5,000+ | $300+ (priced at that stage) |

**The app is essentially free to run during development and early launch.** Costs only start appearing at scale, by which point the app should be generating revenue or have investment.

---

*Grow Smart AI — growsmartai.co.uk*
