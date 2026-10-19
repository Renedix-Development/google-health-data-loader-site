---
title: Privacy Policy - Google Health Data Loader
---

# Privacy Policy

_Last updated: 18 October 2026_

Google Health Data Loader ("the app") is a personal tool operated by Renedix Development. It is used
only by its owner, to load the owner's own health data.

## Data the app accesses

With your consent through Google's OAuth screen, the app requests read-only access to the following
Google Health API data:

- **Sleep** data (`googlehealth.sleep.readonly`)
- **Health metrics and measurements**, used for heart rate data
  (`googlehealth.health_metrics_and_measurements.readonly`)

The app cannot change or delete any of your Google data.

## How the data is used and stored

- The app runs on a schedule in the owner's private Amazon Web Services (AWS) account. It retrieves
  the data above and writes it to a private, encrypted Amazon S3 bucket in that account.
- The OAuth client credentials and refresh token are stored in AWS Secrets Manager in the same
  account.
- The data is used only for the owner's personal analysis.
- The data is not sold, shared with third parties, used for advertising, or used to train AI or
  machine learning models.

## Google API Services User Data Policy

The app's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Retention and deletion

Data stays in the owner's S3 bucket until the owner deletes it. You can stop the app's access at any
time by removing it at [myaccount.google.com/permissions](https://myaccount.google.com/permissions).
After that, the app cannot retrieve any new data.

## Contact

For questions about this policy, contact: [damiensebay88@googlemail.com](mailto:damiensebay88@googlemail.com)
