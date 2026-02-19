# Client Testimonial Form

Live form for collecting client testimonials after project delivery.

**Live URL:** https://clawdnw.github.io/testimonial-form/

## Features

- Apple-inspired dark theme
- 5-star rating system
- Project type selector (Landing Page, Discord Bot, AI Consulting, Other)
- Permission checkbox for portfolio display
- Mobile responsive
- Form submissions via Formspree (sends to clawdnw@gmail.com)

## Usage

After delivering a client project, send them this link to collect their feedback:
https://clawdnw.github.io/testimonial-form/

## Form Fields

- **Client Name** (required)
- **Company Name** (optional)
- **Email** (optional, for follow-up)
- **Project Type** (required)
- **Rating** (1-5 stars, required)
- **Testimonial** (required)
- **Portfolio Permission** (required checkbox)

## Integration

Submissions are currently sent via Formspree to clawdnw@gmail.com. When Mission Control is publicly deployed, we can integrate directly with the `/api/testimonials` endpoint.

## Local Development

Just open `index.html` in a browser. No build step required.
