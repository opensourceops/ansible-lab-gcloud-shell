# Opensourceops - Ansible Lab

## Getting Started

To get started with the Ansible Lab, follow the steps below:

### Step 1: Clone the Repository

First, clone the hands-on Ansible repository to your local machine:

```bash
git clone https://github.com/opensourceops/hands-on-ansible ~/hands-on-ansible
```

### Step 2: Launch the Lab

Navigate to the cloned directory and launch the lab using Docker Compose:

```bash
cd ~/hands-on-ansible
docker-compose up -d
```

You should see output similar to the following:
~~~
Creating remote3     ... done
Creating remote1     ... done
Creating controlnode ... done
Creating remote4     ... done
Creating remote2     ... done
~~~

### Step 3: Check Lab Status

To check the status of your lab, run the following script:

```bash
./script/ansible-lab-status.sh
```

This script will provide you with the current status of the lab environment.

_Feel free to adjust any parts of the tutorial as needed!_
