# Project Summary
The Flare Events Inc. - Cross-Platform UX Optimization: Improving Navigation and Conversion for Flare Events' Websites is an Arizona State University capstone project, focusing on UX/UI design, where the goal is to improve navigation and redesign Flare Events' WordPress and Shopify pages. The team uses competitive analysis research on different websites before moving to Figma to redesign and prototype the homepage, city pages, and the new consolidated events page. New features for the redesigned website include functional, flipped event cards and filter and sort-by dropdowns. Once finished, the team moves into Shopify to create the redesigned pages based on the Figma design, using Shopify Liquid. The Shopify Liquid code created by the team is stored in this repository, including the redesigned city and home pages, and the new consolidated events page.

# Installation Instructions and Technical Documentation
## Architecture diagrams of the system
The system is built on the Shopify theme architecture, where the frontend is structured using a combination of Liquid templates, sections, and snippets. The homepage and other pages are made up of reusable components or sections that render dynamic content using Liquid. CSS is used to handle styling and layout, while JavaScript is used for minor interactivity such as hover effects and dynamic behaviors.

## File navigation information
- There are several directories in the Shopify Theme 
- /sections contains reusable page sections that we primarily implemented our new redesigns in 
- /snippets contains smaller reusable components 
- Pages contain the actual redesigned pages 

## Installation process
- No traditional installation process was required since development was done within Shopify’s hosted environment
- However, the setup involved:
  - Gaining collaborator access to the Shopify store
  - Accessing the Shopify Theme Editor
  - Duplicating existing sections or adding completely new sections to avoid affecting the live site
  - Editing code directly within Shopify or through a local code editor if needed
  - Connecting to Figma for design reference

## Licenses
- The project operates under Shopify’s platform usage terms. No additional third-party licenses were required for the features implemented.
- Design assets, such as images or branding, are owned or provided by the project sponsor.

## Libraries - including source and version
No external library versions were required for this implementation.

## API / SDK - including source and version
No external APIs or SDKs were directly used for the project.

# User Guide
## Description of how the system works
The Flare Events platform allows users to browse and discover speed dating and social events across multiple cities through an intuitive and centralized interface. Users can navigate from the homepage to either individual city pages or a consolidated “Find Events” page, where all available events are displayed. The system is designed to guide users through event discovery, provide key event details, and allow seamless navigation between different sections of the website. Interactive elements such as event cards, filters, and navigation buttons help users efficiently explore and select events based on their preferences.

## Goals and functionality - EPICS/User Stories
The main goal of the system is to improve event discoverability and user experience by simplifying navigation and presenting information clearly. Key functionalities include implementing a redesigned homepage for better user onboarding, creating a consolidated events page to centralize all events across cities, improving event cards to highlight important details and specialty events, and integrating filter and sort-by dropdowns to allow users to refine their search. These features support user needs such as quickly finding relevant events, exploring different cities, and understanding event offerings with minimal confusion.

## Inputs & Outputs
Users interact with the system through inputs such as selecting city buttons, clicking on event cards, and applying filters or sorting options. These inputs allow users to customize their browsing experience based on location or preferences. The outputs of the system include displaying filtered event results, navigating users to specific city pages, and presenting detailed event information through visually structured event cards. The system responds dynamically to user actions to ensure a smooth and responsive experience.

## Services and/or features
Key features of the platform include a redesigned homepage with improved navigation and visual hierarchy, a consolidated events page for centralized browsing, interactive city buttons that direct users to specific city pages, and enhanced event cards that visually differentiate event types, such as specialty or almost sold-out events. Additional features include filter and sort-by dropdowns to refine event searches, embedded media such as videos to increase user engagement, and structured informational sections like “How Speed Dating Works” to guide users through the experience. Together, these features create a cohesive and user-friendly interface.
