# 🌦️ Salesforce Weather Dashboard

A weather information application built using Salesforce Lightning Web Components (LWC), Apex, and the OpenWeather API. It allows users to search for a city and view its current weather information directly in Salesforce.

## 🚀 Features

- Search weather information by city name
- Display current temperature and feels-like temperature
- Show humidity and atmospheric pressure
- Display minimum and maximum temperatures
- Responsive dashboard interface
- Retrieve weather data through Apex HTTP callouts
- Built using Salesforce Lightning Web Components

## 🛠️ Technologies Used

- Salesforce Platform
- Apex
- Lightning Web Components (LWC)
- JavaScript
- HTML and CSS
- OpenWeather API
- Salesforce Remote Site Settings

## 🏗️ Project Structure

```text
Salesforce-Weather-Dashboard/
├── config/
├── force-app/
│   └── main/
│       └── default/
│           ├── classes/
│           │   ├── WeatherDetailsClass.cls
│           │   └── WeatherDetailsClass.cls-meta.xml
│           └── lwc/
│               └── weatherScreen/
│                   ├── weatherScreen.html
│                   ├── weatherScreen.js
│                   ├── weatherScreen.css
│                   └── weatherScreen.js-meta.xml
├── manifest/
├── scripts/
├── README.md
├── package.json
└── sfdx-project.json
