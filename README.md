# Repository

Centos/Rhel (8.5)

repo-link: https://vault.centos.org/

[centos-AppStream]
name = BaseOS
baseurl = https://vault.centos.org/8.5.2111/AppStream/x86_64/os/
gpgcheck = 0
enabled = 1

[centos-BaseOS]
name = BaseOS
baseurl = https://vault.centos.org/8.5.2111/BaseOS/x86_64/os/
gpgcheck = 0
enabled = 1



[Docker-CE]
name = Docker
baseurl = https:///download.docker.com/linux/centos/7/x86_64/stable/
gpgcheck = 0
enabled = 1

