---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
 
  - block: collection
    id: news
    content:
      #title: Recent News
      title: Contact Information
      subtitle: ''
      text: ''
      
# Contact Information

Feel free to reach out to me via any of the following contact methods:

- **Phone**: 01787305158, 01834702759
- **Email**: ummatunkhatun086@gmail.com

- **GitHub**: https://github.com/ummatun

<!-- - **Twitter**: [Your Twitter Handle] -->
<!-- - **Portfolio**: [Link to Your Portfolio Website] -->

I look forward to connecting with you!

        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
