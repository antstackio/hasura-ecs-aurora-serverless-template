# Hasura Deployment to ECS with Aurora Serverless

Cloudformation Template for deploying Hasura GraphQL Engine into auto scalable ECS cluster along with Aurora Serverless. [Read our blog to learn more.](https://www.antstack.io/blog/how-to-deploy-hasura-grapql-to-aws-with-ecs-and-aurora-serverless/)

## Deploy Hasura with default DNS of Load Balancer

Deploy Hasura Engine with a auto generated DNS from Load Balancer.

<p align="center">
  <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/template?stackName=Hasura-GraphQL&templateURL=https://antstack-opensource.s3.amazonaws.com/hasura-aws/hasura-default-domain.yaml" target="_blank" rel="noopener noreferrer">
    <img border="0" alt="Click to Deploy to Cloudformation" src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png">
  </a>
</p>

## Deploy Hasura with custom domain and SSL

Deploy Hasura Engine with custom domain name and SSL from Amazon Certificate Manager.

<p align="center">
  <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/template?stackName=Hasura-GraphQL&templateURL=https://antstack-opensource.s3.amazonaws.com/hasura-aws/hasura-ssl.yaml" target="_blank" rel="noopener noreferrer">
    <img border="0" alt="Click to Deploy to Cloudformation" src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png">
  </a>
</p>
