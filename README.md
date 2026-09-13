# kAI Connect

kAI Connect is a food waste reduction platform designed to help households make better use of the food they already have.

The application tracks pantry items, highlights food approaching expiry, recommends meals based on available ingredients, records food-saving outcomes, and helps users make more informed decisions before their next grocery shop.

Built for the AUT AI Hackathon 2026, kAI Connect combines practical household food management with the principles of Hua Parakore.

## The Problem

Households often buy more food than they need, lose track of what they already have, and throw away food that could have been eaten.

kAI Connect aims to reduce this waste by helping users answer three simple questions:

1. What food do I already have?
2. What should I use first?
3. What should I buy next time?

## Features

### Pantry Management

Track the food currently available in your household.

Food is grouped by urgency:

* Use today
* Use soon
* Fresh
* Long life

Users can add food manually, update quantities, remove items, or simulate adding groceries through receipt scanning.

### Expiry Alerts

kAI Connect identifies ingredients approaching expiry and highlights them before they become waste.

Notifications direct users toward ingredients requiring attention and provide a shortcut to suitable recipes.

### Smart Recipe Suggestions

Recipe recommendations prioritise ingredients already available in the pantry, especially food approaching expiry.

Each recipe includes:

* Ingredients already available
* Extra ingredients required
* Estimated additional cost
* Servings
* Cooking time
* Nutrition information
* Ingredients saved from potential waste
* Cooking instructions

### Receipt Scanning

The prototype includes a receipt scanning workflow for quickly adding newly purchased groceries to the pantry.

### Food Donation

Food that will not be used can be redirected instead of discarded.

kAI Connect uses the user's location to search for nearby food banks and community food organisations, with a verified New Zealand directory available as a fallback.

### Impact Tracking

The impact dashboard helps users see the results of their decisions over time.

The goal is to connect individual actions with:

* Less food waste
* Lower unnecessary food spending
* Better use of existing groceries
* Reduced landfill impact
* Better household shopping habits

## How It Works

kAI Connect follows a continuous feedback loop:

```text
Groceries purchased
        ↓
Expiry risk detected
        ↓
Use-soon action suggested
        ↓
Outcome recorded
        ↓
Household pattern learned
        ↓
Next shop improved
        ↺
```

Each outcome provides information that can improve future recommendations.

## Hua Parakore Principles

The project draws inspiration from Hua Parakore and its focus on food, people, and the environment.

kAI Connect incorporates four key principles:

Kaitiakitanga

Care for resources, whenua, and the things that sustain us.

Manaakitanga

Support whānau with care and without judgement.

Whanaungatanga

Recognise the relationships between people, kai, community, and land.

Mauri

Protect the value carried by food and the resources required to produce it.

## Tech Stack

| Technology                   | Purpose                           |
| ---------------------------- | --------------------------------- |
| Next.js 16                   | Application framework             |
| React 19                     | User interface                    |
| TypeScript                   | Application development           |
| Tailwind CSS 4               | Styling                           |
| Lucide React                 | Interface icons                   |
| Drizzle ORM                  | Database tooling                  |
| SQLite                       | Database                          |
| OpenStreetMap / Overpass API | Nearby food bank search           |
| Browser Geolocation API      | Finding nearby donation locations |
| Local Storage                | Prototype state persistence       |

## Getting Started

### Requirements

Install the following before running the project:

* Node.js 22.13.0 or newer
* npm

### Clone the Repository

```bash
git clone https://github.com/KaidenZiegler/KaiConnect.git
cd KaiConnect/kaiconnect
```

### Install Dependencies

```bash
npm install
```

### Start the Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

in your browser.

## Available Commands

```bash
npm run dev
```

Starts the Next.js development server.

```bash
npm run build
```

Creates a production build.

```bash
npm start
```

Runs the production build.

```bash
npm run lint
```

Runs ESLint.

```bash
npm test
```

Runs the project build as the current test command.

```
```
