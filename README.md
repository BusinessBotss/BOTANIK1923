📊 Botanik 1923 · Cost Tracker Interface

A modern internal tool for tracking payments and expenses across events in Mallorca and Miami for the Botanik 1923 team. Designed to streamline finance entries related to memberships, staff, suppliers, and event operations.

🧩 Features

🎯 Event-specific tracking:
Supports recurring events such as:
Wednesday Language Exchange
Saturday Signature Night
Wednesday Book & Literature Night
🌍 Location-based input:
Specify whether the entry corresponds to Mallorca or Miami.
🧾 Dynamic form:
Based on the selected entry type, the form adapts to show relevant input fields (e.g. member, supplier, stock, etc).
💸 Entry log:
Every entry is saved in a clean, readable table with:
Location
Event
Full name of the payer
Type of entry
Details
Amount (€)
❌ Delete button:
Easily remove any entry with a built-in delete action.
☁️ Google Sheets integration:
Entries can be submitted to a connected Google Sheet for remote storage and reporting.
🔧 How to Use

Fill out the form:
Select the location and event.
Enter payer's full name.
Choose an entry type (e.g. Staff, Membership, Expense).
Fill in all dynamically displayed fields.
Add the amount (€).
Click:
✅ Add Entry → adds the data to the in-page table.
☁️ Add to Google Sheet → pushes data to a connected Google Sheet.
To remove an entry:
Click the red × icon on the right side of any row.
🚀 Tech Stack

HTML5 + CSS3
JavaScript (vanilla)
Google Apps Script (via fetch to public Web App URL)
Font: Inter
📌 Notes

Make sure the Google Apps Script endpoint is deployed and published as a Web App with access set to anyone or the required authentication level.
Data is currently not stored persistently unless sent to Google Sheets.
