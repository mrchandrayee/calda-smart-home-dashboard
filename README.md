# Calda — Smart Home Dashboard

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/calda-smart-home-dashboard/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

Responsive vanilla HTML/CSS/JavaScript reconstruction of the uploaded 4.43-second screen recording (720 × 1280, 30 fps).

## Run
1. Extract `calda-smart-home-dashboard.zip`.
2. Open `index.html` in Chrome, Edge, Firefox or Safari.
3. No npm install, build tool or server is required.

Optional local server:
```bash
python3 -m http.server 8000
```
Open `http://localhost:8000`.

## Source video observations

The video title reads **Dashboard Animation**. The smart-home product is branded **Calda**, with the property label **22 Wren Terrace**. The interface is a dark charcoal smart-home control dashboard with blue accent controls, grey glass-like cards, a compact horizontal navigation bar and a slim home sidebar.

### Navigation visible
Home · Rooms · Devices · Climate · Energy · Security · Media · Scenes · Family

### Home screen visible details
- Greeting: “Good evening, Tobi.”
- Home status: 21.1° inside, 5 lights on, 1 door open, 3 of 4 home.
- Living room card with room filters: Living, Kitchen, Dining, Bedroom, Den.
- Living room metrics: 21.6° temperature, 44% humidity, 3 devices on.
- Devices: Ceiling pendant (On), Floor lamp (Off), Living speaker (On), Living TV (Off).
- Climate dial: 21.5°, Calda T2 · Heat; mode controls Heat, Cool, Auto, Off, Eco.
- Weather: 9°, feels 6°, clouds breaking, NW 14 km/h, 78%.
- Doors: Front door locked, Garden door locked, Garage open.
- Energy card: 162 kWh used in last 7 days, +8.5%.
- Pinned devices and “Who’s home” panel.

### Energy screen visible details
Tabs: Usage, By device, Budget. Export CSV action.
- Today so far: 14.5 kWh
- This month: 244 kWh
- Cost this month: $59.83 of $160 budget
- Drawing now: 1.5 kW, 12 devices on
- Weekly bar chart and peak/off-peak usage comparison.

### Security screen visible details
- Security mode selector: Disarmed, Home, Away.
- Tabs: Locks, Cameras, Activity.
- Door cards: Front door (Hall), Garden door (Kitchen), Garage (Driveway).
- Guest code and Lock every door actions.
- Camera view shows three live camera tiles.

## Interactions implemented
- Navigate all nine sections.
- Collapse sidebar / mobile navigation.
- Room selector on the Home view.
- Climate temperature up/down and mode selector.
- Toggle device switches.
- Energy Usage / By device / Budget tabs and CSV export.
- Security mode and Locks / Cameras / Activity tabs.
- Demo door lock action, guest code notification and run scene actions.
- Add device, room, scene and invite member modal.
- Responsive desktop/tablet/mobile layouts.

## Files
- `index.html` — app shell
- `styles.css` — dark smart-home dashboard styling
- `app.js` — local sample data, page views and interactions
- `README.md` — source notes and run instructions

## Accuracy and limitations
This is a screen-based reconstruction, not the original source repository. The recording shows the running product rather than a code editor, so no original HTML/CSS/JavaScript source can be extracted from it. Visible labels and numbers have been transcribed where legible; values or interactions not clearly shown are demo approximations. The smart-home device actions, locks, cameras, weather and energy values are simulated locally. No Calda account, Matter/HomeKit/Home Assistant integration, live sensor, camera stream, lock controller or cloud backend is connected. Do not use this demo to control real home security equipment.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
