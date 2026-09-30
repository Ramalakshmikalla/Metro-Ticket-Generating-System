# 🚇 Metro Ticket Generating System – ServiceNow

A digital metro ticket booking and QR-based ticket generation system developed using **ServiceNow**. The project automates the metro ticket booking process by allowing users to select stations, enter passenger and journey details, calculate fares automatically, and generate digital tickets with QR codes.

## 📌 Project Overview

The **Metro Ticket Generating System** is designed to simplify and automate the metro ticket booking process using **ServiceNow Service Catalog and automation features**.

Users can book metro tickets through a user-friendly catalog form by providing their source station, destination station, passenger details, and journey type.

The system validates the entered information, calculates the fare based on the selected stations, journey type, and number of passengers, and generates a digital ticket with a QR code.

## ⭐ Key Features

* 🚉 Source and destination station selection
* 🎟️ Digital metro ticket booking
* 💵 Automatic fare calculation
* 👥 Passenger-based fare calculation
* 🔁 Single and return journey support
* ✔️ Mandatory field validation
* 👀 Conditional field visibility
* ⚙️ Automated field mapping and population
* 📲 QR code-based digital ticket generation
* 🔐 ServiceNow-based data and access management

## 🧰 Technologies Used

| Technology                    | Usage                                   |
| ----------------------------- | --------------------------------------- |
| **ServiceNow**                | Main development platform               |
| **Service Catalog**           | Metro ticket booking form               |
| **Catalog Client Scripts**    | Client-side validation and calculations |
| **UI Policies**               | Conditional field visibility            |
| **JavaScript**                | Business logic and automation           |
| **Flow Designer**             | Workflow and ticket processing          |
| **Process Automation Engine** | Automated field mapping                 |
| **Business Rules**            | Server-side automation                  |
| **QR Code Generation**        | Digital ticket generation               |

## 🔄 System Workflow

```text
        👤 User
          ↓
   📝 Metro Ticket Form
          ↓
 🚉 Select Source & Destination
          ↓
 👥 Enter Passenger Details
          ↓
 🔁 Select Journey Type
          ↓
    💵 Fare Calculation
          ↓
      ✔️ Validation
          ↓
    📤 Order Submission
          ↓
    ⚙️ Ticket Processing
          ↓
    🎟️ Ticket Generation
          ↓
   📲 QR Code Generation
          ↓
   🎫 Digital Metro Ticket
```

## 📚 Project Documentation

The complete project documentation covers:

* Requirement Analysis and Planning
* ServiceNow Application Configuration
* Service Catalog Development
* Catalog Client Scripts
* UI Policies
* Flow Designer Configuration
* Business Rules
* Data Handling and Security
* QA Testing
* Deployment and Configuration
* Technical Blueprint
* Setup Manual
* Future Enhancements

The detailed project report and setup documentation are available in the **Documentation** folder.

## 🧪 Testing

The system was tested with different metro ticket booking scenarios, including:

* Valid source and destination selection
* Same source and destination validation
* Passenger count validation
* Single journey fare calculation
* Return journey fare calculation
* Mandatory field validation
* Conditional field visibility
* Ticket generation
* QR code generation

## 🔒 Security and Access Management

The project uses ServiceNow platform capabilities to manage application data and user access.

Security-related configurations include:

* Role-based access
* Table and record access controls
* Service Catalog access
* User authentication
* Controlled access to application data

## 🎯 Project Objectives

The main objectives of this project are to:

1. Digitize the metro ticket booking process.
2. Reduce manual ticket booking effort.
3. Automate fare calculation.
4. Provide a simple digital ticketing experience.
5. Generate QR-based tickets for easy verification.
6. Improve data validation and accuracy.
7. Use ServiceNow automation to streamline ticket processing.

## 🚀 Future Enhancements

The system can be further enhanced with:

* 💳 Online payment integration
* 🚫 Ticket cancellation and refund
* 🚆 Real-time train information
* 📱 Mobile application integration
* 📖 Ticket booking history
* 🚇 Multiple metro-line support
* 📍 Real-time station information
* 💰 Dynamic fare updates
* 📊 Admin dashboard and reporting

## 👩‍💻 Project Completed By

**Veera Venkata Rama Lakshmi Kalla**

### 📄 Project Type

**ServiceNow Academic**

## 📝 Conclusion

The **Metro Ticket Generating System** demonstrates how ServiceNow can be used to develop an automated digital ticketing solution. By combining Service Catalog, JavaScript, UI Policies, Flow Designer, Business Rules, and QR code generation, the project provides an automated process from ticket booking to digital ticket generation.

The system provides a foundation for future enhancements such as online payments, ticket cancellation, real-time metro information, mobile application integration, and advanced reporting.
