# EPIC:  AI_PLATFORM_PURCHASE_GUIDE_APP
*  Description: A platform that will help organization to understand their business requirement for digital transformation and guide/suggest relevant AI tools and platform subscriptions. 

## Feature-01: Secured Company Sign up and Login
Enable users to securily register and login in the app 

### User_Story-01:
As a user, I want to securily register using company email, so that I can start exploring the platform. 

#### Acceptance Criteria: 
* User can enter first name, last name, company email and create a password to register.
* Created password must meet the password policy, then the system shows error message and asks to create password again.

#### Task:
* Design "Sign-up" page with marked mandatory fields.
* Develop registration API to accept new user details and save it to database.
* Implement passowrd policy validation.


### User-Story-02:
* As a registered user, I want to receive an email with account verification link, so that I can activate my account. 

#### Acceptance Criteria: 
* User can receive account verification link via email.
* The verification link remains valid for 24 hours.
* User will be directed to page mentioning successful verification.

#### Task:
* Integrate email services for triggering emails.
* Generate secure verification token.
* Implement token expiry logic.
* Design "Successful Account Verification Page" with Login Link.


## Feature-02: Home Page with Search bar and registered list of AI platforms within the app
Users can explore what are 


