# Conference Event Planner

A React + Redux web application for planning conference expenses by selecting venue spaces, AV add-ons, and meal packages, with live subtotal and total cost calculation.

## Features

- Venue selection with quantity controls
- Add-on (AV equipment) selection with quantity controls
- Meal package selection with per-person pricing
- Adjustable attendee count for meal cost calculations
- Consolidated “Show Details” view with itemized totals
- State management with Redux Toolkit

## Tech Stack

- React 18
- Redux Toolkit + React Redux
- Vite
- ESLint

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
npm install
```

### Run in Development

```bash
npm run dev
```

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

## Project Structure

```text
src/
  App.jsx                # Landing page + app flow
  ConferenceEvent.jsx    # Main planning UI and calculations
  TotalCost.jsx          # Final total and itemized display
  venueSlice.js          # Venue state/actions
  avSlice.js             # AV add-on state/actions
  mealsSlice.js          # Meal state/actions
  store.js               # Redux store configuration
```

## How It Works

1. Choose venue rooms and required add-ons.
2. Select meal types and set number of attendees.
3. Review computed totals per section (Venue, Add-ons, Meals).
4. Open details view to see itemized final event cost.

## License

This project is licensed under the terms of the [MIT License](./LICENSE).