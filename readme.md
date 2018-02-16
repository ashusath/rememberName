# Remember Name

Simple Alexa skill example to save sessions in dynamo DB.

Tutorial : https://www.youtube.com/watch?v=cNJvyv0nYaw&t=231s


To execute dynamo DB Requests we will have to provide dynamo DB execution permissions

Go to aws.amazon.com

Open IAM

   * Select Roles -> Create role
   * Select Lambda from AWS service -> Next
   * Select AWSLambdaBasicExecutionRole and AmazonDynamoDBFullAccess -> Next
   * Provide lambda_dyanamo name in role name (you can change to any unique name)
   * Create Role

Open Lambda in aws console

  * Open your lambda function
  * Change execution role to lambda_dyanamo
  * This will give dynamo DB execution permissions to lambda function
