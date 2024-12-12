# Creating a Personal Website using AWS Services

This repository demonstrates how to create and host a personal website using AWS services. Follow the steps below to set up your website, leveraging AWS tools and services like S3, CloudFront, and CloudWatch.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Architecture Diagram](#architecture-diagram)
3. [AWS Services Used](#aws-services-used)
4. [Prerequisites](#prerequisites)
5. [Step-by-Step Guide](#step-by-step-guide)
   - [1. Create and Configure an S3 Bucket](#1-create-and-configure-an-s3-bucket)
   - [2. Set Up a Custom Domain with Route 53](#2-set-up-a-custom-domain-with-route-53)
   - [3. Configure CloudFront for Content Delivery](#3-configure-cloudfront-for-content-delivery)
   - [4. Deploy Your Website Files](#4-deploy-your-website-files)
   - [5. Set Up HTTPS with SSL/TLS](#5-set-up-https-with-ssl-tls)
6. [Testing and Validation](#testing-and-validation)
7. [Future Enhancements](#future-enhancements)
8. [Contributing](#contributing)
9. [License](#license)

---

## Project Overview

This project showcases how to deploy a personal website on AWS using a serverless architecture. The website will be:

- **Highly available**: AWS S3 and CloudFront ensure reliability.

## Architecture Diagram

![Architecture](assets/Personal_CV.drawio.png)


## AWS Services Used

- **Amazon S3**: For static website hosting.
- **Amazon CloudFront**: For caching and content delivery.
- **Amazon CloudWatch**: For monitoring and observability.


## Prerequisites

- An AWS account.
- Website files (HTML, CSS, JavaScript, and assets).

