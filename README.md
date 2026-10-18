







# StepLock

**Earn your screen time by moving.**

StepLock is an Android screen-time management and habit-tracking application built around a simple idea: make access to distracting apps something you earn through physical activity.

Instead of relying entirely on willpower to limit screen time, StepLock encourages users to get moving before accessing their restricted apps.

## Showcase

[A video demonstrating StepLock's interface and functionality will be available here.
](https://github.com/user-attachments/assets/154cbcdc-83b9-4e0d-af91-cf2faab5a173)

## Features

- **App Restriction:** Restricts access to selected apps when the user's available screen time is exhausted.
- **Walking-Based Screen Time:** Lets users earn access to restricted apps by reaching step goals.
- **Step Tracking:** Integrates with Health Connect, with an accelerometer-based fallback.
- **Live Step Tracking:** Includes a custom step-tracking implementation for responsive counting and alarm-related functionality.
- **Habit Tracking:** Helps users track habits alongside their screen-time goals.
- **Local Data Storage:** Uses Room for persistent local data.
- **Background Functionality:** Uses foreground services for functionality that needs to continue while the app isn't in the foreground.

## Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Local Database:** Room
- **Health Integration:** Health Connect
- **Background Processing:** Android foreground services
- **Platform:** Android

## Engineering Highlights

One of the central engineering challenges in StepLock was implementing reliable app restriction enforcement.

The implementation uses Android accessibility events to detect when monitored apps are opened and an overlay-based approach to display the restriction interface. The project also involves background execution, step-counting logic, device integrations, and coordination between application state and enforcement behavior.

## Project Status

**Development complete; planned commercial release.**

StepLock is feature-complete and intended for a paid release on Google Play. It is not currently publicly available for installation.

This repository serves as a project showcase. The source code is not licensed for public reuse unless a separate license or written permission explicitly allows it.




- LinkedIn: https://www.linkedin.com/in/asad-rauf-58141b334

