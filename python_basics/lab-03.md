# Python Basics Task List  
## Topic: For Loops and File Input/Output

## Part 1: Basic For Loops

### Task 1: Loop Through a List

Create a Python file named:

```bash
loops_files_practice.py
```

Inside the file, create a list:

```python
tools = ["Linux", "Python", "Git", "Docker", "Kubernetes"]
```

Use a `for` loop to print each tool.

Expected output:

```text
Linux
Python
Git
Docker
Kubernetes
```

---

### Task 2: Loop Through a String

Create a variable:

```python
word = "Python"
```

Use a `for` loop to print each character.

Expected output:

```text
P
y
t
h
o
n
```

---

### Task 3: Loop Through a Tuple

Create a tuple:

```python
ports = (22, 80, 443, 3306)
```

Use a `for` loop to print each port.

Expected output:

```text
22
80
443
3306
```

---

### Task 4: Loop Using `range()`

Use `range()` to print numbers from `1` to `5`.

Expected output:

```text
1
2
3
4
5
```

---

### Task 5: Print Even Numbers

Use a `for` loop and `range()` to print even numbers from `2` to `10`.

Expected output:

```text
2
4
6
8
10
```

---

### Task 6: Print Multiplication Table

Create a variable:

```python
number = 5
```

Use a `for` loop to print the multiplication table of `5`.

Expected output:

```text
5 x 1 = 5
5 x 2 = 10
5 x 3 = 15
5 x 4 = 20
5 x 5 = 25
5 x 6 = 30
5 x 7 = 35
5 x 8 = 40
5 x 9 = 45
5 x 10 = 50
```

---

## Part 2: For Loops with Lists

### Task 7: Print Server Names

Create a list:

```python
servers = ["web01", "web02", "db01", "cache01"]
```

Use a `for` loop to print:

```text
Checking server: web01
Checking server: web02
Checking server: db01
Checking server: cache01
```

---

### Task 8: Count Items in a List Manually

Create a list:

```python
users = ["alice", "bob", "charlie", "david"]
```

Use a `for` loop to count the number of users without using `len()`.

Expected output:

```text
Total users: 4
```

---

### Task 9: Create a New List Using a Loop

Create a list:

```python
packages = ["nginx", "mysql", "python3"]
```

Create a new list where each package name has this prefix:

```text
install-
```

Expected output:

```text
['install-nginx', 'install-mysql', 'install-python3']
```

---

### Task 10: Filter Running Services

Create a list:

```python
services = ["nginx:running", "mysql:stopped", "docker:running", "redis:stopped"]
```

Use a `for` loop to print only running services.

Expected output:

```text
nginx is running
docker is running
```

Hint: Use `in` or string splitting.

---

### Task 11: Find a Specific Item

Create a list:

```python
installed_packages = ["nginx", "python3", "git", "docker"]
```

Check if `"docker"` is installed using a `for` loop.

Expected output:

```text
docker is installed
```

---

### Task 12: Loop with Index

Create a list:

```python
tasks = ["Update system", "Install nginx", "Start service", "Check status"]
```

Print task numbers with task names.

Expected output:

```text
Task 1: Update system
Task 2: Install nginx
Task 3: Start service
Task 4: Check status
```

Hint: Use `enumerate()`.

---

## Part 3: For Loops with Dictionaries

### Task 13: Loop Through Dictionary Keys

Create a dictionary:

```python
server = {
    "hostname": "web01",
    "ip": "192.168.1.10",
    "os": "Ubuntu",
    "status": "running"
}
```

Use a `for` loop to print all keys.

Expected output:

```text
hostname
ip
os
status
```

---

### Task 14: Loop Through Dictionary Values

Using the same dictionary, print all values.

Expected output:

```text
web01
192.168.1.10
Ubuntu
running
```

---

### Task 15: Loop Through Dictionary Items

Using the same dictionary, print both keys and values.

Expected output:

```text
hostname: web01
ip: 192.168.1.10
os: Ubuntu
status: running
```

---

### Task 16: Print Environment Variables

Create a dictionary:

```python
env_vars = {
    "APP_ENV": "production",
    "APP_PORT": "8000",
    "DEBUG": "false"
}
```

Use a `for` loop to print:

```text
APP_ENV=production
APP_PORT=8000
DEBUG=false
```

---

### Task 17: List of Dictionaries

Create a list of dictionaries:

```python
servers = [
    {"name": "web01", "status": "running"},
    {"name": "db01", "status": "stopped"},
    {"name": "cache01", "status": "running"}
]
```

Use a `for` loop to print only running servers.

Expected output:

```text
web01 is running
cache01 is running
```

---

### Task 18: Kubernetes Pod Status Check

Create a list of dictionaries:

```python
pods = [
    {"name": "frontend", "status": "Running"},
    {"name": "backend", "status": "CrashLoopBackOff"},
    {"name": "database", "status": "Running"}
]
```

Use a `for` loop to print only pods that are not running.

Expected output:

```text
backend is in CrashLoopBackOff state
```

---

## Part 4: Basic File Writing

### Task 19: Write Text to a File

Create a file named `output.txt` using Python.

Write this line into the file:

```text
Python file handling practice
```

Expected result:

A new file named `output.txt` should be created with the above text.

---

### Task 20: Write Multiple Lines to a File

Create a list:

```python
lines = ["Linux\n", "Python\n", "Docker\n", "Kubernetes\n"]
```

Write all lines to a file named:

```text
tools.txt
```

Expected file content:

```text
Linux
Python
Docker
Kubernetes
```

---

### Task 21: Write Server Names to a File

Create a list:

```python
servers = ["web01", "web02", "db01", "cache01"]
```

Use a `for` loop to write each server name into a file named:

```text
servers.txt
```

Expected file content:

```text
web01
web02
db01
cache01
```

---

### Task 22: Append Text to a File

Create a file named:

```text
log.txt
```

Write this line first:

```text
Application started
```

Then append this line:

```text
Application running
```

Expected file content:

```text
Application started
Application running
```

---

### Task 23: Append Multiple Log Entries

Create a list:

```python
logs = [
    "nginx started",
    "mysql started",
    "docker started"
]
```

Append all log entries into a file named:

```text
service.log
```

Expected file content:

```text
nginx started
mysql started
docker started
```

---

## Part 5: Basic File Reading

### Task 24: Read a Complete File

Create a file named `message.txt` manually and add this content:

```text
Welcome to Python file handling
```

Use Python to read and print the complete file content.

Expected output:

```text
Welcome to Python file handling
```

---

### Task 25: Read File Line by Line

Create a file named `names.txt` manually with this content:

```text
Amit
Neha
Rahul
Priya
```

Use a `for` loop to read the file line by line and print each name.

Expected output:

```text
Amit
Neha
Rahul
Priya
```

---

### Task 26: Read Server List from a File

Create a file named `server_list.txt` manually:

```text
web01
web02
db01
cache01
```

Read the file and print:

```text
Checking server: web01
Checking server: web02
Checking server: db01
Checking server: cache01
```

---

### Task 27: Count Lines in a File

Create a file named `users.txt`:

```text
alice
bob
charlie
david
```

Use a `for` loop to count the number of lines.

Expected output:

```text
Total users: 4
```

---

### Task 28: Search Text in a File

Create a file named `services.txt`:

```text
nginx running
mysql stopped
docker running
redis stopped
```

Use Python to find lines that contain the word `"running"`.

Expected output:

```text
nginx running
docker running
```

---

## Part 6: File Processing with Loops

### Task 29: Create a Basic Report File

Create a list:

```python
servers = ["web01", "web02", "db01"]
```

Write a report file named `server_report.txt` with this content:

```text
Server Report
-------------
Server: web01
Server: web02
Server: db01
```

---

### Task 30: Convert List Data into CSV Format

Create a list of dictionaries:

```python
students = [
    {"name": "Amit", "course": "Python"},
    {"name": "Neha", "course": "DevOps"},
    {"name": "Rahul", "course": "Linux"}
]
```

Write this data into a file named `students.csv`.

Expected file content:

```text
name,course
Amit,Python
Neha,DevOps
Rahul,Linux
```

---

### Task 31: Read CSV-Like File

Create a file named `inventory.csv`:

```text
server,ip,role
web01,10.0.0.11,web
db01,10.0.0.12,database
cache01,10.0.0.13,cache
```

Read the file and print each server in this format:

```text
Server web01 has IP 10.0.0.11 and role web
Server db01 has IP 10.0.0.12 and role database
Server cache01 has IP 10.0.0.13 and role cache
```

Hint: Use `split(",")`.

---

### Task 32: Create a Failed Service Report

Create a file named `service_status.txt`:

```text
nginx running
mysql stopped
docker running
redis stopped
```

Read the file and create a new file named `failed_services.txt`.

The new file should contain only stopped services:

```text
mysql stopped
redis stopped
```

---

## Part 7: Mini Assignment

### Task 33: Student Attendance File

Create a list:

```python
students = ["Amit", "Neha", "Rahul", "Priya"]
```

Create a file named `attendance.txt`.

Write the attendance in this format:

```text
Attendance Report
-----------------
Amit: Present
Neha: Present
Rahul: Present
Priya: Present
```

---

### Task 34: DevOps Service Checker

Create a file named `services_input.txt` with this content:

```text
nginx running
mysql stopped
docker running
jenkins stopped
redis running
```

Read the file and create two files:

```text
running_services.txt
stopped_services.txt
```

Expected `running_services.txt`:

```text
nginx running
docker running
redis running
```

Expected `stopped_services.txt`:

```text
mysql stopped
jenkins stopped
```

---

### Task 35: Simple Inventory Generator

Create a list of dictionaries:

```python
inventory = [
    {"name": "web01", "ip": "10.0.1.10", "role": "web"},
    {"name": "db01", "ip": "10.0.1.20", "role": "database"},
    {"name": "cache01", "ip": "10.0.1.30", "role": "cache"}
]
```

Use a `for` loop to create a file named `inventory_report.txt`.

Expected file content:

```text
Infrastructure Inventory Report
-------------------------------
Server Name: web01
IP Address: 10.0.1.10
Role: web

Server Name: db01
IP Address: 10.0.1.20
Role: database

Server Name: cache01
IP Address: 10.0.1.30
Role: cache
```

---

## Bonus Tasks

### Bonus Task 1: Read and Number Lines

Create a file named `commands.txt`:

```text
ls
pwd
df -h
free -m
```

Read the file and print each command with a number.

Expected output:

```text
1. ls
2. pwd
3. df -h
4. free -m
```

Hint: Use `enumerate()`.

---

### Bonus Task 2: Count Running and Stopped Services

Create a file named `status.txt`:

```text
nginx running
mysql stopped
docker running
redis stopped
jenkins stopped
```

Read the file and print:

```text
Running services: 2
Stopped services: 3
```

---

### Bonus Task 3: Generate Shell Script File

Create a list:

```python
commands = [
    "sudo apt update",
    "sudo apt install nginx -y",
    "sudo systemctl start nginx",
    "sudo systemctl enable nginx"
]
```

Write these commands into a file named `install_nginx.sh`.

Expected file content:

```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
```

---

### Bonus Task 4: Create Kubernetes Pod Report

Create a list of dictionaries:

```python
pods = [
    {"name": "frontend", "namespace": "default", "status": "Running"},
    {"name": "backend", "namespace": "default", "status": "CrashLoopBackOff"},
    {"name": "database", "namespace": "prod", "status": "Running"},
    {"name": "worker", "namespace": "prod", "status": "ImagePullBackOff"}
]
```

Create a file named `pod_report.txt`.

Expected file content:

```text
Kubernetes Pod Report
---------------------
Pod: frontend
Namespace: default
Status: Running

Pod: backend
Namespace: default
Status: CrashLoopBackOff

Pod: database
Namespace: prod
Status: Running

Pod: worker
Namespace: prod
Status: ImagePullBackOff
```

---

### Bonus Task 5: Create Failed Pod Report

Using the same pod list from Bonus Task 4, create another file named:

```text
failed_pods.txt
```

The file should contain only pods that are not in `Running` state.

Expected file content:

```text
backend default CrashLoopBackOff
worker prod ImagePullBackOff
```

---


