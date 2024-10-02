# Next js Training Highlights
## Platform details which is to be made:- 
- To build a website similar to Practo, which is a platform for booking doctor appointments, managing health records, and providing telemedicine services, you’ll need to consider several essential features and technologies. Here's a detailed breakdown:

### Key Features to Implement
   - User Registration & Authentication
   - User Types: Patients, doctors, and admins.
   - Sign Up / Login: Allow users to register with email, phone, or social media accounts.
   - Search by Doctor, Specialty, Location: Provide filters for patients to search for doctors based on specialty, location, availability, or rating.
   - Profile Information: Each doctor should have a detailed profile with qualifications, experience, reviews, consultation fees, and available appointment slots.
   - Rating & Reviews: Patients can rate doctors and leave feedback.  
   - Appointment Booking System
      - Real-Time Availability: Show available time slots for each doctor in real-time. 
      - Booking Confirmation: Send confirmation via email or SMS after a patient books an appointment.
      - Appointment Reminders: Send reminders to patients about their upcoming appointments.
Telemedicine & Video Consultation
      - Video Call Integration: Integrate APIs like Twilio or WebRTC to provide video consultations.
      - Chat Functionality: Allow patients to communicate with doctors via chat, especially for follow-up questions.
      - Payment Gateway Integration: Use services like Stripe, Razorpay, or PayPal to process payments for consultations.
Prescription & Medical Records
      - Digital Prescriptions: Allow doctors to send prescriptions to patients digitally.
Upload Health Records: Patients should be able to upload and store their medical history and reports securely.
      - Payments & Billing
        - Secure Payment Gateway: Integrate payment gateways to process consultation fees and other services.
        - Invoices & Receipts: Generate and send receipts to patients via email.
      - Notifications
          - Push Notifications: Send reminders about upcoming appointments, new messages from doctors, and prescription updates.
          - SMS/Email Notifications: Notify users about important events, including booking confirmations and appointment cancellations.
      - Admin Dashboard
          - User Management: Admins should be able to manage both patient and doctor accounts.
      - Appointment Management: Admins can oversee appointments and handle disputes or cancellations. 
      - Analytics: Track performance metrics like user activity, bookings, revenue, etc.
### Tech Stack
   - Frontend Framework
       - Next.js: React framework for building full-stack applications.
       - Programming Language
            - TypeScript: Used for both frontend and backend development.
       - UI Components and Styling
           - Shadcn UI: Collection of components built on top of Radix UI.
           - Radix UI: Unstyled React components.
           - Tailwind CSS: Utility-first CSS framework for styling.
       - Authentication
            - Clerk: Comprehensive authentication solution with features like email/password, social login, multi-factor authentication, and more.
      - Database Management
        - Drizzle ORM: Type-safe ORM that integrates with TypeScript.
        - Drizzle Kit: CLI tool for database migration.
        - Drizzle Studio: Visual interface for managing the database.
      - Payment Processing
        - Stripe: Handles payments and subscriptions.
      - Internationalization
        - Next-Intl: Library for supporting multiple languages in Next.js.
        - Crowdin: Localization platform that integrates with GitHub.
      - Form Management and Validation
          - React-Hook-Form: Simplifies form handling in React.
          - Zod: Ensures data validation.
      - Testing
          - Vitest: Test runner that supports TypeScript and ESM.
              - React Testing Library: Utilities for interacting with React components.
                - Playwright: Tool for end-to-end and integration testing.
      - Continuous Integration
          - GitHub Actions: Automates running tests and checks on code.
      - Logging
          - Pino: Fast and lightweight logging library for Node.js.
          - Better Stack: Platform for real-time log monitoring, alerting, and visualization.
      - Error Monitoring
          - Sentry: Captures errors and exceptions, providing detailed reports.
      - Environment Variables
          - T3 Env: Uses Zod to validate and transform environment variables.
      - Linter and Code Formatter
ESLint: Ensures code quality by enforcing best practices.
        - Prettier: Enforces a consistent coding style.
        - eslint-plugin-playwright: Ensures Playwright tests follow best practices.
        - eslint-plugin-tailwind: Enforces best practices for Tailwind CSS.
      - Code Editor and Extensions
          - VSCode: Code editor of choice.
          - vscode-eslint: Integrates ESLint into VS Code.
          - vscode-tailwindcss: Provides IntelliSense and - syntax highlighting for Tailwind CSS.
          - vscode-github-actions: Manages GitHub Actions workflows directly in VSCode.
          - i18n-ally: Supports internationalization, offering translation key management.
## Important Links 
 [Async communication for remote work](https://handbook.gitlab.com/handbook/company/culture/all-remote/asynchronous/)

 [Figma Files](https://www.figma.com/design/iR4O6scj0ZA2Vehnnmw0og/Shedula-V.2.0?node-id=357-486&t=OgRFCsizaPdgDGlO-1)

 [Design Patterns](https://samnewman.io/patterns/architectural/bff/)