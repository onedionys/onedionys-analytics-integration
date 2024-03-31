<h1 align="center">Welcome to One Dionys - Analytics Integration! 👋 </h1>

<p align="center">Functions for integrating analytics tools such as Google Analytics into web applications. 💖 </p>

<p align="center">
<img src="https://img.shields.io/github/contributors/onedionys/onedionys-analytics-integration?style=flat-square">
<img src="https://img.shields.io/github/issues/onedionys/onedionys-analytics-integration?style=flat-square">
<img src="https://img.shields.io/github/stars/onedionys/onedionys-analytics-integration?style=flat-square"> 
<img src="https://img.shields.io/github/forks/onedionys/onedionys-analytics-integration?style=flat-square">
<img src="https://img.shields.io/github/last-commit/onedionys/onedionys-analytics-integration.svg?style=flat-square">
<img src="https://img.shields.io/github/languages/code-size/onedionys/onedionys-analytics-integration?style=flat-square">
<img src="https://img.shields.io/github/license/onedionys/onedionys-analytics-integration?style=flat-square">
</p>

## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const { trackEvent } = require('./src/analytics');

// Example usage
const eventName = 'Button Click';
const eventData = { buttonId: 'btnSubmit', page: 'homepage' };

// Send event data to analytics service
trackEvent(eventName, eventData);
```

#### Explanation

* This package provides a simple way to integrate analytics tracking into your application. The trackEvent function allows you to send custom event data to your analytics service, such as Google Analytics, to track user interactions, button clicks, page views, etc.

#### Return Value

* The trackEvent function does not return any value directly. It sends the event data to the analytics service. In the example provided above, it logs the event data to the console for demonstration purposes. However, in a real-world scenario, it would send the data to the configured analytics service.

## 📆 Release Date

* v1.0.0 : 08 March 2024
* v1.0.1 : 11 March 2024
* v4.0.0 : 11 March 2024
* v4.0.1 : 13 March 2024
* v4.0.2 : 18 March 2024
* v5.0.0 : 31 March 2024

## 🧑 Author

* Facebook : <a href="https://www.facebook.com/theonedionys"> Oned Ionys</a>
* Instagram : <a href="https://www.instagram.com/onedionys/"> @onedionys</a>
* Twitter : <a href="https://twitter.com/onedionys"> @onedionys</a>
* LinkedIn :  <a href="https://www.linkedin.com/in/onedionys/"> @onedionys</a>

## 📝 License

* Copyright © 2024 One Dionys
* **One Dionys - Analytics Integration is an open source project licensed under the MIT license**

## ☕️ Suppport & Donation

Love One Dionys - Analytics Integration? Support this project by donating or sharing with others in need.

<a href="https://www.buymeacoffee.com/onedionys"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"/> </a>

**Made with ❤️ One Dionys**
