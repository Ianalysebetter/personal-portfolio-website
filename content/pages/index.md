---
type: PageLayout
title: Harsh Rana
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'I’m a data scientist, machine learning enthusiast, and tech aficionado.'
    subtitle: >-
      This is my story—packed with projects, skills, and experiences that
      showcase my journey and dedication. Dive in to explore more about my work
      and achievements.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: Python
        url: ''
      - type: Label
        label: R
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: Java
        url: ''
      - type: Label
        label: C#
        url: ''
      - type: Label
        label: Data Exploration & Transformation(ETL)
        url: ''
      - type: Label
        label: Machine Learning Model Training
        url: ''
      - type: Label
        label: Hyper-parameter Tuning
        url: ''
      - type: Label
        label: Statistical Modelling
        url: ''
      - type: Label
        label: Hypothesis Testing
        url: ''
      - type: Label
        label: Text Summarization
        url: ''
      - type: Label
        label: Sentiment Analysis
        url: ''
      - type: Label
        label: Deep Learning
        url: ''
      - type: Label
        label: Image Classification
        url: ''
      - type: Label
        label: Neural Networks
        url: ''
      - type: Label
        label: Power BI
        url: ''
      - type: Label
        label: Tableau
        url: ''
      - type: Label
        label: AWS
        url: ''
      - type: Label
        label: ' Git'
        url: ''
      - type: Label
        label: Docker
        url: ''
      - type: Label
        label: CI/CD (GitHub Actions)
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: HeroSection
    title: >-
      Embracing the spirit of "never giving up" (諦めない, Akiramenai) from Naruto,
      dattebayo!
    subtitle: >-
      Data Science Master’s student at TU Dortmund with expertise in collecting,
      processing, and analyzing large and

      complex datasets. Proficient in statistics, machine learning, AWS, and
      natural language processing (NLP). Actively

      seeking a student job or internship in Data Science or Data Analytics to
      leverage my technical skills and contribute

      to impactful projects.
    actions:
      - type: Button
        label: My CV
        altText: ''
        url: ''
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
      caption: Caption of the image
      elementId: ''
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Lets discuss..\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: ''
    subtitle: ''
    text: |+
      <section id="professional-experience">
          <h2>Professional Experience</h2>
          <div style="display: flex; justify-content: space-between;">
              <div class="experience" style="width: 45%;">
                  <h3>Data Project Coordinator</h3>
                  <p><strong>May 2019 – November 2019</strong></p>
                  <p><strong>Uplers Private Limited, Ahmedabad, India</strong></p>
                  <ul>
                      <li>Managed and coordinated multiple projects, ensuring timely delivery and seamless execution.</li>
                      <li>Collaborated with international clients to define project scope and align deliverables, utilizing tools like Jira and Confluence for efficient task management.</li>
                      <li>Conducted budget analysis for high-value projects using Power BI, enabling cost tracking and proactive risk mitigation.</li>
                      <li>Acted as the primary communication liaison, maintaining strong stakeholder engagement through tools like Slack and Skype, effectively minimizing project delays.</li>
                  </ul>
              </div>
              <div class="experience" style="width: 45%; text-align: right;">
                  <h3>Junior Data Analyst</h3>
                  <p><strong>April 2018 – May 2019</strong></p>
                  <p><strong>Uplers Private Limited, Ahmedabad, India</strong></p>
                  <ul style="list-style-position: inside;">
                      <li>Cleaned and prepared datasets using Excel and Python, ensuring data accuracy and consistency for analysis.</li>
                      <li>Assisted senior analysts in generating detailed reports and visualizations with Power BI, aiding clear communication of data insights to business teams.</li>
                      <li>Performed routine data entry and extraction tasks using SQL, supporting database maintenance and optimization efforts.</li>
                      <li>Collaborated on analytics projects, enhancing technical expertise and contributing to successful data processing tasks.</li>
                  </ul>
              </div>
          </div>
          <p style="text-align: center; margin-top: 20px;">Experience Timeline: April 2018 – November 2019</p>
      </section>

    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
---
