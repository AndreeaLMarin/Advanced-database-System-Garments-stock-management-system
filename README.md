# Advanced-database-System-Garments-stock-management-system
Garments Management System

This is the Garments Management System — a Tkinter-based desktop software that allows garment inventory management using an SQLite database. It allows adding/updating/removing/viewing record of garment in little time and visualizing in real-time the stock level using matplot.

Features

✅ Garments management — CRUD (Add, Clear, Update, Delete) the garments table.

✅ Persistent data storage through SQLite database integration.

✅ Tkinter GUI with user-friendly interface.

✅ Matplotlib visualization  monitors garment stock levels.

✅ Buttons created using CustomTkinter to better UI design.



System Requirements

Before running the application, ensure you have the following installed:

Python 3.7 or later

SQLite3 (built into Python)

Required Python libraries:

tkinter

customtkinter

matplotlib

sqlite3

To install missing libraries, run:

pip install customtkinter matplotlib sqlite3




Run the Application:

python main.py

This will launch the Garments Management System GUI.

Select the Garments table from the drop-sown list





How the Application Works

Main Functionalities

Insert a Garment: Insert Garment ID, Garment Name, Category, Availability and Price, then click Add.

Update a Garment — Select a record from the Table, make changes to different fields, and click on Update.

Remove a garment: Select a record and click the Delete button to delete it.

Clear Input Fields: Click Clear to reset the input fields.

Garment stock: A bar chart updates garment stock in real time.

View: Under View drop-down, switch between Garments, Orders and Sales tables.


