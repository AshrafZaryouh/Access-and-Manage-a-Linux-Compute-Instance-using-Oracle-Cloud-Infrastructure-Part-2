# Approach 2: Connect via Terminal Console to the Compute Instance using SSH Username and Password with the OCI Cloud Shell Console

This approach can be used as a backdoor when you do not have any network connectivity to your instance and logging in with SSH is not possible.

`Prerequisites for approach 2`

We need to create the local username and password first and to do this we need to log in with SSH using the private key using one of the other approaches. This is done in Approach 1, 3, 4, 5 and 6.

+ When we log in with SSH using a private key, we can create a new local username and assign a password to that new username. Run the following commands.

```
sudo useradd console
sudo passwd console
```

<img width="1046" height="159" alt="Access-Manage-Linux-Instance-206" src="https://github.com/user-attachments/assets/ae566882-7ea2-47a9-90bb-07264a88cf70" />

It is also possible to create a new local username and password at the instance creation process. But we will show this in another tutorial.

`Continue with approach 2`

Now that we have created the local username and password we can continue with connecting via the terminal console to the compute instance using SSH username and password with the OCI Cloud Shell console.

In this approach, we will connect to a Linux instance using the local console provided by OCI to connect directly to the instance using the OCI Cloud Shell.

<img width="2338" height="1710" alt="Access-Manage-Linux-Instance-202" src="https://github.com/user-attachments/assets/e36e7ac2-c783-4f82-8424-fbf9a15a3a77" />

+ Connect to the OCI Cloud Shell.

1. In **Instance** details page, scroll down.
2. Click **Console Connection** to start OCI Cloud Shell and connect to the console.

<img width="1512" height="824" alt="Access-Manage-Linux-Instance-203" src="https://github.com/user-attachments/assets/d4040488-8a82-4f5b-81ee-f0edb488e432" />

+ Click **Launch Cloud Shell connection.**

<img width="1512" height="824" alt="Access-Manage-Linux-Instance-204" src="https://github.com/user-attachments/assets/7d177a18-4fd3-4e36-9d9f-220690af6507" />

+ The OCI Cloud Shell window only provides a username and not a password.

+ This username and password needs to be created and are not there by default.

1. The OCI Cloud Shell window will be opened.
2. The prompt provides an username.

<img width="1513" height="824" alt="Access-Manage-Linux-Instance-205" src="https://github.com/user-attachments/assets/7496f1f0-a620-4bd6-aebe-dda71c97491c" />

+ Type in the local username and password in the console terminal.

<img width="1512" height="824" alt="Access-Manage-Linux-Instance-207" src="https://github.com/user-attachments/assets/a7a26767-73b0-4f14-9b16-1bb834b0de8e" />

---

---
