## Part 1: Working with Lists

### Task 1: Create a Simple List

Create a Python file named:

```bash
data_structures_practice.py
```

Inside the file, create a list of Linux distributions:

```python
linux_distros = ["Ubuntu", "CentOS", "Debian", "Rocky Linux"]
```

Print the complete list.

Expected output:

```text
['Ubuntu', 'CentOS', 'Debian', 'Rocky Linux']
```

---

### Task 2: Access List Items

Using the same list:

```python
linux_distros = ["Ubuntu", "CentOS", "Debian", "Rocky Linux"]
```

Print the first item and the last item.

Expected output:

```text
First distro: Ubuntu
Last distro: Rocky Linux
```

---

### Task 3: List Indexing

Create a list:

```python
tools = ["Git", "Docker", "Kubernetes", "Jenkins", "Terraform"]
```

Print:

```text
Docker
Kubernetes
Terraform
```

Use list indexing.

---

### Task 4: Negative Indexing in Lists

Using the same list:

```python
tools = ["Git", "Docker", "Kubernetes", "Jenkins", "Terraform"]
```

Print the last two items using negative indexing.

Expected output:

```text
Jenkins
Terraform
```

---

### Task 5: Add Items to a List

Create a list:

```python
cloud_providers = ["AWS", "Azure"]
```

Add `"Google Cloud"` to the list.

Expected output:

```text
['AWS', 'Azure', 'Google Cloud']
```

---

### Task 6: Insert Item at a Specific Position

Create a list:

```python
services = ["nginx", "mysql", "redis"]
```

Insert `"apache"` at index `1`.

Expected output:

```text
['nginx', 'apache', 'mysql', 'redis']
```

---

### Task 7: Update a List Item

Create a list:

```python
environments = ["dev", "test", "stage"]
```

Update `"test"` to `"qa"`.

Expected output:

```text
['dev', 'qa', 'stage']
```

---

### Task 8: Remove an Item from a List

Create a list:

```python
packages = ["httpd", "nginx", "mysql", "php"]
```

Remove `"php"` from the list.

Expected output:

```text
['httpd', 'nginx', 'mysql']
```

---

### Task 9: List Length

Create a list:

```python
users = ["alice", "bob", "charlie", "david"]
```

Print the number of users using `len()`.

Expected output:

```text
Total users: 4
```

---

### Task 10: List Slicing

Create a list:

```python
servers = ["web01", "web02", "db01", "db02", "cache01"]
```

Print only the first three servers.

Expected output:

```text
['web01', 'web02', 'db01']
```

---

## Part 2: Working with Dictionaries

### Task 11: Create a Simple Dictionary

Create a dictionary:

```python
student = {
    "name": "Rahul",
    "course": "Python for DevOps",
    "city": "Delhi"
}
```

Print the complete dictionary.

---

### Task 12: Access Dictionary Values

Using the same dictionary:

```python
student = {
    "name": "Rahul",
    "course": "Python for DevOps",
    "city": "Delhi"
}
```

Print the output in this format:

```text
Name: Rahul
Course: Python for DevOps
City: Delhi
```

---

### Task 13: Create a Server Dictionary

Create a dictionary with the following information:

```python
server = {
    "hostname": "web01",
    "ip": "192.168.1.10",
    "os": "Ubuntu",
    "status": "running"
}
```

Print:

```text
Server web01 is running on 192.168.1.10
```

---

### Task 14: Update Dictionary Value

Using this dictionary:

```python
service = {
    "name": "nginx",
    "status": "stopped"
}
```

Update the status to `"running"`.

Expected output:

```text
{'name': 'nginx', 'status': 'running'}
```

---

### Task 15: Add a New Key to Dictionary

Create a dictionary:

```python
employee = {
    "name": "Amit",
    "role": "DevOps Engineer"
}
```

Add a new key called `"experience"` with value `"2 years"`.

Expected output:

```text
{'name': 'Amit', 'role': 'DevOps Engineer', 'experience': '2 years'}
```

---

### Task 16: Delete a Key from Dictionary

Create a dictionary:

```python
vm = {
    "name": "vm01",
    "cpu": 2,
    "memory": "4GB",
    "temporary": True
}
```

Remove the `"temporary"` key.

Expected output:

```text
{'name': 'vm01', 'cpu': 2, 'memory': '4GB'}
```

---

### Task 17: Dictionary Keys and Values

Create a dictionary:

```python
docker_container = {
    "name": "webapp",
    "image": "nginx:latest",
    "port": 80
}
```

Print all keys.

Then print all values.

Expected output:

```text
dict_keys(['name', 'image', 'port'])
dict_values(['webapp', 'nginx:latest', 80])
```

---

### Task 18: Check if Key Exists

Create a dictionary:

```python
config = {
    "debug": True,
    "port": 8000,
    "host": "0.0.0.0"
}
```

Check if `"port"` exists in the dictionary.

Expected output:

```text
Port configuration exists
```

---

## Part 3: Working with Tuples

### Task 19: Create a Tuple

Create a tuple:

```python
ports = (22, 80, 443, 3306)
```

Print the tuple.

Expected output:

```text
(22, 80, 443, 3306)
```

---

### Task 20: Access Tuple Items

Using the same tuple:

```python
ports = (22, 80, 443, 3306)
```

Print the first and third port.

Expected output:

```text
First port: 22
Third port: 443
```

---

### Task 21: Negative Indexing in Tuples

Create a tuple:

```python
protocols = ("ssh", "http", "https", "mysql")
```

Print the last item using negative indexing.

Expected output:

```text
mysql
```

---

### Task 22: Tuple Length

Create a tuple:

```python
regions = ("ap-south-1", "us-east-1", "eu-west-1")
```

Print the number of regions.

Expected output:

```text
Total regions: 3
```

---

### Task 23: Tuple Slicing

Create a tuple:

```python
backup_days = ("Monday", "Tuesday", "Wednesday", "Thursday", "Friday")
```

Print only the first three days.

Expected output:

```text
('Monday', 'Tuesday', 'Wednesday')
```

---

### Task 24: Understand Tuple Immutability

Create a tuple:

```python
database_ports = (3306, 5432, 27017)
```

Try to update the first value:

```python
database_ports[0] = 3307
```

Observe the error.

Expected error:

```text
TypeError: 'tuple' object does not support item assignment
```

Write a comment in your Python file explaining why this error occurs.

---

## Part 4: Mixed Practice

### Task 25: List of Dictionaries

Create a list of dictionaries:

```python
servers = [
    {"name": "web01", "ip": "10.0.0.11", "role": "web"},
    {"name": "db01", "ip": "10.0.0.12", "role": "database"},
    {"name": "cache01", "ip": "10.0.0.13", "role": "cache"}
]
```

Print the IP address of `db01`.

Expected output:

```text
10.0.0.12
```

---

### Task 26: Dictionary with List Value

Create a dictionary:

```python
project = {
    "name": "RAG Application",
    "services": ["frontend", "backend", "qdrant"],
    "environment": "dev"
}
```

Print all services.

Expected output:

```text
['frontend', 'backend', 'qdrant']
```

---

### Task 27: Add a Service to Dictionary List

Using the same dictionary:

```python
project = {
    "name": "RAG Application",
    "services": ["frontend", "backend", "qdrant"],
    "environment": "dev"
}
```

Add `"redis"` to the services list.

Expected output:

```text
['frontend', 'backend', 'qdrant', 'redis']
```

---

### Task 28: Tuple Inside Dictionary

Create a dictionary:

```python
app_config = {
    "app_name": "student-api",
    "allowed_ports": (8000, 8080),
    "debug": True
}
```

Print the allowed ports.

Expected output:

```text
(8000, 8080)
```

---

### Task 29: DevOps Inventory Structure

Create the following inventory:

```python
inventory = {
    "web_servers": ["web01", "web02"],
    "db_servers": ["db01"],
    "load_balancer": "lb01"
}
```

Print:

```text
Web Servers: ['web01', 'web02']
Database Servers: ['db01']
Load Balancer: lb01
```

---

### Task 30: Kubernetes Pod Dictionary

Create a dictionary:

```python
pod = {
    "name": "nginx-pod",
    "namespace": "default",
    "containers": ["nginx"],
    "status": "Running"
}
```

Print:

```text
Pod nginx-pod is Running in namespace default
```

---

## Part 5: Mini Assignment

### Task 31: Student Course Record

Create a dictionary named `student_record` with the following data:

```python
student_record = {
    "name": "Neha",
    "course": "Python for DevOps",
    "skills": ["Linux", "Python", "Git"],
    "duration": "2 months",
    "active": True
}
```

Print the student profile in this format:

```text
Student Course Record
---------------------
Name: Neha
Course: Python for DevOps
Skills: ['Linux', 'Python', 'Git']
Duration: 2 months
Active: True
```

---

### Task 32: Infrastructure Inventory Parser

Create this data structure:

```python
infra = {
    "environment": "production",
    "servers": [
        {"name": "web01", "ip": "10.0.1.10", "ports": (80, 443)},
        {"name": "db01", "ip": "10.0.1.20", "ports": (3306,)},
        {"name": "cache01", "ip": "10.0.1.30", "ports": (6379,)}
    ]
}
```

Print the output:

```text
Environment: production

Server Name: web01
IP Address: 10.0.1.10
Ports: (80, 443)

Server Name: db01
IP Address: 10.0.1.20
Ports: (3306,)

Server Name: cache01
IP Address: 10.0.1.30
Ports: (6379,)
```

---

## Bonus Tasks

### Bonus Task 1: Convert Tuple to List

Create a tuple:

```python
readonly_ports = (22, 80, 443)
```

Convert it into a list and add port `8080`.

Expected output:

```text
[22, 80, 443, 8080]
```

---

### Bonus Task 2: Convert List to Tuple

Create a list:

```python
mutable_regions = ["ap-south-1", "us-east-1", "eu-west-1"]
```

Convert it into a tuple.

Expected output:

```text
('ap-south-1', 'us-east-1', 'eu-west-1')
```

---

### Bonus Task 3: Nested Data Access

Create this structure:

```python
cluster = {
    "name": "dev-cluster",
    "nodes": [
        {"name": "node01", "status": "Ready"},
        {"name": "node02", "status": "NotReady"}
    ]
}
```

Print the status of `node02`.

Expected output:

```text
NotReady
```

---

### Bonus Task 4: Create a Package List

Create a list of packages:

```python
packages = ["nginx", "mysql-server", "python3", "docker.io"]
```

Add `"git"` to the list.

Remove `"mysql-server"` from the list.

Print the final list.

Expected output:

```text
['nginx', 'python3', 'docker.io', 'git']
```

---

