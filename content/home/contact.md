---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact
#active: true  # Activate this widget? true/false
# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: "📬 Contact"
subtitle:

content:
  # Contact (edit or remove options as required)
  email: info@geogroup.ai
  phone:
  address:
    street:
    city: Mansourieh
    region: Beirut
    postcode: '11 828'
    country: Lebanon
    country_code: LB
  coordinates:
    latitude: '33.8577207'
    longitude: '35.5676237'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Follow us on Twitter
      link: https://twitter.com/AliJGhandour
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true
      success_url: /thank-you
      attachments: true
  
design:
  columns: '2'
  background:
     color: "#FFFFF8"

advanced:
  css_style: "padding-bottom: 0px;"	
---

