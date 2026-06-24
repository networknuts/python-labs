## Part 1: Working with Strings

### Task 1: Create Simple Strings

Create a Python file named:

```bash
strings_practice.py
```

Inside the file, create the following variables:

```python
name = "Rahul"
course = "Python for DevOps"
city = "Delhi"
```

Print all three variables.

Expected output:

```text
Rahul
Python for DevOps
Delhi
```

---

### Task 2: Combine Strings

Create two variables:

```python
first_name = "Aryan"
last_name = "Srivastava"
```

Join them together and print the full name.

Expected output:

```text
Aryan Srivastava
```

---

### Task 3: String Length

Create a variable:

```python
message = "Python is powerful"
```

Print the length of the string using `len()`.

Expected output:

```text
18
```

---

## Part 2: Print Formatting

### Task 4: Print Multiple Values

Create the following variables:

```python
name = "Neha"
age = 22
course = "DevOps"
```

Print the output in this format:

```text
My name is Neha. I am 22 years old. I am learning DevOps.
```

---

### Task 5: Use f-string Formatting

Using f-string formatting, print the following sentence:

```text
Student Rahul is learning Python.
```

Use these variables:

```python
student = "Rahul"
language = "Python"
```

---

### Task 6: Use `.format()` Method

Create these variables:

```python
server = "web01"
ip = "192.168.1.10"
```

Print the sentence using `.format()`:

```text
Server web01 has IP address 192.168.1.10
```

---

### Task 7: Print DevOps Style Output

Create the following variables:

```python
service = "nginx"
status = "running"
port = 80
```

Print this output using f-string:

```text
Service nginx is running on port 80
```

---

## Part 3: String Indexing

### Task 8: Access Characters Using Positive Indexing

Create a variable:

```python
word = "Python"
```

Print:

```python
word[0]
word[1]
word[2]
```

Expected output:

```text
P
y
t
```

---

### Task 9: Access Characters Using Negative Indexing

Using the same variable:

```python
word = "Python"
```

Print:

```python
word[-1]
word[-2]
word[-3]
```

Expected output:

```text
n
o
h
```

---

### Task 10: First and Last Character

Create a variable:

```python
tool = "Kubernetes"
```

Print the first and last character.

Expected output:

```text
First character: K
Last character: s
```

---

## Part 4: String Slicing

### Task 11: Basic Slicing

Create a variable:

```python
language = "Python"
```

Print:

```python
language[0:2]
language[2:6]
language[:3]
language[3:]
```

Expected output:

```text
Py
thon
Pyt
hon
```

---

### Task 12: Slice a DevOps String

Create a variable:

```python
server_name = "prod-web-server-01"
```

Print only:

```text
prod
web
server
01
```

Hint: Use string slicing.

---

### Task 13: Reverse a String

Create a variable:

```python
word = "Linux"
```

Reverse it using slicing.

Expected output:

```text
xuniL
```

---

## Part 5: Practice Problems

### Task 14: Extract Username from Email

Create a variable:

```python
email = "student@example.com"
```

Print only:

```text
student
```

---

### Task 15: Extract Domain from Email

Using the same variable:

```python
email = "student@example.com"
```

Print only:

```text
example.com
```

---

### Task 16: Extract File Extension

Create a variable:

```python
filename = "backup.tar.gz"
```

Print only:

```text
gz
```

---

### Task 17: Format Server Information

Create these variables:

```python
hostname = "app-server-01"
ip_address = "10.0.0.15"
environment = "production"
```

Print the output:

```text
Hostname: app-server-01
IP Address: 10.0.0.15
Environment: production
```

---

### Task 18: Indexing Challenge

Create a variable:

```python
platform = "OpenShift"
```

Print the following characters using indexing:

```text
O
S
t
```

---

## Part 6: Mini Assignment

### Task 19: Student Profile Generator

Create the following variables:

```python
name = "Amit"
course = "Python for DevOps"
duration = "2 months"
institute = "Network Nuts"
```

Print the profile in this format:

```text
Student Profile
---------------
Name: Amit
Course: Python for DevOps
Duration: 2 months
Institute: Network Nuts
```

---

### Task 20: Infrastructure Name Parser

Create a variable:

```python
resource = "prod-db-server-02"
```

Using indexing or slicing, print:

```text
Environment: prod
Service: db
Type: server
Number: 02
```

---

## Bonus Tasks

### Bonus Task 1: Count Characters

Create a variable:

```python
sentence = "Python is used in DevOps automation"
```

Print the total number of characters.

---

### Bonus Task 2: Print Initials

Create these variables:

```python
first_name = "Rohit"
middle_name = "Kumar"
last_name = "Sharma"
```

Print the initials:

```text
R.K.S
```

---

### Bonus Task 3: Mask Email

Create a variable:

```python
email = "aryan@example.com"
```

Print the masked email:

```text
a****@example.com
```

---
