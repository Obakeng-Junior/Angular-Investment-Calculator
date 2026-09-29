# Angular Investment Calculator

A simple Angular project that helps users estimate how their investments could grow over time based on their starting amount, annual contributions, expected return rate, and investment period.

## Overview

This app is designed to give a quick financial projection for long-term investing. Users enter:

- initial investment amount
- annual contribution
- expected yearly return percentage
- duration in years

The app then calculates and displays a year-by-year breakdown of:

- investment value
- interest earned each year
- total interest accumulated
- total amount invested

## Features

- clean and responsive user interface
- simple input form for investment planning
- real-time annual growth projection
- structured results table for yearly analysis
- built with Angular standalone components

## Tech Stack

- Angular
- TypeScript
- HTML
- CSS

## Project Structure

- `src/app/user-input` – form controls and user input logic
- `src/app/investment-results` – investment results table
- `src/app/app.component.ts` – main calculation logic
- `src/app/investment-input.model.ts` – typed input model

## How it works

The app calculates compound growth by applying the expected return rate to the current investment value each year, then adds the yearly contribution. The result is displayed in a table so the user can easily follow the investment growth over time.

## Run locally

1. Clone the repository
2. Navigate to the project folder
3. Install dependencies:

```bash
npm install
```

4. Start the app:

```bash
npm start
```

5. Open the app in your browser at:

```text
http://localhost:4200/
```

## Example

If a user enters:

- Starting amount: 10000
- Annual contribution: 2000
- Expected return: 7%
- Duration: 5 years

The app will generate a yearly investment projection showing the total investment value and interest earned over time.

## Portfolio Note

This project demonstrates front-end development skills in Angular, including component structure, data binding, event handling, and simple financial logic. It is a good example of a practical, user-focused app that solves a real-world problem in a clean interface.
