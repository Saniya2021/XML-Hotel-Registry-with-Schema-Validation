# 🏨 Hotel Directory XML Schema Project

This repository contains the implementation of **CSE 445 — Assignment 4**, focusing on XML documents and schema validation. The goal of the project is to model a directory of hotels using XML, define and enforce rules with an XML Schema (XSD), and demonstrate how to validate XML against its schema — including handling both valid and invalid cases.

---

## 📂 Project Contents

The repository includes the following files:

- **Hotels.xml** – A valid XML file listing multiple hotels and their details.  
- **Hotels.xsd** – The XML Schema Definition that specifies the structure and rules for hotel entries.  
- **HotelsErrors.xml** – An XML file intentionally containing schema violations to test validation logic.

---

## 🎯 Project Overview

This project demonstrates the following XML concepts:

- 📄 Designing structured XML data with elements and attributes.  
- 📊 Defining an XML Schema (`.xsd`) to enforce data constraints and types.  
- ⚠️ Testing XML validation by comparing valid and invalid XML instances against the schema.  

These skills are essential for any work involving structured data exchange, configuration files, or data validation in modern software systems. 

---

## 🛠️ How to Use

1. **Explore the XML Structure**  
   Open `Hotels.xml` to view how hotels are represented using nested elements and attributes (e.g., hotel name, address, rating, etc.).

2. **Review the Schema Rules**  
   The `Hotels.xsd` file contains rules that define which elements and attributes are required or optional, element order, and expected data types.

3. **Validate Your XML Files**  
   Use any XML editor or online validator (such as https://www.xmlvalidation.com/) to test:
   - `Hotels.xml` should pass validation successfully.
   - `HotelsErrors.xml` should fail validation with one or more errors.

---

## 🧪 Recommended Tools

You can use a variety of tools to inspect and validate the XML and XSD:

- **Visual Studio Code** with XML extensions  
- **Notepad++** with XML Tools plugin  
- **Online XML validators**  
- **Browser/XSD-aware editors**

---

## 📌 Notes

- Ensure that the XML namespace and schema locations match when testing in external tools.  
- The invalid XML file helps demonstrate how schema validation can catch structural or data mistakes.

---

## 📚 Educational Purpose

This project reinforces key XML skills taught in CSE 445, including:

- XML hierarchy and attributes  
- XSD syntax and validation logic  
- Error handling and validation testing

Success in this assignment reflects a solid understanding of XML-based data modeling and validation — skills widely used in configuration files, web services, and data interchange formats.
