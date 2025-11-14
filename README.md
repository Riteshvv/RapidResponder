# Rapid Responder  

Rapid Responder is an application that connects trained volunteers and retired first responders with nearby residents who need assistance in non-emergency situations such as minor injuries, wellness checks, or car trouble. Its purpose is to ease pressure on 911 systems, improve community response times, and strengthen neighborhood safety.

---

## Features
- Two user roles: citizens requesting help and verified responders  
- Real-time alerts sent to nearby volunteers  
- Full request status flow: Requested → Accepted → Checked-In → Completed  
- Responder verification system with secure certificate uploads  
- Efficient location matching using geofencing to reduce battery usage  
- Encrypted data storage and JWT authentication  
- Gamified responder system with points and achievements  

---

## Tech Stack

### Frontend
- Swift (iOS)  
- React + JavaScript (Web app)  
- Tailwind CSS, Framer Motion, shadcn/ui  

### Backend
- Node.js / Express  
- MongoDB + Mongoose  
- RESTful APIs with response caching  
- JWT authentication  

### Additional Tools
- Geofencing for location efficiency  
- MongoDB atomic operations and optimistic concurrency  
- Secure certificate handling and verification workflows  

---

## How It Works
1. User creates an account as either a citizen or responder  
2. Responders upload certifications for verification  
3. Citizens submit a help request with details and location  
4. Nearby responders receive instant notifications  
5. A responder accepts the request and checks in upon arrival  
6. Citizen rates the response and provides feedback  

---

## Key Challenges Solved
- Prevented double-accept issues using atomic MongoDB operations  
- Reduced battery drain through geofencing rather than constant GPS updates  
- Secured certificate verification using encrypted storage and JWT auth  
- Achieved smooth communication between Swift, JavaScript, and MongoDB through well-structured REST endpoints  

---

## Impact
A large portion of 911 calls are non-emergencies, overwhelming dispatch systems and delaying critical responses. Rapid Responder offers a community-driven solution where trained local volunteers can handle minor situations quickly without occupying emergency resources.

---

## Screenshots
(Add your screenshots here.)

---

## Installation

### Backend
```bash
npm install
npm run dev
