# cisco_user_compliance

Will check that user account is created on cisco devices. Include extra_vars in AWX or in vars to set these values, or include as custom credendtials in AWX as a hashed password and username.

```
local_pass
local_user
```

Add users to variable to remove these:

```
remove_local_users:
    - user1
    - user2
```
