# Github Action Workflow Templates
### PUBLIC REPO: DO NOT STORE CREDENTIALS HERE

## Description
This repo stores all the reusable workflows for github actions

**NOTE: workflow files are in `.github/workflows` folder due to github actions requirements**

## Naming convention
The workflow filenames follow the standards below:
```
<tool>_<name-of-template>
```

## Workflow Templates
**Please look at the workflow file for required inputs**
| Template | Description |
| -------- | ----------- |
| github_commit-satus-notification | Update the Github commit of the status of the check being run |
| twilio_sms-dev-on-failure | Use Twilio to send an SMS to a developer to notify them of a commit failure |
| displayr_notify-good-build | Indicate that this build is good for use by overnight deployments |
| chrometest_run-batches | Runs Chrome test batches |