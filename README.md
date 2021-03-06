# AWS Advanced Analytics Jumpstarter
Collection of labs designed to enable users to perform advanced analytics on AWS

author: dylatong@amazon.com

## Quick Launch for base lab environment (us-west-2)

<a href="https://console.aws.amazon.com/cloudformation/home?region=us-west-
2#/stacks/new?stackName=adv-analytics-lab&templateURL=https://reinvent2018-sagemaker-pytorch.s3-us-west-2.amazonaws.com/cloudformation/workshops/churn-analytics/adv-analytics-lab.yaml">
![launch stack button](/cf-templates/cloudformation-launch-stack.png)</a>

---

**I. SageMaker Predictive Analytics (est. 1.5 hours)**

Below is content you can package up to demonstrate how to run an Advanced Analytics project on SageMaker.

1. [Workshop Presentation](https://github.com/dylan-tong-aws/aws-advanced-analytics-jumpstarter/blob/master/presentations/AWS-Adv-Analytics-Jumpstarter-Workshops.pdf)
2. [Lab Guide](https://github.com/dylan-tong-aws/aws-advanced-analytics-jumpstarter/blob/master/lab-guides/SageMaker%20Lab-Churn%20Predictive%20Analytics.pdf). 
3. [Lab: Predictive Churn Analytics](https://github.com/dylan-tong-aws/aws-advanced-analytics-jumpstarter/blob/master/notebooks/lab-adv-analytics-workshop-churn-analytics.ipynb):
   - Learn how to query ground truth data from our data warehouse into a pandas dataframe for exploration and feature engineering.
   - Train an XGBoost model to perform churn prediction.
   - Learn how to run a Batch Transform job to calculate churn scores in batch.
   - Optimize your model using SageMaker Neo.
   - Run an AWS Glue job programatically to demonstrate data processing and feature engineering at scale using SparkML.
   - Create a production scale inference pipeline that consists of a SparkML feature engineering pipeline that feeds into an XGBoost churn classification model.
