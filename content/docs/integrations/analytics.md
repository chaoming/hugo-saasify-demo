---
title: Analytics
weight: 1
---

# Analytics Integration

Track your website performance with popular analytics platforms.

## Google Analytics 4

Add your GA4 measurement ID to enable tracking:

```toml
# hugo.toml
[params.analytics]
  googleAnalytics = "G-XXXXXXXXXX"
```

## Plausible Analytics

For privacy-focused analytics, use Plausible:

```toml
[params.analytics]
  plausible = "yourdomain.com"
```

## Custom Events

Track custom events like button clicks and form submissions:

```javascript
// Track a signup button click
plausible('Signup', { props: { plan: 'pro' } });

// Or with Google Analytics
gtag('event', 'signup', { plan: 'pro' });
```

## Privacy Considerations

Hugo Saasify respects user privacy:

- Analytics scripts only load after cookie consent (if enabled)
- No personal data is collected by the theme itself
- You control what data is sent to third-party services
