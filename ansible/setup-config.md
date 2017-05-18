## Google Account setup for Ansbile Server configuration.

### 1. Setup Google Account.

#### Setup keys in google account
#### 1. Create ssh keyt pair
`# ssh-keygen -f admin`

#### 2. Edit the admin.pub file to set the user as `admin` or run the following commands.
`# awk '{print $1,$2,"admin@localhost"}' admin.pub`

#### 3. Copy the above output and keep it under google cloud.

###### a. Goto Compute Engine
###### b. Goto Metadata
###### c. Goto SSHKeys
###### d. Goto "Edit" and then click on "Add Item"
###### e. Paste the content and save it.
