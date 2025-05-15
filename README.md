Collection Manager App

Project Overview

The Collection Manager App is a Windows Forms application developed in C#. It is designed to help users manage and organize their personal collections, whether it be books, games, stamps, or any other collectible items. The app provides an intuitive user interface to add, edit, and delete items in the collection, ensuring easy management of personal belongings.

Features

User-Friendly Interface:

Main Form displays collection overview with navigation options.

Add/Edit Item Form allows users to input and modify item details.

Object-Oriented Design:

Utilizes a base class (CollectionItem) with subclasses for specific item types (e.g., Book, Game).

Data Management:

List structure to maintain collection items.

Save and load collections using file storage.

Data Validation and Error Handling:

Input validation for item details.

Try-catch blocks for safe file operations.

Project Structure

Main Form: Provides an overview of the collection and options for adding, editing, or deleting items.

Add/Edit Form: Allows users to enter item details such as name, date acquired, category, and specific attributes.

Custom Classes:

CollectionItem: Base class with common properties.

Book, Game, Stamp: Subclasses inheriting from CollectionItem with unique properties.

Database Management:

CollectionDB class for saving and loading collection data.

Technologies Used

Language: C#

Framework: .NET Windows Forms

IDE: Visual Studio 2022

Future Improvements

Enhance the user interface with advanced styling.

Add support for database storage (SQL Server).

Implement search and sort features for the collection.
