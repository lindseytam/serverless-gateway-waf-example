# Attach a WAF to API Gateway using the Serverless Framework
This is an example of how you can attach a WAF, or Web ACL, to API Gateway using the Serverless Framework. You can read about this more in depth [here](). 

For some general background on the Serverless Framework, read my article [here](https://medium.com/@lindseytam/create-an-aws-lambda-function-with-the-serverless-framework-33371011ad5b).


## ⚙️ Prerequisites
To get started, it is assumed you already have the following completed:
1. You have an AWS account and the CLI is setup (read more [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html))
2. You have the Serverless Framework installed (read more [here](https://www.serverless.com/framework/docs/getting-started))


## 🛠️ Getting Started
This sample utilizes 2 plugins: [serverless-associate-waf](https://www.npmjs.com/package/serverless-associate-waf) and [serverless-plugin-bind-deployment-id](https://www.npmjs.com/package/serverless-plugin-bind-deployment-id). To install these plugins, you can run `npm i` in the serverless dir.


## 💻 Deployment
To deploy your changes, run `sls deploy` in the serverless dir. After it is done deploynig, you should be able to see the resources created in your AWS account.

