
# GoClean — User Stories and Tasks

## 1. Introduction

User stories describe the features of GoClean from the perspective of the people who may use the service. They help the team understand customer needs, identify requirements and organise the work needed to support those requirements.

We used the proposed digital platform features and our Trello board to identify user stories and break them down into smaller tasks. Each user story explains what a potential customer wants to achieve and why the feature would be useful.

The GoClean application interface includes a Login page and a Services page. These interfaces help illustrate how customers could access the proposed platform and explore laundry services. The user stories, tasks and acceptance criteria in this document describe the intended customer experience and the requirements against which functionality should be evaluated.

## 2. User Stories and Tasks

### User Story 1: Customer Login

**User story:**

As a registered customer, I want to log in securely so that I can access my GoClean account.

**Tasks recorded on our Trello Login Page card:**

- Design a clean, simple login screen.
- Set up the Users table to store login credentials securely.
- Build a login API that verifies customer credentials.
- Test login error handling so customers receive a clear message when login fails.
- Document the login page setup for future maintenance.

**Acceptance criteria:**

- A registered customer can enter their login details.
- The system verifies submitted credentials before granting access.
- Invalid login attempts receive a clear error message.
- Customer credentials are handled securely.
- Successful login takes the customer to the appropriate account area.

**Application evidence:**

The GoClean Login page provides a visual representation of the intended account-access process. It displays email and password fields, a Remember Me checkbox, a password-visibility control, a Login button and a Sign Up link. These interface elements correspond to the requirements identified in this user story.

![GoClean Login page](assets/img/goclean-login.png)

**Trello task evidence:**

Our Trello Login Page card shows five completed subtasks and 100% checklist progress. This demonstrates the progress recorded on the card. Checklist completion alone does not verify that the login API, credential storage and authentication process work successfully together.

![GoClean Login Page tasks](assets/img/login-page-tasks.png)

### User Story 2: Customer Registration

**User story:**

As a new customer, I want to register for an account so that I can use the proposed GoClean booking service.

**Tasks:**

- Design the registration page.
- Identify the customer details required for registration.
- Plan how registration details will be stored securely.
- Define validation requirements for submitted information.
- Document the expected registration process.

**Acceptance criteria:**

- A new customer can enter the required registration information.
- Required fields are validated before submission.
- The customer receives appropriate feedback when information is missing or invalid.
- The platform provides confirmation when an account is created successfully.
- Registration details are associated with the correct customer account.

**Purpose:**

Registration would allow new customers to create accounts before accessing the proposed booking service. The tasks identify the work required to support this feature, including input validation and secure handling of customer information.

The registration interface and its submission process should be evaluated against these acceptance criteria before the feature is considered verified.

### User Story 3: Laundry Booking

**User story:**

As a customer, I want to book a laundry pickup so that I can arrange collection without having to manage the process manually.

**Tasks recorded on our Trello Order Page (Booking) card:**

- Design an easy basket-size and pickup-detail selector.
- Set up orders to be stored with the required details.
- Build the order-creation logic so requests can be processed when the form is submitted.
- Test the order form's validation so customers are warned before submitting incomplete information.
- Document the order flow so future developers understand how bookings are intended to work.

**Acceptance criteria:**

- Customers can select the relevant basket size and provide pickup details.
- Required booking information is validated before submission.
- Customers receive feedback when information is incomplete or invalid.
- A valid booking can be submitted and its details recorded.
- The platform communicates whether the submission was successful.
- Each booking can be associated with the correct customer.

**Related application evidence: Services page**

The GoClean Services page displays six laundry service categories: Wash & Fold, Dry Cleaning, Ironing, Bedding, Pickup & Delivery and Special Care. Each category includes a description and a starting price. This interface supports the requirement to help customers understand the available services before making a booking.

![GoClean Services page](assets/img/goclean-services.png)

The Services page provides evidence of the service-selection interface. The booking process must also be evaluated to establish whether selecting a service leads to a working order form and whether the submitted booking is recorded successfully.

**Trello task evidence:**

Our Trello Order Page (Booking) card shows five completed subtasks and 100% checklist progress. The card lists Solomon Machaule, Lerato Letsoele, Oratilwe Komane, Nomhle Njengele and Thandeka Malande as assignees. This provides evidence of how the booking feature was divided into manageable tasks and how checklist progress was recorded.

![GoClean Order Page Booking tasks](assets/img/order-page-booking.png)

The checklist supports our explanation of task organisation, but it does not independently confirm that the booking feature has been fully implemented, integrated and tested.

### User Story 4: Order Confirmation

**User story:**

As a customer, I want to receive confirmation after submitting a laundry booking so that I know my request has been received.

**Tasks:**

- Plan the order confirmation screen.
- Identify the booking details to display.
- Define confirmation messages for successful submissions.
- Consider how submission errors should be communicated.
- Plan how the confirmation will be linked to the submitted booking.

**Acceptance criteria:**

- A successful booking displays a confirmation message.
- The confirmation provides relevant order information.
- The customer can distinguish a successful submission from an unsuccessful one.
- The confirmation corresponds to the booking that was submitted.
- If submission fails, the customer receives an appropriate message.

**Purpose:**

Order confirmation would give customers feedback after submitting a booking and help them understand whether their request has been received. It should provide accurate information about the submitted order rather than simply displaying a success message.

### User Story 5: Order Tracking

**User story:**

As a customer, I want to track my laundry order so that I can understand its progress.

**Tasks:**

- Design the order tracking page.
- Identify the order statuses customers need to see.
- Plan how order information will be displayed.
- Define how status updates should be communicated.
- Consider how customers will access the correct order information.

**Acceptance criteria:**

- A customer can view the status associated with their order.
- Each order displays an identifiable order reference and its current status.
- The status is selected from the defined stages of the proposed service.
- Customers cannot access another customer's order information without appropriate authorisation.
- If order information is unavailable, the platform displays a clear message.

**Purpose:**

Order tracking is intended to improve communication by allowing customers to understand the progress of their laundry orders. Clear status information would help customers know what stage their order has reached.

### User Story 6: Order History

**User story:**

As a returning customer, I want to view my previous orders so that I can refer to earlier bookings.

**Tasks:**

- Design the order history page.
- Identify the information required for each previous order.
- Plan how customers can access their order history.
- Define an understandable layout for historical order information.
- Consider how orders should be organised for easy reference.

**Acceptance criteria:**

- Customers can view their previous orders associated with their accounts.
- Each entry displays relevant order information.
- The page is organised so customers can distinguish between different orders.
- Customers can identify the details associated with an earlier booking.
- Customers cannot access the private order history of another customer without appropriate authorisation.

**Purpose:**

Order history would help returning customers review previous bookings without having to enter the information again. It would also make it easier to refer to earlier order details.

### User Story 7: Customer Profile and Settings

**User story:**

As a customer, I want to manage my profile details so that my account information remains relevant.

**Tasks:**

- Design the profile and settings page.
- Identify the profile information customers may need to manage.
- Plan validation for changes to profile details.
- Define how changes should be confirmed to customers.
- Consider how customer information should be protected.

**Acceptance criteria:**

- Customers can view their own profile information.
- Editable fields are clearly identified.
- Invalid information receives appropriate feedback.
- Customers receive confirmation when profile changes are saved successfully.
- Customers cannot modify another customer's profile without appropriate authorisation.

**Purpose:**

Profile and settings functionality would allow customers to review and maintain their account details as part of the proposed platform. Appropriate validation and access controls would help protect customer information.

## 3. Prioritisation

We consider account access and laundry booking important because customers need a way to access the proposed service and submit laundry requests. Order confirmation and tracking would support communication, while order history and profile settings would support continued use.

Our proposed priority order is:

1. Customer login and registration.
2. Laundry booking.
3. Order confirmation.
4. Order tracking.
5. Order history.
6. Customer profile and settings.

This priority order is based on the proposed customer journey and the importance of providing the main account and booking functions before supporting features.

The priority order is a planning decision documented here; it should not be interpreted as proof that the features were completed in this sequence. Our Trello product backlog remains the reference for the features and sprint organisation recorded by the team. Priorities may change as requirements, feedback and project constraints are reviewed.

## 4. Reflection

Developing user stories helped me understand the importance of describing requirements from the customer's perspective rather than focusing only on technical tasks. For example, the login story explains the customer's need for secure account access, while its tasks identify the work required to support that need.

The GoClean Login page helped me connect a written user story to a visible interface. The email and password fields, password-visibility control and Login button illustrate how the proposed account-access process is presented to users. Similarly, the Services page helped me connect the service-selection requirement to the information customers would need before choosing a laundry service.

The Trello Login Page and Order Page (Booking) cards demonstrate how larger features can be divided into smaller tasks and how checklist progress can be recorded. This helped me understand how Agile task breakdown improves visibility and organisation within a team. However, I also learned that a completed checklist does not automatically prove that a feature has been implemented, integrated or tested successfully.

I learned that acceptance criteria are important because they describe the conditions a feature should satisfy. Specific criteria can guide testing and help the team identify suitable evidence of successful functionality. For example, the booking feature should not only allow a customer to enter details; it should also validate required information and communicate whether the submission was successful.

One area I would improve is the connection between user stories, Trello tasks and verification evidence. I would encourage the team to record the expected result, actual result and outcome of relevant tests before treating a feature as verified. I would also link each user story to its corresponding Trello card so that requirements, task progress and evidence can be traced more easily.

Overall, this activity improved my understanding of how user stories, tasks, acceptance criteria and prioritisation work together to organise Agile requirements. It also taught me that screenshots, task records and test results provide different types of evidence and should be used appropriately when evaluating project progress.

## 5. Supporting Evidence

The following evidence supports our user stories, task organisation and proposed application design. The Login screenshot is linked to the account-access story, the Services screenshot is linked to the service-selection and booking requirements, and the Trello evidence illustrates the organisation of tasks.

### Evidence 1: GoClean Login Interface

The Login page illustrates the proposed account-access interface, including the email and password fields, Remember Me checkbox, password-visibility control and Login button. It supports the requirements identified in the customer login user story.

![GoClean Login page](assets/img/goclean-login.png)

### Evidence 2: GoClean Services Interface

The Services page displays six laundry service categories and their starting prices. It provides visual evidence of how the proposed platform communicates service information to customers before they proceed towards booking.

![GoClean Services page](assets/img/goclean-services.png)

### Evidence 3: Trello Board and Sprint Lists

Our Trello board shows how proposed application features are organised into the product backlog and sprint lists. It supports our explanation of how the team structures and tracks planned work. The board provides evidence of task organisation and recorded progress rather than independent proof that every feature has been implemented.

![GoClean Trello board](assets/img/goclean-trello-board.png)

### Evidence 4: Proposed Application Wireframes

The GoClean wireframes illustrate the proposed application screens and intended customer journey. They provide design evidence for the planned platform and help communicate how customers might navigate the proposed service.

![GoClean wireframes](assets/img/goclean-wireframes.png)

### Evidence 5: Login Page Task Breakdown

The Login Page card shows five completed subtasks and 100% checklist progress. This supports the explanation of task breakdown and recorded progress on that particular card. Additional implementation and testing evidence is needed to establish whether the login functionality satisfies all its acceptance criteria.

![GoClean Login Page tasks](assets/img/login-page-tasks.png)

### Evidence 6: Order Page Booking Task Breakdown

The Order Page (Booking) card shows five completed subtasks and 100% checklist progress, with all five group members listed as assignees. This illustrates how the booking feature was divided into smaller tasks and how checklist progress was recorded.

![GoClean Order Page Booking tasks](assets/img/order-page-booking.png)
