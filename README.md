# KYBA Review SaaS

This folder contains the core files for the KYBA Review system:

- **review-widget.html**: Embeddable review widget for clients. Pass `?project=yourprojectslug` in URL.
- **dashboard.html**: Admin dashboard to view reviews per project slug.

## Usage

1. Upload files to your web hosting or GitHub Pages.
2. To embed widget on client sites:
   ```html
   <iframe src="https://yourdomain.com/review-saas/review-widget.html?project=kybaenergy" width="400" height="600"></iframe>
