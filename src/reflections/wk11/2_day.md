## Day 2

### MySQL 

#### 1. What is the difference between a primary key and a foreign key

```A primary key is a unique identifier for each row that always exists. Whereas a foreign key is a relationship between two tables.```

#### 2. What is an Alias?

```An alias is an extra name or identifier for simplification or reference.```

#### 3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

```sql
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

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
```

```sql
SELECT 
    dp.*,
    p.*,
FROM doctorpatients dp
    JOIN patients p
        ON p.id = dp.patientId
WHERE dp.doctorId = @doctorId
```
