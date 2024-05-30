# EduMax

EduMax is a subscription-based learning platform designed to showcase core skills in ASP.NET development with an Angular frontend. It allows users to register, subscribe to courses, track their learning progress, and access course materials. This project focuses on key functionalities to demonstrate proficiency in building web applications.

## Features

### User Registration and Authentication

- **User Roles**: Support for Students and Admins.
- **Registration**: Email sign-up.
- **Authentication**: Secure login, password reset, and two-factor authentication (2FA) via email or SMS.

### Subscription Management

- **Subscription Plans**: Single subscription tier.
- **Payment Integration**: Basic integration with a payment gateway (e.g., PayPal, Stripe).
- **Payment Lifecycle**:
  - **Subscription Activation**: Users can activate their subscription by making a payment.
  - **Billing Cycle**: Automated monthly billing with invoice generation.
  - **Reminders**: Email reminders for upcoming renewals and overdue payments.

### Course Management

- **Course Creation**: Admins can create and manage courses.
- **Modules**: Each course can have multiple modules.
- **Content Types**:
  - **Videos**: Upload and manage course videos.
  - **Resources**: Attach files (PDFs, links) to each video.
- **Course Catalog**: List of available courses.

### Learning Experience

- **Dashboard**: Basic student dashboard showing enrolled courses and progress.
- **Progress Tracking**: Track course completion status and module progress.

### Admin Panel

- **User Management**: Manage student accounts.
- **Course Management**: Create and update course details, modules, and resources.

### Notifications

- **Email Notifications**: Course updates, subscription reminders, and 2FA codes.

### Technology Stack

- **Backend**: ASP.NET Core
- **Frontend**: Angular
- **Database**: SQL Server or Azure SQL Database
- **Hosting**: Microsoft Azure or other cloud providers
- **Version Control**: Git (GitHub, GitLab, or Bitbucket)

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download)
- [Node.js and npm](https://nodejs.org/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [Git](https://git-scm.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/edumax.git
   cd edumax
   ```

2. Install backend dependencies:

   ```bash
   dotnet restore
   ```

3. Navigate to the `ClientApp` directory and install frontend dependencies:

   ```bash
   cd ClientApp
   npm install
   ```

4. Configure the database connection in `appsettings.json`.

5. Apply database migrations:

   ```bash
   dotnet ef database update
   ```

6. Run the application:

   ```bash
   dotnet run
   ```

7. In a separate terminal, navigate to the `ClientApp` directory and start the Angular development server:
   ```bash
   cd ClientApp
   ng serve
   ```
