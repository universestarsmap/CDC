# Omantel L1 Assistant Dashboard

Welcome to the **Omantel L1 Assistant Dashboard powered by Basil**! This modern web application is designed to streamline tasks for L1 support teams at Omantel. With a sleek, user-friendly interface built using HTML and CSS, it offers tools for managing alerts, saving IP lists, and tracking call counts—all wrapped in a professional dark blue and orange design.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
  - [Assistant](#assistant)
  - [IP Saver](#ip-saver)
  - [Call Counter](#call-counter)
- [Styling](#styling)
- [Running the Dashboard](#running-the-dashboard)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Omantel L1 Assistant Dashboard** is a static web application tailored for L1 support teams. It provides a tabbed interface to access three main tools: an alert search assistant, an IP list saver, and a call counter. The dashboard combines functionality with a futuristic aesthetic, featuring a dark blue background and vibrant orange accents.

This tool is perfect for:
- Quickly retrieving alert information.
- Storing and retrieving IP lists with associated alert codes.
- Tracking the number of calls made and received during support shifts.

## Features

Here’s what the dashboard offers:

- **Tabbed Navigation**: Easily switch between the Assistant, IP Saver, and Call Counter sections using tabs.
- **Call Counter Buttons**: Persistent buttons at the top of every page for instant call tracking.
- **Assistant Section**: Search for alerts and display results in a readonly textarea.
- **IP Saver Section**: Save IP lists and alert codes, then retrieve them in a preview area for copying.
- **Call Counter Section**: Monitor and update the number of calls made and received.
- **Responsive Design**: A clean, centered layout with a maximum width of 1200px for readability on various screens.
- **Visual Appeal**: A dark theme with gradients, shadows, and smooth hover effects.

## Usage

The dashboard is divided into three main sections, each with its own purpose. Here’s how to use them:

### Assistant

The Assistant section helps you search for and display alert information.

- **Search Alerts**:
  - Enter a keyword or phrase in the search input field.
  - Click the "Retrieve" button to fetch relevant alerts.
- **View Results**:
  - The results appear in a readonly textarea below the input field, making it easy to read or copy the information.

### IP Saver

The IP Saver section lets you store and retrieve IP lists along with alert codes.

- **Save Data**:
  - In the "IP List" textarea, enter IP addresses (one per line, e.g., `192.168.1.1`).
  - In the "Alert Code" input, type an 8-character code (e.g., `ALRT1234`).
  - Click "Save" to store the data locally.
- **Retrieve Data**:
  - Click "Retrieve" to load the saved IP list and alert code into the preview textarea.
- **Preview**:
  - The readonly preview textarea displays the saved data in a format ready for copying.

### Call Counter

The Call Counter section tracks the number of calls made and received.

- **View Counts**:
  - See the current totals for "Calls Made" and "Calls Received" in readonly input fields.
- **Update Counts**:
  - Click "Call Made" to increment the "Calls Made" count by 1.
  - Click "Call Received" to increment the "Calls Received" count by 1.
  - Click "Reset" to set both counters back to zero.
- **Accessibility**:
  - The counter buttons are available at the top of every page, so you can update counts without switching tabs.

## Styling

The dashboard’s design is both functional and visually striking, with a modern dark theme:

- **Color Scheme**:
  - **Background**: `#001f3f` (a deep, professional blue).
  - **Text**: `#d9d9d9` (light gray for high contrast and readability).
  - **Accents**: 
    - Dark blue gradients (`#004080` to `#002060`) for buttons and sections.
    - Orange gradients (`#ff8c00` to `#e07b00`) for highlights and active elements.
- **Visual Effects**:
  - **Gradients**: Applied to buttons, textareas, and headers for a dynamic look.
  - **Shadows**: Subtle glow effects on elements to add depth.
  - **Transitions**: Smooth hover animations on buttons and inputs for interactivity.
- **Layout**:
  - A centered container with a max width of 1200px ensures consistency across devices.
  - Tabs highlight the active section with an orange underline or background.
  - Call counter buttons are fixed at the top for easy access.

## Running the Dashboard

Since this is a static HTML/CSS application, setting it up is simple:

1. **Save the File**:
   - Copy the HTML code into a file named `dashboard.html`.
   - Ensure any accompanying CSS is saved in a linked file (e.g., `styles.css`) if separate.

2. **Open in a Browser**:
   - Double-click `dashboard.html` or drag it into a web browser like Chrome, Firefox, or Edge.

> **Note**: No server or dependencies are required—just a modern web browser!

## Contributing

We welcome contributions to enhance the dashboard! To contribute:

1. **Fork the Repository**: Create your own copy of the project.
2. **Create a Branch**: Work on your feature or fix in a new branch (e.g., `feature/add-login`).
3. **Submit a Pull Request**: Share your changes with a clear description of what you’ve done.

Suggestions for improvements:
- Adding JavaScript for dynamic data storage (e.g., localStorage).
- Enhancing accessibility with ARIA labels.
- Expanding the Assistant with more search options.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full details.

---

**Omantel L1 Assistant Dashboard** – Empowering L1 support with efficiency and style.
