# supercomputer-v1 lab

1. **Login Node:**
  * SingleSignOn Service for authentication
  * NFS Server for /home and /software directories
  * A single test user
2. **Compute Node:**
  * Authenticate against common LDAP server on Login node
  * Mount /home and /software from Login node
