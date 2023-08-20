# EasyDBInstaller
Welcome to EasyDBInstaller! This project is designed to simplify the installation process of various databases, making it effortless to set up and manage your preferred database systems. Whether you're working with PostgreSQL, MongoDB, Redis, Oracle, MariaDB, MySQL, or SQLite, EasyDBInstaller has got you covered
# What is EasyDBInstaller?
EasyDBInstaller is a utility that streamlines the installation and configuration of a range of popular database systems. It eliminates the complexities often associated with setting up databases and provides you with a seamless experience to get your database environments up and running quickly.
## Supported Databases
With EasyDBInstaller, you can effortlessly install the following database systems:

* PostgreSQL
* MongoDB
* Redis
* Oracle (soon)
* MariaDB
* MySQL
* SQLite

## How Does It Work?
Utilizing DatabaseInstaller is a breeze. Just follow these straightforward steps:

* 1. Clone the Repository: Start by cloning this repository to your local machine.

* 2. Choose Your Database: Navigate to the specific directory for the database you wish to install.

* 3. Run the Ansible Playbook: Execute the provided Ansible playbook. DatabaseInstaller will guide you through the installation process seamlessly.

* 4. Automated Configuration: DatabaseInstaller automatically configures your chosen database with optimal settings, saving you time and effort.

Why Use EasyDBInstaller?
* Time Saver: Eliminate the need for manual installations and configurations. DatabaseInstaller speeds up the process and gets you up and running in no time.

* Flexibility: With support for various database systems, you can pick the one that best suits your project's requirements.

* User-Friendly: DatabaseInstaller is designed to cater to users of all experience levels. Its intuitive interface ensures a smooth installation process.

* Consistency: Achieve consistent and accurate installations across different environments with DatabaseInstaller's automation.

* Simplified Management: Once installed, managing and maintaining your databases becomes more manageable.


### How to use ansible to implement Databa

#### Mysql

```
ansible-playbook -i inventory --tag mysql -e 'machine=mysql' install.yml
```

#### Mariadb

```
ansible-playbook -i inventory --tag mariadb -e 'machine=mariadb' install.yml
```

#### Postgresql

```
ansible-playbook -i inventory --tag postgresql -e 'machine=postgresql' install.yml
```

#### Sqlite

```
ansible-playbook -i inventory --tag sqlite -e 'machine=sqlite' install.yml
```

#### Redis

```
ansible-playbook -i inventory --tag redis -e 'machine=redis' install.yml
```

#### Mongodb

```
ansible-playbook -i inventory --tag mongo -e 'machine=mongo' install.yml
```
