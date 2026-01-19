💳 Customer Billing System

A lightweight, console-based billing management application written in C, focused on simplicity, learning, and real-world usage.

🧩 What is This Project?

The Customer Billing System is a menu-driven C application that helps manage customer billing records. It is designed primarily for small shops, cafés, and departmental stores, while also serving as a learning project for students exploring C programming fundamentals.

This project emphasizes:

Structured programming

File handling

User-defined functions

Real-world problem solving using C

🚀 Key Capabilities

✔ Store customer personal and billing information✔ Automatically calculate balances and dues✔ Persist data using file storage✔ Search records quickly using customer name or phone number✔ Simple, text-based interface with no external libraries

🖥️ Program Flow

When you run the program, the following menu is displayed:

[1] Create New Customer Account
[2] Search Existing Account
[3] Exit Application

The system guides the user step-by-step based on the selected option.

🛠️ Core Components

🔹 Functions Used

input() → Captures customer and billing details

writefile() → Saves records permanently to a file

search() → Finds customer data by name or number

output() → Displays stored billing information

Each function is designed to perform a single responsibility, keeping the program modular and readable.

🧱 Data Organization

The project uses structures to group related data efficiently:

📅 Date Structure

Stores payment date:

Day

Month

Year

👤 Account Structure

Stores customer information:

Name

Address

Phone number

Paid amount

Due amount

Payment date

🧮 Billing Logic

Paid and due amounts are calculated internally

Outstanding dues are displayed as negative balances

No manual calculations required by the user

🧪 Technical Details

Item

Description

Language

C

Compiler

GCC

IDE

Code::Blocks

UI

Console (Text-based)

Graphics

❌ Not Used

🎯 Who Should Use This?

🎓 Students learning C programming

🧑‍💻 Beginners exploring file handling

🏪 Small businesses needing simple billing logic

📘 Academic mini-project submissions (with customization)

⚠️ Academic Integrity Notice:
Please modify and enhance this project before submitting it as coursework.

📦 Project Highlights

Unlimited customer record support

Efficient search functionality

Clean and understandable source code

Easy to extend with new features