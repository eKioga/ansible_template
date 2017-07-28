# Ansible Template

This the template I typically start with when building an basic playbook.

It does the following.

* Starts by installing Ansible/Python prerequisites. This step makes the playbook compatible with LXCs and new versions of Ubuntu. 

* User setup.

* Runs common tasks like Fail2Ban, Git and UFW installations.

* Runs SSH hardening.

I reccomend adding anything custom somewhere between the common and SSH role. 
Be sure to edit the username and password variables before use.

                             _
                            | \
                            | |
                            | |
       |\                   | |
      /, ~\                / /
     X     `-.....-------./ /
      ~-. ~  ~              |
         \             /    |
          \  /_     ___\   /
          | /\ ~~~~~   \ |
          | | \        || |
          | |\ \       || )
         (_/ (_/      ((_/

eKioga
