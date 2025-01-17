# Resolving Business Challenges: Evaluating AWS Bedrock Models to Optimize AI Workflows

As a Generative AI Engineer at Valtara, your team faces a critical decision in selecting the most suitable foundation model for conversational AI and text processing tasks to address pressing business challenges. To resolve this, you are to evaluate AWS Bedrock models, particularly Claude 2.1 and Claude 3 Haiku, to determine which model delivers the best performance in terms of response quality, execution efficiency, and alignment with business goals. Leveraging Amazon SageMaker Studio and Boto3, you aim to identify the optimal model that can streamline workflows, enhance AI-driven processes, and support scalable and efficient solutions tailored to the company’s needs.

# Amazon Bedrock

<img width="555" alt="Screenshot 2025-01-17 at 10 57 01" src="https://github.com/user-attachments/assets/8806ba51-a8c3-4132-9351-3dc9b8dad8d3" />


# Activity Guide: Evaluating AWS Bedrock Models to Optimize AI Workflows

1. Set Up SageMaker Studio (Amazon SageMaker Studio)

- Create Domain:
Navigate to the SageMaker Console, go to Domains, and click Create Domain.
- Enable Jupyter Notebook Access:
Ensure the Jupyter Notebook environment is accessible within the domain for running code.
- Configure Resources:
Select instance type ml.t3.medium and complete domain setup.

2. Enable Bedrock Models (Amazon Bedrock)

- Enable Foundation Models:
Ensure Claude 2.1 and Claude 3 Haiku are enabled in the same region as SageMaker Studio (e.g., us-west-2).
- Link IAM Roles:
Attach appropriate permissions to access Amazon Bedrock using Boto3.

3. Analyze Model Performance (Amazon Bedrock, Jupyter Notebook)

- Prepare Data and Scripts:
Use prewritten scripts available for this activity to load test prompts and evaluate responses.
- Invoke Models:
Execute scripts to invoke Claude 2.1 and Claude 3 Haiku models using Boto3.
- Measure Metrics:
Evaluate model performance based on:
- Execution time.
Word count in responses.
Sentiment analysis and readability.

4. Generate Insights (Jupyter Notebook)

- Compare Responses:
Use the provided script to compare the results from Claude 2.1 and Claude 3 Haiku.
- Visualize Results:
Create plots and summary tables showing differences in model efficiency and quality.

5. Clean Up Resources

- Delete Jupyter Space:
Go to SageMaker Studio, stop your Jupyter Space, and delete it from the Actions menu.
- Delete S3 Bucket:
Empty and delete the bucket used for storing output data.
- Remove IAM Roles:
Detach and delete the roles created for Bedrock and SageMaker access.

7. Troubleshooting

Issue: Model Invocation Fails:
Ensure Bedrock is enabled in the correct region and IAM permissions are properly configured.
Issue: Slow Execution:
Upgrade to a larger SageMaker instance (e.g., ml.p3.2xlarge) to improve performance.

8. Summary
Successfully evaluated Claude 2.1 and Claude 3 Haiku models using Amazon Bedrock.

Analyzed metrics such as response quality, execution time, and sentiment to determine the optimal model for business challenges.
# Note: The code for this activity is available in the repository for reference and execution. 
