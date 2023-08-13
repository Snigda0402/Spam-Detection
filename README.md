
# Spam Detection

## Objective : 

Predicting if an email is a spam or not. Spam refers to unsolicited and often irrelevant or inappropriate messages sent in bulk through various communication channels, such as email, text messages, social media, and online forums.

## Expected Outcome : 

1. **Enhancing User Experience:** Helps users focus on genuine and relevant messages, thereby improving their overall experience and productivity. 

2. **Preventing Fraud and Malware:** Prevents users from falling victim by identifying spam messages designed to deceive users into providing personal information, financial details, or downloading malicious software.

4. **Protecting Resources:** Spam messages can consume valuable network bandwidth, storage space, and computational resources. Detecting and filtering out spam helps optimize resource utilization for both service providers and users.

5. **Maintaining Platform Reputation:** Effective spam detection contributes to the email service providers' reputation by ensuring that users receive relevant and trustworthy content.

## Model Overview

Utilized stopwords module from nltk package and estimators like CountVectorizer and TfidfTransformer and classification algorithm Multinomial Naive Bayes from sklearn module to detect whether a mail/message is a spam or a ham.

