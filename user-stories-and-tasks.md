# GoClean — User Stories and Tasks

## 1. Introduction

User stories describe the features of GoClean from the perspective of the people who may use the service. They help our team understand customer needs and organise the work required to support those needs.

We used our proposed digital platform features and Trello board to identify user stories and break them down into smaller tasks. The stories below describe the intended functionality; they do not imply that every feature has been implemented or tested.

## 2. User Stories and Tasks

### User Story 1: Customer Login

**User story:** As a registered customer, I want to log in securely so that I can access my GoClean account.

**Tasks recorded on our Trello Login Page card:**

- Design a clean, simple login screen.
- Set up the Users table to store login credentials securely.
- Build a login API that verifies customer credentials.
- Test login error handling so customers receive a clear message when login fails.
- Document the login page setup for future maintenance.

**Acceptance criteria:**

- A registered customer can enter their login details.
- The system verifies the submitted credentials.
- Invalid login attempts receive a clear error message.
- Customer credentials are handled securely.

**Evidence:** Our Trello Login Page card shows five completed subtasks and 100% checklist progress.

![GoClean Login Page tasks](assets/img/login-page-tasks.png)

### User Story 2: Customer Registration

**User story:** As a new customer, I want to register for an account so that I can use the proposed GoClean booking service.

**Tasks:**

- Design the registration page.
- Identify the customer details required for registration.
- Plan how registration details will be stored.
- Define validation requirements for submitted information.
- Document the expected registration process.

**Acceptance criteria:**

- A new customer can enter the required registration information.
- Required fields are validated.
- The customer receives appropriate feedback when information is missing or invalid.

### User Story 3: Laundry Booking

**User story:** As a customer, I want to book a laundry pickup so that I can arrange collection without having to manage the process manually.

**Tasks recorded on our Trello Order Page card:**

- Design an easy basket-size and pickup-detail selector.
- Set up orders to be stored with full details.
- Build the order-creation logic so requests reach GoClean when the form is submitted.
- Test the order form's validation so customers are warned before submitting incomplete information.
- Document the order flow so future developers understand how bookings work.

**Acceptance criteria:**

- Customers can select the relevant basket size and provide pickup details.
- Required booking information is validated.
- Customers receive feedback when information is incomplete.
- A valid booking can be submitted and its details recorded.

**Evidence:** Our Trello Order Page card contains five subtasks and activity records relating to their completion.

### User Story 4: Order Confirmation

**User story:** As a customer, I want to receive confirmation after submitting a laundry booking so that I know my request has been received.

**Tasks:**

- Plan the order confirmation screen.
- Identify the booking details to display.
- Define confirmation messages for successful submissions.
- Consider how errors should be communicated.

**Acceptance criteria:**

- A successful booking displays a confirmation.
- The confirmation provides relevant order information.
- The customer can distinguish a successful submission from an unsuccessful one.

### User Story 5: Order Tracking

**User story:** As a customer, I want to track my laundry order so that I can understand its progress.

**Tasks:**

- Design the order tracking page.
- Identify the order statuses customers need to see.
- Plan how order information will be displayed.
- Define how status updates should be communicated.

**Acceptance criteria:**

- Customers can access their order status.
- Status information is clear and understandable.
- The displayed information corresponds to the relevant order.

### User Story 6: Order History

**User story:** As a returning customer, I want to view my previous orders so that I can refer to earlier bookings.

**Tasks:**

- Design the order history page.
- Identify the information required for each previous order.
- Plan how customers can access their order history.
- Define an understandable layout for historical order information.

**Acceptance criteria:**

- Customers can view their previous orders.
- Each entry displays relevant order information.
- The page is organised so customers can distinguish between orders.

### User Story 7: Customer Profile and Settings

**User story:** As a customer, I want to manage my profile details so that my account information remains relevant.

**Tasks:**

- Design the profile and settings page.
- Identify the profile information customers may need to manage.
- Plan validation for changes to profile details.
- Define how changes should be confirmed to customers.

**Acceptance criteria:**

- Customers can view their profile information.
- Editable fields are clearly identified.
- Invalid information receives appropriate feedback.

## 3. Prioritisation

We consider account access and booking important because customers need a way to access the service and submit laundry requests. Order confirmation and tracking support communication, while order history and profile settings support continued use.

Our proposed priority order is:

1. Customer login and registration.
2. Laundry booking.
3. Order confirmation.
4. Order tracking.
5. Order history.
6. Customer profile and settings.

This is a proposed priority order based on the customer journey. Our Trello product backlog remains the reference for the features and sprint organisation recorded by our team.

## 4. Reflection

Developing user stories helped me understand the importance of describing a feature from the customer's perspective rather than focusing only on the technical work. For example, the login story explains why secure account access matters, while its tasks identify the work needed to support that need.

The Trello Login Page card demonstrates how a user-facing feature can be broken down into smaller subtasks with assigned responsibilities. This makes work easier to organise and progress easier to review.

I also learned that acceptance criteria help define what a feature should achieve. They provide a basis for checking whether the completed work meets the intended requirement. Going forward, our team should continue to connect each user story to its Trello tasks and record testing results when testing has actually taken place.

## 5. Supporting Evidence

### Evidence 1: Login Page Task Breakdown

Our Trello card records five completed subtasks covering the login screen, credential storage, login API, error handling and documentation.

![GoClean Login Page tasks](assets/img/login-page-tasks.png)

### Evidence 2: Trello Board and Sprint Lists

Our board shows how proposed application features are organised into the product backlog and sprint lists.

![GoClean Trello board](assets/img/goclean-trello-board.png)

### Evidence 3: Proposed Application Wireframes

The wireframes illustrate the proposed screens that support the customer journey.

![GoClean wireframes](assets/img/goclean-wireframes.png)
