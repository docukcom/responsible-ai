# Responsible AI at DOC

How the AI in [DOC](https://doc.uk.com) is designed: what it does, what it does not do and the rules we follow.

> **DOC is in development.** This page describes the service we are building. It is not live yet, and some of what is written here will be checked again before launch. DOC is independent. It is not part of the NHS and is not endorsed by it.

## In one line

AI that drafts. You decide.

## What the AI does

DOC combines a language model with a rule base and official NHS data. The AI writes and explains. The rules and the data decide what is true.

| Part | What it does |
| --- | --- |
| Language model | Reads your story in your own words, asks what is missing, drafts letters and turns specialist letters into plain language |
| Rule base | NHS choice rules for England, written down as checks the model has to pass. Each rule links to its official source |
| Waiting time data | Official NHS England statistics by specialty and provider, refreshed when new figures are published |

In practice, the AI:

- explains rules and options
- drafts letters you can edit
- summarises letters in plain words
- reminds you when to follow up

When it is not sure, it says so and tells you who to ask.

## What the AI does not do

- Assess symptoms
- Suggest a diagnosis or treatment
- Give medical advice
- Send letters or make calls for you
- Choose a clinic for you
- Rank a clinic higher because it paid

## Who decides

**You do.** DOC drafts letters, and you edit them and send them yourself. Your GP also has to agree that a referral is clinically appropriate.

Options are sorted by waiting time and distance only. No clinic can pay to appear higher, and no option is hidden.

## Data and consent

Health information is special category data. UK GDPR gives it extra protection, and so will we.

- We ask only for what a step needs: a postcode for distance, a referral date for the timeline.
- You can delete your account and your data at any time, in one step.
- No selling, no advertising.
- Your data is not shared with clinics or employers. We never share an employee's health information with their employer.

## Rules we are building for

| Rule | What it means for DOC |
| --- | --- |
| [The NHS Choice Framework](https://www.gov.uk/government/publications/the-nhs-choice-framework/the-nhs-choice-framework-what-choices-are-available-to-me-in-the-nhs) | The source of the right to choose in England. It applies to England only, so DOC starts with England only |
| [UK GDPR, special category data](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/lawful-basis/special-category-data/what-is-special-category-data/) | Health data gets extra protection. Before launch we will register with the Information Commissioner's Office (ICO) and publish a full privacy notice for the service |
| [MHRA guidance on software as a medical device](https://assets.publishing.service.gov.uk/media/6abf6c8c943e890cb55e5e52/Medical_device_stand-alone_software_including_apps__including_IVDMDs.pdf) | DOC does not assess symptoms or give medical advice, so we do not expect it to be a medical device. We will confirm this with a specialist before launch |
| [NHS Identity guidelines](https://www.england.nhs.uk/nhsidentity/identity-guidelines/who-cannot-use-the-nhs-identity/) | We mention the NHS only to describe the services we help people with, and we do not use NHS logos |

## Contact

Questions or corrections: open an issue in this repository or email [info@doc.uk.com](mailto:info@doc.uk.com). Please never include real personal or health data.

Security problems: see the [security policy](https://github.com/docukcom/.github/blob/main/SECURITY.md).

## Licence

The text in this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You may share and adapt it, as long as you credit DOC. The DOC name and logo are not covered by this licence.
