# On-Demand Multi-Vendor Delivery and Logistics Platform

A multi-vendor logistics and delivery management platform built with Laravel, Firebase real-time status broadcasting, MongoDB, and payment gateway integrations including Stripe and PayPal.

## Architectural Highlights

- **Multi-Vendor Architecture**: Central administration portal with isolated vendor storefronts, courier dispatching, and customer order tracking.
- **Real-Time Dispatching**: Order lifecycle broadcasting and location dispatching using Google Cloud Firestore and Firebase PHP SDK.
- **Payment Processing**: Integrated Stripe PHP SDK and PayPal Checkout SDK for checkout payments and automated vendor payouts.
- **Hybrid Data Persistence**: Relational MySQL schema for financial transactions paired with MongoDB for high-throughput activity logs.
- **Analytics Dashboard**: Operational metrics, order fulfillment reports, and data querying powered by Yajra DataTables.

## Technology Stack

- **Backend Framework**: Laravel 12 / PHP 8.2+
- **API Authentication**: Laravel Sanctum
- **Real-Time Infrastructure**: Google Cloud Firestore, Firebase PHP SDK
- **Databases**: MySQL (Transactions) and MongoDB (Activity & Realtime Logs)
- **Payment Providers**: Stripe PHP, PayPal Checkout SDK, Paydunya
- **Media Management**: Spatie Laravel MediaLibrary

## Core Modules

1. **Vendor Portal**: Product catalogs, opening hours, pricing, and order acceptance workflows.
2. **Courier Dispatching**: Dynamic order assignment, geofenced routing, and driver payout management.
3. **Administration Console**: Commission rates, settlement reports, platform configurations, and dispute resolution.

## License

This repository is open-source under the MIT License.