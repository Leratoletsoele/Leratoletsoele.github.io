
# GoClean – User Stories and Tasks

## 1. Introduction

User stories describe the features that users need from the GoClean laundry service application. They help the team understand the user's needs and organise the work into smaller tasks.

GoClean is a proposed laundry pickup and delivery service aimed at university students and busy residents who need an affordable and convenient way to manage their laundry.

The user stories below describe the planned functionality of the application and the tasks required to develop it.

## 2. User Stories

### User Story 1: User Login

**As a** registered user,  
**I want to** log in using my email address and password,  
**So that** I can access my account.

**Tasks:**
- Create the login page.
- Add email and password fields.
- Add a password visibility option.
- Include a Login button.
- Provide a link for users who need to register.

**Acceptance criteria:**
- The user can enter an email address and password.
- The password field allows the user to show or hide the password.
- The user can select the Login button.
- A registration link is available.

**Priority:** High

**Supporting evidence:** The screenshot below shows the GoClean login interface. It provides evidence of the designed login page, rather than proof of successful authentication.

![GoClean Login Interface](assets/img/goclean-login.png)

The Login Page task card on Trello also records the team's task breakdown and completed checklist.

### User Story 2: User Registration

**As a** new user,  
**I want to** create an account,  
**So that** I can use the GoClean service.

**Tasks:**
- Create a registration interface.
- Add the required user information fields.
- Provide a way to submit registration details.
- Include a link to the login page.

**Acceptance criteria:**
- A new user can enter the required information.
- The page provides a registration submission option.
- Existing users can navigate to the login page.

**Priority:** High

### User Story 3: View Laundry Services

**As a** potential customer,  
**I want to** view the available laundry services and their prices,  
**So that** I can choose a service that suits my needs and budget.

**Tasks:**
- Create a services page.
- Display the available laundry service categories.
- Show starting prices for the services.
- Provide a way to proceed towards placing an order.

**Acceptance criteria:**
- The available service categories are displayed.
- Starting prices are shown.
- The user can identify a suitable service.

**Priority:** High

**Supporting evidence:** The screenshot shows the GoClean Services page and its displayed service categories and starting prices.

![GoClean Services Interface](assets/img/goclean-services.png)

### User Story 4: Book a Laundry Order

**As a** customer,  
**I want to** book a laundry service,  
**So that** I can request laundry collection and processing.

**Tasks:**
- Design the order-booking page.
- Provide fields for the required order details.
- Allow the customer to select a service.
- Provide a way to submit an order.

**Acceptance criteria:**
- The customer can enter the required booking information.
- The customer can select a service.
- An order submission option is provided.
- The application should provide appropriate feedback after submission.

**Priority:** High

**Supporting evidence:** The Trello Order Page (Booking) card records five checklist subtasks marked complete and shows the team's task organisation. Checklist completion indicates recorded task progress; it does not independently confirm that booking works end to end.

![GoClean Order Page Booking Task](assets/img/order-page-booking.png)

### User Story 5: Receive Order Confirmation

**As a** customer,  
**I want to** receive confirmation after placing an order,  
**So that** I know my booking has been received.

**Tasks:**
- Plan the order confirmation interface.
- Display a summary of the submitted order.
- Provide confirmation feedback to the customer.

**Acceptance criteria:**
- The customer should receive clear feedback after submitting an order.
- The order summary should show the relevant booking information.

**Priority:** High

### User Story 6: Track an Order

**As a** customer,  
**I want to** track the progress of my laundry order,  
**So that** I know its current status.

**Tasks:**
- Plan an order-tracking page.
- Display the relevant order information.
- Provide a status indicator for the order.

**Acceptance criteria:**
- The customer should be able to identify the relevant order.
- The current order status should be displayed when tracking functionality is implemented.

**Priority:** Medium

### User Story 7: View Order History

**As a** returning customer,  
**I want to** view my previous orders,  
**So that** I can review my laundry service history.

**Tasks:**
- Plan an order-history page.
- Display previous orders associated with the customer.
- Show relevant details for each order.

**Acceptance criteria:**
- Previous orders should be displayed for the relevant customer.
- The customer should be able to review the available order details.

**Priority:** Medium

### User Story 8: Manage Profile and Settings

**As a** registered customer,  
**I want to** manage my profile information,  
**So that** my account details can remain up to date.

**Tasks:**
- Plan a profile page.
- Provide fields for relevant customer information.
- Include an option to update profile details.

**Acceptance criteria:**
- The customer should be able to view their profile information.
- The interface should provide a way to update relevant details.

**Priority:** Medium

## 3. Prioritisation

The user stories were prioritised according to the importance of each feature to the proposed customer journey.

| Priority | User stories | Reason |
|---|---|---|
| High | Login, Registration, Services, Laundry Booking, Order Confirmation | These features support access to the service and the intended booking process. |
| Medium | Order Tracking, Order History, Profile and Settings | These features support customers after account creation and booking. |

The prioritisation provides a guide for deciding which features should receive attention first. It does not mean that every feature has been fully implemented or tested.

## 4. Team Task Organisation

The team used Trello to organise project tasks and record progress. User stories were broken down into smaller tasks so that the work could be managed more easily.

The Trello board provided a shared view of the project backlog and sprint organisation. Individual task cards, such as Login Page and Order Page (Booking), also recorded subtasks and checklist progress.

## 5. Reflection

Creating user stories helped me understand the importance of planning a system from the user's perspective. Instead of focusing only on pages and technical features, I considered what customers would need to do when using GoClean.

I learned that acceptance criteria are important because they describe what a feature should achieve. They also provide a basis for checking whether the completed feature meets its intended requirements.

Prioritising the user stories helped me identify the features that are most important to the proposed laundry booking journey. Login, registration, services and booking were given high priority because they form part of the intended customer experience.

The Trello task cards helped the team break larger pieces of work into smaller tasks and record progress. However, I also learned that a completed checklist does not automatically prove that a feature works correctly. Functionality must be checked and tested separately.

If I were to improve this process, I would document clearer test results against each acceptance criterion and maintain evidence of which features have been implemented and verified. This would make it easier to distinguish planned functionality, recorded task progress and working application features.

## 6. Supporting Evidence

The following evidence supports this section:

1. **Login interface screenshot** – shows the designed login page.
2. **Services interface screenshot** – shows the available service categories and displayed starting prices.
3. **Trello Order Page (Booking) task screenshot** – shows the booking task breakdown and recorded checklist progress.
4. **Trello board screenshot** – provides an overview of the team's project and task organisation.

The evidence is included to demonstrate the design, planning and task organisation associated with the user stories. Screenshots of interfaces and Trello cards should not be treated as proof that all features have been completed or tested.
