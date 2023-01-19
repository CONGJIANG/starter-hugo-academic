---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: 联系方式
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
  email: cong.jiang@umontreal.ca
# phone: (+1) 519-722-6158
  address:
    street: Faculté de pharmacie, Université de Montréal
    city: Montreal
    region: 'QC'
    postcode: 'H3C 3J7'
    country: Canada
    country_code: CA
  coordinates:
    latitude: '45.50052347671281'
    longitude: '-73.61476890158093'
  directions: 
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  # contact_links:
  #   - icon: twitter
  #     icon_pack: fab
  #     name: DM Me
  #     link: 'https://twitter.com/Twitter'
  #   - icon: video
  #     icon_pack: fas
  #     name: Zoom Me
  #     link: 'https://zoom.com'

design:
  columns: '2'
---
