# Student Organizer App

A modern Android application built with **Kotlin** and **Jetpack Compose** to help students organize and manage their academic activities. The application provides a centralized interface for viewing assignments, tracking completion status, managing academic information, and configuring application preferences.

The project demonstrates core Android development concepts including **declarative UI development, Compose state management, state hoisting, reusable composables, Material 3 components, and Navigation Compose**.

---

![Kotlin](https://shields.io)
![Jetpack Compose](https://shields.io)


## 📱 Overview

The Student Organizer App is designed as a lightweight academic productivity application for managing student-related information and assignments.

The application consists of five primary screens:

- **Dashboard**
- **Assignments**
- **Add Assignment**
- **Profile**
- **Settings**

Navigation between screens is implemented using **Jetpack Navigation Compose**, while application and UI state are managed using Compose's state APIs.

---

## ✨ Features

### Dashboard

The Dashboard provides an overview of the student's current academic activities.

Features include:

- Welcome section
- Active course statistics
- Pending assignment statistics
- Active course cards
- Course completion progress
- Urgent assignment/deadline section
- Quick access to Add Assignment
- Bottom navigation

---

### Assignment Management

The Assignments screen provides a centralized view of academic assignments.

Features include:

- Display all assignments
- Filter assignments by:
  - All
  - Pending
  - Completed
- Assignment completion tracking
- Interactive completion checkbox
- Assignment priority indicators
- Course information
- Due-date information
- Scrollable assignment list

Assignments are represented using a dedicated Kotlin `data class`.

---

### Add Assignment

The Add Assignment screen provides a form for creating new assignments.

The form contains:

- Assignment title
- Course
- Due date
- Priority
  - Low
  - Medium
  - High
- Description
- Reminder notification preference

Form validation ensures that the following required fields are populated:

- Title
- Course
- Due Date

The **Save** button remains disabled until all required fields are valid.

---

### Student Profile

The Profile screen displays student and academic information.

It includes:

- Student name
- Student ID
- Major
- GPA
- Completed credits
- Current semester
- Edit Profile action
- Export Academic Summary action

---

### Application Settings

The Settings screen provides configurable application preferences.

Current preferences include:

- Dark mode
- Push notification preference
- Default start screen

The application's theme dynamically switches between **Material 3 light and dark color schemes** based on the dark-mode state.

---
