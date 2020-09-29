# cisco_user_compliance

Will check that user account is created on cisco devices. Include extra_vars in AWX or in vars to set these values, or include as custom credendtials in AWX as a hashed password and username.

```
local_pass
local_user
```

# Version 1.0

Add users to variable to remove these:

```
remove_local_users:
    - user1
    - user2
```

# Version 2.0

Purges all users except specified user in the local_user var.
