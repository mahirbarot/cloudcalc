# Cloud Pricing Calculator

**Description:**
A JavaScript script to calculate compute prices on Azure, AWS, and GCP based on region, instance type, and usage hours.

**Installation:**
* No specific installation required.
* Ensure you have Node.js and npm (or yarn) installed.

**Usage:**
```javascript
const calculateComputePrice = require('./yourScript.js');

const azurePrice = calculateComputePrice('azure', 'us-east', 'Standard_D2s_v3', 720);
console.log('Azure price:', azurePrice);
