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
