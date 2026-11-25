# My Bucket List - 60 Countries

A personal travel tracker built with plain HTML, CSS and JavaScript. The goal is simple: pick your Top 10 countries on each of six continents, tick them off as you visit, and watch your progress toward 60 countries.

## Features

- Top 10 destinations for Africa, Asia, Europe, North America, South America and Oceania
- Tick countries as visited, with a live progress bar and counter (0 / 60)
- Antarctica handled separately: no countries, just one tick if you ever go
- "Your Journey" section to set the country you want to start in and the country you want to finish in
- Login and sign up links, with an account details popup for logged-in users
- Warning banner for guests that their list will not be saved long term
- Responsive navigation: full navbar on laptops and desktops, hamburger drawer on phones
- Dark and light mode toggle, remembered between visits
- About and Contact sections with email, phone, WhatsApp, Instagram and Facebook links
- All data saved in the browser with localStorage

## Tech Stack

- HTML5
- CSS3 (flexbox, grid, media queries)
- Vanilla JavaScript (no frameworks or libraries)

## Project Structure

```
.
├── home.html      # Page structure, drawer, account modal
├── home.css       # Styling, dark mode, responsive layout
├── home.js        # List logic, journey, navigation, localStorage
├── imgs/
│   └── cover.jpg  # Background image
└── login-register.html   # Login / sign up page (linked from the navbar)
```

## Getting Started



2. Open the project folder.
3. Open `home.html` in your browser, or run it with a local server such as XAMPP or the VS Code Live Server extension.

Make sure the `imgs/cover.jpg` background image and `login-register.html` are present, otherwise the background and the Login / Sign Up links will not work.

## How It Works

- Your continent lists are stored in `localStorage` under `bucket60_v4`.
- The logged-in user and journey details are stored under `bucket_user` and `bucket_journey`.
- The theme choice is stored under `mode`.
- Clearing your browser data will reset your list.

## Roadmap

- Backend storage so lists sync across devices
- Country autocomplete and flags
- Share your bucket list with friends

## Author

Built by Destine.
