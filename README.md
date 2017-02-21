# proxy-playbook

Requirements:
* Ubuntu 16.04 LTS
* ansible >= 2.0

If you want to use privoxy on loopback, use local_proxy play:

``` $ ansible-playbook -i hosts local_proxy.yml ```

If you want to use privoxy as public proxy, use public_proxy play (you should open port 8118 if closed):

```$ ansible-playbook -i hosts public_proxy.yml ```

Please, edit this hosts file if neccessary.
