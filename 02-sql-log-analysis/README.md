# SQL Log Analysis – Detecting Suspicious Login Activity

## 📄 Description
This project analyzes historical login records using SQL queries to identify anomalous access patterns such as login attempts during off-hours and from foreign IPs.

## 🧰 Tools & Skills
- Tools: SQL Workbench / simulated DB
- Skills: Log analysis, data filtering, anomaly detection

## 🧪 Scenario
Analyst filters login data using time-based and geolocation conditions to detect non-standard behavior from employees.

## 📝 Sample Query

```sql
SELECT username, login_time, ip_address
FROM audit_logins
WHERE login_time BETWEEN '00:00' AND '06:00'
AND login_result = 'Failed';
