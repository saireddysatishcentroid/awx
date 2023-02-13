<img src="https://companieslogo.com/img/orig/DAR-8baea6b3.png?t=1653580821" alt="Project Logo" align="right" width="100">

# INSERT TITLE

> A template repository to use when creating an Ansible role. **Please change this description**

## Requirements

Describe the requirements that have to be met to be able to use this role. Think about the systems it is going to interface with. Are there any Python libraries?..

## Role variables

The following table lists optional Ansible variables along with the default values if not defined.

| Name            | Default value | Description                      |
| --------------- | ------------- | -------------------------------- |
| `variable_foo`  | `bar`         | This variable does stuff         |
| `variable_fizz` | N/A           | This variables does other things |

## Example playbook

This is a sample of the role used in a playbook:

```yaml
- name: Execute role
  ansible.builtin.include_role:
    name: ansible-role-template
  vars:
    variable_foo: "boo"
    variable_fizz: false
```