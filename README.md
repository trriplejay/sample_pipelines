# sample_pipelines

sample workflow for PiiQ:

1. Creates two images during each CI job
2. Two images trigger two manifests, which trigger two deploys
3. one manifest/deploy is using switch:off
