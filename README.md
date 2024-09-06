# Abhigyaan App

Abhigyaan is an Android application built to manage the activities of the Abhigyaan organization, which is dedicated to providing free education and fostering community engagement. This app offers various tools to streamline volunteer management, event coordination, and real-time updates. By leveraging Firebase and modern Android development practices, Abhigyaan ensures efficient communication and organization within the team.

## Features

### Volunteer Management
- **Profile Section:**
  - Displays detailed user information fetched directly from Firebase.
  - Users can view their role, contact details, and assigned batches.

- **Volunteer Schedule:**
  - Automatically updates volunteer names based on the day of the week using Firebase Realtime Database.
  - Displays schedules for different batches: Project Lamani, Disha, Evening Batch, English Batch, and Mess Batch.

- **Custom Fonts:**
  - Consistent and professional font styling applied to all TextViews related to volunteers.

### Substitution Requests
- **Request Activity:**
  - Allows volunteers to request substitutions for their shifts.
  - Features real-time updates so that all users can see and respond to requests instantly.
  - Includes a floating action button (FAB) for adding new requests.

### Events and Updates
- **Events Activity:**
  - Interactive events section with liquid animations for a visually engaging experience.
  - Contains three fragments with image views to showcase upcoming and past events.

- **Update Section:**
  - Displays a list of real-time updates pulled from Firebase.
  - Custom introduction section to provide context about the latest updates.

- **Annual Events:**
  - The app features special sections for major annual events like Independence Day, Teacher's Day, Sports Day, and Abhigyaan Week.
  - Promotes patriotism and community spirit through interactive content.

### Image Galleries and Sliders
- **Carousel and Sliders:**
  - Dynamic image carousels for showcasing event highlights and important announcements.

- **Firebase Photo Gallery:**
  - Allows users to upload, view, and manage photos directly from Firebase Storage.
  - A gallery section that organizes photos by event or batch.

- **Model and Adapter Naming:**
  - Uses distinct names for the model class and adapter in the `galleryActivity` to ensure clarity and maintainability.
    - Model class: `PhotoItem`
    - Adapter class: `PhotoAdapter`

### Birthday Wishes
- **Birthday Feature:**
  - Automatically displays a greeting card with an uplifting message on a volunteer's birthday.
  - Includes animated balloons and other celebratory effects.
  - The feature is managed through Firebase Realtime Database.

- **Birthday Dashboard:**
  - Special shout-out screen on the dashboard for daily birthday wishes.
  - Quotes and messages can be customized for each volunteer.

### Google Authentication
- **One-Tap Sign-In:**
  - Simplifies the login process with Google's One-Tap Sign-In.
  - Ensures secure access to the app using `BeginSignInRequest` and `SignInClient` classes from the Google Identity API.

- **Access Control:**
  - Restricts access to certain activities based on the authenticated Google account.
  - Only approved accounts can access sensitive sections like substitution requests and volunteer management.

### WhatsApp Messaging
- **Send WhatsApp Messages:**
  - Allows authorized users to send WhatsApp messages directly from the app.
  - Features integration with the WhatsApp application for sending messages related to volunteer schedules.

### Content Management
- **Firebase Integration:**
  - Real-time data synchronization across all users, ensuring that everyone sees the most up-to-date information.
  - Integration with Firebase Storage for media files, including images and videos.

- **Donation Activity:**
  - Users can upload images and item names for donation drives, stored in Firebase.
  - A RecyclerView displays all donated items, allowing for easy management and updates.

- **Expandable CardViews:**
  - Supports dynamic addition of items in various activities, allowing users to expand or collapse content as needed.

### UI/UX Customization
- **Light Theme Enforcement:**
  - The app enforces a light theme, regardless of the system settings on the user's device.
  - Ensures a consistent and user-friendly interface.

- **User-Friendly Navigation:**
  - Intuitive bottom navigation bar with streamlined sections for "Upcoming" and "Past" activities.
  - Onboarding walkthrough screens with CardView integration for a seamless user experience.

- **Floating Action Button Visibility:**
  - The FloatingActionButton (FAB) for adding new items or requests is visible only to authorized users.
  - User authorization is based on a list of approved email addresses, ensuring that only specific users can access certain features.

### Web Integration
- **AbhigyaanWeb:**
  - A companion React website designed to reflect key functionalities of the Abhigyaan app.
  - Allows for real-time updates via Firebase, ensuring consistency between the app and the website.
  - Deployment planned via Netlify for reliable and scalable hosting.

- **Cross-Platform Sync:**
  - Ensures that updates made on the web platform are instantly reflected in the mobile app and vice versa.

## Contact

**Email and Contact Info:**  
ANUBHAV CHOURASIA  
9798810492  
f20230939@goa.bits-pilani.ac.in  
![Abhigyaan App](https://github.com/devvcraze/abhigyaanreadme/blob/main/WhatsApp%20Image%202024-08-13%20at%2010.01.53.jpeg)
