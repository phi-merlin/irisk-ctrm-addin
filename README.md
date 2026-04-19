## IRISK CTRM Add-In

**Internal Commodity Trading & Risk Infrastructure**
**(Excel/VBA Front-End | Centralized Risk & Trade Database)**

---

## Overview

IRISK CTRM is a proprietary, lightweight trading and risk infrastructure designed for desk-level deployment within Excel.

It provides a unified environment for:

* Trade lifecycle management
* Real-time P&L and exposure tracking
* Risk measurement and stress testing
* Desk-level reporting and analytics

The system is engineered to replicate core CTRM functionality without reliance on heavyweight enterprise platforms.

---

## Core Capabilities

### Trade Capture & Lifecycle Management

* Full trade booking (physical + derivatives)
* Multi-asset commodity coverage
* Structured pricing models
* Hedge linkage and allocation logic
* External trade import (brokers / confirmations)

---

### Valuation & P&L Engine

* Mark-to-market valuation engine
* Real-time P&L computation at deal and portfolio level
* Accrual handling and cost allocation
* Scenario-based valuation shifts

---

### Risk Analytics

* Position aggregation across books and portfolios
* Sensitivities (Greeks / risk factors)
* Historical and parametric VaR
* Exposure metrics (PFE, stress scenarios)

---

### Reporting Layer

* Fully Excel-native reporting environment
* Embedded pricing and risk functions (VBA UDF layer)
* Automated dashboards for desk monitoring
* Ad-hoc analytical flexibility for traders

---

## Architecture

* **Front End:** Excel VBA Add-In (trader interface layer)
* **Core Data Layer:** Centralized relational database
* **Integration Layer:** VBA services, Excel UDFs, data connectors
* **Market Data:** External feeds + manual inputs

---

## Design Principles

* **Desk-centric design:** optimized for trader workflows
* **Low latency analytics:** immediate recalculation of exposure and P&L
* **Transparency:** fully auditable trade and valuation logic
* **Modularity:** components can be extended independently
* **Cost-efficient architecture:** avoids enterprise CTRM overhead

---

## Deployment Context

* Trading desks (commodity derivatives / physicals)
* Risk and valuation teams
* Structured trading environments
* Hybrid front-to-middle office workflows

---

## Strategic Intent

IRISK CTRM is intended as a **desk-owned system-of-record and analytics layer**, bridging execution, risk, and reporting within a single Excel-native environment.

It is designed to:

* Reduce dependency on enterprise CTRM systems
* Increase trader autonomy in analytics
* Improve speed of decision-making at desk level
