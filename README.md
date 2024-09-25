# Weight Lifting Tracker

![Weight Lifting Tracker Logo](path_to_logo_image.png)

## Table of Contents

- [Project Description](#project-description)
- [Design Work](#design-work)
  - [Interviewing](#interviewing)
  - [Sketching](#sketching)
  - [Feedback](#feedback)
- [Interface Description](#interface-description)
  - [Features and Controls](#features-and-controls)
  - [Screenshots](#screenshots)
- [Implementation Details](#implementation-details)
  - [Technologies and Libraries](#technologies-and-libraries)
  - [Code Structure](#code-structure)
  - [State Management](#state-management)
  - [Styling](#styling)
- [Use of AI](#use-of-ai)
- [Future Work](#future-work)
  - [Planned Enhancements](#planned-enhancements)
  - [Incomplete Work](#incomplete-work)
- [Demo Video](#demo-video)
- [Links](#links)
  - [GitHub Repository](#github-repository)
  - [Live Application](#live-application)
- [Conclusion](#conclusion)

---

## Project Description

**Weight Lifting Tracker** is a user-friendly application designed to help individuals monitor and manage their workout routines effectively. The application allows users to log various types of exercises, track weights and repetitions, monitor cardio activities, and review past performance to visualize progress over time. By addressing common pain points found in existing workout trackers—such as rigidity, cluttered interfaces, and lack of flexibility—**Weight Lifting Tracker** offers a streamlined and customizable experience tailored to the needs of fitness enthusiasts.

**Key Features:**
- **Exercise Logging:** Easily add, edit, and remove exercises with specific weights and repetitions.
- **Cardio Tracking:** Log cardio activities including speed and duration.
- **Water and Stretching Intake:** Monitor daily water intake and stretching routines.
- **Progress Overview:** Visualize your workout progress over days, weeks, and months.
- **User-Friendly Interface:** Intuitive design that minimizes the time spent on data entry, allowing users to focus more on their workouts.

---

## Design Work

### Interviewing

To ensure that **Weight Lifting Tracker** meets the real needs of its users, interviews were conducted with two close friends who are avid gym-goers. The interviews aimed to uncover the strengths and weaknesses of current workout trackers and identify key features that users desire.

**Key Insights from Interviews:**

- **Desired Features:**
  - **Ease of Use:** Users want a straightforward interface that allows quick logging of workouts without unnecessary steps.
  - **Customization:** The ability to track preferred lifts and weights without adhering to rigid pre-made plans.
  - **Comprehensive Logging:** Detailed tracking of weights, reps, and sets for each exercise.

- **Common Issues with Existing Trackers:**
  - **Rigidity:** Lack of flexibility in customizing workouts, forcing users to follow pre-set plans or create extensive routines from scratch.
  - **Cluttered Interfaces:** Overly complex designs with too many features, making simple tasks cumbersome.
  - **Lack of Intuitive UI:** Difficulty in navigating the app to perform basic functions like logging a lift or viewing past entries.

- **Favorite Aspects:**
  - **Progress Visualization:** Tracking improvements over time provides motivation and a sense of accomplishment.
  - **Comprehensive Data Logging:** Detailed records of workouts act as a personal diary, aiding in future workout planning.

### Sketching

Based on the interview feedback, initial sketches were created to outline the application's layout and user flow. The focus was on minimizing clutter while providing essential features, ensuring that users can navigate the app effortlessly.

**Design Priorities:**
- **Minimalist Layout:** Clean design with clearly defined sections for different activities.
- **Accessible Navigation:** Easy access to logging functions and progress overview from the main dashboard.
- **Responsive Design:** Ensuring usability across various devices, including desktops and mobile devices.

### Feedback

Continuous feedback was sought during the design phase to refine the interface and functionality. Iterative testing with potential users helped in identifying areas for improvement, leading to enhancements in usability and feature set.

---

## Interface Description

The **Weight Lifting Tracker** boasts an intuitive and clean interface designed to facilitate seamless workout logging and progress tracking.

### Features and Controls

**Main Dashboard:**
- **User Info Section:** Displays the user's name, current date/time, days since starting the tracker, and active days.
- **Customization Options:** Dropdown menus to set goals and customize activities.
- **Performance Overview:** Visual charts and statistics showcasing workout progress.

**Logging Activities:**
- **Log Exercise:** Searchable interface to add exercises with specific weights and reps.
- **Log Cardio:** Input fields for speed (mph) and time (minutes).
- **Log Water Intake:** Simple input to record daily water consumption.
- **Log Stretching:** Entry field for minutes of stretching.
- **Log Current Weight:** Update current body weight with an input field.

**Previous Entries:**
- **List of Past Workouts:** Each entry displays the date, exercises performed, cardio details, stretching time, and options to edit the entry.
- **Edit Entry Modal:** Pop-up form allowing users to modify existing entries with larger input fields for better usability.

### Screenshots

*Replace the placeholder paths with actual screenshots of your application.*

- **Main Dashboard:**
  ![Main Dashboard](path_to_screenshot_main_dashboard.png)

- **Logging Exercise:**
  ![Log Exercise](path_to_screenshot_log_exercise.png)

- **Performance Overview:**
  ![Performance Overview](path_to_screenshot_performance_overview.png)

- **Edit Entry Modal:**
  ![Edit Entry Modal](path_to_screenshot_edit_entry_modal.png)

---

## Implementation Details

### Technologies and Libraries

**Frontend Framework:**
- **Svelte:** Chosen for its reactivity and performance benefits, Svelte facilitates building a dynamic and responsive user interface with minimal overhead.

**Build Tool:**
- **Vite:** Utilized for its fast build times and efficient development workflow, Vite ensures quick iterations during development and optimized production builds.

**Deployment:**
- **GitHub Pages:** The application is hosted on GitHub Pages, providing a reliable and easily accessible platform for users.


**Key Components:**
- **App.svelte:** The root component that orchestrates the layout and routing of the application.
- **main.js:** Entry point that initializes the Svelte application.
- **PreviousEntries.svelte:** Handles the display and editing of past workout entries.
- **stores/entries.js:** Manages the state of workout entries and selected activities using Svelte's store feature.

### State Management

**Svelte Stores:**
- **Entries Store:** Keeps track of all workout entries, allowing components to subscribe and react to changes.
- **SelectedActivities Store:** Manages the list of activities (e.g., Exercise, Cardio) that the user can log.

### Styling

**CSS Variables:**
- Utilized CSS variables to maintain consistency in design and facilitate easy theme customization.

**Responsive Design:**
- Ensured that the application is fully responsive, adapting gracefully to various screen sizes and devices.

---

## Use of AI

*As per the current project details, AI is not utilized in the development of **Weight Lifting Tracker**. However, future plans include integrating AI-driven features.*

**Future AI Integration:**
- **Progressive Overload Recommendations:**
  - **Implementation:** Integrate algorithms that analyze past performance data to suggest optimal weights and reps for future workouts.
  - **Strengths:**
    - **Personalization:** Provides tailored workout plans that adapt to the user's progress.
    - **Efficiency:** Automates the adjustment of workout parameters, saving users time and effort.
  - **Limitations:**
    - **Data Dependency:** Requires sufficient user data to make accurate recommendations.
    - **Complexity:** Incorporating AI models increases the complexity of the application and may require additional resources.

---

## Future Work

### Planned Enhancements

1. **Progressive Overload Function:**
   - **Description:** Enhance the feature to allow users to specify their daily workouts. The app will suggest weights, sets, and reps based on historical data, eliminating the need for manual input.
   - **Implementation:** Incorporate algorithms that analyze past performance to provide tailored workout suggestions.
   - **Benefits:** Enhances user experience by providing intelligent workout recommendations, promoting continuous improvement.

2. **Enhanced User Interface:**
   - **Description:** Further refine the UI to make it even more intuitive and visually appealing.
   - **Implementation:** Incorporate user feedback to make design adjustments, improve navigation, and enhance accessibility.

3. **Additional Activity Tracking:**
   - **Description:** Expand the range of activities that can be tracked, such as flexibility exercises, nutrition logs, and sleep patterns.
   - **Implementation:** Add new sections and input fields to accommodate additional data types.

4. **Mobile Application:**
   - **Description:** Develop a mobile version of the application to provide users with on-the-go access.
   - **Implementation:** Use frameworks like Svelte Native or React Native to build cross-platform mobile apps.

5. **AI Integration:**
   - **Description:** Incorporate AI features to provide personalized workout recommendations based on user data.
   - **Implementation:** Integrate machine learning models and possibly cloud-based AI services to handle data processing and recommendations.

### Incomplete Work

- **Progressive Overload Notification System:**
  - **Description:** Currently, the app autopopulates exercises based on existing data. The next step involves notifying users with suggested weights and reps tailored to their progress.
  - **Current Status:** Initial groundwork laid; requires integration of notification triggers and user input handling.
  - **Screenshot Placeholder:**
    ![Progressive Overload Feature](path_to_screenshot_progressive_overload.png)

---

## Demo Video

Creating a demo video is an excellent way to showcase your application's features and usability. Below are the steps to create and integrate a demo video into your project.

### Recording the Demo

**Tools Needed:**
- **Screen Capture Software:** Tools like [OBS Studio](https://obsproject.com/), [QuickTime Player](https://support.apple.com/quicktime), or [Loom](https://www.loom.com/) can be used.
- **Microphone:** For voiceover narration explaining the application's features.

**Recording Steps:**
1. **Prepare Your Script:**
   - **Introduction:** Briefly introduce yourself and the project.
   - **Features Overview:** Highlight key features such as logging exercises, tracking cardio, viewing past entries, and editing entries.
   - **User Flow:** Demonstrate how a user would interact with the app, from logging a workout to viewing progress.
   - **Conclusion:** Summarize the application's benefits and future enhancements.

2. **Capture the Screen:**
   - **Navigate Through the App:** Show each feature in action, ensuring smooth transitions and clear visibility.
   - **Highlight Important Elements:** Use cursor movements and zoom features to draw attention to specific parts of the interface.

3. **Provide Narration:**
   - **Explain Each Step:** Verbally guide viewers through the application's functionalities.
   - **Emphasize Ease of Use:** Highlight how the interface design simplifies workout logging and tracking.

4. **Finalize the Video:**
   - **Edit the Recording:** Trim unnecessary parts, add annotations if needed, and ensure the audio is clear.
   - **Export the Video:** Save the video in a commonly supported format like MP4.

### Uploading the Demo Video

**Options:**
- **YouTube:**
  - **Upload Steps:**
    1. Log in to your YouTube account.
    2. Click on the upload icon and select your demo video.
    3. Add a descriptive title, e.g., "Weight Lifting Tracker Demo by Jacob Sayatovic."
    4. Provide a detailed description outlining the video's content.
    5. Set the video to **Public** or **Unlisted**.
    6. Click **Publish**.

### Linking the Demo Video

**On Your Webpage:**
```markdown
## Demo Video

Watch a short demo of the **Weight Lifting Tracker** in action.

[![Watch the Demo Video](path_to_thumbnail_image.png)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)
