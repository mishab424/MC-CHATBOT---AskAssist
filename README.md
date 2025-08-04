# MC CHATBOT - User Manual

## Overview

**MC CHATBOT** is a pre-configured, modern chatbot plugin designed for Oracle APEX applications. It offers an advanced and intuitive UI/UX for delivering predefined question-answer interactions.

---

## Description

MC CHATBOT provides a structured chatbot interface where each conversation follows a defined hierarchy of main questions, sub-questions, and answers. It enhances user experience and helps automate responses to frequently asked queries.

---

## Use Case

MC CHATBOT is ideal for:

* Customer support systems
* Employee onboarding
* User training and navigation guidance
* Automated FAQ interactions
* Guided lead qualification

---

## Features

* Predefined question-answer flow
* Dynamic loading of sub-questions based on user input
* Real-time response delivery using Ajax
* Modern and mobile-friendly UI
* Simple integration within Oracle APEX pages

---

## Installation Guide

### Step 1: Download the Plugin

Download the plugin file from the `src` folder.

### Step 2: Import the Plugin

In your Oracle APEX application:

* Navigate to **Shared Components > Plug-ins > Import**.
* Upload and install the MC CHATBOT plugin.

### Step 3: Create a Region

* Go to the desired page in your app.
* Add a new **Region**.
* Set the **Region Type** to `MC CHATBOT`.

> **Note:** Do **not rename** the region or process names used in the plugin.

### Step 4: Prepare Backend Tables

Create the following backend tables for chatbot operations:

* Main Questions Table
* Sub-Questions Table
* Answers Table

You may request the exact table structure if needed.

### Step 5: Create Ajax Callback Processes

Create the following Ajax processes:

* `fetch_main_question`
* `fetch_sub_question`
* `fetch_answer`

These processes dynamically load data for your chatbot.

> **Note:** The process names should not be renamed or changed.

### Step 6: Output Storage (Optional)

You can optionally create a table to store user interactions or chatbot analytics data.

---

## Demo Application

Explore the live demo here:
👉 [MC CHATBOT Demo App](https://apex.oracle.com/pls/apex/r/aishwaryak_dev/demo/home?session=10097774760994)

---

## License

**MC CHATBOT** is proprietary software developed by **Muhammed Mishab PP**.

### License Terms

* Non-exclusive, non-transferable license for internal use.
* Redistribution, resale, or commercial reuse is prohibited without written permission.
* Support and updates available through official contact.

### Allowed:

* Internal use across multiple APEX pages
* Custom styling and behavior (non-commercial)

### Not Allowed:

* Public redistribution or resale
* Removing author credits
* Claiming ownership of the plugin

For custom licensing needs, contact the developer.

---

## 📣 Contact for Purchase / Customization

**LinkedIn:** [Muhammed Mishab PP](https://www.linkedin.com/in/muhammed-mishab-pp-/)
**Email:** [mishabpoomala424@gmail.com](mailto:mishabpoomala424@gmail.com)

---

Thank you for using **MC CHATBOT**. For feature extensions or support, feel free to reach out.
