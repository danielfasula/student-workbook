# Journal Day 2 - Week 11

## Daily Journal Questions


1. What is the difference between a primary key and a foreign key

  A Primary Key is what makes an item in a table unique from the others in that table. Foreign Keys are keys adopted from other tables used to identify a property in a different table.

2. What is an Alias?

  An alias is declared following the first instance of the written table name and can be used in place of writting out the full table name.

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

`
CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorpatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
`
SELECT * FROM doctorpatients dp
INNER JOIN patients p ON p.id = dp.patientId
INNER JOIN doctors d ON d.id = dp.doctorId;

## Project

https://github.com/danielfasula/contractor