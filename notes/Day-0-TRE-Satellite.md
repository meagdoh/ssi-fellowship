
## Meag Notes - TRE Satelite Meeting
### Event Details
https://github.com/meagdoh/ssi-fellowship/blob/main/talks/TRE-RSECon-lightning-talk.md </br>

_will update with final notes when they are shared_

### BLUF
There is a clear interest to break down silos in TRE development across UK. As TREs proliferate so do the user experiences. There's some interesting work to be done to streamline common workflows and interfaces for analysts, in particular analysts who use more than one TRE.

### People and Places (non-exhaustive)
  - EPCC
  - National Records of Scotland
  - Health Research Authority (akin to IRB?)
  - Research Ethics Groups
  - Secure Data Acces Professionals Network (SDAP)
  - Microsoft Research (independent research group) / Microsoft TRE OSS
  - HPC/AI EMEA Research Lab
  - Outbreak Data Analysis Platform (ODAP) 
  - Data Safe Haven @ Turing code that people can use but they don’t deploy
  - Data Connect
  - Treehoos OSS TRE 
  - DICOM
  - HRDUK has a catalog of datasets
  - Amazon TRE (you can see what data you have access to)

### Learnings
  - Some users are used to using one dataset while other may be using many many TREs
  - A few of these solutions are remote desktops with pre-loaded applications and data access 
  - Radiology/Imaging specific
      - DICOM is a standard but devices have different implementation
      - Metadata on its own is not enough
      - Image storage was meant for hospital IT systems not research so a lot of times systems alter the resolution
      - Radiology reports are good bu not great. They are called “structured reports” but they are unstructured text fields
      - MUST tie to other data
  - Industry researchers may behesitant to share algorithms because of IP
  - Some would love to do more ux but time is a problem
  - With TREs you are giving people a prescribed way of working, and the expectations are not clear (like I need to apply more than once)
     - Some people want choice even if it's a fixed list of choices but the ability to have some flexibility
  - Some people don’t always know what’s available. Return users are great because they know what is there but for newcomers the value is hidden. People don’t know what they don’t know. 
  - People want widely different things: CSV —> HPC enviroements
  - An RSEs goal: “to reduce the barriers to access, so more people can use it” 
  - 2FA on mobile device for people who want to keep work and non-work separate, there’s no alternative for them


## What's Next?
-  Draft an infrastructure looking visual to describe the customer experience workflows and services that exist across All of Us in order to show the embdedded features of UX throughout the research lifecycle
-  Outline a research plan, in collaboration with the 'User Experience in TREs' breakout group members, for better understanding the common user problems that exist across TREs. Activities could include:
   -  Interview a handful of researchers who have used more than 1 TRE over the past year and find out more about their experiences
   -  Conduct a ux review of TREs, looking at common patterns in the user journey:
        - Registration
        - Data Browsing/Onboarding (getting started came up as a big sticking point for many)
        - Project Definition/Description (the thing that says this is how I plan to use the data)
        - Workspace Management
- Write down why end users should be involved throughout the data governance development process. 
  - This stems from an observation in the discusions: If the curation and cleaning are separate from the data analysis.. are we sure that the researchers really understand the data? (one way to understnad the data is to be involved in the governance process. What are other ways?)
- Write a talk called UX is *not* asking users what they want and just doing that
   
