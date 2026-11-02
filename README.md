# Playwright Practice

Beginner browser-automation practice using Playwright (JavaScript) on SauceDemo, a public demo shop made for testing practice.

## Tests (6)
**Login (`tests/saucedemo-login.spec.js`)**
- Valid user can log in
- Invalid login shows an error message
- Locked-out user cannot log in

**Shopping (`tests/saucedemo-shopping.spec.js`)**
- Adding an item updates the cart count
- Removing an item clears the cart count
- User can log out

## Result
All 6 tests passed in Chromium (see `Screenshots/`).

## How to run
1. Install Node.js
2. `npm install`
3. `npx playwright install`
4. `npx playwright test --project=chromium`
5. `npx playwright show-report`

## Tools
Playwright, JavaScript, Node.js, VS Code

## Status
Beginner practice project.
