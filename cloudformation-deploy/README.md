<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/cloudformation-fundamentals-102/blob/main/cloudformation-deploy/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# AWS CloudFormation Deploy Command

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

## Commands

    aws cloudformation deploy --stack-name demo --template-file template.yml

Vs

    aws cloudformation create-stack --stack-name demo --template-body file://template.yml
    aws cloudformation update-stack --stack-name demo --template-body file://template.yml

## Video

[![Watch the video](https://learn-uploads.boltops.com/e341148ofoe7d7jtn4yy1g8b9196)](https://learn.boltops.com/curriculums/aws-and-cloudformation/courses/aws-cloudformation-fundamentals-102/lessons/aws-cloudformation-deploy)
