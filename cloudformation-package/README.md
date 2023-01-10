<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/cloudformation-fundamentals-102/blob/main/cloudformation-package/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# AWS CloudFormation Package Command

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[![BoltOps Learn Badge](https://img.boltops.com/boltops-learn/boltops-learn.png)](https://learn.boltops.com)

## Commands

    aws cloudformation package --template-file template.yml --s3-bucket cloudformation-artifacts-demo --output-template-file packaged-template.yml
    aws cloudformation deploy --template-file packaged-template.yml --stack-name demo --capabilities CAPABILITY_IAM

## Video

[![Watch the video](https://learn-uploads.boltops.com/9x2dwgxkuvppsh7uaih3tc0djqhr)](https://learn.boltops.com/curriculums/aws-and-cloudformation/courses/aws-cloudformation-fundamentals-102/lessons/aws-cloudformation-package)
