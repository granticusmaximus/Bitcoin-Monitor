React Bitcoin Monitor

An app that monitors changes in the Bitcoin Price Index (BPI).

By default, the BPI will be shown for USD, GBP, and EUR. Optionally, one can select ones own currency to display in addition to the 3 aforementioned currencies.

Bitcoin Monitor makes use of the CoinDesk Bitcoin Price Index API. Go here for more price information by CoinDesk.

Go here for live demo.

The application is composed of the following components:

Header - A heading that displays application title

BitcoinMonitor - The primary (root) component that manages state for itself and all underlying components. It is also responsible for connecting to BitcoinService to retrieve Bitcoin Price Index data.

Display - Displays the Bitcoin Price Index data for USD, GBP, and EUR as a default. Also allows one to select a currency as a fourth price to monitor.

Indicator - Used by the Display component, it displays an indicator that shows if the current price is up or down from previous price.

Component Diagram Component Diagram

The following services are used to obtain Bitcoin Price Index data:

BitcoinService

A wrapper that is responsible for integrating with the CoinDesk Bitcoin Price Index API

Service Diagram react-bitcoin-monitor-services

Features:

Show BPI for USD, GBP, and EUR
Show BPI for any custom selected currency
This project also demonstrates:

a typcial React project layout structure
babel setup and configuration
webpack setup and configuration
eslint setup and configuration
SCSS setup and configuration
CoinDesk Bitcoin Price Index API integration
Screenshots:

...	...
	
	
Developed With

Visual Studio Code - A source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring
Node.js - Javascript runtime
React - A javascript library for building user interfaces
Babel - A transpiler for javascript
Webpack - A module bundler
SCSS - A css metalanguage
Bootstrap 4 - Bootstrap is an open source toolkit for developing with HTML, CSS, and JS
Axios - Promise based HTTP client for the browser and node.js
CoinDesk Bitcoin Price Index API - Provides Bitcoin Price Index data
Surge - Static web publishing for Front-End Developers
