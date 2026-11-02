# Adaptive Heat Risk Coach

A web app that learns how heat affects you and coaches you before symptoms get worse.

**Live app:** https://zoegoudas.github.io/heat-risk-coach/

## What it does

- Log the temperature, humidity, time outdoors, hydration, activity, symptoms, sleep and heart rate. The quick log takes four taps.
- Fill in the weather automatically from your location or a city or ZIP code, using [Open-Meteo](https://open-meteo.com/).
- Get a personal heat risk score from 0 to 100, with a list of what's driving it.
- See coach tips that adapt to your patterns. The coach asks whether each tip helped, and puts the ones that work for you first.
- Log warning signs of heat stroke, which bring up a clear "Call 911" alert.
- View your history and patterns, like the heat index where you usually start to feel symptoms.
- Export your logs as a spreadsheet or a printable report to share with a doctor.

## How the score works

The score adds points for the heat index (calculated with the National Weather Service formula), hydration, time outdoors, activity, symptoms and sleep. If you're above the heat index where your symptoms usually start, it adds 8 more points. The full breakdown is on the app's About page.

## Privacy

Logs are stored only in your browser, on your device. Nothing is sent to a server, except your approximate location when you ask for live weather.

## About

Built by Zoe Goudas for Topics in BME: Health Tech Innovation at Rutgers University. This is a student project, not medical advice. If you think someone has heat stroke, call 911.

The whole app is a single file, `index.html`, with no build step.
