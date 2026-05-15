# test-fixtures

A collection of generic test fixture files for use in automated tests and integrations.

## Structure

| Directory | Description |
|-----------|-------------|
| [`ical/`](ical/) | Example iCalendar (`.ics`) files |

## ical

The `ical/` directory contains example [iCalendar](https://en.wikipedia.org/wiki/ICalendar) files covering common scenarios:

| File | Description |
|------|-------------|
| [`basic-event.ics`](ical/basic-event.ics) | A simple one-off event |
| [`all-day-event.ics`](ical/all-day-event.ics) | An all-day event |
| [`recurring-event.ics`](ical/recurring-event.ics) | A weekly recurring event |
| [`multi-event.ics`](ical/multi-event.ics) | A calendar containing multiple events |

## GitHub Pages

All fixture files are published via GitHub Pages and can be fetched directly:

```
https://sander-van-damme.github.io/test-fixtures/<path>
```

For example:

```
https://sander-van-damme.github.io/test-fixtures/ical/basic-event.ics
```
