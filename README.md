## ansible-hipchat-v2

Notify HipChat v2 API from Ansible


###examples

*source hacking/env-setup
*hacking/test-module -m library/notification/hipchat_v2 -a 'room=1234567 token=asdf1234567 msg=hello world'

```
- name: Test hipchat v2 module
  hipchat_v2:
    msg="Hello from my playbook!"
    room=1234567
    token=asdf1234567
  tags: hipchat
```
