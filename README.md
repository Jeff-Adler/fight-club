# fight-club

This app is an attempt to make it easier to connect martial arts dojos and studios with interested trainees!

It scrapes (sources TBD) to attach keywords to different schools in the region.

The user then submits information that matches those keywords, to find the ideal dojo!

## Ideas

- What about an app in which you submit your symptoms, and web scraper spits out a diagnosis, and relevant sites where you can learn more? Scrapes pages for the words you enter

  - Title: SkipDiagnostic. Diagnosis. HiveMedical.
  - Possible Implementations:

    - 1. Use NLP to match word clouds of user info and scraped data
    - 2. Use form to go through flow in YT video for diagnosing back problems

  - Must use techonlogies:

    - Web Scraper
    - NLP tool

  - Simplest version of medical app:
    - Give preset options for medical symptoms.
    - Calculate likeliness of given disease based on those symptoms

## Technologies

- React
- Node/Express
- TypeScript
- Formsort
- Web Scraper
- Keyword Extraction: Spacy, FuzzyWuzzy, Flask: https://towardsdatascience.com/build-a-keyword-extraction-api-with-spacy-flask-and-fuzzywuzzy-4909d7ffc105
