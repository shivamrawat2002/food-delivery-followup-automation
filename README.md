# 🍕 AI-Powered Food Delivery Follow-Up Automation

## 📌 Introduction

Customer retention is one of the biggest challenges for food delivery
businesses like Zomato, Swiggy, or Uber Eats. While marketing campaigns
help, they often lack personalization and consistency.

This project demonstrates how to build an end-to-end automation pipeline
using **Make.com, Google Forms, Google Sheets, Slack, Google Gemini AI,
and Email integration** to re-engage customers automatically.

------------------------------------------------------------------------

## ❗ Problem Statement

Food delivery businesses often face the issue of one-time customers who
place an order and then never return. Manual follow-ups are not
scalable, and traditional marketing emails tend to feel robotic.

The goal of this automation is to: - Send personalized, witty follow-up
emails automatically. - Re-engage customers three days after their
order. - Save time for the business while improving retention.

------------------------------------------------------------------------

## 🔄 Workflow Overview

The workflow has been implemented in **Make.com** and consists of the
following steps:

1.  **Google Forms** -- Customers fill out a feedback/order form
    including their name, email, and order details.\
2.  **Google Sheets** -- Form responses are automatically stored in a
    Google Sheet for record-keeping.\
3.  **Router** -- A decision point that checks whether an email address
    is available. If yes, the follow-up process continues; otherwise,
    the operations team is notified.\
4.  **Google Gemini AI** -- Takes the customer's name and generates a
    witty, funny follow-up email similar to Zomato or Swiggy campaigns.\
5.  **Email Module** -- Sends the generated email directly to the
    customer after 3 days.\
6.  **Slack Notification** -- Sends a notification to the team with
    details of the follow-up for transparency.

------------------------------------------------------------------------

## 📝 Detailed Workflow Steps

### Step 1: Google Forms

The process begins when a customer submits an order feedback form via
Google Forms. The form collects essential information such as name,
email, phone number, order details, and delivery preferences.

### Step 2: Google Sheets

Each response is automatically logged into a Google Sheet. This acts as
a database of customer interactions and ensures structured data storage
for automation.

### Step 3: Router

The router checks conditions before proceeding. For example: - If the
email column is empty → Send a Slack alert to the team.\
- If the email is available → Proceed to AI-powered email generation.

### Step 4: Google Gemini AI

Gemini AI is used to generate a witty and personalized email. The prompt
includes the customer's name and instructs the AI to write a fun
follow-up email three days after the order. The AI ensures that every
customer gets a unique and engaging message that encourages them to
return.

### Step 5: Email Module

The generated email is mapped into the Email module in Make.com. The
recipient's email is dynamically fetched from the Google Form response.
The email is then sent to the customer with no manual effort required.

### Step 6: Slack Notification

To maintain transparency and team awareness, a Slack message is sent to
the marketing or operations team with the details of the follow-up
email. This allows monitoring and quick intervention if needed.

------------------------------------------------------------------------

## 🚀 Value Proposition

The benefits of this workflow are significant:

-   **Personalization at Scale** -- Customers receive fun, personalized
    emails using their name and context.\
-   **Time Efficiency** -- Eliminates the need for manual follow-ups.\
-   **Consistency** -- Ensures every customer gets contacted 3 days
    after ordering.\
-   **Customer Retention** -- Increases chances of repeat orders.\
-   **Team Visibility** -- Slack notifications keep the team updated.

------------------------------------------------------------------------

## ✅ Conclusion

This Make.com workflow demonstrates the power of combining AI with
automation tools to improve customer engagement. In less than an hour,
businesses can set up a system that continuously re-engages customers,
boosts retention, and saves operational time.

This is a scalable solution for food delivery businesses aiming to drive
growth.
