# Technical Challenge: Custom Fields and Entities Feature for CRM

## Objective

<hr>

Design a database schema that enables the dynamic addition of custom fields to leads within a CRM system. Each lead should be capable of having multiple custom fields associated with it, facilitating the storage of diverse and adaptable information unique to each lead. The schema should efficiently support the operations for creating, updating, retrieving, and deleting leads and their custom fields.

## Requirements

<hr>

#### Lead Entity Design

- Design the foundational structure for a lead entity, including standard fields such as lead ID, name, email, phone number, and other essential information deemed necessary.

#### Custom Fields Structure

- Implement a flexible design that permits the dynamic addition of custom fields to a lead. These custom fields may include a variety of data types, such as text, numbers, dates, and boolean.
- Ensure the system can manage a potentially extensive number of custom fields per lead without significant degradation in performance.

#### Relationships and Integrity

- Clearly delineate the relationships between leads and custom fields, ensuring data integrity and efficient data access patterns.
- The schema should be designed to allow adding or removing a custom field or altering a lead without necessitating extensive schema modifications.

#### Scalability and Performance

- Optimize the schema for read and write operations, considering frequent access and modification of lead data and associated custom fields in the CRM system.
- Explore indexing strategies or other database optimizations to enhance performance, especially for querying leads by their custom fields.

#### Flexibility and Future Growth

- The design should be sufficiently flexible to accommodate future requirements, such as the introduction of new data types for custom fields or the integration with other CRM features.
- Contemplate the impact of new features, like searching or filtering leads based on custom field values, on the design.

## Deliverables

<hr>

- Detailed database schema diagrams illustrating the structure of the lead entity, custom fields, and their relationships.
- SQL script(s) for creating the necessary tables, constraints, and relationships in a relational database management system (RDBMS).

This challenge aims to evaluate candidates' abilities to create a flexible, scalable, and efficient database design that accommodates complex and dynamic requirements typical in CRM systems.
