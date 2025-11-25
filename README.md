# BoredBot

A fun, interactive web app that gives you a random activity whenever you’re bored! Click the button and let BoredBot suggest something to do.

## Features

- Fetches a random activity from the Bored API("https://www.boredapi.com/")
- Updates the page dynamically without refreshing
- Changes page title and background when a new activity is displayed
- Accessible for screen readers using aria-live & aria-label

## Demo

Live Demo Link: 
https://chisu-kawahara.github.io/boredbot/

## How It Works

HTML Structure:
- A title (<h1>), description (<h4>), and a button to fetch an activity.
- The activity text is inside a <p> with aria-live="polite" for accessibility.

CSS Styling:
- Gradient background for the page.
- Button styled as a circle.
- Fun mode background applied dynamically when a new activity is fetched.

JavaScript Functionality:
- Event listener on the button. 
- Fetch request to https://apis.scrimba.com/bored/api/activity.
- Updates the activity text, changes the page title, and adds a fun class to the body.

## Installation / Usage

Clone the repository:
- git clone https://github.com/chisu-kawahara/boredbot.git
- Open index.html in your browser.
- Click the 🎲 button to get a random activity!

## Accessibility

The activity container uses aria-live="polite" to announce updates to screen readers.
Dynamic content changes are announced politely without interrupting the user.

## Technologies Used

HTML5
CSS3 (Flexbox & Gradients)
JavaScript (Fetch API)
Bored API