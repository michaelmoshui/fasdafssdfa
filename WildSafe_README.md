
# FireLink - Wildfire Tracker and Emergency Support

## Overview

FireLink is an iOS application designed to assist users during wildfire emergencies. Built using Swift, SwiftUI, and developed with Xcode, this app incorporates GPS functionality to track required items and provide real-time resource allocations for critical situations. It aims to simplify reporting incidents and coordinating resources with minimal user effort.

## Installation and Execution Instructions

### Installation

- macOS device with Xcode installed.
- iOS device for deployment or an iOS Simulator in Xcode.

### Execution

1. Select your target device or simulator from the device menu in Xcode.

2. Build and run the project using the Run button (▶️) at the top left or by pressing Cmd + R.

3. If deploying to a physical device, ensure it is connected and trusted by your macOS system.

## Dependencies and Libraries Used

FireLink utilizes the following frameworks and libraries:

- **SwiftUI**: For building the user interface with a modern declarative approach.
- **MapKit**: For map visualization and location-based features.
- **CoreLocation**: For GPS and real-time location tracking.

## File Structure and Purpose

- **WildFire.swift**: The main entry point of the application, initializing the app's structure and UI.
- **ContentView.swift**: The primary user interface that integrates buttons, map views, and lists for interaction.
- **Info**: This file contains important app metadata, app settings, and app permissions.
- **Assets**: manages images, icons, and various forms of media content.

## How It Works
1. **Launch the App**: Open WildSafe during an emergency situation.
2. **Report an Incident**: Click the respective button for the type of incident or resource you need or can provide.
3. **View and Share Resources**: Check the dynamic list to locate others who need or provide resources nearby.
4. **Respond Effectively**: Use the app to coordinate help without needing extensive input or communication.
5. **Delete Items**: Long press on an item to remove it from the list.

## Technology Stack
- **Programming Language**: Swift
- **Frameworks**: SwiftUI
- **Development Platform**: Xcode
- **Core Features**: GPS integration, dynamic list management, and map visualization
  
## Features and Use Cases

### 1. Incident Reporting
- **Quick and Easy**: Users can report emergencies by pressing a button.
- **Location Tracking**: Automatically captures the user’s latitude and longitude.
- **Visual Markers**: Highlights incidents (e.g., fires) on the map with clear, colored indicators.

### 2. Resource Coordination
Provides categories like:
- Fire
- Food
- Fire Trucks
- Health Services
- Gas Stations

Includes **Need** and **Have** buttons to differentiate resource requests and offers.

### 3. Dynamic List Management
- **Real-Time Updates**: Continuously synchronizes user-submitted data.
- **Comprehensive Entries**: Displays location, type of resource or incident, and status (Need/Have).

## Contact

For inquiries or support, please contact:

- **Email**: winnie.hsiang@mail.utoronto.ca
- **Phone**: 778-929-6648

Thank you for choosing FireLink—helping you stay safe and connected during wildfire emergencies!
