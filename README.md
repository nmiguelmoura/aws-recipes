# AWS Cloudformation Recipes

## api-gateway-to-sqs-body.yaml
Recipe for sending the body on an api call to SQS.

## api-gateway-to-sqs-path-params.yaml
Recipe for sending the path params on an api call to SQS.

## lambda-to-sns-to-sqs-to-lambda.yaml
Recipe for sending data to lambda that will forward it to a SNS Topic attached to a SQS and a lambda that will handle messages from the queue.

## lambda-to-sqs-to-lambda.yaml
Recipe for a scheduled lambda that will send messages to a queue and a lambda that will process them.