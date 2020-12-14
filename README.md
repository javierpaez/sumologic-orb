# Sumologic Orb
https://circleci.com/orbs/registry/orb/circleci/sumologic

Easily capture analytics from your CircleCI jobs in your Sumologic dashboard!

## workflow-collector
Add this job to your workflow with no require statements. This job will run in parallel with the rest of your workflow for monitoring and will exit when all other jobs have completed. Custom data can be supplied via the custom-data parameter in the form of valid JSON. Keys and values can be supplied literally or as environment variables, though supplying values as additional, nested JSON is not supported. Passing the custom-data parameter as a folded-style (>) block scalar is recommended (see examples).

