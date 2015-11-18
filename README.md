motd Cookbook
=============
This cookbook setups /etc/issue.net file to provide a message on SSH connection (before logon)

Requirements
------------
None.

Attributes
----------
```json
{
  "motd": {
    "message": ".."
  }
}
```

Usage
-----
#### motd::default
Just include `motd` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[motd]"
  ]
}
```

Contributing
------------
Need help for testing following best practises, if you can help you are welcome!

License and Authors
-------------------
License: MIT

Authors:

Simone Dall'Angelo
