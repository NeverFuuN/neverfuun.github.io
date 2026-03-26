---
layout: page
title: Privacy Policy
description: Privacy Policy for the FuelCheck Sumy Android application
permalink: /fuelcheck/privacy
---

# Privacy Policy for FuelCheck Sumy

_Last updated: March 26, 2026_

This Privacy Policy describes how the **FuelCheck Sumy** mobile application (the “App”) collects, uses, and shares information when you use it.

By using the App, you agree to the practices described in this Policy.

---

## 1. Overview

- The App is designed to show fuel prices, gas stations in Sumy, and help you track your fuel expenses.
- The App does not require registration or an account.
- I do not store your personal data on my own servers. Most data is stored locally on your device, and some technical/usage data may be processed by third-party services (Google/Firebase/AdMob) for analytics, advertising, and crash diagnostics.

---

## 2. Information We Collect and Process

### 2.1. Data Stored on Your Device

The App stores data locally using a database and preferences, including:

- **Fuel log / expense history**:
  - refueling date;
  - gas station ID (internal ID tied to station directory);
  - fuel type;
  - fuel volume;
  - price per liter;
  - total cost;
  - odometer reading.

- **Preferences and settings**:
  - selected fuel type for filtering;
  - list of favorite gas stations;
  - other UI preferences.

This data is used only inside the App and is **not uploaded to my own servers**.

### 2.2. Data Retrieved from the Network

To function, the App calls a remote API to fetch:

- a list of gas stations and their coordinates;
- brands and current fuel prices;
- additional details about stations (logos, names, addresses).

Requests to this API do not include information that directly identifies you (such as your name, email, phone number, etc.). As with any HTTP request, technical information like your IP address and device characteristics may be processed by the hosting provider.

### 2.3. Location and Maps

- The App **does not request location permissions** (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`) and **does not track your GPS location**.
- The map displays coordinates of gas stations provided by the remote API. For some stations, the App may use Android’s built-in reverse geocoding to derive a street address from the station’s coordinates, not from your location.

### 2.4. Analytics

The App uses **Firebase Analytics** to help understand how it is used and to improve it.

Examples of events that may be collected:

- App open;
- Screen views (prices, map, calculator, expenses);
- Fuel type selection;
- Adding/removing expense logs;
- Success/failure of station data refresh;
- Ad show and ad errors.

Event parameters may include:

- fuel type code;
- number of stations loaded;
- error type when a request fails.

The App does **not** send your name, email, phone number, payment card numbers, or any other obvious personal text fields to analytics.

Data collection and processing is performed by Google in accordance with their privacy policies:  
https://policies.google.com/privacy

### 2.5. Crash Reports (Crashlytics)

The App uses **Firebase Crashlytics** to diagnose crashes and errors. When a crash occurs, the following may be sent:

- information about the crash (stack trace, error type);
- app version and OS version;
- device model and technical details.

These reports are used solely to fix bugs and improve stability. I do not use crash data to identify individual users.

More details:  
https://firebase.google.com/support/privacy

### 2.6. Advertising (Google AdMob)

The App displays banner and interstitial ads using **Google AdMob**. For ad delivery and measurement, AdMob may collect and process:

- your advertising ID (Google Advertising ID);
- approximate location (based on IP address);
- device information and usage data;
- interactions with ads (impressions, clicks, errors).

The exact scope and use of data is governed by Google’s own policies. I do not have direct access to all raw data processed by AdMob.

More details:  
https://policies.google.com/technologies/ads

---

## 3. How We Use the Information

We use data for the following purposes:

1. **To operate the App**:
   - display fuel prices and stations;
   - show the map and search;
   - store your fuel logs and expense history;
   - remember your favorite stations and fuel type.

2. **To analyze and improve the App**:
   - understand which features and screens are used most;
   - diagnose crashes and technical issues;
   - improve user experience and data quality.

3. **To show advertising**:
   - serve ads that help support further development of the App;
   - measure ad performance and prevent fraud.

---

## 4. Sharing of Information

I do **not sell or share** your personal data with third parties for their own marketing purposes.

Third-party services that may process data (in scope of their SDKs) include:

- Google Firebase Analytics – usage analytics;
- Google Firebase Crashlytics – crash reporting;
- Google AdMob – ad delivery;
- Google Maps and related Google services – maps and map APIs;
- Hosting provider of the remote fuel API – providing fuel and station data.

These services process data according to their own privacy policies.

---

## 5. Data Storage and Security

- Fuel logs, favorites, and other user data are stored locally on your device.
- Some app data may be included in Android’s system backup (if enabled in your device settings).
- Security is provided by built-in Android mechanisms and the security measures of third-party SDKs (Firebase, AdMob, etc.).
- While reasonable measures are taken, no method of transmission or storage is 100% secure.

---

## 6. Your Rights and Controls

Because the App does not use accounts or server-side profiles, you control your data mainly through your device:

- **Delete data**:
  - delete individual expense entries inside the App;
  - clear the App’s data via Android settings  
    (Settings → Apps → FuelCheck Sumy → Storage → Clear data);
  - uninstall the App (this removes all local data).

- **Control analytics and ads**:
  - limit personalized ads in your Google account and device settings (limit ad tracking);
  - disable backup for the App in your device settings if desired.

If you have questions about data or want more details, you can contact me at:  
**viashmadev@gmail.com**

---

## 7. Children’s Privacy

The App is not directed to children under 13 and is not intended for use by them. I do not knowingly collect information from children. If you believe a child has provided any information through the App, please contact me to have it removed.

---

## 8. Changes to This Policy

I may update this Privacy Policy from time to time. The latest version will always be available at the link provided in the App’s listing on Google Play.

By continuing to use the App after changes take effect, you agree to the updated Policy.

---

## 9. Contact

If you have any questions about this Privacy Policy or data processing in the App, please contact:

- Email: **viashmadev@gmail.com**
