# Arubeauty — Makeup Studio & Training Courses

This repository contains the Midterm Project for the Web Technologies course. 
The site represents a fully responsive, front-end frozen state for a real, physically existing makeup studio in Astana.

**Author:** Serikkali Nariman

## Project Overview
This project builds upon the HTML5 skeleton from Assignment 1, the custom CSS from Assignment 2, and the responsive grid system via Bootstrap 5 from Assignment 3. 

For the Midterm, the project has been finalized as a cohesive, logical product. All elements, forms, links, and design states are fully prepared for the future integration of JavaScript. No dead links (`href="#"`) exist, and all user flows can be completed independently by a single visitor.

## File Structure
* `index.html` — The main landing page outlining the studio's philosophy, location, and quick actions.
* `services.html` — Contains a structured data table with service prices, course descriptions, and enrollment steps.
* `booking.html` — A comprehensive appointment booking page with a detailed HTML5 form and future JS response containers.
* `portal.html` — The client help center featuring a Bootstrap accordion FAQ, search, and dual authentication forms (Sign In / Register).
* `css/base.css` — Shared styles for the overall layout, typography, and color palette.
* `css/custom.css` — Specific layout corrections and predefined state classes (e.g., `.is-hidden`, `.state-error`) prepared for JavaScript logic.
* `images/` — Contains real, original photographs replacing any placeholder content.

## Three User Journeys

As required, here are three complete journeys a single visitor can take through the site:

**Journey 1: Booking a Makeup Session**
1. **Start:** The visitor lands on `index.html` and reads about the studio.
2. **Steps:** They click "Services & Prices" in the navigation and review the costs in the table on `services.html`. Deciding on "Day / Evening Makeup", they press the "Book" button in that row, which opens `booking.html`.
3. **End:** They fill out their personal details, select the service and preferred time in the form, and click "Submit Request". (A hidden container with `id="booking-message-container"` is prepared below the form to display the confirmation once JavaScript is added).

**Journey 2: Finding Preparation Info and Contacting the Studio**
1. **Start:** A client needs to know how to prepare their skin for tomorrow's appointment. They start on `index.html`.
2. **Steps:** They navigate to `portal.html` via the top menu. They scroll to the "Help Center (FAQ)" and open the accordion tab titled "How should I prepare my skin before the appointment?" to read the guidelines.
3. **End:** Having read the FAQ, they scroll down to the global footer on the same page and click the phone number link (`tel:+77768480043`) to call the studio and confirm their arrival time.

**Journey 3: New Client Registration**
1. **Start:** A new user wants to create an account to have a client account. They open `index.html`.
2. **Steps:** They click "Client Portal & FAQ" in the navigation, arriving at `portal.html`. They scroll past the FAQ directly to the "Account Management" section.
3. **End:** Under "Create New Account", they input their Full Name, Email, and a secure password, then click "Register". (A hidden container with `id="reg-message-container"` is ready to display the successful registration message once JS is implemented).

## How to Run
Clone the repository and open `index.html` in any modern web browser. The site relies on a Bootstrap CDN, so an active internet connection is required for proper layout rendering.