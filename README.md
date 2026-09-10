# BharatYatra AI

### **भारत केवल देखा नहीं जाता, भारत जिया जाता है।**

> **Discover India. Your Way.**

> An integrated AI-powered tourism ecosystem designed to bring **destination discovery, cultural heritage, hidden gems, GIS-based crowd intelligence, transportation planning, digital travel passes, local crafts, GI-tagged products, festivals, and conversational travel assistance** into a unified platform.

<p align="center">

[![Smart India Hackathon](https://img.shields.io/badge/SIH-2026-orange.svg?style=for-the-badge)](https://www.sih.gov.in/)
[![Problem Statement](https://img.shields.io/badge/SIH26204-Student%20Innovation-blue.svg?style=for-the-badge)](https://www.sih.gov.in/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge\&logo=html5\&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/Vanilla%20JavaScript-F7DF1E.svg?style=for-the-badge\&logo=javascript\&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Leaflet](https://img.shields.io/badge/Leaflet-GIS-199900.svg?style=for-the-badge\&logo=leaflet\&logoColor=white)](https://leafletjs.com/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717.svg?style=for-the-badge\&logo=github)](https://github.com/shivkoli07/BharatYatra)

</p>

---

# 🌏 1. Project Overview

**BharatYatra AI** is a technology-driven tourism platform created with the vision of making India's enormous cultural, historical, geographical, and culinary diversity easier to discover and experience.

Traditional tourism platforms often focus on only one part of the travel journey — such as hotel booking, transportation, maps, or destination listings.

BharatYatra takes a broader approach.

It attempts to connect the complete tourism journey:

```text
DISCOVER
   ↓
EXPLORE
   ↓
PLAN
   ↓
BOOK
   ↓
VERIFY
   ↓
EXPERIENCE
```

The platform combines:

* 🇮🇳 Indian destination discovery
* 🏛️ Historical and UNESCO heritage
* 💎 Hidden-gem discovery
* 🗺️ GIS-based spatial visualization
* 👥 Crowd-density intelligence
* 🚆 Multimodal transportation planning
* 🏨 Hotel and stay discovery
* 🍽️ Restaurant and local-food discovery
* 🎨 Traditional crafts
* 🏺 GI-tagged products
* 🗓️ Cultural and festival calendar
* 🎟️ Unified digital travel passes
* 🔐 Pass verification
* 🤖 AI-powered travel assistance
* 🧭 Personalized itinerary generation
* 🌐 Multilingual interface

The long-term vision is to transform BharatYatra into a **unified digital tourism ecosystem for India**.

---

# 🎯 2. Problem Statement

### Smart India Hackathon 2026

**Problem Statement ID:** `SIH26204`

**Theme:** Travel & Tourism

**Category:** Student Innovation

### Problem Context

India has a vast tourism ecosystem covering:

* Historical monuments
* Forts and palaces
* Temples
* Beaches
* Islands
* Mountains
* Wildlife
* UNESCO heritage sites
* Traditional crafts
* GI-tagged products
* Regional cuisines
* Festivals
* Local markets
* Rural tourism
* Cultural communities

However, travelers still face several problems.

<div align="center">

<table>
<tr>
<th>🚧 Challenge</th>
<th>📌 Problem</th>
<th>💡 BharatYatra Approach</th>
</tr>
<tr>
<td><b>Platform Fragmentation</b></td>
<td>Travelers use different applications for destinations, hotels, food, maps and transport.</td>
<td>Unified tourism ecosystem</td>
</tr>
<tr>
<td><b>Over-Tourism</b></td>
<td>Popular attractions can experience excessive crowding.</td>
<td>Hidden-gem discovery + crowd intelligence</td>
</tr>
<tr>
<td><b>Hidden Destinations</b></td>
<td>Lesser-known destinations receive less visibility.</td>
<td>Alternative destination discovery</td>
</tr>
<tr>
<td><b>Artisan Marginalization</b></td>
<td>Traditional artisans and local communities may receive limited digital exposure.</td>
<td>Craft and GI ecosystem</td>
</tr>
<tr>
<td><b>Travel Complexity</b></td>
<td>Transportation, stays and attractions require separate planning.</td>
<td>Integrated travel planning</td>
</tr>
<tr>
<td><b>Cultural Discovery</b></td>
<td>Tourists may not know about regional traditions, festivals and cuisine.</td>
<td>Cultural calendar + local experiences</td>
</tr>
</table>

</div>

---

# 💡 3. Our Solution

BharatYatra addresses these problems through a centralized tourism platform.

The system connects:

```text
                    🇮🇳 BHARATYATRA
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
       ▼                  ▼                  ▼
  DESTINATION          CULTURE           PLANNING
       │                  │                  │
       ▼                  ▼                  ▼
   Heritage            Festivals        Transport
   Hidden Gems         Crafts           Hotels
   UNESCO              GI Products      Restaurants
   Attractions         Local Food       Itinerary
       │                  │                  │
       └──────────────────┼──────────────────┘
                          │
                          ▼
                  TRAVEL EXPERIENCE
```

Instead of treating tourism as a simple destination directory, BharatYatra connects **places, people, culture, mobility, information and technology**.

---

# 🏗️ 4. Core System Concept

The complete BharatYatra ecosystem is divided into several major layers.

```text
┌───────────────────────────────────────────────────────────────┐
│                         USER EXPERIENCE                       │
│       Discover • Explore • Plan • Book • Verify              │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                       BHARATYATRA MODULES                     │
│                                                               │
│ Destinations | UNESCO | Hidden Gems | Crafts | GI | Calendar │
│ Tickets | Verification | Chatbot | Authentication            │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                    INTELLIGENCE LAYER                         │
│                                                               │
│ AI Assistant | Itinerary | Crowd Intelligence | GIS          │
│ Recommendations | Route Planning                              │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                    EXTERNAL SERVICES                          │
│                                                               │
│ Groq API | Leaflet | OpenStreetMap | GeoJSON | GIS           │
│ Google Identity Services | Future OpenCV / FastAPI           │
└───────────────────────────────────────────────────────────────┘
```

---

# 🎨 5. Design System

BharatYatra uses a **royal Indian cinematic design language** combined with modern dark-mode interfaces.

## 🎨 Color Palette

<div align="center">

<table>
<tr>
<th>Color</th>
<th>Token</th>
<th>Hex</th>
<th>Purpose</th>
</tr>

<tr>
<td style="background:#D4AF37;color:#000000;padding:15px;">🟨</td>
<td><code>--gold-primary</code></td>
<td><code>#D4AF37</code></td>
<td>Primary actions, active links, borders and CTA elements</td>
</tr>

<tr>
<td style="background:#F5E6A3;color:#000000;padding:15px;">🟨</td>
<td><code>--gold-light</code></td>
<td><code>#F5E6A3</code></td>
<td>Headlines, highlights, hover effects and active tags</td>
</tr>

<tr>
<td style="background:#997A15;color:#FFFFFF;padding:15px;">🟫</td>
<td><code>--gold-dark</code></td>
<td><code>#997A15</code></td>
<td>Dividers, subtle borders and secondary accents</td>
</tr>

<tr>
<td style="background:#0B0B0C;color:#FFFFFF;padding:15px;">⬛</td>
<td><code>--bg-dark</code></td>
<td><code>#0B0B0C</code></td>
<td>Main application background</td>
</tr>

<tr>
<td style="background:#151518;color:#FFFFFF;padding:15px;">⬛</td>
<td><code>--bg-card</code></td>
<td><code>#151518</code></td>
<td>Cards, modals and glassmorphic surfaces</td>
</tr>

<tr>
<td style="background:#FFFFFF;color:#000000;padding:15px;">⬜</td>
<td><code>--text-primary</code></td>
<td><code>#FFFFFF</code></td>
<td>Main headings and important information</td>
</tr>

<tr>
<td style="background:#9BA1A6;color:#000000;padding:15px;">◽</td>
<td><code>--text-muted</code></td>
<td><code>#9BA1A6</code></td>
<td>Secondary text, descriptions and metadata</td>
</tr>

<tr>
<td style="background:#22C55E;color:#FFFFFF;padding:15px;">🟢</td>
<td><code>--crowd-low</code></td>
<td><code>#22C55E</code></td>
<td>Low crowd level: &lt; 35%</td>
</tr>

<tr>
<td style="background:#EAB308;color:#000000;padding:15px;">🟡</td>
<td><code>--crowd-mid</code></td>
<td><code>#EAB308</code></td>
<td>Moderate crowd level: 35–70%</td>
</tr>

<tr>
<td style="background:#EF4444;color:#FFFFFF;padding:15px;">🔴</td>
<td><code>--crowd-high</code></td>
<td><code>#EF4444</code></td>
<td>High crowd level: &gt; 70%</td>
</tr>

</table>

</div>

## Typography

### Headings

* **Cinzel**
* **Cinzel Decorative**

Used to create a royal, historical and Indian heritage-inspired identity.

### Information & UI

* **Plus Jakarta Sans**
* **DM Sans**

Used for readable navigation, descriptions, forms, cards and technical information.

---

# 🖥️ 6. Platform Architecture

```text
BharatYatra/
│
├── index.html
├── destinations.html
├── hidden_gems.html
├── unesco_sites.html
├── crafts.html
├── gi_tag.html
├── calendar.html
├── ticket_generator.html
├── verify_pass.html
├── chatbot.html
├── login.html
│
├── assets/
│   ├── images/
│   ├── videos/
│   ├── music/
│   ├── css/
│   └── js/
│
├── .gitattributes
├── .gitignore
└── README.md
```

---

# 🏠 7. `index.html` — Central Gateway

The homepage is the primary entry point into BharatYatra.

## Major Features

### 📖 3D Heritage Granth

An interactive digital-book experience designed to introduce users to India's civilization and heritage.

It can present content related to:

* Preamble of the Constitution
* Jana Gana Mana
* Vande Mataram
* Indian geography
* Indian civilization
* Historical heritage
* Cultural identity

### 🎬 Cultural Video Reels

The homepage uses cinematic visual media representing:

* Bharatanatyam
* Kathakali
* Lavani
* Ganga Aarti
* Rath Yatra
* Indian festivals
* Traditional cultural experiences

### 🌐 Language Switcher

The interface supports dynamic language switching using `data-i18n` based localization.

Current interface languages include:

* English
* Hindi
* Marathi

### 📢 Feature Ticker

The homepage contains a scrolling information ticker highlighting major BharatYatra capabilities.

---

# 🗺️ 8. `destinations.html` — Destination Explorer

The destination module provides a structured way to explore India's geography.

## 🇮🇳 Coverage

The interface organizes destinations across:

* 28 States
* 8 Union Territories

## Regional Zones

```text
North
North East
East
Central
West
South
```

## Features

* Region filters
* State filtering
* Union Territory filtering
* Search functionality
* Destination cards
* Regional guides
* Local cuisine information
* Transportation information
* Stay recommendations

### Objective

To reduce destination-discovery fragmentation by providing a centralized geographic directory.

---

# 💎 9. `hidden_gems.html` — Hidden Gems & Crowd Intelligence

This is one of the most important innovation-oriented modules of BharatYatra.

The objective is to reduce **over-tourism** by promoting alternative destinations.

## 🔄 Popular Spot vs Hidden Gem

The interface compares:

```text
Popular Destination
        ↓
Crowd Level
        ↓
Nearby Alternative
        ↓
Hidden Gem
```

Instead of sending every traveler toward the same popular landmark, the system can suggest less crowded alternatives.

---

# 🗺️ GIS Integration

The platform uses **Leaflet GIS** for spatial visualization.

Potential mapping stack:

```text
Leaflet
   +
OpenStreetMap
   +
GeoJSON
   ↓
Interactive Tourism Map
```

The map can display:

* Tourist destinations
* Hidden gems
* Crowd indicators
* Geographic boundaries
* Spatial relationships

---

# 👥 Crowd Intelligence

The platform uses three crowd states:

```text
🟢 LOW
< 35%

🟡 MODERATE
35% – 70%

🔴 HIGH
> 70%
```

The frontend architecture is designed so that future versions can consume real crowd-count data from:

* CCTV cameras
* OpenCV
* Drone telemetry
* Computer-vision pipelines
* Backend APIs

### Future Architecture

```text
CCTV / Drone
     ↓
OpenCV
     ↓
Crowd Detection
     ↓
FastAPI
     ↓
BharatYatra
     ↓
Live Crowd Map
     ↓
Alternative Destination
```

This makes the module suitable for future real-time deployment.

---

# 🏛️ 10. `unesco_sites.html` — UNESCO Heritage Explorer

The UNESCO module provides a dedicated heritage discovery experience.

## Features

### 🗺️ Interactive Map

Leaflet is used to display heritage locations geographically.

### 🏛️ Heritage Categories

The interface organizes sites into:

* Cultural
* Natural
* Mixed

Examples include:

**Cultural**

* Ajanta Caves
* Taj Mahal
* Hampi

**Natural**

* Kaziranga
* Sundarbans

**Mixed**

* Khangchendzonga National Park

### 📚 Heritage Information

Each location can provide information such as:

* Historical period
* Construction era
* Architectural significance
* Cultural importance
* Location
* Navigation information

---

# 🎨 11. `crafts.html` — Indian Crafts & Artisan Hub

BharatYatra treats India's traditional crafts as an important part of tourism.

## Coverage

The platform provides a state/UT-oriented craft directory covering India's regional traditions.

Examples include:

* Pashmina weaving
* Madhubani painting
* Bastar Dhokra
* Warli art
* Bidriware
* Traditional textiles
* Handloom traditions
* Regional handicrafts

## Features

* State/UT filtering
* Craft profiles
* Cultural descriptions
* Artisan traditions
* Visual media
* Craft-process videos

### Objective

The module aims to connect tourism with:

```text
Tourists
   ↓
Craft Discovery
   ↓
Local Artisan
   ↓
Cultural Preservation
   ↓
Local Economic Opportunity
```

---

# 🏺 12. `gi_tag.html` — GI-Tagged Products

Geographical Indication products represent the unique identity of specific regions.

The GI module creates a digital discovery layer for such products.

## Product Categories

* Agricultural products
* Handicrafts
* Textiles
* Food products
* Traditional products

## Example

```text
Region
   ↓
GI Product
   ↓
Origin
   ↓
Traditional Process
   ↓
Traveler Discovery
```

## Features

* GI product catalog
* Registration information
* Historical registration tracking
* Regional origin
* Product descriptions
* Traveler advisory information

### Objective

The module connects **tourism + cultural heritage + local economic ecosystems**.

---

# 🗓️ 13. `calendar.html` — Indian Cultural Calendar

The tourism calendar connects travel planning with India's festivals and cultural events.

## Features

* 12-month calendar
* Date navigation
* Festival highlighting
* Cultural information
* Seasonal planning
* Festival media
* Festival-specific descriptions

Examples:

* Diwali
* Holi
* Durga Puja
* Pushkar Fair
* Rath Yatra
* Regional festivals

The objective is to help travelers plan journeys around authentic cultural experiences.

---

# 🎟️ 14. `ticket_generator.html` — One-Ticket Digital Pass

BharatYatra introduces a unified digital-pass concept.

Instead of managing multiple pieces of travel information separately, the platform can generate a consolidated digital travel pass.

## Booking Flow

```text
SOURCE
   ↓
DESTINATION
   ↓
TRAVEL DATE
   ↓
TRANSPORT
   ↓
HOTEL
   ↓
ATTRACTION
   ↓
PAYMENT
   ↓
DIGITAL PASS
```

## Features

### 🚆 Transport Selection

Examples of supported travel concepts:

* Express Flight
* Vande Bharat
* Volvo Sleeper
* Other multimodal options

### 🏨 Stay Selection

Hotel/stay information can be associated with the journey.

### 💳 Payment Interface

The prototype includes a simulated UPI-style checkout experience.

### 🎫 Digital Pass

The generated pass can contain:

* PNR
* Passenger details
* Booking details
* Price breakdown
* Travel information
* Verification information
* Brand identity

### 🖨️ Print Support

Print-specific CSS allows the digital pass to be formatted for:

* Printing
* PDF saving
* Physical verification

---

# 🔐 15. `verify_pass.html` — Pass Verification

The verification module closes the loop between:

```text
PASS GENERATION
       ↓
PASS STORAGE
       ↓
PASS VERIFICATION
       ↓
ENTRY / CHECK-IN
```

## Features

### PNR Verification

The operator can enter the generated PNR.

### Status

The system can show statuses such as:

```text
🟢 VALID
🟡 ALREADY CHECKED-IN
🔴 EXPIRED
```

### Capacity Tracking

Check-in information can also be used to track venue capacity.

This can eventually help heritage sites manage visitor limits.

---

# 🤖 16. `chatbot.html` — AI Travel Companion

The chatbot is the conversational intelligence layer of BharatYatra.

The project is designed to use the **Groq API** for high-speed LLM inference.

## Travel Setup

The assistant can collect:

```text
Origin
Destination
Trip Duration
Travel Preferences
```

## AI-Generated Output

The assistant can generate:

* Day-by-day itinerary
* Transportation comparison
* Budget suggestions
* Destination recommendations
* Travel suggestions
* Activity planning

## Structured Responses

Instead of returning only plain paragraphs, the assistant can organize information into structured Markdown tables.

Example:

```text
| Day | Location | Activity | Transport |
|-----|----------|----------|-----------|
| 1   | Jaipur   | Fort Tour | Cab       |
| 2   | Jaipur   | Heritage | Local     |
| 3   | Pushkar  | Culture  | Bus       |
```

## Budget Modes

Potential itinerary categories include:

* 🎒 Backpacker
* 🏨 Mid-Range
* 👑 Luxury

---

# 🔗 17. Chatbot → Booking Integration

One of the important concepts is connecting conversational planning with booking.

```text
USER
 ↓
AI CHATBOT
 ↓
PERSONALIZED ITINERARY
 ↓
TRANSPORT
 ↓
HOTEL
 ↓
ATTRACTIONS
 ↓
ONE-TICKET GENERATOR
```

This avoids forcing the traveler to manually re-enter all itinerary information.

---

# 🔑 18. `login.html` — Authentication & User State

The authentication module provides account and session functionality.

## Authentication Concepts

* Email/password login
* Registration
* Google Identity Services
* Client-side session state
* User profile
* Booking history
* Saved information

## Navigation Personalization

After login, the navigation can dynamically display the traveler's name.

---

# 💾 19. Browser Data Architecture

The current prototype uses browser-side persistence for several functions.

## Local Storage

### `bharatUser`

Stores current user/session information.

```text
bharatUser
   ↓
Current User
Display Name
Authentication State
```

### `bharat_bookings`

Stores generated booking/pass information.

```text
bharat_bookings
   ↓
PNR
Passenger
Booking
Transaction
Pass Information
```

### `bharat_users_table`

Acts as a client-side mock user registry for the prototype.

---

# 🎵 20. Session Continuity

BharatYatra uses `sessionStorage` for maintaining certain states between page transitions.

### `bharat_audio_time`

Stores the current background-audio playback position.

### `bharat_audio_playing`

Stores whether the audio is currently playing.

This allows the cinematic background-music experience to continue more smoothly while navigating through pages.

---

# ⚙️ 21. Technical Architecture

```text
┌───────────────────────────────────────────────────────────────┐
│                    PRESENTATION LAYER                         │
│                                                               │
│ HTML5 │ CSS3 │ JavaScript │ Bootstrap │ Responsive UI        │
│                                                               │
│ Cinzel │ DM Sans │ Jakarta Sans │ Video │ Audio              │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                    APPLICATION LOGIC                          │
│                                                               │
│ Filters │ Search │ Authentication │ Booking │ Passes         │
│ Calendar │ Itinerary │ Crowd UI │ GIS Interaction            │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                    BROWSER STORAGE                            │
│                                                               │
│ localStorage │ sessionStorage                                │
│                                                               │
│ Users │ Bookings │ Authentication │ Audio State              │
└───────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
┌───────────────────────────────────────────────────────────────┐
│                  EXTERNAL SERVICES                            │
│                                                               │
│ Groq API │ Google Identity │ Leaflet │ OpenStreetMap         │
│ GeoJSON │ Future FastAPI │ Future OpenCV                     │
└───────────────────────────────────────────────────────────────┘
```

---

# 🗺️ 22. GIS Architecture

The spatial layer uses Leaflet-based mapping.

```text
                    BHARATYATRA GIS
                          │
              ┌───────────┴───────────┐
              │                       │
              ▼                       ▼
        OpenStreetMap              GeoJSON
              │                       │
              └───────────┬───────────┘
                          ▼
                   Leaflet Map
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
         Destinations  Hidden Gems   Heritage
             │            │            │
             └────────────┼────────────┘
                          ▼
                    User Decision
```

---

# 👥 23. Future Real-Time Crowd Intelligence

The crowd-balancing system is designed to become a real-time tourism management solution.

## Production Architecture

```text
CCTV / Drone / Sensor
          ↓
     Video Stream
          ↓
       OpenCV
          ↓
   Person Detection
          ↓
    Crowd Estimation
          ↓
       FastAPI
          ↓
    BharatYatra API
          ↓
      Leaflet GIS
          ↓
   Crowd Visualization
          ↓
Alternative Destination
Recommendation
```

### Example

```text
Taj Mahal
   ↓
Crowd: 87%
   ↓
HIGH CONGESTION
   ↓
Nearby alternative recommended
   ↓
Traveler redistributed
```

This can help:

* Reduce congestion
* Protect monuments
* Improve visitor experience
* Promote lesser-known destinations
* Spread tourism spending
* Support sustainable tourism

---

# 🔄 24. Complete User Journey

```text
                         START
                           │
                           ▼
                    BharatYatra Home
                           │
                           ▼
                    Explore India
                           │
            ┌──────────────┼──────────────┐
            ▼              ▼              ▼
       Destinations     Heritage       Culture
            │              │              │
            └──────────────┼──────────────┘
                           ▼
                    Select Destination
                           │
                           ▼
                  Check Crowd / Gems
                           │
                           ▼
                   Plan Your Journey
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
          Transport      Hotel       Restaurant
              │            │            │
              └────────────┼────────────┘
                           ▼
                     AI Assistant
                           │
                           ▼
                 Personalized Itinerary
                           │
                           ▼
                  One-Ticket Generator
                           │
                           ▼
                     Digital Pass
                           │
                           ▼
                   Pass Verification
                           │
                           ▼
                   Travel Experience
                           │
                           ▼
                         🇮🇳
```

---

# 🧠 25. AI Architecture

The AI component is designed around conversational travel intelligence.

```text
USER
 │
 ▼
Travel Query
 │
 ▼
BharatYatra Chatbot
 │
 ▼
Groq API
 │
 ▼
LLM Inference
 │
 ├── Destination Recommendations
 ├── Itinerary Generation
 ├── Transport Suggestions
 ├── Budget Planning
 └── Travel Information
 │
 ▼
Structured Response
 │
 ▼
Booking Integration
```

### Future AI Enhancements

The platform can evolve toward:

* RAG-based tourism knowledge
* Personalized recommendation models
* Semantic destination search
* Travel preference learning
* Budget optimization
* Crowd-aware itinerary generation
* Multilingual conversational AI
* Context-aware travel assistance

---

# 🧠 26. Future RAG Architecture

A Retrieval-Augmented Generation layer can be added in future versions.

```text
                  USER QUERY
                      │
                      ▼
               Query Processing
                      │
                      ▼
              Vector Retrieval
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
   Heritage DB     Food DB      Tourism DB
        │             │             │
        └─────────────┼─────────────┘
                      ▼
                 Retrieved Data
                      │
                      ▼
                    LLM
                      │
                      ▼
            Verified Travel Answer
```

Potential knowledge sources:

* Tourism information
* Heritage databases
* Destination information
* Cultural resources
* Food databases
* GI records
* Craft information
* Government tourism data

---

# 🌐 27. Multilingual Tourism

India has a highly diverse linguistic landscape.

Future versions can expand the current multilingual interface to include:

* English
* Hindi
* Marathi
* Gujarati
* Bengali
* Tamil
* Telugu
* Kannada
* Malayalam
* Punjabi
* Other regional languages

The objective is to make tourism information accessible to both domestic and international travelers.

---

# 💰 28. Smart Budget Planning

Future itinerary generation can consider:

```text
Total Budget
+
Number of Travelers
+
Number of Days
+
Travel Preferences
```

and estimate:

```text
Transportation
       +
Accommodation
       +
Food
       +
Activities
       +
Local Travel
       ↓
Estimated Trip Budget
```

This can allow the user to choose between:

```text
🎒 Budget
🏨 Standard
👑 Premium
```

---

# 🌦️ 29. Weather-Aware Travel Planning

Future versions can integrate weather APIs to provide:

* Weather-based recommendations
* Best visiting dates
* Seasonal destination suggestions
* Outdoor activity recommendations
* Weather warnings
* Monsoon-aware planning

---

# 📍 30. Location-Based Recommendations

With future geolocation support, BharatYatra can provide:

```text
Nearby Attractions
Nearby Restaurants
Nearby Hotels
Nearby Hidden Gems
Nearby Crafts
Nearby Heritage Sites
Nearby Cultural Experiences
```

This can transform BharatYatra into a contextual travel assistant rather than only a static tourism website.

---

# 🛠️ 31. Technology Stack

## Current / Core Technologies

| Layer           | Technology                                            |
| --------------- | ----------------------------------------------------- |
| Structure       | HTML5                                                 |
| Styling         | CSS3                                                  |
| Client Logic    | Vanilla JavaScript                                    |
| UI Components   | Bootstrap                                             |
| Maps            | Leaflet                                               |
| Map Data        | OpenStreetMap                                         |
| Spatial Data    | GeoJSON                                               |
| Typography      | Cinzel, Cinzel Decorative, DM Sans, Plus Jakarta Sans |
| Browser Storage | LocalStorage                                          |
| Session State   | SessionStorage                                        |
| AI              | Groq API                                              |
| Authentication  | Google Identity Services                              |
| Media           | HTML5 Video / Audio                                   |
| Version Control | Git                                                   |
| Repository      | GitHub                                                |
| Large Media     | Git LFS                                               |

## Planned / Integration-Ready Technologies

| Area            | Technology                  |
| --------------- | --------------------------- |
| Backend         | FastAPI / Node.js           |
| Database        | PostgreSQL / MongoDB        |
| Crowd Detection | OpenCV                      |
| AI Knowledge    | RAG                         |
| Vector Database | FAISS / Chroma / pgvector   |
| AI Models       | LLM / Recommendation Models |
| Weather         | Weather APIs                |
| Location        | Geolocation APIs            |
| Transport       | Live transport APIs         |
| Hotels          | Hotel APIs                  |
| Restaurants     | Restaurant APIs             |

---

# 📦 32. Installation

## Prerequisites

Install:

* Git
* Python 3
* VS Code
* Modern web browser

Optional:

* Node.js
* VS Code Live Server

---

## Clone Repository

```bash
git clone https://github.com/shivkoli07/BharatYatra.git
```

## Enter Project

```bash
cd BharatYatra
```

---

# ▶️ 33. Run Locally

## Option 1 — Python HTTP Server

```bash
python -m http.server 8000
```

Open:

```text
http://localhost:8000
```

---

## Option 2 — VS Code Live Server

1. Open the project in VS Code.
2. Install **Live Server**.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

---

## Option 3 — Node.js

```bash
npx serve .
```

Then open the URL displayed by the server.

---

# 🔐 34. Environment & API Security

If external APIs are used, **never commit private API keys directly into GitHub**.

Do not upload:

```text
API Keys
Passwords
OAuth Secrets
Private Tokens
Credentials
.env files containing secrets
```

For a production architecture, API calls should be routed through a secure backend rather than exposing sensitive credentials in client-side JavaScript.

---

# ⚠️ 35. Prototype vs Production

BharatYatra currently combines implemented frontend functionality with integration-ready architecture.

### Current Prototype Layer

* Tourism UI
* Destination exploration
* Heritage discovery
* Cultural content
* Crafts
* GI products
* Festival calendar
* GIS visualization
* Client-side authentication state
* Digital-pass prototype
* Pass verification prototype
* AI travel-assistant interface
* Browser-based persistence

### Production Expansion

* Secure backend authentication
* Real database
* Live transport APIs
* Real hotel APIs
* Real restaurant APIs
* Real payment gateway
* Real-time crowd feeds
* OpenCV crowd detection
* Cloud infrastructure
* RAG knowledge system
* Production LLM integration
* Real-time notifications

This distinction is important because BharatYatra is currently a **working tourism prototype with a production-oriented architecture and expansion roadmap**, rather than claiming that every external service is already connected to live production infrastructure.

---

# 📊 36. Expected Impact

BharatYatra is designed to create impact across multiple tourism stakeholders.

<div align="center">

| Stakeholder              | Potential Benefit                  |
| ------------------------ | ---------------------------------- |
| 🧳 Travelers             | Easier trip discovery and planning |
| 🏛️ Heritage Sites       | Better visitor management          |
| 💎 Hidden Destinations   | Increased visibility               |
| 🎨 Artisans              | Greater digital exposure           |
| 🏺 GI Communities        | Product and cultural discovery     |
| 🍛 Local Food Businesses | Culinary tourism exposure          |
| 🏨 Hospitality           | Better destination connectivity    |
| 🚆 Transport Providers   | Integrated travel planning         |
| 🇮🇳 Tourism Ecosystem   | More distributed tourism activity  |

</div>

---

# 🌱 37. Sustainable Tourism Vision

A major long-term objective of BharatYatra is **balanced tourism**.

Instead of:

```text
Millions of visitors
        ↓
Few popular locations
        ↓
Overcrowding
        ↓
Environmental & cultural pressure
```

BharatYatra aims for:

```text
Visitors
   ↓
Multiple destinations
   ↓
Hidden Gems
   ↓
Local Communities
   ↓
Distributed Tourism
   ↓
Sustainable Growth
```

This can help distribute both **visitor footfall and economic opportunity**.

---

# 🏆 38. Key Innovation Areas

The project's major innovation areas are:

### 1. 🗺️ GIS-Based Tourism Intelligence

Spatially representing destinations and crowd conditions.

### 2. 💎 Hidden-Gem Redistribution

Using alternative destinations to reduce concentration at popular attractions.

### 3. 👥 Crowd-Load Balancing

Designing the platform to eventually consume real-time crowd data.

### 4. 🎟️ Unified Digital Pass

Connecting multiple travel components into one digital travel-pass concept.

### 5. 🤖 Conversational Travel AI

Generating personalized travel plans through an AI assistant.

### 6. 🎨 Cultural Preservation

Connecting tourism with Indian crafts, traditions and local communities.

### 7. 🏺 GI Tourism

Promoting geographically unique Indian products through tourism.

### 8. 🗓️ Festival-Based Travel

Helping tourists plan journeys around India's cultural calendar.

---

# 🚀 39. Future Roadmap

```text
PHASE 1
───────
Tourism Discovery
       ↓
Heritage + Culture
       ↓
Crafts + GI + Festivals


PHASE 2
───────
GIS
       ↓
Hidden Gems
       ↓
Crowd Visualization


PHASE 3
───────
AI Assistant
       ↓
Personalized Itinerary
       ↓
Budget Planning


PHASE 4
───────
Live Transport
       ↓
Hotels
       ↓
Restaurants
       ↓
Digital Booking


PHASE 5
───────
OpenCV Crowd Detection
       ↓
Real-Time GIS
       ↓
Crowd Redistribution


PHASE 6
───────
RAG Tourism Knowledge
       ↓
Multilingual AI
       ↓
Fully Personalized
National Tourism Ecosystem
```

---

# 📌 40. Project Status

**Status:** 🚧 Active Development

BharatYatra is currently being developed as an SIH-oriented tourism technology prototype.

The project establishes the core tourism interface and several specialized modules while providing an architecture that can be expanded into a full-stack, API-driven, AI-powered national tourism ecosystem.

---

# 🧪 41. Testing Strategy

Future testing can cover:

### Functional Testing

* Navigation
* Search
* Filters
* Login
* Ticket generation
* Pass verification
* Calendar
* Chatbot

### GIS Testing

* Marker accuracy
* Map loading
* GeoJSON boundaries
* Destination coordinates

### AI Testing

* Itinerary relevance
* Travel recommendations
* Response consistency
* Budget generation
* Prompt handling

### Security Testing

* Authentication
* API key protection
* Input validation
* Session handling
* Authorization

### Performance Testing

* Large media loading
* Map performance
* Mobile responsiveness
* API response time

---

# 👨‍💻 42. Developer

## Shiv Koli

**B.E. Information Technology**

Bharati Vidyapeeth College of Engineering, Navi Mumbai

### GitHub

[github.com/shivkoli07](https://github.com/shivkoli07)

### Project Repository

[github.com/shivkoli07/BharatYatra](https://github.com/shivkoli07/BharatYatra)

---

# 🏆 43. Hackathon Information

| Field             | Details                                |
| ----------------- | -------------------------------------- |
| Project           | **BharatYatra AI**                     |
| Hackathon         | **Smart India Hackathon 2026**         |
| Problem Statement | **SIH26204**                           |
| Theme             | **Travel & Tourism**                   |
| Category          | **Student Innovation**                 |
| Domain            | **Tourism Technology**                 |
| Core Focus        | **Indian Tourism & Cultural Heritage** |

---

# 📜 44. Disclaimer

BharatYatra is currently an **educational and hackathon-oriented prototype**.

Information, booking flows, payment interfaces, crowd indicators, transportation recommendations and other services should be connected to verified official or commercial APIs before being used for real-world commercial travel operations.

The prototype should not be considered an official ticketing, payment, transportation, hotel or government tourism service.

---

# 🇮🇳 45. Vision

> ## **BharatYatra is not just about finding a destination.**
>
> ## **It is about discovering the story, culture, people, food, crafts and experiences behind that destination.**

The long-term vision is to build a digital ecosystem where technology helps travelers:

```text
DISCOVER INDIA
      ↓
UNDERSTAND INDIA
      ↓
EXPERIENCE INDIA
      ↓
SUPPORT LOCAL INDIA
      ↓
TRAVEL RESPONSIBLY
```

---

# BharatYatra AI

### **Discover India. Explore Its Heritage. Experience Its Culture.**

### **भारत केवल देखा नहीं जाता, भारत जिया जाता है। 🇮🇳**
