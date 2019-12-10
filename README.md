# Basic Linux Setup
More services can be added or removed by updating

## Instructions
Below are instructions for creating the cluster with or

### Configuration and installation

```
$ sudo su -
$ yum install -y git
$ git clone https://github.com/joyer7/BasicLinuxSetup.git
$ cd BasicLinuxSetup
$ chmod +x setup-custom.sh
```

The script `setup.sh` takes 3 arguments:
- the cloud provider name: `aws`,`azure`,`gcp`.

```
$ ./setup-custom.sh aws 