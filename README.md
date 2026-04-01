<div align="center">

# Abdullah Ghaznavi
### Full Stack Mobile Engineer · Flutter · Clean Architecture · ERP & Marketplace Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdullah_Ghaznavi-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/abdullah-flutterdev/)
[![Email](https://img.shields.io/badge/Email-flutterdev999@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:flutterdev999@gmail.com)
[![Location](https://img.shields.io/badge/Location-Lahore,_Pakistan-2D8653?style=flat-square&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Lahore,Pakistan)

</div>

---

## About Me

I'm a Full Stack Mobile Engineer based in Lahore, Pakistan, with 2–3 years of hands-on experience building production-grade Flutter applications for real businesses. My work spans enterprise ERP systems, multi-vendor marketplace platforms, and B2B SaaS tools — all shipped and live.

I specialise in **Clean Architecture**, **BLoC/Cubit state management**, and **RESTful API integration** with a strong focus on scalability, code maintainability, and delivering measurable business value. I've architected systems handling 52+ feature modules, multi-tenant configurations, real-time analytics dashboards, biometric security, and multi-currency financial reporting — not in side projects, but in production apps used by real companies.

I don't just write Flutter code. I think in systems: data flow, domain boundaries, failure states, and UX outcomes. Every feature I build is designed to be extended, tested, and maintained by a team.

> Currently open to **remote contracts**, **freelance engagements**, and **full-time roles** in Flutter / mobile engineering.

---

## Tech Stack

**Mobile & Frontend**
`Flutter` `Dart` `BLoC / Cubit` `GetX` `Provider` `fl_chart` `Lottie` `flutter_animate`

**Backend Integration**
`REST APIs` `Laravel (consumption)` `Firebase (Auth · Firestore · FCM)` `JWT Authentication` `Dio` `WebSocket`

**Architecture & Patterns**
`Clean Architecture` `Domain-Driven Design` `Repository Pattern` `Use Case Pattern`
`Interceptor Pattern` `Sentinel/CopyWith Pattern` `Dependency Injection` `SOLID Principles`

**Data & Storage**
`Hive` `SharedPreferences` `flutter_secure_storage` `iOS Keychain` `Android Keystore (AES-256-GCM)`

**Payments & Maps**
`CMI Payment Gateway` `Firebase Auth` `OpenStreetMap` `flutter_map` `Geolocator` `Nominatim`

**Export & Reporting**
`PDF Generation` `Excel (XLSX)` `CSV (RFC 4180)` `QR Code` `Printing`

**Tools**
`Git` `Android Studio` `Xcode` `VS Code` `CocoaPods` `Gradle` `build_runner` `json_serializable`

---

## Featured Projects

### Pipetal — Enterprise ERP for Steel Trading
> Production-grade, multi-tenant ERP mobile application serving steel trading businesses

A **52-module Flutter ERP system** built with Clean Architecture, BLoC/Cubit + GetX, and Dio-based API integration. Covers the full business lifecycle: Sales, Procurement, Inventory, Finance, and Reporting — replacing manual workflows with a mobile-first enterprise solution.

**Highlights:**
- JWT auth with automatic token refresh and concurrent request queuing
- Biometric login (Face ID / Fingerprint) with platform-native AES-256-GCM encrypted storage
- Real-time KPI dashboard with 12 custom interactive chart widgets (bar, doughnut, aging, rankings)
- Complete financial suite: Trial Balance, P&L (standard + comparative), Balance Sheet, Account Ledger
- Inventory management: stock valuation, rackwise tracking, slow-moving analysis, item drill-down
- Multi-tenant architecture with dynamic API base URL switching per company
- 20+ data export services: PDF (landscape A4), Excel (XLSX), CSV, clipboard, print
- Functional error handling with `dartz` Either type across all use cases

`Flutter` `Clean Architecture` `BLoC/Cubit` `GetX` `Dio` `fl_chart` `dartz` `Hive` `Multi-Tenancy` `ERP`

---

### Dabablane — Consumer Marketplace & Booking Platform
> Multi-category deal discovery and reservation app — live on Google Play

[![Play Store](https://img.shields.io/badge/Google_Play-Dabablane_User-414141?style=flat-square&logo=googleplay)](https://play.google.com/store/apps/details?id=com.dabablane.app)

A full-featured **marketplace and booking platform** for restaurants, beauty, sports, and entertainment. Supports instant and scheduled reservations, multi-modal payments, GPS-based filtering, and real-time order management.

**Highlights:**
- Multi-provider auth: Email/Password, Google, Facebook, Apple Sign-In + email verification
- Dual backend: Firebase Auth + Laravel REST API
- Reservation engine with real-time slot availability, capacity limits, QR code confirmation
- 3 payment modes: Cash, Online (CMI gateway via WebView), Partial payment with VAT breakdown
- GPS-based location detection, reverse geocoding (Nominatim), location-filtered offers
- Full bilingual support (French + English) with runtime language switching
- Rich media: image carousel, full-screen pinch-to-zoom gallery, video playback
- Paginated search with category/subcategory filters, price range, and sort options

`Flutter` `Firebase` `Laravel API` `Provider` `CMI Gateway` `Geolocator` `i18n` `QR Code`

---

### Dabablane Vendor — B2B Vendor Management Platform
> Full vendor-side operations app for the Dabablane ecosystem — live on Google Play

[![Play Store](https://img.shields.io/badge/Google_Play-Dabablane_Vendor-414141?style=flat-square&logo=googleplay)](https://play.google.com/store/apps/details?id=com.dabablane.vendor)

A comprehensive **B2B SaaS mobile application** enabling vendors to manage their entire business from a single app — offers, reservations, orders, financials, analytics, and customer communications.

**Highlights:**
- Dual-backend auth: Firebase + Laravel with WhatsApp OTP verification
- Complex offer scheduling: working days, time intervals, excluded time slots, weekly/custom exclusions
- Analytics dashboard: KPI cards (revenue, reservations, orders, avg basket) with period filtering
- Calendar/agenda system with day/week/month views and status-based event filtering
- Commission tracking, payout schedules, monthly invoice PDF generation with company branding
- Membership/subscription system with tiered plans and promo code support
- QR scanner for contactless reservation confirmation
- Morocco-specific location hierarchy with interactive OpenStreetMap location picker
- 600+ localisation keys with full bilingual support

`Flutter` `Firebase` `Laravel API` `Provider` `flutter_map` `OpenStreetMap` `PDF` `QR Scanner` `FCM`

---

## Live Apps

| App | Platform | Link |
|-----|----------|-------|
| Dabablane (User) | Google Play | [View on Play Store](https://play.google.com/store/apps/details?id=com.dabablane.app) |
| Dabablane (Vendor) | Google Play | [View on Play Store](https://play.google.com/store/apps/details?id=com.dabablane.vendor) |

---

## GitHub Stats

<div align="center">

![Abdullah's GitHub Stats](https://github-readme-stats.vercel.app/api?username=agkhawja&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=agkhawja&layout=compact&theme=default&hide_border=true)

</div>

---

## Domain Expertise

```
ERP Systems              ████████████████████  Production
Marketplace / Booking    ████████████████████  Production
Financial Reporting      ███████████████░░░░░  Advanced
Inventory Management     ███████████████░░░░░  Advanced
Multi-Tenant SaaS        ██████████████░░░░░░  Advanced
Payment Integration      █████████████░░░░░░░  Advanced
Biometric / Security     ████████████░░░░░░░░  Intermediate–Advanced
Maps & Geolocation       ████████████░░░░░░░░  Intermediate–Advanced
```

---

## Currently

- Building production Flutter applications for clients across **Pakistan, Morocco, and Europe**
- Deepening expertise in **offline-first architecture** and **Flutter Web**
- Open to collaborating on impactful mobile products

---

<div align="center">

**Let's build something production-grade.**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdullah-flutterdev/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:flutterdev999@gmail.com)

</div>
