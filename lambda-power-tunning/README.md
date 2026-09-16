# AWS Lambda Power Tunning

**AWS Lambda Power Tuning** is an AWS open-source tool that helps you determine the optimal memory configuration for a Lambda function by testing multiple memory sizes and comparing their performance and cost.

Instead of guessing whether your Lambda should run at 256 MB, 512 MB, 1024 MB, or 3008 MB, the tool executes the function at different memory levels and produces a visual report showing:

- Execution duration
- Estimated cost
- Performance improvements
- Cost vs performance trade-offs
- The "sweet spot" where both factors are balanced

## How it Works

![how-it-works.png](assets/how-it-works.png)
______________________________________________
## Why Use It

Suppose your Lambda runs at 128 MB:
- Execution Time: 2.5 seconds
- Cost: Higher than expected due to long runtime

We can use this tool from AWS to optimise Performance and cost. 
________________________________________________________________

## Overview of Project
This project demonstrates how AWS Lambda Power Tuning can be used to identify the optimal memory configuration for a serverless microservice.

The solution follows a serverless architecture using Postman to send HTTPS requests to API Gateway, which in turn invokes Lambda Function.






