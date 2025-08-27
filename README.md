# ICS File Generator

[Demo](https://icsmaker.netlify.app)

A simple web-based ICS file generator that allows users to create calendar events with default series settings and individual event overrides. Designed with a clean UI, mobile support, and accordion-style event details for a less cluttered experience.

## Features

- **Series Defaults:** Set a default title, location, timezone, start/end times, and description for all events.
- **Add Event:** Quickly add new events that inherit the series defaults.
- **Accordion UI:** Event details are collapsible to reduce visual clutter.
- **Highlight Date:** Each event highlights the date input to ensure it is filled.
- **ICS Export:** Generate `.ics` files compatible with calendar apps.
- **Timezone Selection:** Typeable input with datalist populated from `timezones.json`.
- **Responsive Design:** Works on both desktop and mobile devices.

## Usage

1. Open `index.html` in your browser.
2. Set the series defaults at the top of the page.
3. Fill in the event dates and make adjustments to individual events if needed.
4. Click **+ Add Event** to create additional events.
5. Click **Generate ICS** to download your calendar file.

## File Structure

- `index.html` – Main HTML and JavaScript for the app.
- `timezones.json` – JSON file containing timezone data for the datalist.

## Future Improvements

- Better timezone selection UX (typeable input, common regions, scrolling, or map-based selection).
- Automatic updating of existing events if series defaults are modified.
- Mobile UI tweaks for improved usability.

## License

MIT License – Free to use and modify.
