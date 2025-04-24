

#  Hayat Arena App

Welcome to **Hayat Arena** – the ultimate companion for football enthusiasts to **book matches**, **explore player stats**, **track live games**, **follow friends**, **order food**, and more – all in one beautifully designed SwiftUI application.

---

## 📱 App Overview

Hayat Arena is a SwiftUI-based mobile application that connects football fans and players through a smart platform where they can:

- Discover and book matches.
- View detailed match stats.
- Learn more about players.
- Track live events and updates.
- Order food during games.
- Navigate venues with smart maps.

---

## 🔑 Features & Functionalities

### 🏠 Home Screen (`MatchesView`)
- Displays upcoming and past matches in a sleek, tabbed layout.
- Filters by league and match type.
- Each match cell shows:
  - Club logos and names.
  - Match round.
  - Time and date.
  - Status (live/upcoming/past).

---

### 📅 Book Now Screen (`BookNowView`)
- Book a match at your favorite stadium.
- Top section shows:
  - High-quality stadium image.
  - Stadium name, rating, distance.
- Tabs include:
  - **Description** – Details about the venue.
  - **Reviews** – Community feedback.
  - **Photos** – Additional images.
- Stadium Features section:
  - Turf type, Lighting, Facilities, etc.
- Booking Button:
  - `Take a seat` – leads to seat selection and payment.

---

### 🎟️ Ticket Confirmation (`TicketView`)
- After booking:
  - A digital ticket is shown with:
    - Venue image.
    - Booking date & time.
    - Seat numbers.
    - Booking code.
    - QR/Barcode for scanning.
- Share or save the ticket.

---

### 👥 Player Info (`MoreAboutPlayersView`)
- Learn more about teams and players:
  - Player photos.
  - Position.
  - Stats (Goals, Assists, Cards).
  - Brief bios.

---

### 📊 Match Details (`MatchDetailsView`)
Tabbed interface with:
- **Overview** – Summary of match.
- **Stats** – Visual breakdown (possession, shots, fouls).
- **Playing XI** – Lineups for both teams.
- **Video** – Highlights and clips (if available).

---

### 🍔 Food Ordering (`FoodsView`)
In-app food delivery:
- Search bar for items or restaurants.
- Food categories (e.g. Burgers, Pizza, Drinks).
- Tabs: **Recommended** & **Popular**.
- Restaurant list with:
  - Logos, Names (e.g., McDonald's, KFC).
  - Estimated delivery time.
  - Ratings.

---

### 🗺️ Smart Stadium Map (`SmartMapView`)
- Interactive map of the stadium.
- Locate your seat.
- Track friends & family using:
  - **Group Code** system.
- View facilities (Toilets, Food Stalls, Exits).

---

### 🔐 Authentication
- **LoginView**
  - Email & password input.
  - Navigates to `HomePage` or `MatchesView` after success.
- Session maintained using secure state management.

---

## 🛠️ Tech Stack

- **Language**: Swift
- **Framework**: SwiftUI
- **Architecture**: MVVM
- **Maps**: MapKit
- **State Management**: `@State`, `@Binding`, `@ObservedObject`, `@EnvironmentObject`
- **Local JSON / API**: for match/player data and food menus

---

## 🚧 Features in Progress / To-Do

- Notifications for match reminders.
- Social login (Apple/Google).
- Chat system for team coordination.
- Loyalty points system for regular users.
- Admin panel for stadium managers.

---

## 🌟 Future Enhancements

- **Augmented Reality (AR) Navigation** inside stadiums using camera overlay.
- **Live commentary and stats overlay** during matches.
- **Team building feature** for friendly matches.
- **AI-powered player recommendation** for building ideal lineups.
- **Gamification**: leaderboards, XP, and rewards for users.
- **In-app referee rating system** after matches.
- **Stadium condition & weather updates** integrated live.
- **Multilingual support** including Arabic and French.
- **Offline booking mode** with QR verification upon entry.
- **Sponsorship & advertising module** for brands.
- **Fantasy League Integration** with real-time stats.

---

## 📸 UI/UX Style Guide

- Professional and modern design inspired by global sports and food apps.
- Rounded corners (`cornerRadius(20)`).
- Padding consistency and clean spacing.
- Bold fonts for key elements.
- Animations for transitions and interactions.

---

## 🧪 Testing

- UI tested across different iPhone sizes.
- Manual test cases for:
  - Booking flow.
  - Authentication.
  - Match detail rendering.
  - Seat selection logic.
  - SmartMap tracking accuracy.

---

## 📬 Contact

For questions, feedback, or support, reach out to:  
📧 **Rimasalshahrani56@gmail.com**
