# Ownership, Copyright, Attribution & Takedown Notice

**Document Reference:** CF-IP-2026-V2  
**Effective Date:** October 30, 2026  
**Last Updated:** November 24, 2026  
**Author & Sole Rights Holder:** Govind Vijayakumar  
**Application Identity:** Clearfold: Multi-Angle News (`org.clearfold.news`, v1.0.71+) *(formerly developed under the working name ClearNews)*  
**Support, Publisher Opt-Out & Takedown Contact:** `support.clearnews@gmail.com`  
**Proprietor Licensing & IP Inquiries:** `govind.vij.26@gmail.com`  

---

## 1. Copyright Declaration & Scope of Ownership

© 2026 Govind Vijayakumar. All Rights Reserved.

**Clearfold** is an independent, ad-free, on-device Android RSS news reader and multi-perspective news discovery application. Clearfold is proprietary, closed-source software; while currently offered free of charge without advertising, the rights holder reserves all commercial and non-commercial rights.

1. **Protected Human-Authored Works:** Copyright applies to all original human-authored source code (Kotlin / Jetpack Compose), software architecture, on-device clustering and filtering algorithms, Room database schemas, DataStore state models, user interface implementations, original editorial copy, and documentation created for Clearfold.
2. **Third-Party Open-Source Software & Public Datasets:** Clearfold incorporates third-party open-source libraries (such as AndroidX/Jetpack, Kotlin Coroutines, OkHttp, Coil, RSS Parser, and Jsoup) and derives media-spectrum metadata from the open-source Idiap / MBFC dataset (`Apache-2.0`). Clearfold makes no exclusive ownership claim over those third-party works; full license attributions are maintained in [`THIRD_PARTY_NOTICES.md`](THIRD_PARTY_NOTICES.md).
3. **Decorative AI-Assisted Illustrations:** Certain decorative onboarding, visual guide, settings, and empty-state illustrations in the app were produced with AI image-generation tools and edited for UI integration. No exclusive human-authorship copyright registration claim is asserted over purely AI-generated graphical elements where excluded by applicable copyright law.
4. **Reservation of Rights:** Except as expressly permitted by mandatory law or prior written authorization from the copyright holder, no portion of Clearfold's proprietary source code or compiled distribution packages (`.apk` / `.aab`) may be copied, redistributed, repackaged, mirrored, sublicensed, reverse-engineered, or used to train machine learning models.

---

## 2. Brand Names & Feature Nomenclature

The following brand names, tagline, and product feature names are used in commerce by Govind Vijayakumar to identify Clearfold and its user-facing capabilities. Common-law trademark rights are claimed in connection with news aggregation and RSS reading software:

| Mark / Feature Name | Mark Type | Context in Clearfold |
| :--- | :--- | :--- |
| **Clearfold™** | Primary Brand Mark | Application name, brand identity, and Android package namespace (`org.clearfold.news`). |
| **"The Full Picture, Clearly Unfolded"™** | Tagline / Slogan | Official brand tagline displayed in the app masthead and Google Play Store listing. |
| **Clearfold Pulse Summary™** | Feature Name | On-device extractive multi-angle briefing compiled locally from publisher RSS summaries with explicit source attribution. |
| **Spectrum Split™** | Feature Name | Story-level comparison matrix displaying participating newsrooms across Political Leaning, Factuality, and Ownership. |
| **Unseen Angles™** | Feature Name | On-device detection highlighting stories covered predominantly by one side of the political spectrum while omitted by another. |

*(Note: Common-law trademark notice uses `™`. Registered federal/national trademark protection `®` applies only if and when formally registered with a relevant trademark office such as the USPTO or IP India.)*

---

## 3. On-Device Architecture & Zero-Scraping Design

Clearfold (`ClearNews-withoutScraping`) is engineered to operate **100% on-device** with respect for publisher copyrights and reader privacy:

1. **Direct RSS/Atom Retrieval Only:** The app connects directly from the user's device to publicly syndicated RSS/Atom feeds. Clearfold does **not** perform server-side article scraping, does **not** bypass paywalls, and does **not** re-host full article bodies.
2. **Local Processing & Storage:** Story clustering, topic/region filtering, keyword/spoiler muting, saved items, and reading preferences are processed and stored locally using Android Room and Jetpack DataStore with zero user accounts, zero GPS tracking, zero ads, and zero analytics SDKs.
3. **Dynamic Monogram Avatars:** Newsroom badges in the Channels directory and story cards are generated programmatically using typography and harmonic color palettes (`SourceMonogramAvatar`) rather than bundling or redistributing third-party publisher trademark logos.

---

## 4. Respect for News Publishers & Editorial Cartoonists

Clearfold respects the copyrights, trademarks, and editorial independence of every referenced newsroom and cartoonist:

1. **Publisher Ownership Retained:** All news headlines, short RSS feed excerpts, article preview thumbnails, and editorial cartoons remain **100% the intellectual property** of their respective publishers, news agencies, and cartoonists.
2. **No Affiliation or Endorsement:** Clearfold is independently developed and is not affiliated with, funded by, sponsored by, or endorsed by any listed publisher, political organization, or government entity.
3. **Nominative Identification & Direct Attribution:** Publisher names and domains are used solely for nominative source identification so readers know where each RSS item originates. Every story opens directly on the publisher's official website via Android Custom Tabs / browser so publishers retain their audience and pageviews.
4. **Cartoon of the Day (Political Satire):** Editorial political satire cartoons displayed in Search are fetched directly from public editorial cartoon RSS feeds (currently dedicated political cartoonist feeds from *The Guardian*, *Truthdig*, and *The Hindu* Cartoonscape). Every cartoon displays the publisher name, cartoonist credit when provided in the feed, and a prominent clickable **"Open Source"** / **"Open on [Publisher]"** link directly to the original publication page.
5. **Media Bias & Factuality Methodology:** Leaning and factuality labels reference the open-source *News Media Bias and Factuality Dataset* (Sergio Burdisso et al., Idiap Research Institute / MBFC, `Apache-2.0`) alongside public ownership registries. These labels are informational context only and not statements of legal fact or editorial endorsement.

---

## 5. Publisher Opt-Out, Corrections & Copyright Takedown (DMCA)

If you are a news publisher, cartoonist, or rights holder and wish to:
- Request immediate removal (opt-out) of your RSS feed or editorial cartoon feed from Clearfold,
- Report a copyright or attribution concern (including DMCA takedown notices), or
- Request a correction to channel URL, paywall flag, or metadata,

please email **`support.clearnews@gmail.com`** with:
1. Your name, organization, and authority to act for the rights holder,
2. The specific feed URL, publication name, or item at issue, and
3. The action requested (removal, URL update, or attribution correction).

Verified publisher opt-out and copyright takedown requests are prioritized and typically processed within **2 business days**.

---

## 6. Legal & Licensing Contacts

- **Rights Holder:** Govind Vijayakumar
- **General Support, Publisher Opt-Out & Copyright Takedown:** `support.clearnews@gmail.com`
- **Proprietary Licensing & IP Inquiries:** `govind.vij.26@gmail.com`
- **Public Legal Pages:**
  - Privacy Policy: `https://vgovind94.github.io/clearnews-privacy/privacy-policy.html`
  - Contact & Entity Information: `https://vgovind94.github.io/clearnews-privacy/contact.html`
