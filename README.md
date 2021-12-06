# Pi Helper

Deploy projects to a headless raspberry pi in VS code

## Setup

Create a file in the root directory of this project called `pi.config` containing:
* the Pi's IP address; and 
* the target directory on the pi.

**Leave no space** between the variable name and its value. An example is given below:
```bash
ipaddr=192.168.1.1
working_dir="~/my-awesome-project/"
```