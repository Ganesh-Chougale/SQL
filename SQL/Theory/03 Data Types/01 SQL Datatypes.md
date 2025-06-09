### 🔢 **Numeric Types**

| Data Type         | Description            | Size (Bytes) | Range (Approx.)                                |
| ----------------- | ---------------------- | ------------ | ---------------------------------------------- |
| `TINYINT`         | Very small integer     | 1            | 0 to 255 (unsigned)                            |
| `SMALLINT`        | Small integer          | 2            | –32,768 to 32,767                              |
| `MEDIUMINT`       | Medium integer (MySQL) | 3            | –8,388,608 to 8,388,607                        |
| `INT` / `INTEGER` | Standard integer       | 4            | –2,147,483,648 to 2,147,483,647                |
| `BIGINT`          | Large integer          | 8            | ±9.22 quintillion                              |
| `DECIMAL(p,s)`    | Exact fixed-point      | Varies       | Depends on precision & scale (up to 65 digits) |
| `FLOAT(p)`        | Approximate float      | 4            | \~±3.4E38                                      |
| `DOUBLE`          | High precision float   | 8            | \~±1.7E308                                     |
| `NUMERIC(p,s)`    | Exact fixed-point      | Varies       | Same as DECIMAL                                |

---

### 🔤 **Character/String Types**

| Data Type     | Description             | Size (Bytes)        | Limit                        |
| ------------- | ----------------------- | ------------------- | ---------------------------- |
| `CHAR(n)`     | Fixed-length string     | 1 × n               | Max 255 chars                |
| `VARCHAR(n)`  | Variable-length string  | 1 + n               | Max 65,535 bytes (row size)  |
| `TEXT`        | Large text              | Up to 65,535        | \~64 KB                      |
| `TINYTEXT`    | Small text              | Up to 255           | 255 bytes                    |
| `MEDIUMTEXT`  | Medium text             | Up to 16,777,215    | \~16 MB                      |
| `LONGTEXT`    | Very large text         | Up to 4,294,967,295 | \~4 GB                       |
| `NCHAR(n)`    | Fixed Unicode string    | 2 × n               | Max 4,000 chars (SQL Server) |
| `NVARCHAR(n)` | Var Unicode string      | 2 × n               | Max 4,000 or `MAX` (\~2 GB)  |
| `NTEXT`       | Deprecated Unicode text | Varies              | Max 2 GB                     |

---

### 📅 **Date & Time Types**

| Data Type   | Description | Size (Bytes) | Example Format        |
| ----------- | ----------- | ------------ | --------------------- |
| `DATE`      | Date only   | 3            | `YYYY-MM-DD`          |
| `TIME`      | Time only   | 3            | `HH:MM:SS`            |
| `DATETIME`  | Date + Time | 8            | `YYYY-MM-DD HH:MM:SS` |
| `TIMESTAMP` | Date + Time | 4            | Auto updated          |
| `YEAR`      | Year        | 1            | `YYYY`                |

---

### ✅ **Boolean Type**

| Data Type | Description | Size (Bytes) | Range               |
| --------- | ----------- | ------------ | ------------------- |
| `BOOLEAN` | True/False  | 1 (usually)  | 0 (FALSE), 1 (TRUE) |

---

### 📦 **Binary Types**

| Data Type      | Description            | Size (Bytes)        | Limit            |
| -------------- | ---------------------- | ------------------- | ---------------- |
| `BINARY(n)`    | Fixed binary           | n                   | Max 255 bytes    |
| `VARBINARY(n)` | Variable binary        | 1 + n               | Max 65,535 bytes |
| `TINYBLOB`     | Small binary object    | Up to 255           | 255 bytes        |
| `BLOB`         | Standard binary object | Up to 65,535        | 64 KB            |
| `MEDIUMBLOB`   | Medium binary object   | Up to 16,777,215    | \~16 MB          |
| `LONGBLOB`     | Large binary object    | Up to 4,294,967,295 | \~4 GB           |

---

### 📎 **Special / Other Types**

| Data Type  | Description              | Size (Bytes) | Limit                     |
| ---------- | ------------------------ | ------------ | ------------------------- |
| `ENUM`     | One value from list      | 1–2          | Max 65,535 values (MySQL) |
| `SET`      | Multiple values from set | Up to 8      | Up to 64 items            |
| `JSON`     | JSON data (MySQL, PGSQL) | Up to 1 GB   | Structured JSON text      |
| `UUID`     | Unique identifier        | 16           | Fixed 36-char string      |
| `XML`      | XML data (SQL Server)    | Varies       | DBMS-specific             |
| `GEOMETRY` | Spatial data             | Varies       | \~65 KB (MySQL)           |

---