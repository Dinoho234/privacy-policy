# Privacy Policy for Threads Api Wrapper

**Last Updated:** September 14, 2025

## 1. Introduction

Welcome to Threads Api Wrapper ("the Service"). This Service provides a simplified API wrapper to interact with the official Threads Graph API, offered to developers via the RapidAPI marketplace. This Privacy Policy explains how we handle information in the course of providing our Service.

Our service is designed to be stateless. We do not create or maintain user accounts, and we do not permanently store data retrieved from the Threads API on behalf of our users.

## 2. Information We Process

To provide our Service, we process the following categories of information:

#### a) Developer & Request Information
* **RapidAPI Credentials:** When you subscribe to our API on RapidAPI, we receive information from RapidAPI necessary for billing and usage tracking, such as your RapidAPI user ID and subscription level.
* **Request Data:** We process standard web request data, such as IP addresses and request headers, for security, monitoring, and rate-limiting purposes.

#### b) User-Provided Threads Credentials
* **Threads Access Token:** To use our Service, you must provide a valid Threads User Access Token in the `Authorization` header of your API request. **We do not save, store, or log this token.** It is held in memory only for the duration of your API request and is passed directly to Meta's servers to authenticate your request.

#### c) Threads Data
* **Proxied Data:** Our Service acts as a proxy. When you make a request, we fetch the data you specified from the Threads API on your behalf and immediately return it to you in the API response. We do not permanently store this data (such as Threads posts, user profiles, comments, or media).

## 3. How We Use Information

The information we process is used exclusively for the following purposes:
* To provide, operate, and maintain our API Service.
* To authenticate your requests with the Threads Graph API using the token you provide.
* To manage your subscription, billing, and API usage limits through RapidAPI.
* To monitor the health, security, and performance of our Service.
* To improve the performance of our Service through temporary caching.

## 4. Data Retention and Caching

We do not store Threads data retrieved on your behalf in any permanent database.

To enhance performance and reduce latency, we may temporarily cache the results of identical API requests for a short period (e.g., up to 15 minutes). This cached data is automatically deleted after its short Time-To-Live (TTL) expires and is not used for any other purpose.

## 5. Data Sharing and Disclosure

We do not sell, rent, or share your information with third parties, except in the following limited circumstances:
* **With Meta:** We pass your Threads Access Token and your API request parameters to the Threads Graph API to fulfill your request.
* **With RapidAPI:** Your usage data is processed by RapidAPI for billing and analytics as per your agreement with them.
* **For Legal Compliance:** We may disclose information if required to do so by law or in response to valid requests by public authorities.

## 6. Data Deletion and User Rights

As we do not store personal data from Threads, users seeking to exercise their data rights (such as access or deletion) should do so directly with Meta.

In compliance with Meta's Platform Terms, we provide the following contact point for any data deletion requests:
* **Data Deletion Requests:** Please send any requests to dinoho234@gmail.com.

## 7. Security

We implement reasonable technical measures to protect the data we process. All communication with our API and with the Threads Graph API is encrypted using industry-standard TLS (HTTPS).

## 8. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page.

## 9. Contact Us

If you have any questions about this Privacy Policy, please contact us at:
dinoho234@gmail.com
