# Python Basics Task List  
## Topic: Python Functions

## Part 1: Basic Functions

### Task 1: Create a Simple Function

Create a Python file named:

```bash
functions_practice.py
```

Inside the file, create a function named `greet()`.

The function should print:

```text
Welcome to Python Functions
```

Call the function.

Expected output:

```text
Welcome to Python Functions
```

---

### Task 2: Function to Print Course Name

Create a function named `show_course()`.

The function should print:

```text
Python for DevOps
```

Expected output:

```text
Python for DevOps
```

---

### Task 3: Function with One Argument

Create a function named `greet_student(name)`.

Call the function with:

```python
greet_student("Rahul")
```

Expected output:

```text
Hello Rahul
```

---

### Task 4: Function with Two Arguments

Create a function named `student_details(name, course)`.

Call the function with:

```python
student_details("Neha", "Python for DevOps")
```

Expected output:

```text
Student Name: Neha
Course: Python for DevOps
```

---

### Task 5: Function to Add Two Numbers

Create a function named `add_numbers(a, b)`.

The function should print the sum of two numbers.

Call the function with:

```python
add_numbers(10, 20)
```

Expected output:

```text
Sum: 30
```

---

### Task 6: Function to Multiply Two Numbers

Create a function named `multiply_numbers(a, b)`.

Call the function with:

```python
multiply_numbers(5, 4)
```

Expected output:

```text
Result: 20
```

---

## Part 2: Return Values

### Task 7: Return Sum from Function

Create a function named `add(a, b)`.

The function should return the sum of `a` and `b`.

Store the returned value in a variable and print it.

Expected output:

```text
30
```

---

### Task 8: Return Full Name

Create a function named `get_full_name(first_name, last_name)`.

The function should return the full name.

Call the function with:

```python
get_full_name("Aryan", "Srivastava")
```

Expected output:

```text
Aryan Srivastava
```

---

### Task 9: Return Server Name

Create a function named `get_server_name()`.

The function should return:

```text
web01
```

Print the returned value.

Expected output:

```text
web01
```

---

### Task 10: Function to Calculate Square

Create a function named `square(number)`.

The function should return the square of the number.

Call the function with:

```python
square(6)
```

Expected output:

```text
36
```

---

### Task 11: Function to Check Even Number

Create a function named `is_even(number)`.

The function should return `True` if the number is even, otherwise return `False`.

Call the function with:

```python
is_even(10)
is_even(7)
```

Expected output:

```text
True
False
```

---

## Part 3: Default and Keyword Arguments

### Task 12: Function with Default Argument

Create a function named `connect_server(host="localhost")`.

The function should print:

```text
Connecting to localhost
```

Call the function without passing any argument.

Expected output:

```text
Connecting to localhost
```

---

### Task 13: Override Default Argument

Using the same function:

```python
def connect_server(host="localhost"):
    print(f"Connecting to {host}")
```

Call the function with:

```python
connect_server("192.168.1.10")
```

Expected output:

```text
Connecting to 192.168.1.10
```

---

### Task 14: Function with Multiple Default Arguments

Create a function named `create_user(username, shell="/bin/bash")`.

Call the function with:

```python
create_user("devops")
```

Expected output:

```text
Creating user devops with shell /bin/bash
```

---

### Task 15: Use Keyword Arguments

Create a function named `server_info(hostname, ip, role)`.

Call the function using keyword arguments:

```python
server_info(role="web", ip="10.0.0.10", hostname="web01")
```

Expected output:

```text
Hostname: web01
IP: 10.0.0.10
Role: web
```

---

### Task 16: Function with Environment Default

Create a function named `deploy_app(app_name, environment="dev")`.

Call it twice:

```python
deploy_app("student-api")
deploy_app("payment-api", "production")
```

Expected output:

```text
Deploying student-api to dev environment
Deploying payment-api to production environment
```

---

## Part 4: Functions with Lists

### Task 17: Print List Items Using Function

Create a function named `print_tools(tools)`.

Pass this list to the function:

```python
tools = ["Linux", "Python", "Git", "Docker"]
```

The function should print each tool on a new line.

Expected output:

```text
Linux
Python
Git
Docker
```

---

### Task 18: Count Items in a List

Create a function named `count_items(items)`.

The function should return the number of items in a list.

Call it with:

```python
users = ["alice", "bob", "charlie"]
```

Expected output:

```text
3
```

---

### Task 19: Find Package in List

Create a function named `is_package_installed(packages, package_name)`.

Use this list:

```python
packages = ["nginx", "python3", "git", "docker"]
```

Check whether `"docker"` is installed.

Expected output:

```text
docker is installed
```

---

### Task 20: Return Running Services

Create a function named `get_running_services(services)`.

Use this list:

```python
services = ["nginx:running", "mysql:stopped", "docker:running", "redis:stopped"]
```

The function should return a list of only running service names.

Expected output:

```text
['nginx', 'docker']
```

---

### Task 21: Add Prefix to List Items

Create a function named `add_install_prefix(packages)`.

Use this list:

```python
packages = ["nginx", "mysql", "python3"]
```

The function should return:

```text
['install-nginx', 'install-mysql', 'install-python3']
```

---

## Part 5: Functions with Dictionaries

### Task 22: Print Dictionary Data

Create a function named `print_student(student)`.

Use this dictionary:

```python
student = {
    "name": "Rahul",
    "course": "Python for DevOps",
    "city": "Delhi"
}
```

Expected output:

```text
Name: Rahul
Course: Python for DevOps
City: Delhi
```

---

### Task 23: Return Value from Dictionary

Create a function named `get_server_ip(server)`.

Use this dictionary:

```python
server = {
    "hostname": "web01",
    "ip": "192.168.1.10",
    "status": "running"
}
```

The function should return only the IP address.

Expected output:

```text
192.168.1.10
```

---

### Task 24: Update Dictionary Using Function

Create a function named `update_service_status(service, new_status)`.

Use this dictionary:

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

### Task 25: Create Server Dictionary

Create a function named `create_server(hostname, ip, role)`.

The function should return a dictionary.

Call the function with:

```python
create_server("web01", "10.0.0.10", "web")
```

Expected output:

```text
{'hostname': 'web01', 'ip': '10.0.0.10', 'role': 'web'}
```

---

### Task 26: Check Pod Status

Create a function named `check_pod_status(pod)`.

Use this dictionary:

```python
pod = {
    "name": "backend",
    "namespace": "default",
    "status": "CrashLoopBackOff"
}
```

Expected output:

```text
Pod backend is in CrashLoopBackOff state
```

---

## Part 6: Functions with Files

### Task 27: Write Text to File Using Function

Create a function named `write_message(filename, message)`.

Call the function with:

```python
write_message("message.txt", "Hello from Python function")
```

Expected file content in `message.txt`:

```text
Hello from Python function
```

---

### Task 28: Read Text from File Using Function

Create a file named `message.txt` with this content:

```text
Hello from Python function
```

Create a function named `read_message(filename)`.

The function should read and print the file content.

Expected output:

```text
Hello from Python function
```

---

### Task 29: Write List to File

Create a function named `write_lines(filename, lines)`.

Use this list:

```python
servers = ["web01", "web02", "db01"]
```

Write each server name into a file named `servers.txt`.

Expected file content:

```text
web01
web02
db01
```

---

### Task 30: Read File Lines into List

Create a file named `users.txt`:

```text
alice
bob
charlie
```

Create a function named `read_users(filename)`.

The function should read the file and return a list:

```text
['alice', 'bob', 'charlie']
```

---

### Task 31: Count Lines in File

Create a file named `commands.txt`:

```text
ls
pwd
df -h
free -m
```

Create a function named `count_file_lines(filename)`.

Expected output:

```text
Total lines: 4
```

---

### Task 32: Filter Running Services from File

Create a file named `services.txt`:

```text
nginx running
mysql stopped
docker running
redis stopped
```

Create a function named `get_running_services_from_file(filename)`.

Expected output:

```text
['nginx running', 'docker running']
```

---

## Part 7: DevOps-Style Function Practice

### Task 33: Service Status Function

Create a function named `check_service(service_name, status)`.

Call the function with:

```python
check_service("nginx", "running")
check_service("mysql", "stopped")
```

Expected output:

```text
nginx is running
mysql is stopped
```

---

### Task 34: Server Health Function

Create a function named `server_health(hostname, cpu_usage, memory_usage)`.

If CPU usage is greater than `80`, print:

```text
CPU usage is high
```

If memory usage is greater than `80`, print:

```text
Memory usage is high
```

Call the function with:

```python
server_health("web01", 85, 70)
server_health("db01", 60, 90)
```

Expected output:

```text
Server: web01
CPU usage is high

Server: db01
Memory usage is high
```

---

### Task 35: Generate User Creation Command

Create a function named `create_user_command(username, shell="/bin/bash")`.

The function should return a Linux command string.

Call the function with:

```python
create_user_command("devops")
```

Expected output:

```text
useradd -m -s /bin/bash devops
```

---

### Task 36: Generate Package Install Command

Create a function named `install_package_command(package_name)`.

Call it with:

```python
install_package_command("nginx")
```

Expected output:

```text
sudo apt install nginx -y
```

---

### Task 37: Generate Docker Run Command

Create a function named `docker_run_command(container_name, image, port)`.

Call it with:

```python
docker_run_command("web", "nginx:latest", 80)
```

Expected output:

```text
docker run -d --name web -p 80:80 nginx:latest
```

---

### Task 38: Kubernetes Namespace YAML Generator

Create a function named `generate_namespace_yaml(namespace)`.

Call it with:

```python
generate_namespace_yaml("dev")
```

Expected output:

```yaml
apiVersion: v1
kind: Namespace
metadata:
  name: dev
```

---

## Part 8: Mini Assignment

### Task 39: Student Profile Generator Function

Create a function named `generate_student_profile(student)`.

Use this dictionary:

```python
student = {
    "name": "Amit",
    "course": "Python for DevOps",
    "duration": "2 months",
    "institute": "Network Nuts"
}
```

The function should return this formatted string:

```text
Student Profile
---------------
Name: Amit
Course: Python for DevOps
Duration: 2 months
Institute: Network Nuts
```

Print the returned string.

---

### Task 40: Infrastructure Report Generator

Create a function named `generate_inventory_report(inventory)`.

Use this list of dictionaries:

```python
inventory = [
    {"name": "web01", "ip": "10.0.1.10", "role": "web"},
    {"name": "db01", "ip": "10.0.1.20", "role": "database"},
    {"name": "cache01", "ip": "10.0.1.30", "role": "cache"}
]
```

The function should create a file named `inventory_report.txt`.

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

### Task 41: Failed Pod Report Function

Create a function named `create_failed_pod_report(pods)`.

Use this list:

```python
pods = [
    {"name": "frontend", "namespace": "default", "status": "Running"},
    {"name": "backend", "namespace": "default", "status": "CrashLoopBackOff"},
    {"name": "database", "namespace": "prod", "status": "Running"},
    {"name": "worker", "namespace": "prod", "status": "ImagePullBackOff"}
]
```

The function should create a file named `failed_pods.txt`.

Expected file content:

```text
backend default CrashLoopBackOff
worker prod ImagePullBackOff
```

---

## Bonus Tasks

### Bonus Task 1: Function with `*args`

Create a function named `install_packages(*packages)`.

Call the function with:

```python
install_packages("nginx", "git", "docker", "python3")
```

Expected output:

```text
Installing nginx
Installing git
Installing docker
Installing python3
```

---

### Bonus Task 2: Function with `**kwargs`

Create a function named `create_vm(**config)`.

Call the function with:

```python
create_vm(name="vm01", cpu=2, memory="4GB", os="Ubuntu")
```

Expected output:

```text
name: vm01
cpu: 2
memory: 4GB
os: Ubuntu
```

---

### Bonus Task 3: Return Multiple Values

Create a function named `server_summary(server)`.

Use this dictionary:

```python
server = {
    "hostname": "web01",
    "ip": "10.0.0.10",
    "status": "running"
}
```

The function should return hostname, IP, and status.

Expected output:

```text
Hostname: web01
IP: 10.0.0.10
Status: running
```

---

### Bonus Task 4: Function to Validate Port Number

Create a function named `is_valid_port(port)`.

The function should return `True` if the port number is between `1` and `65535`.

Test with:

```python
is_valid_port(80)
is_valid_port(70000)
```

Expected output:

```text
True
False
```

---

### Bonus Task 5: Function to Generate `.env` File

Create a function named `generate_env_file(config)`.

Use this dictionary:

```python
config = {
    "APP_NAME": "student-api",
    "APP_ENV": "dev",
    "APP_PORT": "8000",
    "DEBUG": "true"
}
```

The function should create a file named `.env`.

Expected file content:

```text
APP_NAME=student-api
APP_ENV=dev
APP_PORT=8000
DEBUG=true
```

---

