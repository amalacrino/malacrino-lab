---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

#  email: test@example.org
 # phone: 888 888 88 88
  address:
    street: Dipartimento di Agraria, Università Mediterranea di Reggio Calabria, Loc Feo di Vito
    city: Reggio Calabria
    region: RC
    postcode: '89122'
    country: Italy
    country_code: IT
  coordinates:
    latitude: '38.120727'
    longitude: '15.668327'
#  directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
 # office_hours:
 #   - 'Monday 10:00 to 13:00'
 #   - 'Wednesday 09:00 to 10:00'
#  appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

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

design:
  columns: '1'
---

