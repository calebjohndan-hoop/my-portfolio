# Caleb | Personal Portfolio

A single-page personal portfolio built with semantic HTML and Tailwind CSS (via CDN), featuring a pink frosted-glass card layout, personal highlights, and an interactive greeting button.

## Features

- **Frosted-Glass Profile Card:** Centered layout (`max-w-2xl`) over a soft pink backdrop (`bg-pink-100`) using `backdrop-blur-md`, rounded corners, and subtle borders.
- **About & Spotlight Section:** Introduces Caleb's interests in basketball, hip-hop (Travis Scott and Don Toliver), and web building, paired with a `lebron.jpeg` showcase image and hover zoom effect.
- **3-Column Highlight Grid:** Responsive cards (`grid-cols-1 md:grid-cols-3`) covering **Hoops**, **On Repeat**, and **Shipping Code** (including Hack Club projects).
- **Interactive Greeting Trigger:** A button (`Say Wassupppp👋`) that displays a browser alert on click.

## Tech Stack

- **HTML5** (`index.html`)
- **Tailwind CSS** (loaded via `https://cdn.tailwindcss.com`)
- **Inline JavaScript** (`onclick` alert handler)

## Project Structure

```text
.
├── index.html   # Main portfolio page (rename your HTML file to index.html if needed)
├── lebron.jpeg  # Image referenced by the spotlight section
└── README.md
