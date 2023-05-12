## Meag Notes - JupyterCon 2023
### Event Details
https://cfp.jupytercon.com/2023/schedule/

_will update with final notes when they are shared_

### BLUF


### People, Places, Things (non-exhaustive)
- [docs.jupyter.com](https://docs.jupyter.org/en/latest/) (documentation for Jupyter)
- [Outreachy](https://www.outreachy.org/) (OSS interships for underrepresented groups)
- https://quantstack.net/ (OSS group who improve Jupyter)
- https://www.twosigma.com/ (parnters with OSS groups to improve Jupyter)
- https://woods.stanford.edu/research/funding-opportunities/realizing-environmental-innovation-program/optimizing-groundwater-recharge (uses theba)
- http://eschultz.fr/ (humanities researcher insterested in STS adoption of notebooks)
- https://www.epfl.ch/education/educational-initiatives/cede/ (teaching computational thinking)
- https://github.com/jmshea/jupytercards (flashcards in jupyter)
- https://jmshea.github.io/Foundations-of-Data-Science-with-Python/intro.html (interesting layout)


## Learnings
- _Navigating the Jupyter Landscape_
  - JupyterLite: not listed in the map. Why is that?
    - computation works in the browser. also works offline
  - Need: making the docs more accessible to newcomers. Explain each concept with one line. 
- _How to grow the JupyterHub community and improve its practices by mentoring Outreachy interns_
  - Goal: inclusive and effective pathways for contributions
  - [documentation about what Outreach process taught us](https://jupyterhub-outreachy.readthedocs.io/en/latest/)
  - Challenge: mentors are not paid, incorrect resourcing. <-- this is a how do we fund open science problem not just a JupyterHub problem.
  - Challenge: overwhelming number of applicants. Over 40 applications. This was a good problem to have but there was a lot of invisible labor to keep up with the requests.
  - Challenge: Writing a first good issue is difficult. There's a fine line btwn getting it right and making it too easy.
  - Need: Streamline communications channels, creating pathways for applicants.
  - **this kind of initiative is life-changing for interns. They experience the power and value of open source**
  - Need: Recompense mentors for their time.
  - Need: Improve management process of contributions.
  - JupyterHub does not have a organizational entity behind it therefore it was not possible to transition these internships into full-time roles
- wrong session but
  - "productization of data science is hard."
- _How JupyterLab 4 is strategic to Two Sigma (and you)_
  - my employer: what we do and why we care so much
  - 500 Jupyter users -- data scientists
  - .5 FTE working on Jupyter out of 1,000 engineers
  - "when there are a lot of comments, a small scale developer may think 'oh, this is probably for a core dev." ???
  - [is this just Jupyter Hub? Why not Notebook?]
  - challenge: not a lot of UX expertise at Two Sigma. That's why we partnerd with Quant Stack.
  - These improvements were intensive for the Jupyter code stack.
  - how does the relationship work?
    - annual partnerships with Focus Areas. Stops at "Real-time Collaboration." We trust the expertise of the partners to find the best path forward.
  - internal and open source extenstions can help productivity but wrecks havoc when Jupyter Lab has improvements
  - Q&A: maybe you don't want RTC. Is this where data science is going?
  - Use Case: two researchers working together who want to explore the same problem.
  -  Q&A: What's the business case for companies to participate in these types of collaborations? 
- _Capytale: a case of large-scale use of jupyter notebooks in education_
  - 500k users on a single server.
  - Completed in French
  - Done in Jupyter Lite
- _Thebe - add Jupyter-based interactive computing to modern websites_
  - Prez built with MyST
  - "release candidate" heard that a few times today
  - prez started with what it is rather than why it exists/what problem it solves (this may be obvious to others)
  - https://thebe.readthedocs.io/en/stable/
  - interactive publications with MyST: https://myst-parser.readthedocs.io/en/latest/live-preview.html
- _How to convince French HSS researchers to use Jupyter Notebooks ? Autopsy of a missed attempt_
  - Humanities and Social Sciences 
  - looked at CAIRN INFO and did not find any humanities projects describing Jupyter.
  - Callisto: Jupyter Hub for social science by Huma-Nun
  - hosted focus groups and learned about researcher needs and created 5 dedicated notebooks to teach 
  - triple failure: notebooks were odd; Jupyter Hub service was discontinued; difficult to diffuse the results
  - what are the REAL practices in HHS
  - too many options for low code researchers. notebooks are too much. 
  - notebooks are an "intemediary object"
  - hm. maybe reproducibility is not the reason for jupyter notebooks
- _Jupyter notebooks for education: Computational thinking in practice_
  - Virtual demos > live coding > interactive notebwooks
  - clear design goals. knows what it is "we don't do HPC and research"   
  - **"easy authentication is the key for lowering the barrier to notebooks."**
  - tidygram
- _Tools for Interactive Education Experiences in Jupyter Notebooks and Jupyter Books_
   - models of learning:
     - the bicycle model of learning. keep trying until you get it.
     - spaced repitition 
  - lots of limitations in Jupyter notebook -- certain code, media types.
  - Flashcard tools and quiz tools. Some have ability to group students who didn't get the answer and who did get the answer.
  - Jupyter libraries: `pip install jupytercards`, `pip install jupyterquiz`
  - string concactenation. If a="1" and b="2", a+b=12
    - the + operator is concatenation
-  OSSCAR: leveraging interactive Jupyter notebooks to enhance teaching in the scientific domain
  - Audiences are TEACHERS, STUDENTS, RESEARCHERS, AND CONTRIBUTORS (WHO COULD BE TEACH, STUDENT AND/OR RESEARCHER)
  - need: minimize waiting times. Allow students to get started quickly without much configuration.
  - interactive visualizations
- _The past, present and future of the Jupyter Notebook_
  - Notebook 6, "Classic notebook" has been around for 8 years but it's a bit outdated. Jupyter Lab is a seperate prodcut that can do more things. 
  - Curently thre is no migration path
  - Anouncing *Jupyter 7*
    - it's now compaitble with Jupyter Lab extensions
    - !! real time collaboration is coming to Jupyter Notebook in V.7 !!
      - `pip install jupyter-collaboration`
    - "Debugger Controls" pause/play during execution (allows for checking code while it's mid run) ".. stop? could this help prevent spending 1,000s of dollars when you make an accidental run a function on the full dataset
- _The UX of computational thinking_
  - the UX of "computational notebooks"
  - narration and code are two distinct experiences
  - this env works for children/teachers because they learn by trial and errror and love storytelling
  - implication: scientists don't like storytelling
  - Jupyter has been hard to adopt because it's a new paradigm/way of working 
  - challenge: Jupyter is an open framework. unlike e-commerce. Need to allow for exploration and creation.
    - 10s of personas and 100s of workflows it can be difficult to keep up.
    - https://glueviz.org/
    - https://quansight.com/
  - Q&A: thoughts about Jupyter Lab versus Notebook. How to help people onboard.
  - Challenges: the users who are easy to access are the active contributors so they have a bias of being in the community. it's hard to get these folks outside the community.
- _Community-first open source: An action plan!_
  - Company-backed OSS
  - Community-driven OSS
  - Nebari (https://www.nebari.dev/)
  - support, development, and meeting notes are the public communication channels
- WAAAT! Accessibility Testing JupyterLab
  - https://hackmd.io/@gabalafou/waaat
  - Focus Indicator as a key WCAG requirement. helps people with low viison and those with attention limits.
  - disabilityvisibility.com
  - lots of parallels between security and accessiblity. 
  - Axe-core is really the only checker. Lighthouse and Pa11y are built on Axe-core
  - these checkers are very limiting
  - Playwright is a good solution






## Ideas for What's Next
- Host a wrap up of my SSI fellowship to share findings and explore what's next
- Explore offline capabilities to expand access to low resource settings
- Internships based on clear and concise projects
- Real-time Collaboration (RTC) strategies (intended and unintended consequences)
- Partnership/Collaboration Model for UX teams across different partners
- What does Computational UX look like? 
- People moved on from Jupyter Notebook. Jupyter Notebook 7 has the Lab backend. What's Jupyter Lab vs. Jupter Notebook vs. Jupyter Hub
- What's the business case for being invested in community development? I guess when the pain is too strong and internal staff workflows are suffering due to poor performance/ lack of collaboration. 
- Jupyter language options. Does the same work for OHDSI? Other variables?
- Review workflow strategy.. in the example of Capytale they have a teacher review function.
- [Workflow Description Language](https://terra.bio/resources/analysis-tools/)
- Audit of domain publications and mine for technology used.
- UX use cases for jupyter cards and quizzes? 
- UX user journey use cases for interactive visualizations?
- is there a jupyter workflow library?
- "I was so happy to see your talk. i've been in this community for years and nobody has been really talking about design"




