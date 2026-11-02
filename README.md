# TM App — implementation scaffold

This is the first implementation pass from the supplied TM Build Specification: a mobile-first PWA shell/design system with responsive navigation and the required top-level screens. It deliberately does not fake backend-dependent actions.

## Run
1. `npm install`
2. `npm run dev`
3. Open the local Vite URL.

For PWA installation, serve the production build over HTTPS.

## Implemented in this pass
- PWA manifest, theme metadata, service worker shell cache, install guidance.
- Oxblood/pink design system, accessible tap targets, responsive layouts.
- Phone/tablet/laptop navigation structure.
- Welcome, guest mode, onboarding, login, Home, Chats, Chat, Discover, Profile, AI Studio lock, Plans, Wallet, Settings and Safety screens.
- Dark mode respecting the app setting.
- Basic chat composer interaction in the UI.
- Explicit Coming Soon states for backend/payment/safety actions rather than fake functionality.

## Not claimed as production-ready yet
Real TM-number authentication, secure 4-digit code hashing/lockout, Supabase database/RLS, realtime messaging, media upload/transcoding, payments/webhooks, push notifications, moderation, and admin operations require backend integration and device testing. The supplied specification requires those to be completed before release.
