### ⚙️ **Comparison Operators**

| Type             | Operator      | Description                      | Example                  |
| ---------------- | ------------- | -------------------------------- | ------------------------ |
| Equality         | `=`           | Equal to                         | `WHERE age = 25`         |
| Inequality       | `!=`          | Not equal to (MySQL, SQL Server) | `WHERE name != 'John'`   |
| Inequality       | `<>`          | Not equal to (standard SQL)      | `WHERE name <> 'John'`   |
| Greater Than     | `>`           | Greater than                     | `WHERE score > 90`       |
| Less Than        | `<`           | Less than                        | `WHERE score < 40`       |
| Greater or Equal | `>=`          | Greater than or equal            | `WHERE age >= 18`        |
| Less or Equal    | `<=`          | Less than or equal               | `WHERE age <= 65`        |
| NULL Check       | `IS NULL`     | Checks if value is NULL          | `WHERE email IS NULL`    |
| NOT NULL         | `IS NOT NULL` | Checks if value is NOT NULL      | `WHERE name IS NOT NULL` |

---

### 🔁 **Logical Operators**

| Type | Operator | Description          | Example                            |
| ---- | -------- | -------------------- | ---------------------------------- |
| AND  | `AND`    | Both conditions true | `WHERE age > 18 AND city = 'Pune'` |
| OR   | `OR`     | At least one true    | `WHERE score > 90 OR grade = 'A'`  |
| NOT  | `NOT`    | Reverses condition   | `WHERE NOT (status = 'active')`    |

---

### 🔍 **Pattern Matching**

| Type     | Operator   | Description             | Example                               |
| -------- | ---------- | ----------------------- | ------------------------------------- |
| LIKE     | `LIKE`     | Pattern match           | `WHERE name LIKE 'Gan%'`              |
| NOT LIKE | `NOT LIKE` | Pattern not matched     | `WHERE name NOT LIKE 'A%'`            |
| Wildcard | `%`        | Zero or more characters | `'A%'` matches "Alex", "Arun"         |
| Wildcard | `_`        | Exactly one character   | `'G_nesh'` matches "Ganesh", "Gonesh" |

---

### 🧮 **Arithmetic Operators**

| Type     | Operator | Description            | Example         |
| -------- | -------- | ---------------------- | --------------- |
| Addition | `+`      | Adds two values        | `SELECT 5 + 3`  |
| Subtract | `-`      | Subtracts values       | `SELECT 10 - 2` |
| Multiply | `*`      | Multiplies values      | `SELECT 4 * 2`  |
| Divide   | `/`      | Divides values         | `SELECT 10 / 2` |
| Modulo   | `%`      | Remainder (MySQL only) | `SELECT 10 % 3` |

---

### 📦 **Set Operators**

| Type        | Operator      | Description               | Example                             |
| ----------- | ------------- | ------------------------- | ----------------------------------- |
| IN          | `IN (...)`    | Matches any in list       | `WHERE age IN (25, 30, 35)`         |
| NOT IN      | `NOT IN`      | Doesn’t match any in list | `WHERE city NOT IN (...)`           |
| BETWEEN     | `BETWEEN`     | Range (inclusive)         | `WHERE age BETWEEN 18 AND 30`       |
| NOT BETWEEN | `NOT BETWEEN` | Outside range             | `WHERE score NOT BETWEEN 50 AND 80` |
| EXISTS      | `EXISTS`      | Subquery returns rows     | `WHERE EXISTS (SELECT...)`          |
| NOT EXISTS  | `NOT EXISTS`  | Subquery returns no rows  | `WHERE NOT EXISTS (SELECT...)`      |

---

### 🧠 **Bitwise Operators (MySQL, SQL Server)**

| Type        | Operator | Description         | Example         |            |     |
| ----------- | -------- | ------------------- | --------------- | ---------- | --- |
| AND         | `&`      | Bitwise AND         | `SELECT 5 & 3`  |            |     |
| OR          | \`       | \`                  | Bitwise OR      | \`SELECT 5 | 3\` |
| XOR         | `^`      | Bitwise XOR         | `SELECT 5 ^ 3`  |            |     |
| NOT         | `~`      | Bitwise NOT         | `SELECT ~5`     |            |     |
| Left Shift  | `<<`     | Bitwise left shift  | `SELECT 1 << 2` |            |     |
| Right Shift | `>>`     | Bitwise right shift | `SELECT 4 >> 1` |            |     |

---

### 🔄 **Other Special Symbols**

| Symbol | Meaning                       | Example                       |
| ------ | ----------------------------- | ----------------------------- |
| `*`    | Wildcard / all columns        | `SELECT * FROM users`         |
| `;`    | Statement terminator          | `SELECT * FROM users;`        |
| `()`   | Grouping / function arguments | `WHERE (age > 18 AND active)` |
| `,`    | Separator in lists            | `SELECT name, age`            |
| `.`    | Table/column access           | `users.name`                  |

---