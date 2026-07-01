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


### User_Story-02:
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


## Feature-02: Home Page with Search bar, advance search and registered list of AI platforms within the app
Users can search and explore what all platforms they can explore within the app

### User_Story-01:
As a user, I want to type in the search bar , so that I can find specific AI platform I am interested in. 

#### Acceptance Criteria: 
* User can enter one or more keywords in the search bar.
* User will see relevant results with respect to the input given in the search bar.
* If no products match, a "No products found" message is displayed.

#### Task:
* Design and implement search bar UI.
* Develop backend search bar API to get relevant results.
* Design "No result found" page message


### User_Story-02: 
As s User, I want to filter the list of platforms by different criteria(pricing, usage, business needs)  so that I can narrow results suitable for my requirements.

#### Acceptance Criteria:
* One or more filters can be applied to narrow down the reults.
* When there are no matchinh results with multiple filters applied, reset filter option should appear.

#### Task:
*




