# Security Awareness Demonstration

Educational security-awareness demonstration using normal browser permission prompts.

## Files

- `index.html` — public demonstration page.
- `admin.html` — authenticated administrator dashboard.

## Supabase

The frontend uses the Supabase publishable key only. The private Storage bucket and administrator access remain protected by Supabase policies and the Edge Function.

## Deployment

This is a static HTML project and can be deployed directly to Vercel.

Camera, screen sharing, and geolocation are requested only through the browser's standard permission mechanisms.
