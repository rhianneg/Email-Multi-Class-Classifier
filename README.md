Email Multi-class Classifier

Using machine learning algorithms to classify emails into 8 different classes

Brief Description

This project was part of the Foundations of Machine Learning Course at CentraleSupélec - Université Paris-Saclay. It was hosted as a Kaggle Competition and the ipynb file in the repository contains code of the machine learning algorithms I tried. 

Motivation

We often face the problem of searching meaningful emails among thousands of promotional emails.

Challenge Goal

This challenge focuses on creating a multiclass classifier that can classify an email into eight classes based on metadata extracted from the email.

Dataset Features

• date - unix style date format, date-time on which the email was received, e.g. Sat, 2 Jul 2016 11:02:58 +0530
• org - organisation of the sender, e.g. centralesupelec, facebook, and google
• tld - top level domain of the organisation, eg. com, ac.in, fr, and org
• ccs - number of emails cced with this email, e.g. 0, 2, and 10
• bcced - is the receiver bcc'd in the email. Can take two values 0 or 1
• mail_type - type of the mail body, e.g. text/plain and text/html
• images - number of images in the mail body, e.g. 0, 1, and 100
• urls - number of urls in the mail body, e.g. 0, 1, and 50
• salutations - is salutation used in the email? Either 0 or 1
• designation - is designation of the sender mentioned in the email. Either 0 or 1
• chars_in_subject - number of characters in the mail subject, e.g. 0, 1, and 10
• chars_in_body - number of characters in the mail body, e.g. 10 and 10000
• label - label of this email. Eight classes are 'Updates', 'Personal', ‘Promotions’, 'Forums', 'Purchases', 'Travel', 'Spam', and ‘Social’. Class ids start from 0 to 7

Class Labels

0, Updates: Mails from bank, insurance providers, etc. These emails are update on some kind of service that the email account holder has opted for. Mails about account statement, delivery of product, flight tickets, etc.
1, Personal: Mails from personal network
2, Promotions: Promotional/advertisement mails
3, Forums: Mails from professional groups
4, Purchases: Updates about purchases
5, Travel: Advertisement about travel and tourism
6, Spam: Spam mails
7, Social: Mails from social networks
