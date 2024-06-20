﻿# otp-generator-js

## OTP Generation Example

### Generating OTPs using JavaScript

```javascript
const generateOtp = require('generateOtp');

generateOtp(digit,'secretKey')


// Generate a 6-digit OTP with a custom secret key
console.log(generateOtp(6, 'myCustomSecretKey'));

// Generate a 4-digit OTP with the default secret key
console.log(generateOtp(4));
