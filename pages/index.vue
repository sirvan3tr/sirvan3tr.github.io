<template lang="pug">
v-container
  p.text-h3 Sirvan Almasi
  p Welcome to my personal page, I am a PhD Candidate at Imperial College London's Computing department, and under the supervision of Prof William Knottenbelt and Prof Philip Treleaven.
  p Please note that this website does not include everything about me and my work.
  p
    v-btn(text href='https://github.com/sirvan3tr')
      v-icon(small left) mdi-github
      | Github
    v-btn(text href='https://www.linkedin.com/in/salmasi/')
      v-icon(small left) mdi-linkedin
      | LinkedIn
    v-btn(text href='https://twitter.com/sevthreetr')
      v-icon(small left) mdi-twitter
      | Twitter

  v-row.d-flex
    v-col(lg='9')
      v-card
        v-card-title Projects
        v-card-text
          div.text-caption Some of the projects I have worked on or am working on in no particular order.
          ol
            li
              a(href="https://sirvan3tr.github.io/pandas_game/")
                h3 Pandas Game
              div.text-caption Prototype of a game to learn coding, e.g. Pandas.
            li
              a(href="https://aquamarine-cocada-c77c38.netlify.app")
                h3 ICLR2024 Explorer
              div.text-caption Simple app to filter and explore ICLR2024 papers.
            li
              h3 AXON
              div.text-caption Re-make of the OpenBCI EEG hardware using ESP32.
            li
              h3 Stoic Writer
              div.text-caption Writing app that forces you to just write. It also tracks your progress.
            li
              h3 InnovationLab (at UCL with Prof. Philip Treleaven)
              div.text-caption Rethinking the science of innovation.
            li
              h3 InnovoTeams
              div.text-caption Creating high-performing teams and co-founder matching using skills (via NLP techniques) and persoanlity matching.
            li
              h3 The Innovation Estimate.
              div.text-caption Analytical framework to create a strategy for a venture. Based on The Combat Estimate.
            li
              h3 deeID: Identity and Authentication System.
            li 
              h3 Document Provenance Using Blockchain.
            li
              h3 SmartCommuter (Founder)
              div.text-caption
                | Novel property search engine.
                |  Was part of 
                a(href='https://conceptionx.org/' target='_blank') ConceptionX&apos;s
                |  Cohort III accelerator programme.
            li
              h3 BrainGym (Engineer and Co-founder)
              div.text-caption
                | Neurofeedback device to improve focus and concentration.
                |  Was part of 
                a(href='https://conceptionx.org/' target='_blank') ConceptionX&apos;s
                |  Cohort 4 accelerator programme.

      v-card.mt-3
        v-card-title Posts
        v-card-text
          ul
            li
              a(href="docs/gpt2.pdf")
                h4 Mathematics of the Attention Layer (draft)
              div.text-caption My own mathematical intuition of the attention layer.
      v-card.mt-3
        v-card-title Papers, Essays, and Dissertations
        v-card-text
          ol
            li
              | Mar 2024 - S. Almasi and W.J. Knottenbelt.  
              a(href="docs/20240319_passwordninja.pdf") PasswordNinja: Password Composition and Complexity Insights from Manually Labelled Datasets
            li
              | Mar 2024 - S.Almasi.  
              a(href="docs/papers/20240422_tie.pdf") The Innovation Estimate
            li
              | Mar 2022 - S. Almasi and W.J. Knottenbelt.  
              a(href='docs/papers/api_modelling_techniques.pdf') API Modelling Techniques 
            li
              | Feb 2020 - S. Almasi and W.J. Knottenbelt. 
              a(href='docs/papers/Protecting_user_secrets_NDSS_Workshop.pdf') Protecting Users from Compromised Browsers andForm Grabbers.
              i  NDSS Workshop on Measurements, Attacks, and Defenses for the Web (MADWeb 2020)
              | , San Diego, California, USA, Feb 2020.
            li
              | Oct 2019 - S. Almasi  
              a(href='docs/essays/royalsignalessay_sirvan.pdf') Impact of Technology on the Battlefield of the Future.
            li
              | Jan 2019 - S. Almasi and W.J. Knottenbelt.  
              a(href='docs/papers/deeID_USENIX_Feb_2020wnames.pdf') Human Identity and the Quest to Replace Password Continued
          hr
          v-row
            v-col(cols="auto")
              img(src="img/lsr_poster_small.png")
            v-col
              div.text-caption PhD Computer Science - 2024
              h3 Protecting User Secrets in Hostile Environments (ongoing)
              a(href="docs/20240404-LSR_poster-almasi.pdf")
                v-icon(color="red") mdi-file-pdf-box
                | Late Stage Review Poster
          hr
          v-row
            v-col(cols="auto")
              img(src="img/beng-poster-small.jpg")
            v-col
              div.text-caption BEng Aerospace Engineering Dissertation - 2014
              h3 Use of Turboprop Propelled Aircraft and Cargo UAV’s for Long Haul Flights
              a(href="img/beng-poster.jpg")
                v-icon(color="red") mdi-file-image
                | POSTER
              a(href="docs/degrees/Use of turboprop propelled aircraft and Cargo UAV.pdf") 
                v-icon(color="red") mdi-file-pdf-box
                | DISSERTATION
      v-card.mt-3
        v-card-title Presentations
        v-card-text
          ul
            li
              | Innovation of Bitcoin--how to take it mainstream. 
              a(href='docs/presentations/2020-10-09_sirvan_bitcoin-innovation.pdf') [pdf]
    v-col(lg='3')
      v-card
        v-card-title Links and other
        v-card-text
          ul
            li
              a(href='http://www.norvig.com/') Peter Norvig
              v-icon(small) mdi-launch
            li
              a(href='http://norvig.com/21-days.html') Teach yourself programming in ten years
              v-icon(small) mdi-launch
            li
              a(href='http://www.catb.org/~esr/faqs/hacker-howto.html') Eric Raymond&apos;s How to become a hacker
              v-icon(small) mdi-launch
            li
              a(href='http://www.paulgraham.com/useful.html') Paul Graham&apos;s How to write usefully
              v-icon(small) mdi-launch
            li
              a(href='docs/inspire/Toolsmith-CACM.pdf') The Computer Scientist as a Toolsmith [pdf]
</template>