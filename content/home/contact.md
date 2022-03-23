---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: zthabet at wellesley dot edu
  contact_links:
    - icon: twitter
      icon_pack: fab
      link: 'https://twitter.com/zahra_thab'
    - icon: linkedin
      icon_pack: fas
      link: 'https://www.linkedin.com/in/zahra-t-098760221/'

design:
  columns: '2'
---
