---
title: Contact
type: landing
date: 2023-12-03

sections:
  - block: contact
    content:
      title: Contact
      subtitle:
      text: " "
      # Contact (add or remove contact options as necessary)
      appointment_url: 'https://calendly.com/amarmandavia'
<!-- Calendly badge widget begin -->
<link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
<script type="text/javascript">window.onload = function() { Calendly.initBadgeWidget({ url: 'https://calendly.com/amarmandavia', text: 'Schedule time with me', color: '#0069ff', textColor: '#ffffff', branding: false }); }</script>
<!-- Calendly badge widget end -->

      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/amar36'
        - icon: google-scholar
          icon_pack: ai
          link: https://scholar.google.com/citations?user=ce1HkCQAAAAJ&hl=en
        - icon: github
          icon_pack: fab
          link: https://github.com/AmarMandavia/
        - icon: linkedin
          icon_pack: fab
          link: https://www.linkedin.com/in/amar-mandavia/

      # Automatically link email and phone or display as text?
      autolink: true
      
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
        
    design:
      columns: '1'
---