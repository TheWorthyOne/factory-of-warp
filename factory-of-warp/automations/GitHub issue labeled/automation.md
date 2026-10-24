---
triggers:
    - provider: github
      event: issue_labeled
      filter:
        labels:
            - factory:frank-the-foreman
        repos:
            - TheWorthyOne/Website-downloader
    - provider: github
      event: issue_created
      filter:
        labels:
            - factory:frank-the-foreman
        repos:
            - TheWorthyOne/Website-downloader
---

