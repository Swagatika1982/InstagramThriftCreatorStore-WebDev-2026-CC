# InstagramThriftCreatorStore-WebDev-2026-CC
Database design project for an Instagram thrift store marketplace using ER diagram.
# Instagram Thrift Creator Store – ER Diagram

This repository contains the **ER diagram (Entity Relationship Diagram)** for an **Instagram-based thrift and handmade creator store platform**.

The purpose of this project is to design a clean and normalized database structure for an online social media thrift marketplace.

## Project Overview

The platform is designed to support:

* customers placing multiple orders
* products listed by sellers or creators
* unique thrift items
* reusable handmade inventory
* order and order item flow
* payment details
* shipping and address details
* product condition tracking

This project focuses only on **database design and business understanding**.

No frontend, backend, or SQL queries are included.

## Main Entities Included

* Customer
* Seller
* Product
* Category
* Inventory
* Orders
* Order Item
* Payment
* Shipment
* Shipping Address

## Key Design Considerations

* One customer can place multiple orders
* One order can contain multiple products
* Many-to-many relationship handled using `Order_Item`
* Supports both single unique pieces and reusable stock
* Payment and shipping are separated for better normalization
* Primary keys and foreign keys are clearly marked

## Diagram File

The ER diagram is included in this repository as:

* image / PNG export
  or
* PDF export
  or
* board link file

## Learning Goal

This project helped me practice:

* entity identification
* primary and foreign key design
* relationship cardinality
* normalization concepts
* real-world business flow thinking

This is a database design project created for learning SQL system design fundamentals.
