# Python Script – IP Access Control File Cleaner

## 📄 Description
A Python script that removes outdated or disallowed IP addresses from a file controlling access to protected systems.

## 🧰 Tools & Skills
- Tools: Python 3, File handling
- Skills: Automation, list filtering, scripting for security

## 📝 Core Functionality

```python
for ip in old_list:
    if ip not in removal_list:
        updated_list.append(ip)
