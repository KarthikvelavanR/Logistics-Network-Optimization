# Logistics & Distribution Network Performance Optimization

## Project Overview

This project focuses on analyzing and optimizing logistics and distribution network performance using Power BI. The dashboard was developed to help management monitor operational efficiency, delivery performance, SLA compliance, transportation costs, and hub-level operations through centralized business intelligence reporting.

The solution enables logistics stakeholders to identify operational bottlenecks, monitor high-cost routes, improve shipment delivery performance, and support data-driven decision-making.

---

# Business Problem Statement

A national logistics company operating multiple distribution hubs and delivery routes across the country was facing several operational challenges:

* Rising delivery delays and SLA breaches
* Increasing transportation and warehousing costs
* Uneven hub performance across regions
* Poor visibility into shipment profitability and operational efficiency
* Difficulty identifying operational bottlenecks and high-cost delivery routes

Although operational data was available across multiple systems, management lacked a centralized analytics platform to monitor performance and improve logistics operations.

---

# Business Objectives

The primary objectives of this project were to:

1. Improve on-time delivery performance
2. Reduce transportation and operational costs
3. Identify underperforming hubs and routes
4. Optimize hub capacity utilization
5. Improve SLA compliance monitoring
6. Enable data-driven operational decision-making

---

# Datasets Used

## 1. Warehouse Hub Dataset

Contains operational information related to logistics hubs:

* Hub location and region
* Hub type and operational status
* Warehouse size and capacity
* Shipment throughput metrics
* Hub operating costs
* Infrastructure utilization analysis

---

## 2. Shipments Dataset

Primary transactional dataset containing shipment-level operations:

* Shipment and delivery dates
* Origin and destination cities
* Distance traveled and transport mode
* Fuel and logistics operational costs
* SLA status and customer information
* Delivery performance tracking

---

## 3. Shipment Type Dataset

Contains shipment category and cargo handling details:

* Cargo category and subcategory
* Handling costs
* Risk level classification
* Temperature control requirements
* SLA delivery duration
* Cargo-specific operational analysis

---

# Data Preparation & Modeling

The datasets were cleaned, transformed, and modeled in Power BI to ensure reliable analytics and reporting.

## Data Cleaning Steps

* Removed approximately 200 blank rows from the Shipments dataset
* Converted Shipment Date and Delivery Date using locale settings:

  * English (United Kingdom)
* Verified and standardized data types across datasets
* Created relationships between fact and dimension tables
* Implemented star schema modeling

---

## Calendar Table Implementation

* Created a dedicated Calendar table
* Established relationship with shipment dates
* Marked the calendar as the official Date Table in Power BI

### Validation Included

* Unique dates
* Continuous date range
* No duplicate values
* Valid date datatype

This enabled accurate time intelligence and trend analysis.

---

# Dashboard KPIs

The dashboard includes the following operational KPIs:

* Total Shipments
* On-Time Delivery %
* SLA Breach Count
* Total Logistics Cost
* Cost per Shipment
* Average Delivery Time
* Cost Efficiency Index
* Capacity Utilization %
* Fuel Cost
* Hub Operating Cost
* Delivery Days
* Average Shipment Cost

---

# Dashboard Pages

## 1. Executive Overview

Provides centralized monitoring of:

* Operational KPIs
* SLA compliance trends
* Shipment distribution
* City-wise SLA breaches
* Logistics efficiency indicators

---

## 2. Hub Performance Analysis

Analyzes:

* Shipment volume by hub
* SLA breaches by hub
* Hub operating costs
* Hub-level operational efficiency

---

## 3. Route & Delivery Analysis

Monitors:

* Delay-prone delivery routes
* Average delivery time by region
* Distance vs logistics cost relationship
* SLA performance trends

---

## 4. Cost & Profitability Analysis

Evaluates:

* High-cost delivery routes
* Fuel cost by transport mode
* Cost per shipment by hub and route
* Transportation cost efficiency

---

# Key Insights

* Certain hubs handled significantly higher shipment volumes, indicating operational dependency on major distribution centers.
* Specific delivery routes consistently recorded higher SLA breaches.
* Longer shipment distances showed higher operational costs and increased delay tendency.
* Transportation costs varied significantly across transport modes and delivery routes.
* Fuel costs contributed heavily to overall logistics operational expenditure.

---


# Features Implemented

* Interactive dashboard navigation
* KPI cards and operational analytics
* Slicers and dynamic filtering
* Bookmark-based interactions
* Reset filter functionality
* Time intelligence analysis
* Multi-page dashboard architecture

---

# Business Impact

The Power BI dashboard provides:

* Centralized operational visibility
* Improved SLA monitoring
* Better transportation cost analysis
* Faster identification of operational bottlenecks
* Improved decision-making through interactive analytics
* Enhanced logistics performance monitoring

---



# Author

## Karthik Velavan

