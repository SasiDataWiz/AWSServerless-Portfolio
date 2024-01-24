# Sasidhar Gadepalli's Portfolio Website

Welcome to the GitHub repository for my professional portfolio website. This site showcases my skills as a Data Engineer and AWS Professional, and it features a dynamic visitor counter demonstrating my expertise in serverless architecture.

## Features

- **Static Web Hosting**: The website is hosted on AWS S3, enabling fast and reliable access.
- **Serverless Backend**: Utilizes AWS API Gateway, AWS Lambda, and Amazon DynamoDB to implement a visitor counter.
- **Responsive Design**: Crafted to provide an optimal viewing experience across a wide range of devices.

## How It Works

- The `Resume.html` contains the structure and content of my portfolio.
- JavaScript embedded in the HTML makes a call to an API Gateway endpoint.
- The API Gateway triggers a Lambda function, which then updates a counter in a DynamoDB table.
- On successful execution, the Lambda function returns the updated count to the website, where it is displayed.

  <img width="625" alt="Screenshot 2024-01-20 at 2 50 58 PM" src="https://github.com/SasiDataWiz/AWSServerless-Portfolio/assets/128953667/7552118f-4bea-411f-8451-e11338d2d0c7">

## Tech Stack

- S3
- CloudFront
- Route 53
- Lambda
- API Gateway
- DynamoDB

## Local Development

To clone and run this website locally, follow these steps:

