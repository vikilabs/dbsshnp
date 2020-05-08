
## Utility to connect to ssh remote host without password


This package (dbsshnp) does the following,
    
    - Setup password less ssh connectivity to remote host with public and private key encryption
    - Connect to remote host without password using public and private key encryption
    - Disable password less ssh connectivity to remote host   

Note: dbsshnp is based on openssh.

### How to install this package?

    1. git clone
    2. cd src/
    3. chmod +x install.sh
    3. sudo ./install.sh

### How to use this command?

#### Step 1: Setup password less ssh connectivity to remote server

    $dbsshnp  enable <username>@<domain/ip_address>
    
#### Example
    
    $dbsshnp  enable testuser@192.168.1.10
    

#### Step 2: Connect to remote server without password 

    Step 1 should be completed before executing step 2

    $dbsshnp  <username>@<domain/ip_address>
    
##### Example
    
    $dbsshnp  testuser@192.168.1.10
    

#### Step 3: Disable password less ssh connectivity to remote server

    $dbsshnp  disable <username>@<domain/ip_address>
    
##### Example
    
    $dbsshnp  disable testuser@192.168.1.10
 

### Tested Systems

    - Ubuntu
    - Mac OSX
