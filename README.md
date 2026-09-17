# k6 Load Testing Project

This project demonstrates basic performance and load testing using Grafana k6.

## Test Scenario

- 10 Virtual Users (VUs)
- Test duration: 10 seconds
- HTTP GET request
- HTTP status code validation
- Performance metrics analysis

## Tools Used

- Grafana k6
- JavaScript
- Visual Studio Code
- Git
- GitHub

## Test Script

The `script.js` file sends HTTP requests to the k6 test website and verifies that the response status is `200`.

## Run the Test

Make sure k6 is installed, then run:

```bash
k6 run script.js
