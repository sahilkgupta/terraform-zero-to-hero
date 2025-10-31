Path is nothing but mounting

Like we are running vault on ec2 instance. so to store our secrets data it must be stored somewhere in machine path is that location where our secrets are going to be stored.

User's can access that credentials from that location.
we will give that path in place of our actual credentials in our source code to enhance security.

Hashicorp will store the encrypted version of secret at that location. the decrypted version is still stored in hashicorp only.



Policy in Hashicorp:

Like AWS for accessing the resources in AWS we need roles.
In hashicorp as well we need to create a role to access credential which has been stored in it.

