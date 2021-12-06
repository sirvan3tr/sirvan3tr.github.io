<template lang="pug">
v-container
  p.text-h3 Sirvan Almasi
  p Welcome to my personal page, I am a PhD Candidate at Imperial College London's Computing department, and under the supervision of Prof William Knottenbelt and Prof Philip Treleaven.
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
          ol
            li
              a(href='http://innovationlab.uk') InnovationLab.UK
              v-icon(small) mdi-launch
              | Rethinking the science of innovation.
            li
              a(href='http://innovoteams.com') InnovoTeams
              v-icon(small) mdi-launch
              | Applying NLP techniques in connecting creators using skills and personality.
            li
              strong The Innovation Estimate (draft one coming soon)
              | Analytical framework to create a strategy for a venture. Based on The Combat Estimate.
            li
              | deeID: Identity and Authentication System. Now part of 
              a(href='https://conceptionx.org/' target='_blank') ConceptionX&apos;s
              |  Cohort III venture builder.
            li Document Provenance Using Blockchain.
            li
              strong
                a(href='http://www.smartcommuter.innovationlab.uk/' target='_blank') SmartCommuter
                v-icon(small) mdi-launch
              |  Novel property search engine.
            li
              a(href='docs/essays/royalsignalessay_sirvan.pdf') Impact of technology on the battlefield of the future.
              |  [pdf]
      v-card.mt-3
        v-card-title Papers and publications
        v-card-text
          ul
            li
              | S. Almasi and W.J. Knottenbelt. 
              a(href='docs/papers/deeID_USENIX_Feb_2020wnames.pdf') Human Identity and the Quest to Replace Password Continued
              |  - Being Reviewed
            li
              | S. Almasi and W.J. Knottenbelt. 
              a(href='docs/papers/Protecting_user_secrets_NDSS_Workshop.pdf') Protecting Users from Compromised Browsers andForm Grabbers.
              i NDSS Workshop on Measurements, Attacks, and Defenses for the Web (MADWeb 2020)
              | , San Diego, California, USA, Feb 2020.
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