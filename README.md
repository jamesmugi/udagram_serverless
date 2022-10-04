# Getting Started


dashboard: https://app.serverless.com/jameskaranja/apps/serverless-udagram/serverless-udagram/prod/us-east-2
endpoints:
  GET - https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod/todos
  POST - https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod/todos
  PATCH - https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod/todos/{todoId}
  DELETE - https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod/todos/{todoId}
  POST - https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod/todos/{todoId}/attachment



Stack Outputs:
  AuthLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-Auth:1
  GenerateUploadUrlLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-GenerateUploadUrl:2
  UpdateTodoLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-UpdateTodo:1
  GetTodosLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-GetTodos:2
  DeleteTodoLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-DeleteTodo:2
  EnterpriseLogAccessIamRole: arn:aws:iam::541453266566:role/serverless-udagram-prod-EnterpriseLogAccessIamRole-1RE1SZV0KBNX1
  CreateTodoLambdaFunctionQualifiedArn: arn:aws:lambda:us-east-2:541453266566:function:serverless-udagram-prod-CreateTodo:2
  ServiceEndpoint: https://2nn4m0zgv9.execute-api.us-east-2.amazonaws.com/prod
  ServerlessDeploymentBucketName: serverless-udagram-prod-serverlessdeploymentbucke-1clw7q6asofxi
