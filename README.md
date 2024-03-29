![image](https://github.com/IjaasMohamed/OOP-PROJECT-Inventory-Management/assets/96341377/7cf00ca4-c2e6-4d2a-9ec3-d8656d82c545)

# Inventory-CRUD: Java Banana Stock Control 🍌📈

Welcome to **Inventory-CRUD**, where we manage goods with the finesse of a banana juggler! 🎪🍌

## What's the Peel? 🍌

Inventory-CRUD is a robust Java application that dances with MySQL to handle your stock like a fruity maestro. Whether you're tracking pineapples or paperclips, we've got you covered! 🍍📎

## Features 🍌

- **CRUD Operations**: Create, Read, Update, and Delete—our bananas do it all! 🍌📝
- **Banana-Proof Database**: Our MySQL backend is as sturdy as a gorilla's grip on a bunch of ripe bananas. 🦍🍌
- **Versioned API**: Get yer inventory v1.0.0 right here! 🍌🔢
- **Banana Metrics**:
    - `/inventory/`: Returns all values in the inventory (caution: no limit, so don't slip on a banana peel if the DB gets too large). 🍌📊
    - `/inventory/:upc`: Fetch a specific product by UPC (like peeling a banana). 🍌🔍
    - `/inventory/:upc/quantity`: Increment or decrement the quantity for a particular UPC (because bananas multiply, you know). 🍌🔄

## Installation 🍌

1. Peel open your terminal.
2. Compile the Java code: `javac InventoryCRUD.java`
3. Execute the program: `java InventoryCRUD`
4. MySQL setup:
    - Create a database named `inventory`.
    - Import the provided SQL schema: `mysql -u username -p inventory < inventory.sql`

## Example Usage 🍌

### Get All Inventory Items

