Good, I have strong research backing. Now let me build the presentation.Here's your presentation + everything you need for the voiceover:

---

## 🎙️ Voiceover Script

**[TAB 1 — THE IDEA]**

> The central question of our project is simple but uncomfortable: does a platform that lets people speak freely end up rewarding them for being negative?
>
> We're going to answer this using Twitter data from the world's most influential accounts — politicians, celebrities, public figures — and run sentiment analysis alongside engagement metrics: likes, retweets, and replies. The key insight we're testing is whether negative content earns disproportionately more engagement than positive content.
>
> And this isn't just a hunch. Research from Cambridge and Nature found people are nearly _twice as likely_ to share negative news articles. A UC Berkeley audit of Twitter's own algorithm found it amplifies emotionally charged, hostile content — content users themselves say makes them feel worse. So the literature is on our side. We just want to show it _in the data itself_.
>
> As a twist: we're overlaying a second dataset — Russian IRA troll tweets — to ask whether manufactured negativity mirrors organic negativity, or exceeds it."

**[TAB 2 — GENRE & MOCKUP]**

> "For our genre, we're going with the _Interactive Slideshow_ from Segel and Heer's taxonomy. Here's why: we have a clear narrative arc — we want to argue a point — but engagement data is multi-dimensional. Likes, retweets, and replies don't always move together. So readers need to be able to filter and explore themselves.
>
> In our mockup here, you can click through filter chips to see engagement breakdowns by account type. Notice what happens when you switch to Troll Accounts — the negativity index jumps to 89%. That's the 'aha' moment we're designing toward. The slideshow guides you there, then lets you poke around."

**[TAB 3 — DATA ANALYSIS]**

> "Two datasets. The influencer set from Kaggle is around 200,000 tweets, roughly 150 megabytes. Each tweet has likes, retweets, replies, date, user info, and text. The Russian troll archive is _much_ larger — around 3 million tweets across split CSV files, totalling roughly 2.5 gigabytes. It also includes account category tags like 'Left Troll', 'Right Troll', 'News Feed'.
>
> For our preliminary distributions, we're seeing the classic power law on likes and retweets — most tweets get very little, a small number go viral. About 62% of tweets in the influencer set score negative on a VADER sentiment pass. That's our baseline. And we'll build from there."

---

**Research sources worth mentioning:**

- Watson et al. (2024) in _Nature Scientific Reports_ — 1.91× more sharing of negative content
- Milli et al. (2024) via Knight First Amendment Institute — Twitter algorithm audit (N=806)
- ScienceDirect (2025) — toxic tweets get 85.7% more retweets
