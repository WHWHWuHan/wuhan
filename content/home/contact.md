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
  email: lzhlt01@hotmail.com
  address:
    street: 柳台大道555号
    city: 成都市
    region: 四川省
    postcode: '611130'
    country: 中国
    country_code: CN
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: Researchgate
      icon_pack: fab
      name: DM Me
      link: 'https://www.researchgate.net/profile/Longtao-He'

design:
  columns: '2'
---
