# AirBnB_clone
The goal of the project is to deploy on your server a simple copy of the AirBnB website.

The AirBnB website operates an online marketplace for travel information and booking services. The Company offers lodging, home-stay, and tourism services via websites and mobile applications. Airbnb serves clients worldwide.
## Getting Started

 
**What’s a command interpreter?**

Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to

be able to manage the objects of our project:

  

- Create a new object (ex: a new User or a new Place)

- Retrieve an object from a file, a database etc…

- Do operations on objects (count, compute stats, etc…)

- Update attributes of an object

- Destroy an object
## Execution

  
Your shell should work like this in interactive mode:

  
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF help quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

But also in non-interactive mode: (like the Shell project in C)

```
$ echo "help" | ./console.py

(hbnb)

Documented commands (type help <topic>):
========================================

EOF help quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

  
Documented commands (type help <topic>):
========================================
EOF help quit
(hbnb)
$

```

## Usage Examples

**Launching the console**
```
$ ./console.py
(hbnb) 
```
**Creating a new object**
```
(hbnb) create
** class name missing **
(hbnb) create User
670265eb-5982-489e-8b92-2dff054f0776
```
**Show an object**
```
(hbnb) show User
** instance id missing **
(hbnb) show User 670265eb-5982-489e-8b92-2dff054f0776
[User] (670265eb-5982-489e-8b92-2dff054f0776) {'created_at': datetime.datetime(2020, 2, 19, 18, 8, 58, 458246), 'id': '670265eb-5982-489e-8b92-2dff054f0776', 'updated_at': datetime.datetime(2020, 2, 19, 18, 8, 58, 458261)}
```
**Update an object**
```
(hbnb) all
["[User] (70f71c16-962b-48ad-9df8-9203fe23d612) {'created_at': datetime.datetime(2020, 2, 19, 18, 11, 32, 341144), 'id': '70f71c16-962b-48ad-9df8-9203fe23d612', 'updated_at': datetime.datetime(2020, 2, 19, 18, 11, 32, 341161)}"]
(hbnb) update
** class name missing **
(hbnb) update User
** instance id missing **
(hbnb) update User 70f71c16-962b-48ad-9df8-9203fe23d612
** attribute name missing **
(hbnb) update User 70f71c16-962b-48ad-9df8-9203fe23d612  Age "20"
(hbnb) all
["[User] (70f71c16-962b-48ad-9df8-9203fe23d612) {'Age': 20, 'created_at': datetime.datetime(2020, 2, 19, 18, 11, 32, 341144), 'id': '70f71c16-962b-48ad-9df8-9203fe23d612', 'updated_at': datetime.datetime(2020, 2, 19, 18, 13, 9, 937933)}"]
(hbnb)
```
**Destroy an object**
```
(hbnb) destroy
** class name missing **
(hbnb) destroy User
** instance id missing **
(hbnb) destroy User 670265eb-5982-489e-8b92-2dff054f0776
(hbnb)
```
Test for initial commit

#File lists individuals who contributed content to this repository.

Koranteng Kwesi Kessie <kessiekoranteng88@gmail.com>
