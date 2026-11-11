# https-bikzooom.web.app-
A modern, full-stack bike rental and fleet management web application with customer booking tracking and a dedicated administrative portal

# Bikzooom — Two-Wheeler Rental & Fleet Management System

**Bikzooom** is an end-to-end web platform designed to streamline on-demand bike rentals for riders and automate booking verifications for showroom staff. Hosted on Firebase, the platform combines a user-facing booking portal with a secured internal administration suite.

---

## 🚀 Key Features

### 🛵 Customer Portal (`/`)
* **Fleet Catalog & Exploration:** Browse available two-wheelers categorized by riding style and use cases.
* **Dynamic Rental Duration:** Real-time rental rate calculation based on custom pickup and return times.
* **KYC-Integrated Booking:** Seamless reservation workflow collecting identity verification details (Aadhaar & Driving Licence) upfront.
* **Live Booking Tracker:** Dedicated tracking page (`/track.html`) enabling riders to monitor verification, approval, and dispatch status via a unique booking code.
* **Fulfillment Options:** Flexible showroom pickup or doorstep delivery scheduling.

### 🛡️ Admin Suite (`/admin/`)
* **Staff Authentication:** Restricted, role-based login ensuring secure operational access.
* **Reservation Lifecycle Management:** Verify customer KYC credentials, approve or decline rental requests, and update order stages in real time.
* **Fleet & Availability Tracking:** Monitor bike status across active rentals, returns, and maintenance.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Modern JavaScript (Vanilla ES6+)
* **Backend & Database:** Firebase (Firestore / Realtime Database, Firebase Authentication)
* **Hosting & Deployment:** Firebase Hosting
