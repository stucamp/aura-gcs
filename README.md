# Aura Ground Station Interface

Provides a web based interface to the AuraUAS autopilot system.  The
front end web pages work in conjunction with a backend python server
(usually running on the same laptop) which connects the aircraft
telemetry with the gui.

Each of these pages can be opened up in a separate tab (or window)
with your favorite browser.  These can be spread across multiple
displays or even pulled up on multiple devices simultaneously.


## Aura Map

A top down map for real time flight tracking, path planning, etc.

![map](screenshots/map.png "FAA Sectionals")


## Aura Panel

An analog-style instrument panel that displays flight status in a
format that is intuitive to pilots.

![panel](screenshots/panel.png "Analog Style Instrument Panel")


## Aura Props

A text-based page that shows all the values available on the ground
station that are either directly received from the aircraft, or
derived from values received from the aircraft.  This is intended as a
debugging tool and possibly for advanced users who wish to monitor
values that are not represented in the other pages.

![props](screenshots/props.png "Raw Property Viewer")