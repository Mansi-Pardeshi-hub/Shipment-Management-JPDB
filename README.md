# Shipment Management System

## Description
This is a web-based micro-project developed to manage shipment logistics data. It provides an intuitive user interface to store, retrieve, and update shipment details seamlessly. The application is built using HTML, CSS (Bootstrap), JavaScript, and relies on **JsonPowerDB** as the serverless backend database to handle data operations securely and efficiently.

## Table of Contents
- [Description](#description)
- [Illustrations](#illustrations)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Release History](#release-history)
- [Sources](#sources)

## Illustrations
*(Note to evaluator: The user interface is a clean, Bootstrap-styled form containing fields for Shipment No, Description, Source, Destination, Shipping Date, and Expected Delivery Date with dynamic Save, Update, and Reset controls).*

## Scope of Functionalities
- **Data Insertion (Create):** Users can add new shipment records by entering details like Shipment-No, Description, Source, Destination, Shipping-Date, and Expected-Delivery-Date.
- **Data Retrieval (Read):** Automatically fetches and fills existing shipment details when a registered Shipment-No is entered.
- **Data Modification (Update):** Allows users to modify existing shipment details (except the primary key) and update them directly in the database.
- **Form Reset:** Clears all fields and resets the form to its default disabled state.

## Examples of Use
1. Open the `index.html` file in any modern web browser.
2. Enter a new **Shipment No** and press `Tab`. The form will unlock to allow data entry.
3. Fill in the shipment details and click **Save** to insert the data into the database.
4. To update, enter an existing **Shipment No** and press `Tab`. The data will load automatically. Make changes and click **Update**.

## Project Status
**Completed** - The micro-project meets all the requirements and is functioning as expected.

## Benefits of using JsonPowerDB
JsonPowerDB (JPDB) is a highly efficient and developer-friendly database. Key benefits observed during this project include:
- **Serverless & Schema-Free:** No need to pre-define database tables or schemas. The database (`DELIVERY-DB`) and relation (`SHIPMENT-TABLE`) were created dynamically upon the first data insertion.
- **Nimble & Fast:** JPDB is built on an innovative architecture making read/write operations incredibly fast compared to traditional RDBMS.
- **REST API Support:** It provides easy-to-use Web-services APIs, eliminating the need for complex server-side scripting (like PHP or Node.js). Everything was handled directly via frontend JavaScript.
- **Multi-Mode:** Functions perfectly as an In-Memory Database, Real-time Database, and Document Store simultaneously.

## Release History
* **v1.0.0 (Current)** - Initial release of the Shipment Management System.
  - Implemented Create, Read, and Update functionalities using JsonPowerDB `jpdb-commons.js` library.

## Sources
- [JsonPowerDB Official Documentation](http://login2explore.com/work/tech/jpdb/api.html)
- Bootstrap 3.4.1 Documentation
- jQuery Library
