# buyanything — Native Android + multi-role delivery platform prototype

This project upgrades the original blue food delivery blueprint into a **native Android Jetpack Compose app** with a premium blue design and four role workspaces.

## Included
### Customer
- Premium home screen, promo hero, search and food categories
- Vegetarian, quick meal and popular filters; price sorting
- Dish cards, favorites, cart quantity controls
- Demo checkout form and itemized bill
- ₹80 sample offer on cart subtotal ₹299+; minimal-packaging toggle
- Order timeline with simulated progress
- Dark mode and profile preference screen

### Restaurant owner
- Sales and order KPI cards (sample values)
- Incoming order queue with local demo actions
- Menu-management quick-action tiles

### Delivery partner
- Availability toggle, earnings/trips metrics (sample values)
- Suggested delivery card and demo accept action

### Admin
- Platform overview and sample metrics
- Restaurant approvals, support, coverage, promotions and safety queue

## Build an APK
1. Install Android Studio (current stable) and a compatible JDK 17.
2. Open this folder as an existing Gradle project.
3. Allow Gradle to sync and install the Android SDK Platform 35 if prompted.
4. Run the `app` configuration on an emulator or Android phone.
5. To create a debug APK, choose **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
6. Android Studio will show the output location. A signed release APK/AAB requires your own signing key and release configuration.

This workspace provides **source code, not a precompiled APK**. It has not been built or device-tested in this environment.

## Important
The app is a functional UI prototype, not a production marketplace. Checkout and role dashboards are demo-only; data is in memory and resets when the app process restarts. It does not connect to real restaurants, live delivery dispatch, GPS, payments, SMS, push notifications, or cloud storage. Dashboard numbers and tracking statuses are illustrative.

See `backend/README.md` for the recommended backend architecture, data model, order lifecycle, and security checklist before real-world launch.
