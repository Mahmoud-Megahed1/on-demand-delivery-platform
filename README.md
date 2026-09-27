# 🚚 On-Demand Multi-Vendor Delivery & Logistics Platform

A robust, enterprise-grade on-demand logistics and delivery management platform built with **Laravel**, **Firebase Real-Time Tracking**, **MongoDB**, and multi-gateway payment processing (**Stripe & PayPal**).

## 🚀 Architectural Highlights

- **🏢 Multi-Vendor Architecture**: Comprehensive merchant, driver, customer, and central administrator portal.
- **📍 Real-Time Dispatch & Live Tracking**: Real-time order status dispatch and courier location broadcasting via Google Cloud Firestore & Firebase.
- **💳 Multi-Gateway Payment Processing**: Integrated with Stripe, PayPal Checkout SDK, and local vendor payout automations.
- **📊 Advanced Analytics Dashboard**: Real-time business metrics, revenue summaries, and high-performance querying with Yajra DataTables.
- **🗄️ Hybrid Database Architecture**: Relational consistency for financial transactions combined with MongoDB for unstructured logging and high-throughput events.

## 🛠️ Tech Stack & Dependencies

- **Backend Framework**: Laravel 12 / PHP 8.2+
- **Authentication**: Laravel Sanctum API Tokens
- **Real-Time & Cloud Services**: Google Cloud Firestore, Firebase PHP SDK
- **Databases**: MySQL (Transactions) & MongoDB (Activity & Realtime Logs)
- **Payment Gateways**: Stripe PHP SDK, PayPal Checkout SDK, Paydunya
- **Media Management**: Spatie Laravel MediaLibrary

## 📦 Core Modules

1. **Vendor Portal**: Menu/product catalog management, branch timing, discount promotions, and order acceptance.
2. **Courier / Driver System**: Dynamic order assignment, geofenced order dispatching, and vendor bank account payouts.
3. **Admin Control Center**: System settings, commission rates, financial statements, and customer support.

## 📄 License
This repository is open-sourced under the MIT License.