# Smart India Hackathon Workshop

**Date:** 26-10-2026

**Register Number:** 212224040336

**Name:** SUDHISHNA P

---

## Problem Title
**SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations**

## Problem Description

**Background:** Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections.

**Description:** The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers.

**Expected Solution:** A multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. It should include:
- A mobile application with 3D interactive maps and step-by-step navigation.
- Digital kiosks located throughout the station with touch-screen interfaces.
- Voice-guided navigation for visually impaired passengers.
- Regular updates to reflect changes in station layout and facility locations.
- Integration with existing railway apps and services for a seamless user experience.

## Problem Creator's Organization
Ministry of Railways

---

## Idea

### Functional Requirements Overview

**1. Indoor Map & Navigation**
- Interactive 2D/3D station maps showing platforms, ticket counters, restrooms, food courts, waiting rooms, lifts, escalators, and exits.
- Search for any facility, platform, or train number and get the shortest route from the user's current location.
- Step-by-step directions with estimated walking time.
- Multi-floor routing (stairs, lifts, escalators, foot-over-bridges).

**2. Accessibility Features**
- Voice-guided navigation for visually impaired passengers (text-to-speech, voice commands).
- Wheelchair-friendly routes (ramps and lifts, avoiding stairs).
- High-contrast mode and large fonts.
- Multilingual support (English, Hindi, and regional languages).

**3. Digital Kiosks**
- Touch-screen kiosks placed across the station showing the map with a "You are here" marker.
- QR code on the kiosk to continue the same route on the passenger's phone.

**4. Real-Time Updates**
- Live platform changes, train delays, and facility closures (e.g., a lift under maintenance) reflected on the map.
- Admin dashboard for station staff to update layouts, add or remove facilities, and push alerts.

**5. Railway App Integration**
- Integration with existing railway services (PNR status, live train status) to auto-suggest the platform route for the passenger's train.

### Technical Considerations

**User Experience**
- Responsive design for mobile, tablet, and kiosk screens.
- Simple, intuitive interface usable by all age groups.
- Compliance with accessibility standards (WCAG).

**Positioning**
- Indoor positioning using Wi-Fi / BLE beacons, with GPS for outdoor areas and QR-code checkpoints as a fallback.

**Security & Privacy**
- HTTPS/TLS for data transmission.
- Minimal collection of location data, with user consent and privacy controls.
- Role-based access for the admin panel.

### Phases of Arrangement

**Phase 1: Planning and Requirement Gathering**
- Collect requirements from passengers, station staff, and railway officials.
- Prepare station floor plans and a list of facilities.

**Phase 2: Design and Prototyping**
- Create wireframes for the mobile app, kiosk UI, and admin dashboard.
- Take feedback from sample users, including differently-abled passengers.


