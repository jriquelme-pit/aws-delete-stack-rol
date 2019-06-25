aws cloudformation deploy --template-file template.yaml --stack-name <name-stack> --capabilities CAPABILITY_NAMED_IAM
aws cloudformation delete-stack --stack-name <stack-name> --role-arn <ROL_ARN>
