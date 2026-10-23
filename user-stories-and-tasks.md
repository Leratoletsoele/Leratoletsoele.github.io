# GoClean — User Stories and Tasks

## 1. Introduction

User stories describe the features of GoClean from the perspective of the people who may use the service. They help our team understand customer needs and organise the work required to support those needs.

We used our proposed digital platform features and Trello board to identify user stories and break them down into smaller tasks. Each story explains what a potential customer wants to achieve and why the feature would be useful.

The stories and acceptance criteria below describe the intended functionality of the proposed GoClean platform. They do not imply that every feature has been implemented or tested.

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
- The system verifies the submitted credentials.
- Invalid login attempts receive a clear error message.
- Customer credentials are handled securely.

**Evidence:**

Our Trello Login Page card shows five completed subtasks and 100% checklist progress. This demonstrates the recorded completion of the checklist, although further implementation and testing evidence would be needed to verify that the feature works as intended.

![GoClean Login Page tasks](assets/img/login-page-tasks.png)

### User Story 2: Customer Registration

**User story:**

As a new customer, I want to register for an account so that I can use the proposed GoClean booking service.

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
- The registration process explains when an account has been created successfully.

**Purpose:**

Registration would allow new customers to create accounts before accessing the proposed booking service. The tasks identify the planning and development work required to support this feature.

### User Story 3: Laundry Booking

**User story:**

As a customer, I want to book a laundry pickup so that I can arrange collection without having to manage the process manually.

**Tasks recorded on our Trello Order Page (Booking) card:**

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
- The booking process communicates whether the submission was successful.

**Evidence:**

Our Trello Order Page (Booking) card shows five completed subtasks and 100% checklist progress. The tasks are assigned to Solomon Machaule, Lerato Letsoele, Oratilwe Komane, Nomhle Njengele and Thandeka Malande. This demonstrates how the booking feature was divided into manageable tasks and how completion was recorded on Trello. However, checklist completion alone does not independently confirm that the booking functionality has been fully implemented and tested.

![GoClean Order Page Booking tasks](assets/img/order-page-booking.png)

### User Story 4: Order Confirmation

**User story:**

As a customer, I want to receive confirmation after submitting a laundry booking so that I know my request has been received.

**Tasks:**

- Plan the order confirmation screen.
- Identify the booking details to display.
- Define confirmation messages for successful submissions.
- Consider how errors should be communicated.

**Acceptance criteria:**

- A successful booking displays a confirmation.
- The confirmation provides relevant order information.
- The customer can distinguish a successful submission from an unsuccessful one.
- The confirmation corresponds to the booking that was submitted.

**Purpose:**

Order confirmation would give customers feedback after submitting a booking and help them understand whether their request has been received.

### User Story 5: Order Tracking

**User story:**

As a customer, I want to track my laundry order so that I can understand its progress.

**Tasks:**

- Design the order tracking page.
- Identify the order statuses customers need to see.
- Plan how order information will be displayed.
- Define how status updates should be communicated.

**Acceptance criteria:**

- Customers can access the status of their relevant order.
- Status information is clear and understandable.
- The displayed information corresponds to the correct order.
- Customers can distinguish between different stages of the proposed service.

**Purpose:**

Order tracking is intended to improve communication by allowing customers to understand the progress of their laundry orders.

### User Story 6: Order History

**User story:**

As a returning customer, I want to view my previous orders so that I can refer to earlier bookings.

**Tasks:**

- Design the order history page.
- Identify the information required for each previous order.
- Plan how customers can access their order history.
- Define an understandable layout for historical order information.

**Acceptance criteria:**

- Customers can view their previous orders.
- Each entry displays relevant order information.
- The page is organised so customers can distinguish between orders.
- Customers can identify the details associated with an earlier booking.

**Purpose:**

Order history would help returning customers review their previous bookings without having to enter the information again.

### User Story 7: Customer Profile and Settings

**User story:**

As a customer, I want to manage my profile details so that my account information remains relevant.

**Tasks:**

- Design the profile and settings page.
- Identify the profile information customers may need to manage.
- Plan validation for changes to profile details.
- Define how changes should be confirmed to customers.

**Acceptance criteria:**

- Customers can view their profile information.
- Editable fields are clearly identified.
- Invalid information receives appropriate feedback.
- Customers receive confirmation when profile changes are saved successfully.

**Purpose:**

Profile and settings functionality would allow customers to review and maintain their account details as part of the proposed platform.

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

The priority order is a planning decision for this document. Our Trello product backlog remains the reference for the features and sprint organisation recorded by our team. Priorities may change as the team reviews requirements, feedback and project constraints.

## 4. Reflection

Developing user stories helped me understand the importance of describing a feature from the customer's perspective rather than focusing only on the technical work. For example, the login story explains why secure account access matters, while its tasks identify the work required to support that need.

The Login Page and Order Page (Booking) Trello cards demonstrate how features can be divided into smaller subtasks, assigned to team members and tracked through checklists. This makes the work more visible and helps the team understand how individual tasks contribute to a larger feature.

I also learned that acceptance criteria help define what a feature should achieve. They provide a basis for checking whether completed work meets the intended requirement. More specific acceptance criteria can make it easier to identify what needs to be tested and what evidence is needed to demonstrate that a feature works correctly.

One area for improvement is ensuring that each user story is consistently linked to its corresponding Trello card and that task completion is supported by appropriate implementation or testing evidence. In future, I would encourage the team to record testing outcomes and update task statuses carefully so that planned work, checklist progress and verified functionality are clearly distinguished.

Overall, this activity helped me understand how user stories, tasks, acceptance criteria and prioritisation work together to organise Agile project requirements.

## 5. Supporting Evidence

The following evidence supports our user stories, task organisation and proposed application design. Screenshots of the Login Page and Order Page (Booking) task breakdowns are included alongside their relevant user stories above to avoid unnecessary repetition.

### Evidence 1: Trello Board and Sprint Lists

Our Trello board shows how the proposed application features are organised into the product backlog and sprint lists. It supports our explanation of how the team structures and tracks planned work.

![GoClean Trello board](assets/img/goclean-trello-board.png)

### Evidence 2: Proposed Application Wireframes

The GoClean wireframes illustrate the proposed application screens and intended customer journey. They provide design evidence for the planned platform rather than proof that all screens have been implemented.

![GoClean wireframes](assets/img/goclean-wireframes.png)
