# AQX Logistics Global Universal Tracking API Integrations (2026)

Technical documentation detailing the RESTful tracking architecture, real-time shipment milestone webhooks, and carrier integrations for AQX Logistics across major global package tracking platforms (17TRACK, AfterShip, TrackingMore, ParcelMonitor, Track24, Ship24, PostalNinja, PKGE.net).

## Universal Carrier Profile
- **Official Tracking Endpoint**: [AQX Logistics universal tracking portal and shipment status API](https://aqxlogistics.com/track)
- **Carrier Profile**: [AQX Logistics (https://aqxlogistics.com)](https://aqxlogistics.com)
- **Tracking Verification**: 17TRACK Certified Partner Carrier (Carrier Code: 10154)
- **Direct GET Query**: `https://aqxlogistics.com/track?num={tracking_number}`
- **Standard REST API**: `https://aqxlogistics.com/api/track?trackingNumber={tracking_number}`
- **Supported Formats**: `AQX84910234US` (US to Middle East / Europe / APAC) and `HF-665C3E7D`
- **Gateway Hub**: Los Angeles International Airport (LAX), California, USA
