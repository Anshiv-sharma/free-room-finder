# Free Room Finder

A lightweight campus utility that helps students find available classrooms and study spaces for a selected time slot.

## Features

- Select a time slot from the dropdown.
- View the rooms listed as free during that slot.
- Displays available classrooms, labs, and study spaces.
- Updates the room list automatically when the selected slot changes.
- Simple, responsive interface with no external dependencies.

## Tech Stack

- **HTML** for the page structure
- **CSS** for styling and layout
- **Vanilla JavaScript** for slot selection and room-list rendering

## Getting Started

No installation or build tools are required.

1. Download or clone the project.
2. Open `index.html` in any modern web browser.
3. Choose a time slot from the dropdown.
4. View the rooms shown as free for that slot.

## How It Works

The available rooms are stored in a JavaScript object. Each key represents a time slot, and its value is a list of rooms marked as free during that slot.

When the selected time slot changes, JavaScript reads the corresponding room list and updates the page.

## Sample Availability

| Time Slot | Rooms Listed as Free |
|---|---|
| 9–10 | A101, B204, Lab 3 |
| 10–11 | B204, C12 |
| 11–12 | A101, C12, Library Hall |
| 12–1 | A101, B204, C12, Lab 3 |
| 2–3 | Lab 3, Library Hall |
| 3–4 | A101, B204 |

## Current Limitations

- Room availability is hardcoded in the JavaScript source.
- The app does not connect to a college timetable or room-booking system.
- Availability is not verified in real time.
- There is no backend, database, login, or room-booking functionality.
- Only the time slots included in the sample data are available.

## Project Structure

```text
free-room-finder/
└── index.html
```

## Possible Future Improvements

- Connect to a live timetable or room-management system.
- Add more buildings, rooms, and time slots.
- Show room capacity and facilities such as projectors or Wi-Fi.
- Add filters for classrooms, labs, and study spaces.
- Allow students to reserve a room or report incorrect availability.
- Add an admin interface to update room schedules.

---

*Built as a simple front-end project to help students find a place to study on campus.*
