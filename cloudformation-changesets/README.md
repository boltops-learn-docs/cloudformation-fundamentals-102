<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/cloudformation-fundamentals-102/blob/main/cloudformation-changesets/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# AWS CloudFormation Change Sets

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

## Commands

    aws cloudformation create-change-set --change-set-name cs1 --stack-name demo --template-body file://template.yml
    aws cloudformation execute-change-set --change-set-name cs1 --stack-name demo

## Video

[![Watch the video](https://learn-uploads.boltops.com/3mb13x8hyi9fcu61zicuqo60plea)](https://learn.boltops.com/curriculums/aws-and-cloudformation/courses/aws-cloudformation-fundamentals-102/lessons/cloudformation-change-sets)
