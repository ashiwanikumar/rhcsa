## CONTROLLING NEW FILE PERMISSIONS AND OWNERSHIP

""
 -  1. Log in as alice on your serverX virtual machine and open a window with a Bash prompt.
Use the umask command without arguments to display Alice's default umask value.

2. Create a new directory /tmp/shared and a new file /tmp/shared/defaults to see how
the default umask affects permissions

3. Change the group ownership of /tmp/shared to ateam and record the new ownership and
permissions

4. Create a new file in /tmp/shared and record the ownership and permissions

5. Ensure the permissions of /tmp/shared cause files created in that directory to inherit the
group ownership of ateam.

6. Change the umask for alice such that new files are created with read-only access for
the group and no access for other users. Create a new file and record the ownership and
permissions.

7. Open a new Bash shell as alice and view the umask

8. Change the default umask for alice to prohibit all access for users not in their group

9. Log out and back into serverX as alice and confirm that the umask changes you made
are persistent

1