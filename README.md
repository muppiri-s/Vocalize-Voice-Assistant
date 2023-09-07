# Vocalize Voice Assistant

## Table of Contents
1. Objectives
2. Implementation

## Objectives

**Vocalize Voice Assistant** utilizes the Electron framework as a critical asset of the entire application, providing a simple way to package our product in the Electron Package Manager. However, before deployment can commence, several challenges must be addressed:

1. **Executable Conversion:** Vocalize Voice Assistant employs various programming languages, primarily Python. To ensure compatibility with any Windows device, every Python script needs to be converted into an executable file.

2. **Development vs. Production Mode:** The system must determine whether it is in development or production mode. In production mode, executable functions will be run instead of .py files to protect proprietary source code.

3. **Target Audience Identification:** Before deployment, the team needs to understand the target audience of the application. OAuth 2.0, which allows various functionalities like reminders, lists, and email, also provides a way to uniquely identify users. This information will be used to customize the application for a broader audience.

The end goal is to provide a voice-based virtual assistant to assist users with their daily computer tasks.

## Implementation

The implementation of Vocalize Voice Assistant is well underway, with most requirements already integrated into the application. An older version of Vocalize has been compiled and packaged as a test run, and OAuth 2.0 has been fully implemented. However, further testing and implementation of functions that require OAuth 2.0 will be necessary to ensure a seamless user experience.
