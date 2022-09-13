# express-dynamodb-starter
Getting started guide for an express app that relies on AWS DynamoDB as it's database. 

1. Setup AWS account here: https://portal.aws.amazon.com/gp/aws/developer/registration/index.html?refid=78b916d7-7c94-4cab-98d9-0ce5e648dd5f 
2. Follow the Javascript Developer AWS setup guide: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-started-nodejs.html
    1. This will include the necessary setup for your credentials and the general Node SDK
    2. This will set you up with a small Node script that accesses an S3 bucket (S3 is an object store/file store service on AWS)
3. Follow this short guide to make sure that your shared credentials are correctly set up: https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/loading-node-credentials-shared.html
4. Use the following guide to put together your Express API with Dynamo DB — honestly, their route naming for the REST API aren’t the best but I really like the explanations they have on the connection with DynamoDB and AWS https://referbruv.com/blog/reading-and-writing-to-aws-dynamodb-using-nodejs-with-example/  
    1. Here are some more complex examples of interaction with DynamoDB using the Javascript SDK (they also have examples using async/await instead of promises if you prefer that): https://www.fernandomc.com/posts/eight-examples-of-fetching-data-from-dynamodb-with-node/ 
