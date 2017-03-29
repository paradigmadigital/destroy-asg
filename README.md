# destroy-asg

Destroy Auto Scaling Groups

## Role Variables

* `asg.name`   : Auto Scaling Group name
* `asg.region` : Region to launch the ec2 instance to create the new AMI

## Example playbook

```yaml
- hosts: localhost
  connection: local
  gather_facts: no
  roles:
    - destroy-asg
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigmadigital.com)
