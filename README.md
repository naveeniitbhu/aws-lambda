`sls create -t aws-nodejs`
Replace hello by rank
Change stage to dev or prod
Change service name to username (IAM) i.e. rankly-lambda
If we want to send an error from lambda, change the status code.
dont touch null as that is taken care of by lambda.
`sls deploy`
`sls invoke --function rank` : dont do often as it would cost money.
`sls invoke local --function rank`
