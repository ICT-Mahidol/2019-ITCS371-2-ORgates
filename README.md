# 2019-ITCS371-2-ORgates

Car rental service
==================

Our client wanted an application that is easy to use and provide great
security so, we come up with new way to buy customer trust with system
to show history of the car that customer rent to make sure that their
car will be reliable furthermore, customer can rent car easily by only
register to the application and use it to rent for the payment we will
accept both cash and credit card. When customer come to get their car,
they will need only to show their ID card or passport to receive the car
furthermore, almost all of the support function can be accessed through
application such as emergency call to company call company, promotion
for customer that rent for certain time then they can use promotion code
by just tab in application so, no need for customer to find coupon code
for discount on the economy side customer also can rent car with no GPS
services for cheaper price. Our application will also provide another
axillary function such as 16 language interfaces, theme changing.

### Functional

1.  Before renting the car, the customer must register on our
    application to use the application.

2.  The system has fast service, which means when the customer already
    registers on application. They can rent the car by the application
    then bring the citizen ID card or passport to the near brunch to
    receive their car.

3.  The user chooses the payment method via credit card, debit card or
    cash.

4.  When the user opens the application, they will see the pop-up about
    a promotion that we serve for the customer

5.  The main page on the application, the customer will see the map that
    shows the nearest branch.

6.  The user's history will show the history of the rental car.

7.  Menu promotion tap has the code about the promotion such as users
    rent the car for more than 10 hours there will be a discount
    promotion.

8.  Contact service is the information that the customer can use to
    contact us.

9.  The system has a setting tab to edit the form of application.

### Non-functional

1.  The customer can go to receive the car from each branch around them.

2.  After the car that has the problem while the user is using, the user
    can contact to call center.

3.  The user can change the color theme on the application.

4.  On application, the user can change the language up to 16 languages.

5.  For the car rental method, the user can choose the car with GPS or
    not.

6.  According to the car rental method, the user also decides to choose
    the car that has the front/back camera.

### Constraint 

-   The system support both of IOS and Android.

### Requirements Prioritization

| Req#|Brief req. description|Req. Source|Req. Priority|Req. Status|
|---	|---	|---	|---	|---	|
|1|Before using the app, user must register|Client|1|Accepted for this release|
|2|The pop-up of the promotion will appear on the screen|Client|2|Postponed for next release|
|3|The user can check their history about the rental car|Client|3|Postponed until req. 2 was released|
|4|The user can contact the call center to get help|Client|3|The pop-up of the promotion will appear on the screen|
|5|The user can edit the form of the application via the setting tab|Client|3|Postponed until req. 2 was released|
|6|The user uses the code to get the promotion to their propose|Client|3|Postponed until req. 2 was released|
|7|The user chooses the payment method|Client|4|Postponed until req. 3 was released|
|8|The user can view the nearest branch on the map to rent a car|Client|5|Postponed until req. 3 was released|
|9|Implement fast service by using a citizen ID card or passport to receive the car|Client|5|Postponed until req. 4 was released|

### Use case

#### Actor list

|Actor|Role|
|-----|---|
|  User   |  Rent the car by interact with the system.|
|  System |  Receive the rental form that from the user and sent to branch.|
|  Admin  |  Manage the system and answer the user question.|
|  Branch |  Give the car to the user who sent the form to rent.|

#### Use case list

 |Use case name|Description|
 |-------------|-----------|
|Sign in |To use the rental car application, the user must sign in the application.|
|Use citizen ID card or passport to receive the car|When the user arrives in selected branch, they must show the citizen ID card or passport to receive the car|
|Setting tab|The user can change language or color theme of the application|
|Payment method|The system receives the payment method that chooses by the user|
|Location of near branch|The system will recommend about the nearest branch for user that easy for them to go to get the car.|
|Record history|The system will record each user a history of rental car.|
|Contact center|The system will receive the contact from the user and sent it to the admin.|
|Fix car service|When the administrator receives the problem about the car, they will send the employee to fix the car.|
|Manage promotion|The admin can set up a promotion for the user.|
|Receive customer from system|The branch will receive the customer who want to rent the car from the system.|

## Use case diagram
![Alt text](https://raw.githubusercontent.com/ICT-Mahidol/2019-ITCS371-2-ORgates/master/se1.jpg?token=AKKBEBJMELMMK7H7GGIVHAK5T55EM)

#### Use case Narrative

|       Use Case:                   | Rent the car                      |
|-----------------------------------|-----------------------------------|
| Primary actor:                    | User                              |
| Precondition:                     | User must register before using the application|
| Trigger:                          | When the user wants to rent the   |
|                                   | car.                              |
| Scenario:                         | 1.  The user must register before |
|                                   |     using the application.        |
|                                   |                                   |
|                                   | 2.  The user login to the         |
|                                   |     application.                  |
|                                   |                                   |
|                                   | 3.  The pop-up of the promotion   |
|                                   |     will show on the screen.      |
|                                   |                                   |
|                                   | 4.  The user presses the button   |
|                                   |     to rental the car and chooses |
|                                   |     the addition device such as   |
|                                   |     GPS and front/back camera.    |
|                                   |                                   |
|                                   | 5.  If the user interested in the |
|                                   |     promotion, they can use the   |
|                                   |     promotion tab to see the      |
|                                   |     promotion.                    |
|                                   |                                   |
|                                   | 6.  The user chooses the payment  |
|                                   |     method.                       |
|                                   |                                   |
|                                   | 7.  The user searches for the     |
|                                   |     nearest branch to get the     |
|                                   |     car.                          |
|                                   |                                   |
|                                   | 8.  When the user arrives at the  |
|                                   |     branch, they only using a     |
|                                   |     citizen ID card or passport   |
|                                   |     to receive the car.           |
| Exceptions:                       | 1.  If the user didn't register,  |
|                                   |     go to registration.           |
|                                   |                                   |
|                                   | 2.  If the user fills username or |
|                                   |     password incorrect, the       |
|                                   |     system will let them fill     |
|                                   |     again.                        |
|                                   |                                   |
|                                   | 3.  If the user didn't open the   |
|                                   |     location, the system will     |
|                                   |     inform you to open it.        |
| Post-condition                    | The user gets the car.            |



| Use Case:                   | Use promotion on application            |
|-----------------------------|-----------------------------------------|
| Primary actor:              | User                                    |
| Precondition:                     | User must register before using   |
|                                   | the application.                  |
| Trigger:                          | When the user wants to view or    |
|                                   | get the promotion                 |
| Scenario:                         | 1.  The user looks for promotion  |
|                                   |     by tapping on the promotion   |
|                                   |     tap bar.                      |
|                                   |                                   |
|                                   | 2.  The user chooses the          |
|                                   |     promotion and gets the code.  |
|                                   |                                   |
|                                   | 3.  The user brings the code and  |
|                                   |     fills in the payment method   |
|                                   |     to get the promotion.         |
| Exceptions:                       | 1.  If the user\'s property does  |
|                                   |     not match the promotion, the  |
|                                   |     system will warn the user.    |
|                                   |                                   |
|                                   | 2.  If the code that the user     |
|                                   |     fill is incorrect, the system |
|                                   |     will alert and tell the user  |
|                                   |     to fill it again.             |
| Post-condition                    | The user gets the promotion.      |

## Data flow diagram

![Alt text](https://raw.githubusercontent.com/ICT-Mahidol/2019-ITCS371-2-ORgates/master/se2.jpg?token=AKKBEBPYHI7YW5CQBBTKYXK5T55IM)

### Relevant tools
Pandoc : a tool to convert docx to markdown (but can't convert good tables)
https://github.com/jgm/pandoc
Markdown table generator : a tool to generate tables.
https://www.tablesgenerator.com/markdown_tables
