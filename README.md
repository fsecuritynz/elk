# ELK.sh
An easy-to-deploy script of ELK stack for RHEL/CENTOS/FEDORA/ROCKY Linux


# Minimum Hardware Requirements for small deployments
- 4x Cores of a relatively modern CPU
- 8 GB of RAM (policed)
- 1 TB of storage


# Recommended (strongly) Hardware Requirements
- 8x Cores Xeon (or equivalent)
- 16-32 GB of RAM
- 4 TB of storage (RAID 1+0)

# Installation
<pre>
sudo su -

cd /opt

curl -O https://raw.githubusercontent.com/fsecuritynz/elk/main/elk.sh

chmod +x elk.sh

sudo sh elk.sh
</pre>

profit
