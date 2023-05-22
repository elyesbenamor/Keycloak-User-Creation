# Keycloak User creation and Role mapping

The setup is simple and will be **extended** in the future.
It is meant for now to create users and assign roles based on existing `client_name` variable.

## Usage

```
 ansible-playbook keycloak-user-rovision.yaml -e instance_config_name=example
  
```
The config folder can have nested directories where you can define multiple instances layer.
use `instance_config_name` option to run the playbook for the instance you wish to create
