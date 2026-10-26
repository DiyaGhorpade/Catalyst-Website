CATALYST MANAGEMENT CONSULTING - WEBSITE FILES
==============================================

What's here
  index.html    the whole website (Home, About, Services, Training, Case Studies, Insights, Contact)
  img/          photos (Neovia and client branding blurred) and your founder photo
  logo.svg      logo, scalable (use for print and LinkedIn banners)
  logo.png      logo, transparent PNG
  favicon.svg   browser-tab icon

Go live on Cloudflare Pages (free)
  1. Create a free account at dash.cloudflare.com
  2. Workers & Pages > Create > Pages > Upload assets
  3. Drag this whole folder in and deploy. You get a free *.pages.dev address.
  4. Custom domains > add your domain (e.g. catalystmgt.in) and follow the DNS steps.

Make the contact form email you
  1. Create a free access key at web3forms.com using Umesh@catalystmgt.in
  2. In index.html, near the bottom, set:
       const FORM_ENDPOINT = "https://api.web3forms.com/submit";
       const FORM_KEY = "your-access-key";
  Until then, the form shows the visitor their message to copy and send by email or WhatsApp.
