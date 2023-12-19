# yoga-firm
# Problem Statement:


Assume that you are the CTO of an outsourcing firm which has been chosen to build an
admission form for the Yoga Classes which happen every month.
Requirements for the admission form are:
- Only people within the age limit of 18-65 can enroll for the monthly classes and they will
be paying the fees on a month on month basis. I.e. an individual will have to pay the fees
every month and he can pay it any time of the month.
- They can enroll any day but they will have to pay for the entire month. The monthly fee is
500/- Rs INR.
- There are a total of 4 batches a day namely 6-7AM, 7-8AM, 8-9AM and 5-6PM. The
participants can choose any batch in a month and can move to any other batch next
month. I.e. participants can shift from one batch to another in different months but in the
same month they need to be in the same batch.

# Implementation details:


You will be building a simple form in React (preferably or any basic frontend language) to
accept the details from user and make a call to a REST api (in any backend language) which
does the following:

● Accepts the user data, does basic validations

● Store the data in database (please provide the ER diagram for the database design)

● Assume that you have a mock function named CompletePayment() which accepts the
details of user and payment and does the payment for you. You don’t need to
implement it.

● Return the response to front-end depending on the payment response from
CompletePayment() function

# Steps:

Database Schema:

![yoga_firm_schema(1)](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/aca235bf-1d1b-4742-ac41-857b6c9aaabb)

![yoga_firm_schema(2)](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/ccc2302f-2b5a-422c-ac9d-801cfd4fdcaa)

![yoga_firm_schema(3)](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/246eb031-de48-45a6-8b55-d2f0e09a2aac)

![yoga_firm_schema(4)](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/38b95cd2-9863-49dc-9237-c1af62ffeffd)

![yoga_firm_schema](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/b6f75791-e325-4d57-8209-3f276ce6111f)

# ER Diagram:

![ER Diagram](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/f8ac903b-757a-4901-b75b-17cd17c0693e)

# Tech stack :
HTML, CSS, JS, PHP, MySQL

# Design Approach:
Created Registration form which takes Name, Age, Start_date, email and password.

After submitting details, redirect to payment page.

After payment, Login through email and password.

View Details and Edit Batch timings in portal.

# How it works:

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/c79cffb4-7f9e-4230-bc5e-0230dce69a57)

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/d236ef6c-0759-4b3f-bdbb-f6b4fe7d6135)

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/06528dfd-8fe9-4017-b53c-39630d35ef9a)

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/88423df9-a46e-4fb9-ad07-4cf93e2e0d39)

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/9b763919-c5eb-49ae-bdb3-800de333bd4c)

![image](https://github.com/deshmukhneha595/yoga-firm/assets/83139163/7e7c8ec8-969f-4f61-824c-b936ef4c9093)









