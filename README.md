ß# ansible-akamai
Ansible Module for working with Akamai OPEN APIIs

# Prerequisites
- Edgegrid-Python (install with `pip install edgegrid python`), works with Python 2.7+

# Install
- Drop `akamai.py` and `config.py` into `./library` in any Ansible playbook, then invoke it like any standard module

# Credentials
- Akamai OPEN credentials are required to use this module.  A reference to get the credentials can be found here - https://developer.akamai.com/introduction/Prov_Creds.html

- The currently supported method for storing credentials is via an `.edgerc` file, the recommended location to store the file is in the home directory

# Variables
- `section` - Section of `.edgerc` file
- `endpoint` - API endpoint to hit
- `method` - GET or POST, similar to HTTPie and the Akamai CLI

# Acknowledgements
- `config.py` is from the Akamai Technologies [api-kickstart](https://github.com/akamai/api-kickstart) repository where many other Akamai API examples are available!
