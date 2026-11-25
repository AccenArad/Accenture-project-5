Project-5
Secure Linux Server Permissions

The objective of this project was to apply user-based access restrictions on a Linux server.

A group named "capstone-secure" was created along with two users, "capstone-user1" and "capstone-user2". "capstone-user1" was added to the "capstone-secure" group, while "capstone-user2" was kept outside the group.

A protected directory "/opt/capstone-secure" and a file "secret.txt" were created with restricted ownership and permissions. Access was then tested for both users.

"capstone-user1" was able to access and read the protected file, confirming allowed access. "capstone-user2" was denied access, confirming that the user-based permission restrictions were working correctly.

The project demonstrates how Linux users, groups, ownership, and file permissions can be used to control access to sensitive resources.
