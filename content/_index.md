---
title: ""
summary: ""
date: 2026-09-13
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: About
        education: Education
        interests: Research Interests
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    id: research
    content:
      title: Research
      text: |
        My research focuses on **post-quantum cryptography, quantum-safe communication, and cryptographic protocols**, with particular interest in hybrid cryptographic architectures and their application to secure power-grid environments.

        I am currently working at the **Indian Institute of Science (IISc), Bengaluru**, as a Research Associate in the Information & Security Lab under the SPARKS Program. My current work involves developing a **Quantum-Safe Hybrid TLS Protocol** that combines classical and post-quantum cryptographic primitives.

        My broader research interests include **TLS 1.3, cryptographic agility, symmetric cryptography, sparse modeling, signal processing, matrix estimation, and machine learning**.
    design:
      columns: "1"

  - block: markdown
    id: education
    content:
      title: Education
      text: |
        ### M.Tech in Data Science
        **Indian Institute of Technology Palakkad** · *2023 – 2025*

        **CGPA:** 8.14/10.0

        **Thesis:** *Coherence Reduction in Sparse Modeling – A Hadamard Transform Approach*

        ---

        ### M.Sc in Mathematics
        **Ramakrishna Mission Vivekananda Educational and Research Institute** · *2019 – 2021*

        **CGPA:** 9.71/10.0

        **Department Gold Medal** for Outstanding Academic Performance and Excellence in Mathematics.

        ---

        ### B.Sc in Mathematics (Honours)
        **The University of Burdwan** · *2015 – 2018*

        **Percentage:** 67.75%
    design:
      columns: "1"

  - block: collection
    id: projects
    content:
      title: Selected Research
      filters:
        folders:
          - projects
      count: 4
    design:
      view: card
      columns: 2

  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
      count: 5
    design:
      view: citation

  - block: markdown
    id: experience
    content:
      title: Research Experience
      text: |
        ### Research Associate — Information & Security Lab
        **Indian Institute of Science (IISc), Bengaluru** · *2026 – Present*

        Part of the **SPARKS Program**, working under Prof. Sanjit Chatterjee on developing a **Quantum-Safe Hybrid TLS Protocol** combining classical and post-quantum cryptographic primitives. Also investigating hybrid cryptographic architectures for quantum-safe communication in power-grid environments.

        ### IISc–ICASSP Fellowship
        **Indian Institute of Science (IISc), Bengaluru** · *April 2025 – May 2025*

        Worked on **Matrix Estimation Through Matrix-Vector Multiplication** under Prof. Chandra Sekhar Seelamantula.

        ### Assistant Professor
        **Dayananda Sagar University, Bengaluru** · *2025 – Present (On Leave)*

        Teaching undergraduate courses in Artificial Intelligence, Machine Learning, and Data Science, while mentoring students and supervising undergraduate academic projects.
    design:
      columns: "1"
---
