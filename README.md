# Async-Inn

Bulding a RESTful API hotel server that will increase the managmement of the assets in the hotel.

Increatse the ability to modify and manage rooms, amenities, and new hotel locations built.

## ERD Diagrams

### Entities

![image](./images/ERD-Entities.png)


### Tables

![image](./images/ERD-Models.png)

## Explanation

The hotel “Async Inn” has different location.

**Branch**: Represent different location of the hotel, every branch has multiple Rooms.

**Room**: Represent the rooms inside the hotel, every Room has multiple Amenity.

**Amenity**: Represent the amenities inside each Room.

***PK***: *The primary key is the column that contain values that uniquely identify each row in a table

***FK***: *The foreign key is a field in one table, that refers to the ***PK*** in another table. The table with the foreign key is called the child table, and the table with the primary key is called the referenced or parent table.*