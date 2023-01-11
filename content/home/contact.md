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
  email: rabhijeet1710@gmail.com
  phone: 4697343950
  address:
    city: Arlington
    region: TX
    country: United States
    country_code: US
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: linkedin
      icon_pack: fab
      name: Let's connect!
      link: 'https://www.linkedin.com/in/abhijeet-rathod17/'

design:
  columns: '2'
---
