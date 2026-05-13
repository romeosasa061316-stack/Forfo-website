# FORFO Hair & Makeup Studio Website

## Contact Form Setup

To receive form submissions via email, you need to set up Formspree:

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Sign in with your email: romeosasa061316@gmail.com
3. Create a new form and copy the form ID (it looks like: xxxxxxxxxxxx)
4. Replace the form action URL in `index.html`:

   Change this line:
   ```html
   <form id="contactForm" class="contact-form" action="https://formspree.io/f/xpznqkgj" method="POST">
   ```

   To this (replace YOUR_FORM_ID with your actual Formspree form ID):
   ```html
   <form id="contactForm" class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

5. That's it! Form submissions will now be sent to your email.

## Features

- Responsive design
- Gallery lightbox
- Contact form with email integration
- Social media links
- WhatsApp integration

## Local Development

Run the website locally:
```bash
python -m http.server 8000
```

Then visit: http://localhost:8000