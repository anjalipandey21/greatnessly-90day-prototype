# Greatnessly — 90-Day Journey Prototype

A browser-based interactive product concept connecting a future-self blueprint to daily action, reflection and weekly accountability.

## Explore

**Live prototype:** [greatnessly-90day-prototype.vercel.app](https://greatnessly-90day-prototype.vercel.app)

The public Vercel link opens without a login and includes the current design and animated circles, with pause controls and reduced-motion support.

Serve this directory with any static server, for example `python -m http.server 4173`, then open http://localhost:4173.

The app includes a three-step setup, sample dashboard, daily check-ins, editable goals and milestone progress, a 90-day journey map, journaling, progress insights and a sample accountability circle.

The Next Chapter visual refresh adds an interactive welcome-page goal preview, a 90-day journey scrubber, persistent Daylight and Midnight themes, focus sessions with duration presets and pause/resume, and reduced-motion-aware completion feedback.

All changes are stored in the browser. AI guidance is curated. Sample circle activity and RSVP do not send messages or book events. Production authentication, authorization, secure cloud storage, RLS, billing and live AI are outside this prototype.

## Walkthrough

1. Explore the interactive chapter card and journey slider on the welcome page.
2. Try Daylight and Midnight with the theme control in the header.
3. Open Maya's sample dashboard and start a focus session on an unfinished promise.
4. Complete a daily check-in and open the score breakdown.
5. Add a goal, update a milestone, and save a reflection.
6. Explore the sample circle and weekly reset.
7. My future self → Start a fresh journey opens the first-time setup.
8. Settings → Reset demo restores the sample journey.

## Verification

JavaScript syntax and DOM interaction checks passed across onboarding, validation, actions, goals, milestones, journal, local circle posts, RSVP, settings, persistence, score details, reset, themes, goal preview, the journey slider, focus timing and reduced motion. The self-contained HTML also starts without JavaScript or CSS parser errors. Focused visual browser checks passed for the animated compass and community circle on desktop and mobile, including pause/resume, reduced motion and 390px responsive fit. The production Vercel link was tested in a fresh browser without authentication. Other pages still need a full visual browser review.

## Deploying to Vercel

This is a static site with no build or installation step. `vercel.json` configures the repository root for Vercel's Other framework preset. `.vercelignore` limits uploads to the public app assets and hosting configuration. Local Vercel state, environment files and dependencies are excluded from Git.

The current production deployment uses the Vercel CLI. Automatic Git deployments have not been configured.

## Artwork

Original mountain landscape generated with ImageGen for this prototype. No third-party stock image dependency.
