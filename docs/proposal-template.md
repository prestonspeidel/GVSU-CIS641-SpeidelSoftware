Team name: Speidel Software

Team members: Preston Speidel

# Introduction

Vehicle and boat owners often keep maintenance records scattered across paper receipts, shop invoices, and memory, which makes it easy to miss service or lose track of what has been done. This gets harder with multiple vehicles, and boats add the complication of tracking service by engine hours instead of miles.

This project is a native iOS maintenance tracker app that gives owners one place to manage all of their vehicles and boats. Users can log maintenance and repairs, view each asset's full service history, and see what service is upcoming or overdue based on date, mileage, or engine hours. The goal is to help owners avoid costly repairs, extend the life of their assets, and have a complete service record ready when selling.

# Anticipated Technologies

- **Language & UI:** Swift and SwiftUI
- **Local Storage:** SwiftData for storing vehicles and maintenance records on the device
- **Sync & Privacy:** CloudKit (iCloud) to back up and sync data across the user's devices, kept private to their Apple ID
- **Reminders (stretch goal):** UserNotifications for upcoming service alerts
- **Development Tools:** Xcode, iOS Simulator, and a physical iPhone for testing
- **Testing:** XCTest for unit tests and XCUITest for UI tests

# Method/Approach

The project will use an iterative, Agile-style approach with roughly two-week iterations, each delivering a working piece of the system:

1. **Requirements:** Define functional and non-functional requirements, user stories, and use cases.
2. **Design:** Create the data model, UML diagrams, and iOS screen wireframes.
3. **Implementation:** Build the core features in priority order: vehicle management, maintenance logging, service history, and upcoming service tracking.
4. **Testing:** Unit test the service-due logic and end-to-end test the main user flows.
5. **Polish and stretch goals:** Improve usability and, if time allows, add reminders, receipt photos, or history export.

# Estimated Timeline

| Milestone | Target Date |
|---|---|
| Project proposal complete | Sept 27 |
| Requirements and use cases | Oct 11 |
| Design (data model, UML, wireframes) | Oct 25 |
| Xcode project setup and SwiftData model | Nov 1 |
| Vehicle management and maintenance logging | Nov 15 |
| Service history and upcoming service tracking | Nov 29 |
| Testing and polish | Dec 6 |
| Final delivery and presentation | Finals week |

# Anticipated Problems

- **Multiple interval types:** Supporting service due by date, mileage, or engine hours ("whichever comes first") without a confusing interface.
- **Outdated readings:** Upcoming-service accuracy depends on users keeping mileage and engine hours current.
- **Data privacy and sync:** Keeping records private while syncing reliably through iCloud, including handling offline edits.
- **Scope creep:** Keeping the focus on core features before adding extras.
- **Time and learning curve:** Balancing the project with other coursework.
