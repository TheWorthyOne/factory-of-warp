---
triggers:
    - provider: github
      event: issue_mentioned
      filter:
        labels:
            - factory:frank-the-foreman
        mentioned:
            - warp
            - warp-factory
        repos:
            - TheWorthyOne/Website-downloader
    - provider: github
      event: pull_request_mentioned
      filter:
        labels:
            - factory:frank-the-foreman
        mentioned:
            - warp
            - warp-factory
        repos:
            - TheWorthyOne/Website-downloader
    - provider: github
      event: issue_assigned
      filter:
        assignees:
            - warp
            - warp-factory
        labels:
            - factory:frank-the-foreman
        repos:
            - TheWorthyOne/Website-downloader
    - provider: github
      event: pull_request_assigned
      filter:
        assignees:
            - warp
            - warp-factory
        labels:
            - factory:frank-the-foreman
        repos:
            - TheWorthyOne/Website-downloader
---

