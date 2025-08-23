MU Immortal - Event Timers (EU Server)

[Live Demo](https://lvkafija.github.io/MU-immortal-Event-Timer/)

This project is a **real-time event timer** for the game *MU Immortal*, showing all daily and weekly events with countdowns and local time conversion. It includes the ability to see which events are currently active and the next upcoming event.

---

## Features

- **Daily and Weekly Event Timers**  
  Displays all MU Immortal events sorted by daily and weekly schedule.  
- **Up Next Event**  
  Shows the next upcoming event with a countdown.  
- **Currently Active Events**  
  Shows events that are currently ongoing, e.g., Blood Castle, Devil Square, Golden Invasion.  
- **Local Time Conversion**  
  All event times are displayed in the user’s local time while keeping reference to the game server time (UTC+1).  
- **Responsive Design**  
  Optimized for desktop and mobile devices.  
- **Automatic Updates**  
  Timers and active events refresh every minute.

---

## Supported Events

### Daily Events

- Blood Castle
- Devil Square
- Red Dragon Invasion
- Guild Master Event
- Minion EXP +30%
- Cross-server 3v3
- Ethereal Pact Event

### Weekly Events

- Crywolf Fortress (Monday 20:30)
- Chaos Castle (Tuesday 20:00)
- Siege War (Wednesday and Saturday 20:00)
- Divine Trade Route (Monday 20:00, Friday 20:30)

---

## Usage

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. The timer will automatically detect your local timezone and display:
   - Next upcoming event.
   - Currently active events.
   - Daily and weekly event schedules with countdowns.

---

## Live Demo

You can see a live version here:  
[https://lvkafija.github.io/MU-immortal-Event-Timer/](https://lvkafija.github.io/MU-immortal-Event-Timer/)

---

## Customization

- Add new events by editing the `events` array in `index.html`.
- Set event duration (in minutes) using the `duration` property for active timers.
- Adjust time for events relative to UTC+1 if the server schedule changes.

---

## License

This project is open source and available under the MIT License.
