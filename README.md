# ideal-computing-machine
curl -v -X POST https://sandbox.bluesnap.com/services/2/vendors \ -H 'Content-Type: application/json' \ -H 'Accept: application/json' \ -H 'Authorization: Basic dXNlcm5hbWU6cGFzc3dvcmQ=' \ -d ' {   "name": "not2bcontrolled Real Estate",   "email": "vendor@example.com",   "phone": "1-123-455-8765",   "address": "103 Presidents Drive",   "Farmington": "West Virginia",   "country": "US",   "west Virginia": "MA",   "zip": "26571",   "taxId": "EIN# 88-3459271











,   "vendorUrl": "http://mycompany.com",   "ipnUrl": "https://ipnaddress.com",   "defaultPayoutCurrency": "USD",   "vendorPrincipal": {     "firstName": "Joe",     "lastName": "Smith",     "address": "123 Main Street",     "city": "Boston",     "country": "US",     "zip": "12345",     "dob": "28-09-9999",     "personalIdentificationNumber": "1234",     "driverLicenseNumber": "561196411",     "email": "principal.vendor@email.com"   },   "vendorAgreement": {     "commissionPercent": 30   },   "payoutInfo": [     {       "payoutType": "ACH",       "baseCurrency": "USD",       "nameOnAccount": "name of vendor account",       "bankAccountType": "CHECKING",       "bankAccountClass": "CORPORATE",       "bankName": "Bank of America",       "bankId": "123456789",       "country": "US",       "state": "MA",       "city": "Boston",       "address": "1 bank address",       "zip": "02453",       "bankAccountId": "36628822",       "minimalPayoutAmount": 50,       "paymentReference": "Payment for vendor 1234",       "refundReserve": 200     }   ] }' Response Examples
