---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "20rem"

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
          description: Transforming Industries Through Innovation, Empowering Efficiency, Precision and Revolutionizing processes with cutting-edge technology
        - name: Advanced Data Analytics
          icon: bolt
          description: Navigating the Data Landscape, Unleashing Powerful Insights and Strategic Guidance through Innovative Data Analysis Approaches
        - name: Robotic Process Automation (RPA)
          icon: sparkles
          description: Optimizing Workflows, Amplifying Productivity, Harnessing the Transformative Capabilities of Robotic Process Automation
        - name: Industry 4.0 & IoT
          icon: code-bracket
          description: Embracing the Future, Exploring the Synergy of Industry 4.0 and the Internet of Things to Drive Innovation and Connectivity
        - name: Consultancy
          icon: star
          description: Elevating Efficiency and Precision, Empowering Industries through Expert Robotic Solutions Consultancy
        - name: Control Systems & Monitoring
          icon: rectangle-group
          description: Fostering Precision and Stability, Pioneering Control Systems for Seamless Operations and Enhanced Performance
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
      title: Musketeer Robotics
      text: We are a Full Automation and Digital Technology Powerhouse. Our portfolio offers a wide range of smart, secure, and safe solutions, covering, Artificial Intelligence, Big Data, Cybersecurity, Internet, Software and Hardware. We are a comprehensive turn-key high-tech provider, from Strategic Advisory and Project Management, to full Executive Services in Design, Engineering, Data Science, Operations, Growth, Training, Business Strategy and Risk Management — and everything in between. 
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-gray-100 dark:bg-gray-900"
        css_style: ""
---
