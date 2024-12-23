# testdos-burp-extension
testdos is a Burp Suite extension for monitoring HTTP response times. Set a custom threshold (in seconds) to receive alerts for responses exceeding the limit. Works only on in-scope targets, minimizing noise. Ideal for security researchers and testers to detect slow responses and enhance performance monitoring


# testdos Burp Suite Extension

## Overview

`testdos` is a Burp Suite extension designed to monitor HTTP request-response times and alert you when response times exceed a user-defined threshold. This extension allows you to set a threshold in seconds, and it will issue an alert if the response time is greater than the specified threshold. It only operates on in-scope target domains.

## Features

- Set a threshold (in seconds) for HTTP request-response time.
- Alert when the response time exceeds the set threshold.
- Only monitor requests that are within the Burp Suite target scope.
- Simple GUI to input the threshold value.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/testdos-burp-extension.git
