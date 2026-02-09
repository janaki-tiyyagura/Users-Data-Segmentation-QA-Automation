
## 🧪 Braze Segment QA Automation Tool

A **Python-based, GUI-driven automation tool** designed to perform **end-to-end quality assurance for Braze segmentation logic**. This project eliminates manual review errors by programmatically extracting segment definitions via the **Braze Segment API** and validating every attribute, operator, and value against standardized rules.

### 🚩 Problem

Manual QA of Braze segments often fails to detect **hidden data quality issues** such as:

* Leading or trailing spaces
* Inconsistent letter casing
* Mismatched attribute values
* Missing mandatory inclusion or exclusion conditions

These issues are visually hard to detect in the UI but can lead to **incorrect audience targeting, inaccurate segment counts, campaign failures, and compliance risks**.

### ✅ Solution

This tool automates segment validation by:

* Extracting complete segment logic directly from Braze using APIs
* Validating all attributes, operators, and values
* Detecting hidden formatting issues and logic gaps
* Enforcing standardized campaign and country-specific rules
* Generating clear output files highlighting errors for quick remediation

A simple **GUI interface** enables non-technical users to run QA checks easily.

### 📈 Impact

* **70–80% reduction** in manual QA effort
* **90%+ reduction** in campaign errors caused by segmentation issues
* Faster campaign launches with fewer rework cycles
* Improved data accuracy, consistency, and compliance across regions
* Scalable QA process that supports increasing campaign volume without additional effort

### 🛠️ Tech Stack

* **Python**
* **Braze Segment API**
* Data validation and rule-based automation
* GUI-based interface for ease of use

### 🎯 Use Case

Ideal for **campaign managers, QA analysts, and marketing operations teams** who need reliable, repeatable, and scalable validation of segmentation logic before campaign execution.

