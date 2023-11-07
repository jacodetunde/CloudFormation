aws cloudformation create-stack --stack-name myteststack --template-body file://network-infra.yaml --parameters file://dev-parameter-file.json


aws cloudformation delete-stack --stack-name myteststack