# Flight Sim Overlay

A modern, streamer-friendly Microsoft Flight Simulator overlay featuring live telemetry, SimBrief integration, route-aware navigation tracking, flight phase visualization, and theme customization.

## Highlights

### Route Awareness Update (v2.1)
- Live SimBrief route display in the overlay header.
- Active waypoint detection and highlighting.
- Completed, active, and future waypoint visualization.
- Distance-to-next-waypoint tracking using route-aware calculations.
- Theme-aware route progress styling.

### Flight Information
- Airspeed, groundspeed, altitude, vertical speed.
- ETA and Time Enroute display.
- Flight phase tracking.
- Route completion percentage.
- Departure and destination airport information.

### Integrations
- SimConnect
- SimBrief
- SayIntentions (optional)
- VATSIM (optional)

## New Navigation Features

The overlay now displays the full active route:

```
KGEG → TOC → DOXIE → BPI → CHE → TOD → BRK → KCOS
```

Waypoint states:

- Completed waypoints use the completed-progress color.
- Active waypoint is highlighted.
- Future waypoints are displayed in a muted style.

The route strip and flight phase timeline share the same visual language.

## Enhanced ETA and ETE Logic

Ground operations:
- Uses SimBrief planned enroute time.
- Provides accurate ETA and ETE while parked or taxiing.

Flight operations:
- Designed to transition to dynamic route-progress calculations.

## Theme Support

Multiple configurable themes are supported.

Route highlighting automatically follows the currently selected theme.

## Major Improvements Over Previous Versions

### Fixed
- Broken next-waypoint distance reporting.
- Loss of waypoint identifiers from SimBrief routes.
- Route tracking selecting destination instead of active fix.
- Incorrect ground ETA/ETE values caused by unreliable simulator GPS timing.

### Added
- Route point preservation.
- Active waypoint tracking.
- Route progression visualization.
- Expanded telemetry payload.
- Callsign and header layout enhancements.

## For Streamers

Flight Sim Overlay is designed to help viewers understand:

- Where the flight is going.
- Which waypoint is currently active.
- Overall progress through the route.
- Current phase of flight.
- Estimated arrival information.

## License

Refer to the repository license information.
