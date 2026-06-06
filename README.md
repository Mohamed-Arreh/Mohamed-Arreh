# Mohamed

I'm building a tool that helps auto repair shops in Canada recover declined work. It basically takes the brake jobs and suspension work customers said "not today" to and uses Claude to send personalized text follow-ups. Most shops have $50k+ of this sitting in their software and never get to it.

The main project is here: [auto-shop-reactivation-saas](https://github.com/Mohamed-Arreh/auto-shop-reactivation-saas).

The stack is Next.js, Supabase, Claude API, Twilio, Stripe. Pretty standard for this kind of thing. Most of my time recently has been on schema design (multi-tenant with RLS) and figuring out how to build provider-agnostic adapters so I can swap between Tekmetric, Mitchell, CSV uploads, etc. without rewriting the ingestion pipeline.

Based in Ottawa.
