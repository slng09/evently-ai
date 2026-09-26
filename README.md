# evently-ai
Evently AI is a prototype AI-powered event recommendation assistant that helps users discover events that match their interests, goals, budget, availability, and preferred format.

Built as a single-page HTML application for rapid prototyping and hackathon demonstrations, Evently AI showcases how an AI agent can provide transparent, explainable, and personalised recommendations while keeping the user in control.

Overview

Finding relevant events can be time-consuming. Users often need to browse multiple platforms, compare options, and determine which events best match their needs.

Evently AI addresses this challenge by acting as a personal event planning assistant that:

Understands user preferences
Matches preferences against available events
Explains why recommendations were chosen
Supports simulated event registration
Demonstrates calendar integration workflows
Provides transparent recommendation scoring
Key Features
Personalised Recommendations

Users can specify:

Interests (AI, Startups, Fitness, Social, Technology, etc.)
Goals
Budget limits
Availability
Preferred event format (Online or In-Person)

The recommendation engine ranks events based on these preferences.

Explainable AI

Every recommendation includes:

Match score
Recommendation rationale
Budget suitability
Networking relevance
Availability match

This ensures recommendations remain transparent and understandable.

Interactive AI Agent

Users can:

Update preferences using natural language
Adjust budget constraints
Change availability
Shift recommendation priorities
Re-rank results instantly
Simulated Event Registration

Demonstrates:

Event registration flow
Registration confirmation
Registration reference generation
Calendar Integration Prototype

Users can:

Add events to a simulated calendar
Generate Google Calendar links
Generate Outlook Calendar links
Download ICS calendar files
Event Discovery Dashboard

Provides:

Event listings
Match scoring
Event details
Venue information
Maps integration
Responsible AI Design

The prototype was built with Responsible AI principles in mind.

Transparency

Users can see how recommendations are generated.

Explainability

Recommendation scores are broken into understandable factors.

User Control

Users can modify priorities at any time.

Grounded Recommendations

The engine only uses information available within the event dataset.

No Fabricated Event Data

The system does not invent:

Reviews
Ratings
Attendance figures
Registration availability
Event details
Technology Stack
Component	TechnologyFrontend	HTML5
Styling	CSS3
Application Logic	Vanilla JavaScript
Data Storage	Embedded JSON Dataset
Calendar Integration	Google Calendar, Outlook Calendar, ICS Export
Mapping	Google Maps Links

No backend services are required.

Project Structure
Plain Text
evently-ai/
│
├── index.html
├── README.md
└── assets/ (optional)
``
Show more lines

The entire prototype is contained within a single HTML file.

Demo Personas

The prototype includes several predefined personas:

Priya – AI & Startup Networking
Arjun – Fitness & Outdoor Activities
Meera – Startup Learning
Daniel – Budget AI Learner
Ananya – Women in Tech Networking
Rahul – Casual Social Events

These demonstrate how the recommendation engine behaves under different user profiles.

Recommendation Engine

The recommendation engine evaluates:

Hard Constraints
Budget
Availability
Event format
Scoring Factors
Interest Match
Goal Alignment
Networking Potential
Budget Fit

Each event receives a transparent match score out of 100.
