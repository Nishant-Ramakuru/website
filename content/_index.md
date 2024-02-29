---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "10rem"

sections:
  - block: hero
    content:
      title: A Technology Innovation Partner
      text: Artificial Intelligence, Data Analytics and Full Automation Powerhouse
    
      
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: wallpaper.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1M+"
          description: |
            Websites built  
            with Hugo Blox
        - statistic: "10k+"
          description: |
            GitHub stars  
            since 2016
        - statistic: "3k+"
          description: |
            Discord community  
            for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: What we do
      text: Build your future with us 🧱
      items:
        - name: Robotics & Automation
          icon: magnifying-glass
          description: Sensors, Robotics, and Internet of Things (IoT)
        - name: Advanced Data Analytics
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Robotic Process Automation (RPA)
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: Industry 4.0
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Consultancy
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["10rem", 0, "10rem", 0]

  - block: features
    content:
      title: "Meet The Leadership"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["10rem", 0, 0, 0]
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Nishant Ramakuru
          text: Co-founder CEO and CTO, Head of Research and Development
          feature_icon: check
          features:
            - "Robotics & AI postgrad, University of Bristol, UK"
            - "Research Background in Game-Theory, Genetic Algorithms, Multi-agent Modelling"
            - "Experience in Defence sector"
          # Upload image to `assets/media/` and reference the filename here
          image: nishant.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        - title: Harshit Khanna
          text: Co-founder CEO and CTO, Head of Robotics Technology
          feature_icon: bolt
          features:
            - "Ex-KUKA"
            - "6+ Years working experience in Robotic Solutions"
            - "Experience in Defence sector"
          # Upload image to `assets/media/` and reference the filename here
          image: harshit.png
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
        - title: David Guetta
          text: Co-founder CEO and CTO, Head of Engineering
          feature_icon: bolt
          features:
            - "Ex-KUKA"
            - "6+ Years working experience in Robotic Solutions"
            - "Share your site and get feedback"
          image: david.png

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
