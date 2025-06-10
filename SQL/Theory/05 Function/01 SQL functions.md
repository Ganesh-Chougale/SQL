## 🔹 1. **String Functions**

| Function      | Example                             | Output            |
| ------------- | ----------------------------------- | ----------------- |
| `CONCAT()`    | `CONCAT('Ganesh', ' ', 'Chougale')` | `Ganesh Chougale` |
| `LENGTH()`    | `LENGTH('hello')`                   | `5`               |
| `LOWER()`     | `LOWER('HELLO')`                    | `hello`           |
| `UPPER()`     | `UPPER('hello')`                    | `HELLO`           |
| `LTRIM()`     | `LTRIM('  hello')`                  | `hello`           |
| `RTRIM()`     | `RTRIM('hello  ')`                  | `hello`           |
| `TRIM()`      | `TRIM('  hello  ')`                 | `hello`           |
| `REPLACE()`   | `REPLACE('cycle', 'c', 'm')`        | `mymle`           |
| `SUBSTRING()` | `SUBSTRING('abcdef', 2, 3)`         | `bcd`             |
| `INSTR()`     | `INSTR('Ganesh', 'sh')`             | `5`               |
| `LEFT()`      | `LEFT('Ganesh', 3)`                 | `Gan`             |
| `RIGHT()`     | `RIGHT('Ganesh', 3)`                | `esh`             |
| `REPEAT()`    | `REPEAT('Hi', 3)`                   | `HiHiHi`          |
| `REVERSE()`   | `REVERSE('abc')`                    | `cba`             |

---

## 🔹 2. **Numeric Functions**

| Function               | Example           | Output             |
| ---------------------- | ----------------- | ------------------ |
| `ABS()`                | `ABS(-10)`        | `10`               |
| `CEIL()` / `CEILING()` | `CEIL(4.2)`       | `5`                |
| `FLOOR()`              | `FLOOR(4.8)`      | `4`                |
| `ROUND()`              | `ROUND(4.567, 2)` | `4.57`             |
| `MOD()`                | `MOD(10, 3)`      | `1`                |
| `POWER()`              | `POWER(2, 3)`     | `8`                |
| `SQRT()`               | `SQRT(16)`        | `4`                |
| `RAND()`               | `RAND()`          | Random between 0-1 |
| `SIGN()`               | `SIGN(-25)`       | `-1`               |

---

## 🔹 3. **Date/Time Functions**

| Function      | Example                                | Output                |
| ------------- | -------------------------------------- | --------------------- |
| `NOW()`       | `NOW()`                                | `2025-06-09 14:30:00` |
| `CURDATE()`   | `CURDATE()`                            | `2025-06-09`          |
| `CURTIME()`   | `CURTIME()`                            | `14:30:00`            |
| `DAY()`       | `DAY('2025-06-09')`                    | `9`                   |
| `MONTH()`     | `MONTH('2025-06-09')`                  | `6`                   |
| `YEAR()`      | `YEAR('2025-06-09')`                   | `2025`                |
| `DAYNAME()`   | `DAYNAME('2025-06-09')`                | `Monday`              |
| `MONTHNAME()` | `MONTHNAME('2025-06-09')`              | `June`                |
| `HOUR()`      | `HOUR(NOW())`                          | `14`                  |
| `MINUTE()`    | `MINUTE(NOW())`                        | `30`                  |
| `SECOND()`    | `SECOND(NOW())`                        | `00`                  |
| `DATEDIFF()`  | `DATEDIFF('2025-06-09', '2025-01-01')` | `160`                 |
| `ADDDATE()`   | `ADDDATE('2025-06-09', 5)`             | `2025-06-14`          |
| `SUBDATE()`   | `SUBDATE('2025-06-09', 5)`             | `2025-06-04`          |

---

## 🔹 4. **System / Info Functions**

| Function           | Example            | Output                    |
| ------------------ | ------------------ | ------------------------- |
| `USER()`           | `USER()`           | e.g., `root@localhost`    |
| `VERSION()`        | `VERSION()`        | e.g., `8.0.36`            |
| `DATABASE()`       | `DATABASE()`       | Current DB name           |
| `LAST_INSERT_ID()` | `LAST_INSERT_ID()` | Last auto-increment value |

---

## 🔹 5. **Type Conversion Functions**

| Function    | Example                       | Output       |
| ----------- | ----------------------------- | ------------ |
| `CAST()`    | `CAST('123' AS UNSIGNED)`     | `123`        |
| `CONVERT()` | `CONVERT('2025-06-09', DATE)` | `2025-06-09` |

---