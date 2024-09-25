# Weight Lifting Tracker

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

**Weight Lifting Tracker** is a user-friendly application designed to help a person maintain their workouts more systematically. This application will allow users to record various types of exercises, track weights and repetitions, log cardio activities, and review previous performances with time plotted to visualize progress. Addressing common pain points, such as rigidity, cluttered interfaces, and a general lack of flexibility that mainstream exercise trackers may have, **Weight Lifting Tracker** is a lightweight, streamlined workout tracker fully customizable to the wants and needs of fitness enthusiasts.

**Key Features:**
* **Exercise Logging:** Easily add, edit, and remove exercises with specified weights and repetitions.
* **Cardio Tracking:** Log cardio activities with speed and duration.
* **Water and Stretching Intake:** Track daily water intake and daily stretching routines.
- **Progress Overview:** Be able to visualize how your workouts are progressing over days, weeks and months.
- **User-Friendly Interface:** Designed in such a way to keep data entry at an absolute minimum, allowing the user to spend more time with their workout.

---

## Design Work

### Interviewing

To implement real user needs into **Weight Lifting Tracker**, two close friends who visit the gym on a regular basis were interviewed. This interview was meant to reveal different strengths and weaknesses of the current workout trackers and pinpoint key features that users want to see.

**Key Insights from Interviews:**

- **Desired Features:**
- **Ease of Use:** Users want a very simple interface where they can log workouts quickly and easily without extra steps.
- **Customization:** Preferred lifts and weights can be tracked while not being forced into rigid pre-made plans.
- **Comprehensive Logging:** Continuing weight, reps and sets for every exercise.

- **Current Problems in Existing Trackers:**
- **Rigidity:** The impossibility of modifying workouts as desired; one has to follow or get close to some highly pre-set workouts or create extensive routines from scratch.
- **Bloated Interfaces:** Over-designing with too many features results in an interface that performs even the most basic of tasks with cumbersome complexity.
- **Lack of Intuitive UI:** Difficulty navigating through the app to do the most basic functions, like logging a lift or viewing past entries.

- **Favorite Things:**
- **Progress Visualization:** It is very exciting and satisfying to see improvement over time.
- **Extensive Workout Logging:** Detailed workout logs serve as a personal diary and useful in planning for future workouts.

### Wireframing

From the results of the interview, preliminary sketches were used to roughly outline how the application would look, focusing on how the user would progress through it. A minimalist approach was taken in design, including only what is necessary, so that the user may navigate the application with ease.

**Key Features of the Design:**
- **Minimalist Layout:** Clean design where different activities are divided into well-marked sections.
Accessible Navigation: Easy access to log and summary of the progress directly from the main dashboard.
Responsive Design: It should assure usability on all devices, from desktops down to mobile phones.

### Feedback

During the design process, there was continuous feedback being sought to make the interface as functional as possible. Iterative testing with target users surfaced many ways in which this design could be bettered in terms of usability or even for addition of feature sets.

---
Description of Interface

The interface of the **Weight Lifting Tracker** is intuitive and clean, allowing smooth logging of workouts and tracking of progress.

### Features and Controls

**Main Dashboard:**
- **User Info Section:** It displays the user's name, current date/time, days since starting tracker, and active days.
- **Customization Options:** Dropdown menus set goals and customize activities.
- **Performance Overview:** Visual charts and statistics showing workout progress.

**Log Activities:**
Log Exercises: A searchable interface to log exercises, including weight and repetitions. Log Cardio: Input for speed in mph and time in minutes. Log Water Intake: Simple input for recording daily water consumption. Log Stretching: Input field to log minutes of stretching. Log Current Weight: Update current body weight with input field.

Previous Entries
- **Workout History:** Each entry indicates a date, exercises logged, cardio details, time spent stretching, and the option to edit the entry.
- **Edit Entry Modal:** Pop-up form that would allow users to edit previous entries; this is made with larger input fields for ease of use.

### Screenshots

*Replace placeholder paths with your actual screenshots for the application.*

- **Main Dashboard:**
![Main Dashboard](path_to_screenshot_main_dashboard.png)

- **Log Exercise:**
![Log Exercise](path_to_screenshot_log_exercise.png)

- **Performance Overview:**
![Performance Overview](path_to_screenshot_performance_overview.png)

- **Edit Entry Modal:**
Edit Entry Modal.png

---

## Implementation Details

### Technologies and Libraries

**Frontend Framework:**

* **Svelte:** Chosen for its out-of-the-box reactivity and performance, Svelte allows the development of a dynamic and responsive UI with minimal computational overhead.

**Build Tool:**

* **Vite:** Employed due to its speed of build times and streamlined development process, Vite ensures rapid iterations during development and optimized builds for production environments.

**Deployment:**
**GitHub Pages:** The application is hosted in GitHub Pages, making it reliable and easy to access.
.smile

**Important Files**
- **App.svelte:** It is the topmost component and organizes the layout and routing of this application.
- **main.js:** This acts as an entry point to start the Svelte application.
- **PreviousEntries.svelte:** A component for displaying and editing previous workout entries.
- **stores/entries.js:** Deals with state related to workout entries and active selection by utilizing Svelte's store feature.
### State Management

**Svelte Stores:**
- **Entries Store:** Stores all workout entries; components subscribe to and take actions based upon this store.
- **SelectedActivities Store:** Stores the activities - such as Exercise, Cardio - that the user can log.

### Styling

**CSS Variables:**
- Used CSS variables throughout to enforce design consistency and to provide the capability for theming easily.

**Responsive Design:**
- Ensured that the application was fully responsive, displaying with great grace across a wide array of screen sizes and devices.

---

## Use of AI

During the ongoing status of the project details, no AI involvement is involved in developing **Weight Lifting Tracker** but maybe some AI-driven feature integrations might be there in some future enhancements.

**Future AI Integration:**
- **Progressive Overload Recommendations:**
- **Implementation:** Integrate algorithms that learn the performance history to recommend ideal weights and reps for the next workout.
- **Strengths:**
- **Personalization:** The workout plan is tailored to the user and will evolve with them in terms of progress.
- **Efficiency:** Automates workout parameters, thereby saving the time and effort of the user.
- **Limitations:**
- **Data Dependency:** Enough user exercise data is needed for the system to make viable recommendations.
- **Complexity:** The inclusion of AI increases the application's complexity because additional resources are required for the implementation of AI models.

---

## Future Work

### Planned Enhancements

1. **Progressive Overload Function:**
- **Description:** This feature shall enable the user to mark which workouts they do on a daily basis. It will auto-suggest weights, sets, and reps based on historical data. Hence, the user will not have to type this manually.
- **Implementation:** Workout algorithms that will study performance history for intelligent workout suggestions.
- **Benefits:** Enhances user experience with intelligent workout recommendations for continuous improvement of workouts.

2. **Enhanced User Interface:**
- Description: Make the UI even more intuitive and visually appealing.
- Implementation: Thus, incorporation of feedback from users into design changes, more intuitive navigation, and increased accessibility.

3. **Extra Activity Tracking:**
- Description: Increase the variety of trackable activities such as flexibility exercises, nutrition logs, and sleeping patterns.
- **Implementation:** Add new sections and input fields to accommodate all the new data types.

4. **Mobile Application:**
- Description: Develop the application on mobile so it would be accessible on the go.
- Implementation: Construct cross-platform mobile apps using either the Svelte Native or React Native frameworks.

5. **AI Integration:
- **Description:** Integrate AI capabilities in the application to recommend workouts based on users' data.
- **Implementation:** Implement machine learning models and/or cloud-based AI services to handle user data processing and recommendations.
