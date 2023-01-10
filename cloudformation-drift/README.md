<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/cloudformation-fundamentals-102/blob/main/cloudformation-drift/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# AWS CloudFormation Change Sets

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

## Commands

    aws cloudformation deploy --stack-name demo --template-file template.yml

Drift Stack

    aws cloudformation detect-stack-drift --stack-name demo
    aws cloudformation describe-stack-drift-detection-status --stack-drift-detection-id XXX

Drift Resources

    aws cloudformation describe-stack-resource-drifts --stack-name demo | jq

## Video

[![Watch the video](https://learn-uploads.boltops.com/ozku41k3yw8zka0tvzx6a7b9pr4w)](https://learn.boltops.com/curriculums/aws-and-cloudformation/courses/aws-cloudformation-fundamentals-102/lessons/aws-cloudformation-drift-detection)
