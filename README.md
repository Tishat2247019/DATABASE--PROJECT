# Orphanage Management System Database

<img src="https://github.com/user-attachments/assets/1e22663e-50e9-4e0a-966a-5a7f75e0b695">


A comprehensive database solution for managing orphanage operations in a post-war scenario (2122). Developed as part of the Introduction to Database course at American International University - Bangladesh.

## Features

- **Complete Entity Management**: Track all orphanage entities including orphans, staff, donors, adopters
- **Normalized Design**: Fully normalized to 3NF to minimize redundancy
- **Complex Relationships**: Models real-world relationships between entities
- **Query Support**: Pre-tested SQL queries for common operations
- **Data Integrity**: Comprehensive constraints ensure data validity

## Database Schema

### Key Tables
- `ORPHANAGE`: Core orphanage information
- `ORPHAN`: Details about children in care
- `STAFF`: Caretaker information
- `O_COLLECTOR`: Orphan collection team
- `DONOR`: Contributor records
- `ADOPTER`: Family adoption records
- `SCHOOL`: Educational system details

### Relationships
- One-to-many: Orphanage to Orphans, Staff, etc.
- Many-to-many: Teachers to Orphans (through teaching relationship)

## Installation

1. Clone the repository
2. Execute the SQL scripts in order:
