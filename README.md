# <picture><img src="https://ga-curriculum.github.io/universal-resources-internal/ga-logos/ga-red-cog-128x128.png" alt="" height="48" align="absmiddle"></picture> Intro to SQL IV - SQlite PetDB

## About

This module provides a hands-on introduction to database creation and management using Python's sqlite3 library. It is designed to guide you through building a simple database to store information about pets, learning how to interact with it using CRUD (Create, Read, Update, Delete) operations via a custom application programming interface (API).	
						

## Content

| Micro-Lesson | Est. Delivery Time | Learning Objectives |
| ------ |:------------------:| ------ |
| [01 - Introduction to SQLite3 & CRUD (Slides)](./01-Intro%20Slides/README.md) | 30 | • Define SQLite3 and explain its advantages for file-based database applications<br>• Understand CRUD operations (Create, Read, Update, Delete) in database management<br>• Learn how CRUD operations map to SQL commands (INSERT, SELECT, UPDATE, DELETE) |
| [02 - Building Your First SQLite Database - Code Along](./02-creating-sqlite3-db-and-crud/README.md) | 30 | • Generate a quick, file-based SQL database with SQLite3<br>• Carry out table creation, row insertion (C), entry manipulation (U), and entry deletion (D) using SQL |
| [03 - Object-Oriented Database API - Solo Exercise](./03-crud-api/README.md) | 40 | Use OOP to create a full API that interacts with your SQL database |
| **Total content delivery time** | 100 | *Not including breaks and 'bring it home at the end'*|
| **Total module delivery time** | 120 | *Including a suggested 15 min break and 5 min to bring it home at the end*|

## Course Structure

### Introduction Phase
- Located in `01-Intro Slides/` directory
- Combined introduction to SQLite3 and CRUD operations
- Single slide deck covering both topics
- Learning objectives:
  - Understanding SQLite3 advantages
  - CRUD operations in database management
  - Mapping CRUD to SQL commands

### Hands-on Learning Path

#### Phase 1: Database Creation & CRUD Basics
- Directory: `creating-sqlite3-db-and-crud/`
- Focus: Learning to create and manipulate SQLite databases
- Key activities:
  - Creating a new SQLite database
  - Implementing basic CRUD operations
- Solution file: `petdb-create-crud-solutions.ipynb`

#### Phase 2: API Development
- Directory: `crud-api/`
- Focus: Building an Object-Oriented API
- Key activities:
  - Creating a Python API to interact with the database
  - Implementing CRUD operations through the API
- Solution file: `petdb-api-crud-solutions.ipynb`

## References

📖 [Reference Materials](./references/README.md)

## Internal

### Prerequisites

- Basic Python programming knowledge
- Fundamental understanding of SQL concepts
- Understanding of database basics

### Solution code

Microlesson 02: Creating your own Sqlite3 db and implementing CRUD operations [petdb-create-crud-solutions.ipynb](./microlesson-02/petdb-create-crud-solutions.ipynb)

Microlesson 03: Implementing CRUD operations with an API [petdb-api-crud-solutions.ipynb](./microlesson-03/petdb-api-crud-solutions.ipynb)  

**Find a 👾 bug 👾 or have suggestions? [Let us know](https://ga-curriculum.github.io/universal-resources-internal/module-feedback.html)!**
