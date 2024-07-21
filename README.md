# Inventory System

This Python and Tkinter application helps you manage your inventory. You can add, view, search, and remove products with ease.

## Functionality

- **Authentication**: Users must log in using a username and password (initially set to admin\admin).
- **Product Management**: Add new items specifying their name, quantity, and cost. View existing items, search by name, and delete items from the list.
- **User-Friendly Interface**: The application features a straightforward Tkinter-based user interface.

## Requirements

- Python 3.x
- tkinter (included with Python installation)
- SQLite3 (included with Python installation)
- mysql.connector (optional; currently disabled)

## Limitations

- **Basic Security**: Authentication relies solely on a username and password. It lacks advanced security measures such as data hashing or additional identity verification.
- **Single User**: The system is designed for single-user use. To support multiple users concurrently or over a network, significant modifications would be required.
