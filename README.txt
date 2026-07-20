NOVA GRID — IMAGEKIT VERSION
============================

Open index.html in a browser.

All images, the footer transition video and 4 fonts are loaded from the public
ImageKit account novagridsvitlana. The hero uses hero_static_clean.jpg as a
loading poster and then reveals the local scroll-optimized hero video. The
footer transition uses 0719_poster.jpg while 0719_web_small.mp4 loads.

SCROLL-DRIVEN TEST VERSION
==========================

The local assets/video/hero-scroll.mp4 is optimized specifically for scroll
scrubbing with a keyframe every 0.2 seconds. After the animation is approved,
upload this file to ImageKit and replace its local src in index.html with the
new public URL. The supplied scroll-engine script is included without changes.
The hero video reveal also includes a Chrome-safe metadata/data fallback so the
scroll-controlled video cannot remain hidden behind its loading poster.

CALM FOOTER REVEAL
==================

The particle field plays automatically while visible. The dark STAY ON THE GRID
panel is no longer sticky or scrubbed by scroll: it rises only 38 px and fades
in once, creating a quieter ending after the strong scroll-driven hero.

All editorial and content cards share one restrained hover treatment: a 5 px
lift, a cool highlighted border, a soft shadow and a subtle image zoom.

SECTION TRANSITIONS
===================

The hero-to-featured transition remains the main scroll-driven moment. Signals,
Meet Nova and Stories each enter once as a whole section with a subtle upward movement.
Only the two large showcase images use a soft mask reveal; individual cards do
not receive repeated entrance animations.

The isolated micro-particle divider was removed to keep the middle of the page
clean and reserve the particle language for the footer. Every content card now
uses the same restrained hover: 5 px lift, 2.5% image zoom, and a softer cool
border and shadow.

The local hero video is encoded for Chrome-friendly scroll seeking. A public
ImageKit hero video is included as a second source if the local asset cannot be
loaded, and an independent scroll synchronizer provides a safe fallback without
changing the supplied locked hero engine.

The hero background video autoplays and loops continuously, matching the earlier
Nova Grid behavior. Scroll still controls the hero text, overlay and section
transition, while the background remains alive when the page is idle.

INTERACTION UPDATE
==================

The Signals section includes a seamless three-copy marquee moving one exact
copy-width in 16 seconds, linear and infinite. The third copy preserves full
coverage on ultra-wide screens while keeping the same visual speed; hover or
keyboard focus pauses it. Mobile navigation is a full-screen dark menu with an
animated burger/close control, Escape support and page-scroll locking. Desktop
hero navigation is synchronized with the custom momentum-scroll engine: Games,
Tech and Culture open the corresponding story filter, while About restores all
stories. Hero links, feature toggles and newsletter feedback remain functional.

The hero network video is restored to its original full-bleed framing. The
footer particle video uses a subtle 2% overscan so both moving backgrounds reach
every edge without visible vertical seams. When filtered, the square technology
feature is reduced proportionally to 560 px so the complete chip remains clear.
In the unfiltered editorial view, the same square source is also kept
proportional at 524 px on desktop and 464 px on medium screens.

GRAPHEK-INSPIRED NAVIGATION UPDATE
==================================

After the hero, a compact right-side capsule shows page progress, opens quick
links to Hero, Grid, Nova and Stories, and includes a back-to-top control. On
phones the capsule simplifies to the back-to-top arrow only.

On large desktop screens the Signals panel is the site's single immersive
scale transition: it begins almost full-screen, then gently contracts into the
existing rounded dark block while its content remains together. The hero is
unchanged. The Stories heading reveals progressively word by word; reduced-
motion and smaller-screen visitors receive the normal static layout.

HEADER POLISH
=============

The floating glass header now has a stronger cold-blue surface, a compact
circular Nova Grid mark and slightly heavier, larger navigation labels. Menu
items use a restrained dark pill hover while the existing full-screen mobile
menu and all navigation targets remain unchanged.

PRE-FOOTER CTA
==============

The existing particle transition now carries the site's single focused call to
action: STEP INTO THE GRID, one concise subscription promise and the only email
form. It validates the address and shows a clear inline error or success
confirmation. The separate repeated newsletter form was removed.

The dark footer is now compact and uses four restrained visual icons for future
Instagram, Privacy, Impressum and Contact destinations. No fake links or legal
pages are included. The newsletter form submits to the verified Nova Grid
Formspree endpoint and reports real success or failure without leaving the page.

Important: do not rename, move or delete the Nova Grid files in ImageKit unless
the corresponding URLs in index.html are updated.

PRE-DEPLOY TECHNICAL AUDIT
==========================

The document includes a unique descriptive title and meta description, English
language declaration, responsive viewport, Open Graph and Twitter preview data,
a verified 1200 x 630 ImageKit preview image, ImageKit preconnect hints, favicon
and Apple touch icon. Every image has alt handling, intrinsic width and height;
all below-fold images remain lazy loaded. The heading hierarchy contains one H1
followed by H2 section titles and H3 card titles.

All current ImageKit image, video and font URLs returned HTTP 200 during the
audit. Local favicon, touch icon and scroll video paths exist. The supplied
locked hero animation script remains unchanged.

Before production, add the final HTTPS og:url/canonical URL. Insert GA4 and
Meta Pixel only after the correct IDs and consent setup are available. Footer
destination icons intentionally remain visual until real URLs or legal
destinations are supplied.

STORY PAGES
===========

stories.html is the complete filterable article archive. Ten individual pages
inside the articles folder contain the supplied Nova Grid article texts, unique
titles and descriptions, responsive editorial layouts and related-story links.
All ten story cards on the home page now open their matching article, and the
hero LATEST STORIES button opens the archive. These pages work as local files
and require no server.

MOBILE HERO COMPOSITION
=======================

The phone layout keeps the approved desktop hero untouched while using a
dedicated composition below 640 px: the NOVA GRID title retains its original
wide proportions, Nova is larger and moved into the frame, the lower gradient
protects legibility, and both hero actions form one balanced full-width row.

AUDIT PACKAGE FIXES — 2026-07-20
================================

The ZIP directory separators were normalized for Linux hosting. The shared
design-system.css file is now linked on the home page, archive and every article,
so the existing WOFF2 fonts, font-display: swap declarations and shared tokens load.
Twitter preview metadata, OG image alt text, robots directives and accessible menu
labels were completed where missing.

Before deployment, replace YOUR-DOMAIN in the commented canonical/og:url templates,
robots.txt and sitemap.xml with the final HTTPS domain. Keep the robots Sitemap line
commented until that replacement is complete.
