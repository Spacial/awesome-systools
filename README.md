# Awesome Systools[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Lists

- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge)

## Reliability

- [Google - Site Reliability Engineering](https://landing.google.com/sre/book.html)
- [Istio on GKE](https://www.linkedin.com/pulse/istio-gke-googles-sre-box-ganesan-janarthanam-jana-/)- Google's SRE in a Box!

## Licensing

- [A New Social Contract for Open Source](https://hueniverse.com/a-new-social-contract-for-open-source-86d1fcf3e353)

## Linux

### Distros

- [The Void (Linux) distribution](https://voidlinux.org/): Void is a general purpose operating system, based on the monolithic Linux® kernel. Its package system allows you to quickly install, update and remove software; software is provided in binary packages or can be built directly from sources with the help of the XBPS source packages collection.
- [devuan](https://www.devuan.org/): Devuan GNU+Linux is a fork of Debian without systemd.
- [Linux distros without systemd](https://ungleich.ch/en-us/cms/blog/2019/05/20/linux-distros-without-systemd/).

### Kernel

- [Writing a Simple Linux Kernel Module](https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234)
- [eBPF Utilities, Maps, and more](https://github.com/nathanjsweet/ebpf)
- [lsof to graphviz](https://github.com/zevv/lsofgraph)
- [Making Sense of Hexdump](https://www.suse.com/c/making-sense-hexdump/), [man](https://www.systutorials.com/docs/linux/man/1-hexdump/)
- [Interactive map of Linux Kernel](http://www.makelinux.net/kernel_map/)
- [How to prevent unprivileged users from viewing dmesg command output on Linux](https://www.cyberciti.biz/faq/how-to-prevent-unprivileged-users-from-viewing-dmesg-command-output-on-linux/):

```bash
# changing dmesg option
$ sudo sysctl -w kernel.dmesg_restrict=1
```

- [darling](https://github.com/darlinghq/darling): Darwin/macOS emulation layer for Linux
- [Dmesg under the hood](https://ops.tips/blog/dmesg-under-the-hood/): Dmesg allows us to grasp what's going on under the hood when the kernel gets bad. Check out how dmesg is able to read kernel logs and show to the user.
- [Petitboot](https://github.com/open-power/petitboot): is an operating system bootloader based on Linux kexec. It can load any operating system image that supports the Linux kexec re-boot mechanism like Linux and FreeBSD.
- [Killing processes that don't want to die](https://lwn.net/Articles/754980/)
- [musl libc](https://www.musl-libc.org/): is lightweight, fast, simple, free, and strives to be correct in the sense of standards-conformance and safety.
- [Modern USB gadget on Linux & how to integrate it with systemd (Part 2)](https://www.collabora.com/news-and-blog/blog/2019/03/27/modern-usb-gadget-on-linux-and-how-to-integrate-it-with-systemd-(part-2)/)
- [Introduction to Paging](https://os.phil-opp.com/paging-introduction/): Writing an OS in Rust

### Performance

- [Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools](https://github.com/sahilshekhawat/Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools?files=1)
- [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/)
- [bcc](https://github.com/iovisor/bcc/): Tools for BPF-based Linux IO analysis, networking, monitoring, and more
- [bpftrace](http://www.brendangregg.com/blog/2018-10-08/dtrace-for-linux-2018.html)(DTrace 2.0) for Linux 2018
- [What's a CPU to do when it has nothing to do?](https://lwn.net/SubscriberLink/767630/594421f913c3d00a/)
- [How new-lines affect Linux performance](https://nadav.amit.zone/blog/linux-inline)
- [Hooking Linux Kernel Functions, Part 1: Looking for the Perfect Solution](https://www.apriorit.com/dev-blog/544-hooking-linux-functions-1)
- [Hooking Linux Kernel Functions, Part 2: How to Hook Functions with Ftrace](https://www.apriorit.com/dev-blog/546-hooking-linux-functions-2)
- [Hooking Linux Kernel Functions, Part 3: What Are the Main Pros and Cons of Ftrace?](https://www.apriorit.com/dev-blog/547-hooking-linux-functions-3)
- [Heatmaps Make Ops Better](https://www.honeycomb.io/blog/heatmaps-make-ops-better/)
- [execution-trace-viewer](https://github.com/teemu-l/execution-trace-viewer): Tool for viewing and analyzing execution traces
- [Program Profiling](https://www.ibm.com/support/knowledgecenter/ssw_ibm_i_73/ilec/progprof.htm)
- [ebpf_exporter](https://github.com/cloudflare/ebpf_exporter): Prometheus exporter for custom eBPF metrics
- [ARM and Intel have different performance characteristics: a case study in random number generation](https://lemire.me/blog/2019/03/20/arm-and-intel-have-different-performance-characteristics-a-case-study-in-random-number-generation/)
- [Estimating branch probability using Intel LBR feature](https://easyperf.net/blog/2019/05/06/Estimating-branch-probability): The underlying CPU feature that allows this to happen is called LBR(Last Branch Record). LBR feature is used to track control flow of the program. This feature uses MSRs (Model Specific Registers) to store history of last taken branches.
- Linux Applications Performance: [Introduction](https://unixism.net/2019/04/linux-applications-performance-introduction/).

#### Monitoring

- [netdata](https://my-netdata.io/): Real-time performance monitoring, done right! [github](https://github.com/netdata/netdata).
- [Watchman](https://github.com/facebook/watchman): Watches files and records, or triggers actions, when they change.
- [cartography](https://github.com/lyft/cartography): Cartography is a Python tool that consolidates infrastructure assets and the relationships between them in an intuitive graph view powered by a Neo4j database.

### Red Hat/Fedora

- Yum to DNF [Cheatsheet](https://fedoraproject.org/wiki/Yum_to_DNF_Cheatsheet)
- [How to reset a root password on Fedora](https://fedoramagazine.org/reset-root-password-fedora/)
- [Use restic on Fedora for encrypted backups](https://fedoramagazine.org/use-restic-encrypted-backups/)
- [Software Galaxies](https://github.com/anvaka/pm): package managers visualization, [see it](https://anvaka.github.io/pm/)
- [United RPMs repo](https://unitedrpms.sourceforge.io/x86_64/repoview/)
- [chromium on pkgs.org](https://pkgs.org/download/chromium) (or you can build it [on your own](https://chromium.googlesource.com/chromium/src/+/master/docs/linux_build_instructions.md#Instructions-for-Google-Employees))
- [Planet CCRMA at home](http://ccrma.stanford.edu/planetccrma/software/) (SuperCollider home)
- [Fedora Scientific Vagrant boxes are here!](https://echorand.me/fedora-scientific-vagrant-boxes-are-here.html)
- [Install VLC on Fedora](https://www.kaizenuslife.com/2018/10/31/install-vlc-media-player-in-fedora-28-29/):
- [How to install and activate Cockpit web console on RHEL 8](https://www.cyberciti.biz/faq/install-activate-cockpit-the-web-console-on-rhel-8/)
- [How to reset a root password on Fedora](https://fedoramagazine.org/reset-root-password-fedora/)
- [Backup on Fedora Silverblue with Borg](https://fedoramagazine.org/backup-on-fedora-silverblue-with-borg/)
- [Fedora 27 - Laptop won't suspend when closing lid](https://unix.stackexchange.com/questions/414297/fedora-27-laptop-wont-suspend-when-closing-lid)
- [Installing alternative versions of RPMs in Fedora](https://fedoramagazine.org/installing-alternative-rpm-versions-in-fedora/) with [Modularity](https://docs.pagure.org/modularity/)
- [Use Postfix to get email from your Fedora system](https://fedoramagazine.org/use-postfix-to-get-email-from-your-fedora-system/)
- [Trace code in Fedora with bpftrace](https://fedoramagazine.org/trace-code-in-fedora-with-bpftrace/)

```bash
 # installing the repo
 $ sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
  $ sudo dnf install vlc
```

### Packaging

- [Packages — GuixSD](https://www.gnu.org/software/guix/packages/)
- [warp](https://github.com/dgiagio/warp): Create self-contained single binary applications
- [Linux brew](https://linuxbrew.sh/): Linuxbrew is a fork of Homebrew, the macOS package manager, for Linux. [github](https://github.com/Linuxbrew/brew)
- [Nixpkgs](https://github.com/NixOS/nixpkgs): is a collection of packages for the Nix package manager. It is periodically built and tested by the Hydra build daemon as so-called channels.

#### DEB

- [Limiting the power of package installation in Debian](https://lwn.net/Articles/770784/)

#### RPM

- [RPM packages explained](https://fedoramagazine.org/rpm-packages-explained/)

##### Build

- [Creating RPM Packages with Fedora](https://fedoraproject.org/wiki/How_to_create_an_RPM_package)
- Spec file, to create lsutil rpm: [here](https://github.com/pld-linux/lsiutil)

### Storage

- [Mounting a hard disk image including partitions using Linux](http://www.andremiller.net/content/mounting-hard-disk-image-including-partitions-using-linux)
- [How to full encrypt your linux system with lvm on luks](https://www.linux.com/blog/how-full-encrypt-your-linux-system-lvm-luks)
- [Tutorial: ClamAV-Antivirus-Scanning in Nextcloud implementieren](https://ollis.blog/tutorial-clamav-antivirus-scanning-in-nextcloud-implementieren/)
- [Mapping UID and GID of local user to the mounted NFS share - Server Fault](https://serverfault.com/questions/514118/mapping-uid-and-gid-of-local-user-to-the-mounted-nfs-share)
- [RAMCloud](https://github.com/PlatformLab/RAMCloud): RAMCloud is a new class of super-high-speed storage for large-scale datacenter applications. It is designed for applications in which a large number of servers in a datacenter need low-latency access to a large durable datastore. [Overview](https://ramcloud.atlassian.net/wiki/spaces/RAM/overview)
- Synology Resources:
  - [Synomon](http://dottoremoe.com/synomon/)
  - [SynoCommunity](https://synocommunity.com/)
  - [spksrc](https://github.com/SynoCommunity/spksrc): Cross compilation framework to create native packages for the Synology's NAS
- [ssdWearOut](https://github.com/Sid-Sun/ssdWearOut): Do you want to wear out your SSD before the warranty expires?
- [ELSA](https://arxiv.org/pdf/1810.11888.pdf): Efficient Long-Term Secure Storage of Large Datasets
- [drbd](https://github.com/LINBIT/drbd-9.0): LINBIT DRBD-9.0 (new-stable)
- [Analyzing Your File System and Folder Structures with Python](https://janakiev.com/blog/python-filesystem-analysis/)
- [Algorithms behind Modern Storage Systems](https://www.infoq.com/presentations/storage-algorithms): Alex Petrov talks about modern storage system approaches, discussing storage internals, and evaluation techniques to choose a database with the optimal read, write or memory overhead, best suitable for a certain data.
- [PrivateStorage.io](https://privatestorage.io/): Least Authority and Private Internet Access announce PrivateStorage.io. [paper](https://leastauthority.com/blog/least-authority-and-private-internet-access-announce-privatestorage-io-a-secure-and-privacy-focused-cloud-storage-solution/) (using Tahoe-LAFS)
  
### Controllers

- LSILogic util: [lsiutil](https://github.com/kojack/lsiutil)

## Caching

- [Evolution of Application Data Caching : From RAM to SSD](https://medium.com/netflix-techblog/evolution-of-application-data-caching-from-ram-to-ssd-a33d6fa7a690)
  - [EVCache](https://github.com/Netflix/EVCache): A distributed in-memory data store for the cloud
  - [extstore](https://github.com/memcached/memcached/wiki/Extstore): is an addition to memcached which leaves the hash table and keys in memory, but moves values to external storage (usually flash).

## Automation

- [Script to convert a Debian installation on DigitalOcean to Arch Linux](https://github.com/gh2o/digitalocean-debian-to-arch)
- [HomelabOS](https://gitlab.com/NickBusey/HomelabOS): Your very own offline-first privacy-centric open-source data-center!
- [5 Lessons Learned From Writing Over 300,000 Lines of Infrastructure Code](https://blog.gruntwork.io/5-lessons-learned-from-writing-over-300-000-lines-of-infrastructure-code-36ba7fadeac1)
- [ieturk](https://github.com/varal7/ieturk): Intuitive Annotation Tool for Information / Named Entity Recognition using localturk / Amazon Mechanical Turk
- [terraform-aws-secure-baseline](https://github.com/nozaq/terraform-aws-secure-baseline): Terraform module to set up your AWS account with the secure baseline configuration based on CIS Amazon Web Services Foundations.
- [cue](https://github.com/cuelang/cue): Validate and define text-based and dynamic configuration

### Ansible

- Some usefull ansible scripts and tips on [ansible](./ansible) dir.
  - [Playbooks and roles for installing and managing Ansible networking CI](https://github.com/ansible/network-infra-playbooks)
  - [Ansible Role: EPEL Repository](https://github.com/geerlingguy/ansible-role-repo-epel)
  - [Ansible role to install and manage nginx configuration](https://github.com/jdauphant/ansible-role-nginx)
  - [ansible-playbook-gitlab](https://github.com/tingtun/ansible-playbook-gitlab)
  - [ansible-cloudflare](https://github.com/arachnys/ansible-cloudflare)
  - [ansible-pelican](https://github.com/talaniz/ansible-pelican): Ansible playbooks for deploying and updating a pelican blog.
- [Automating Python with Ansible](https://tdhopper.com/blog/automating-python-with-ansible/).
- [dnf module](https://docs.ansible.com/ansible/2.3/dnf_module.html)
- [Python 3 Support](https://docs.ansible.com/ansible/latest/reference_appendices/python_3_support.html): On your hosts ansible file, include a var subsection on your hosts group:
- [CHANGING THE SSH PORT WITH ANSIBLE](https://dmsimard.com/2016/03/15/changing-the-ssh-port-with-ansible/)
- [Understanding Ansible Inventories](https://medium.com/devopslinks/understanding-ansible-inventories-db7b993b3c17): The key to understanding all of Ansible.
- [How to install Ansible on Ubuntu 18.04 for IT automation](https://www.cyberciti.biz/faq/how-to-install-ansible-on-ubuntu-18-04-for-it-automation/)

```config
[group:vars]
ansible_python_interpreter=/usr/bin/python3
```

### Puppet

- [running puppet on openwrt](https://github.com/solarkennedy/puppet-on-openwrt) (dead!)

## Security

- [andOTP](https://github.com/andOTP/andOTP): Open source two-factor authentication for Android
- [Librefox](https://github.com/intika/Librefox): Firefox with privacy enhancements

### Auditing

- [A UNIX security auditing tool based on several security frameworks](https://github.com/lateralblast/lunar)
- [The 101 of ELF files on Linux](https://linux-audit.com/elf-binaries-on-linux-understanding-and-analysis/): Understanding and Analysis

### Hardening

- [ERNW Repository of Hardening Guides](https://github.com/ernw/hardening): This repository contains various hardening guides compiled by ERNW for various purposes.
- [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html) by [stribika](https://github.com/stribika)
- See your site config with [Hardenize](https://www.hardenize.com/)
- Nice article with a lot of resources: [Common approaches to securing Linux servers and what runs on them.](https://medium.com/@ageis/common-approaches-to-securing-linux-servers-and-what-runs-on-them-dadcacc5388b)
- [fero](https://github.com/coreos/fero): YubiHSM2-backed signing server
- [iptables-essentials](https://github.com/trimstray/iptables-essentials): Iptables Essentials: Common Firewall Rules and Commands.
- [tls-what-can-go-wrong](https://github.com/hannob/tls-what-can-go-wrong): TLS - what can go wrong?
- [nftables](https://www.funtoo.org/Package:Nftables): nftables is the successor to iptables. It replaces the existing iptables, ip6tables, arptables and ebtables framework. It uses the Linux kernel and a new userspace utility called nft. nftables provides a compatibility layer for the ip(6)tables and framework.
- [Hardentools](https://github.com/securitywithoutborders/hardentools) is a utility that disables a number of risky Windows features.
- [CCAT](https://github.com/cisco-config-analysis-tool/ccat): Cisco Config Analysis Tool
- [Using a Hardened Container Image for Secure Applications in the Cloud](https://www.cisecurity.org/blog/using-hardened-container-image-secure-applications-cloud/)
- [The Practical Linux Hardening Guide](https://github.com/trimstray/the-practical-linux-hardening-guide): 🔥 This guide details the planning and the tools involved in creating a secure Linux production systems - work in progress.
- [Set up two-factor authentication for SSH on Fedora](https://fedoramagazine.org/two-factor-authentication-ssh-fedora/)
- [How To Secure A Linux Server](https://github.com/imthenachoman/How-To-Secure-A-Linux-Server): An evolving how-to guide for securing a Linux server.
- [Get SSH login notification on Telegram](https://8192.one/post/ssh_login_notification_withtelegram/)

#### Webservers

- A lot of good posts by geek flare:
  - [How to Configure SSL Certificate on Google Cloud Load Balancer?](https://geekflare.com/google-load-balancer-enable-ssl/)
  - [Nginx Web Server Security & Hardening Guide](https://geekflare.com/nginx-webserver-security-hardening-guide/)
  - [IBM HTTP Server Security & Hardening Guide](https://geekflare.com/ibm-http-server-security-guide/)
  - [Apache Tomcat Hardening and Security Guide](https://geekflare.com/apache-tomcat-hardening-and-security-guide/)
  - [How to Enable TLS 1.3 in Nginx, Cloudflare?](https://geekflare.com/enable-tls-1-3/)
  - [Apache Web Server Hardening & Security Guide](https://geekflare.com/apache-web-server-hardening-security/) (broken!??)
- [How do I prevent apache from serving the .git directory?](https://serverfault.com/questions/128069/how-do-i-prevent-apache-from-serving-the-git-directory/128082#128082)
- [Nginx C function](https://nginx-c-function.github.io): Create your desired C application on top of nginx module
- [How to Configure Nginx SSL Certifcate Chain](https://futurestud.io/tutorials/how-to-configure-nginx-ssl-certifcate-chain)
- [NGINX config for SSL with Let's Encrypt certs](https://gist.github.com/nrollr/9a39bb636a820fb97eec2ed85e473d38)
- [CAA Mandated by CA/Browser Forum](https://blog.qualys.com/ssllabs/2017/03/13/caa-mandated-by-cabrowser-forum)
- [LEAR](https://github.com/Glorf/lear): Linux Engine for Asset Retrieval
- [ghp](https://github.com/CurtisLusmore/ghp): A simple web server for serving static GitHub Pages locally
- [security.txt](https://securitytxt.org/): A proposed standard which allows websites to define security policies.
- [NFHTTP](https://github.com/spotify/NFHTTP): A cross platform C++ HTTP library that interfaces natively to other platforms.

#### Tokens

- [Use YubiKey security key to sign into AWS Management Console with YubiKey for multi-factor authentication](https://aws.amazon.com/pt/blogs/security/use-yubikey-security-key-sign-into-aws-management-console/)
- [Introducing the Qubes U2F Proxy](https://www.qubes-os.org/news/2018/09/11/qubes-u2f-proxy/)
- [YubiKey-Guide](https://github.com/drduh/YubiKey-Guide): Guide to using YubiKey for GPG and SSH
- [Using a Yubikey for GPG and SSH](https://0day.work/using-a-yubikey-for-gpg-and-ssh/): Sebastian Neef - 0day.work
- [PIN and Management Key](https://developers.yubico.com/yubikey-piv-manager/PIN_and_Management_Key.html)
- [Improve login security with challenge-response authentication](https://fedoramagazine.org/login-challenge-response-authentication/)

### VPN

- [How I made my own WireGuard VPN server](https://techcrunch.com/2018/07/28/how-i-made-my-own-wireguard-vpn-server/)
- [Secure & Ad-free Internet Anywhere With Streisand and Pi Hole](https://ifelse.io/2019/01/12/secure-ad-free-internet-anywhere-with-streisand-and-pi-hole/)
- [DSVPN](https://github.com/jedisct1/dsvpn): A Dead Simple VPN.
  
### Messaging

- [Tox](https://tox.chat/): The library provides all of the messaging and encryption facilities, and is completely decoupled from any user-interface; for an end-user to make use of Tox, they need a Tox client. MacOS Clients: [uTox](https://github.com/uTox/uTox/) and [qTox](https://github.com/qTox/qTox/).

## Continuous Integration

- [Danger](https://github.com/danger/danger) runs after your CI, automating your team's conventions surrounding code review.
- [The centralized Danger server, freeing Danger from running on CI.](https://github.com/danger/peril)
- [OSS-Fuzz](https://github.com/google/oss-fuzz) - Continuous Fuzzing for Open Source Software
- [Fedora's](http://fedoraproject.org/wiki/CI/Standard_Test_Interface) CI/Standard Test Interface
- [Do continuous deployment with Github and Python](https://fedoramagazine.org/continuous-deployment-github-python/)
- [Terraform](https://www.terraform.io/intro/index.html) ([github repo](https://github.com/hashicorp/terraform))
- [Best way to do linux clones for your CI](https://www.kernel.org/best-way-to-do-linux-clones-for-your-ci.html)
- [Terratest](https://github.com/gruntwork-io/terratest): is a Go library that makes it easier to write automated tests for your infrastructure code.
- [Creating a Faster Jekyll](https://sigpipe.macromates.com/2018/creating-a-faster-jekyll/)
- [Vespene](https://github.com/vespene-io/vespene): A modern continuous integration, deployment, and self-service automation platform
- [pytest-picked](https://github.com/anapaulagomes/pytest-picked): Run the tests related to the changed files (according to Git).
- [Quality Checking Infrastructure-as-Code](https://theithollow.com/2018/11/05/quality-checking-infrastructure-as-code/)
- [PyUP](https://pyup.io/): Automated Python Security and Dependency Updates. [github](https://github.com/pyupio/pyup)
- [Circle CI](https://circleci.com/)
- [Overalls](https://coveralls.io/): We help you deliver code confidently by showing which parts of your code aren’t covered by your test suite.
- [opsmop](https://opsmop.io/): next-gen automation. [github](https://github.com/opsmop/opsmop)
- [Canary analysis](https://cloud.google.com/blog/products/devops-sre/canary-analysis-lessons-learned-and-best-practices-from-google-and-waze): Lessons learned and best practices from Google and Waze
- [Spinnaker](https://github.com/spinnaker/spinnaker): is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.
- [Actions](https://github.com/maddox/actions): A collection of useful GitHub Actions.
- [When the going gets tough](https://lambdasec.github.io/When-the-going-gets-tough-Understanding-the-challenges-with-Product-commoditization-in-SCA/): Understanding the challenges with Product commoditization in SCA
- [Examples and customization tricks](https://docs.pytest.org/en/latest/example/index.html)

### Jenkins

- [Jenkinsfile](https://github.com/vivitc/learning-jenkinsfile) example by [vivitc](https://github.com/vivitc/)
- [Pythran as a bridge between fast prototyping and code deployment](http://serge-sans-paille.github.io/pythran-stories/pythran-as-a-bridge-between-fast-prototyping-and-code-deployment.html)
- [Adding a GitHub Webhook in Your Jenkins Pipeline](https://dzone.com/articles/adding-a-github-webhook-in-your-jenkins-pipeline)
- [Troubleshooting GitHub WebHooks SSL Verification](http://steve-jansen.github.io/blog/2014/12/03/troubleshooting-github-webhooks-ssl-verification/)
- [github - misconfigured SSL using webhooks](https://stackoverflow.com/questions/44337920/misconfigured-ssl-using-webhooks)
- [GitHub Plugin - Jenkins](https://wiki.jenkins.io/display/JENKINS/Github+Plugin)
- [Trigger Jenkins builds by pushing to Github](https://www.fourkitchens.com/blog/article/trigger-jenkins-builds-pushing-github/)
- [Add Users to Jenkins with "Allow users to sign up" Disabled](https://stackoverflow.com/questions/12056851/add-users-to-jenkins-with-allow-users-to-sign-up-disabled)

## Devops

- [Guiding Principles for Developer Tools](https://philcalcado.com/2019/07/30/developer_tools_principles.html)

## Interfaces

- [A sysadmin login session in a web browser](https://github.com/cockpit-project/cockpit)
- [tinywm](http://incise.org/tinywm.html): The tiniest window manager. [github](https://github.com/mackstann/tinywm)
- [nextspace](https://github.com/trunkmaster/nextspace): NeXTSTEP-like desktop environment for Linux
- [Term VM](https://gitlab.com/jD91mZM2/termwm): A floating WM of terminals inside your terminal

## Troubleshooting

- [sysdig](https://github.com/draios/sysdig): Linux system exploration and troubleshooting tool with first class support for containers
- [rbspy](https://rbspy.github.io/): Have a running Ruby program that you want to profile without restarting it? Want to profile a Ruby command line program really easily? You want rbspy! rbspy can profile any Ruby program by running 1 command.
- [drltrace](https://github.com/mxmssh/drltrace): Drltrace is a library calls tracer for Windows and Linux applications.

### Logs

- [Sigma](https://github.com/Neo23x0/sigma): Generic Signature Format for SIEM Systems
- [fluent-bit](https://github.com/fluent/fluent-bit): Fast and Lightweight Log processor and forwarder for Linux, BSD and OSX
- [GoAccess - Visual Web Log Analyzer](https://goaccess.io/)
- [Slagg](https://github.com/drrzmr/slagg) - Simple Log Aggregator
- [The Log File Navigator](https://lnav.org/downloads/) ([github](https://github.com/tstack/lnav))
- [Logging best practices to get the most out of application level logging](https://geshan.com.np/blog/2019/03/follow-these-logging-best-practices-to-get-the-most-out-of-application-level-logging-slides/)

### Benchmarks

- [test-profiles](https://github.com/phoronix-test-suite/test-profiles): A read-only Git copy of the OpenBenchmarking.org test profiles.
- [hardware-effects](https://github.com/Kobzol/hardware-effects): Demonstration of various hardware effects.

## Services

- [How to write LDAP search filters](https://confluence.atlassian.com/kb/how-to-write-ldap-search-filters-792496933.html)
- [LDAP Synchronization Connector](https://github.com/lsc-project/lsc)
- [LDAP Plugin Documentation](http://mutonufoai.github.io/pgina/documentation/plugins/ldap.html)
- [ADtoLDAP](https://github.com/nohupped/ADtoLDAP): A light weight Active Directory to OpenLDAP, or OpenLDAP to OpenLDAP Synchronization Connector written in Golang. 

## Network

- [TCP Tracepoints](http://www.brendangregg.com/blog/2018-03-22/tcp-tracepoints.html)
- [BCC](https://github.com/iovisor/bcc): Tools for BPF-based Linux IO analysis, networking, monitoring, and more
- [dhcpcd](https://roy.marples.name/git/dhcpcd.git/)
- [concurrency-limits](https://github.com/Netflix/concurrency-limits): Java Library that implements and integrates concepts from TCP congestion control to auto-detect concurrency limits to achieve optimal throughput with optimal latency [ [article](https://medium.com/@NetflixTechBlog/performance-under-load-3e6fa9a60581) ].
- [Debugging HTTPS](http://vafer.org/blog/20080221152526/)
  - Some [tcpdump](https://security.stackexchange.com/questions/65178/tcpdump-filter-expression-post-packets) examples.
- [Building my ideal router for $50]( https://blog.tjll.net/building-my-perfect-router/)
- [Detecting the use of "curl | bash" server side | Application Security](https://www.idontplaydarts.com/2016/04/detecting-curl-pipe-bash-server-side/)
- [Scapy](https://github.com/secdev/scapy/): the Python-based interactive packet manipulation program & library. Supports Python 2 & Python 3.
- [Ping test in a shell script](http://jeromejaglale.com/doc/unix/shell_scripts/ping)
- [OpenBGPD](https://labs.ripe.net/Members/claudio_jeker/openbgpd-adding-diversity-to-route-server-landscape): Adding Diversity to the Route Server Landscape
- [netbox](https://github.com/digitalocean/netbox): IP address management (IPAM) and data center infrastructure management (DCIM) tool.
- [￼￼￼NETWORK PROTOCOLS](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=97d3ba4c24d21147): for anyone who knows a programming language.
- [My complete OpenWrt Setup Guide](http://www.jauu.net/2015/03/03/complete-openwrt-guide/)
- [bnet](https://github.com/bkaradzic/bnet): Message oriented networking library using TCP transport.
- [openrsync](https://github.com/kristapsdz/openrsync): clean-room BSD-licensed implementation of rsync. [imported into the tree](https://undeadly.org/cgi?action=article;sid=20190211081518)
- [Using the NetworkManager’s DNSMasq plugin](https://fedoramagazine.org/using-the-networkmanagers-dnsmasq-plugin/).
- [pure JS WiFi QR Code Generator](https://qifi.org/). [github](https://github.com/evgeni/qifi)
- [Operating a Large, Distributed System in a Reliable Way](https://blog.pragmaticengineer.com/operating-a-high-scale-distributed-system/): Practices I Learned
- [Bond WiFi and Ethernet for easier networking mobility](https://fedoramagazine.org/bond-wifi-and-ethernet-for-easier-networking-mobility/)

### Network Troubleshooting

- [10 examples of Linux ss command to monitor network connections](https://www.binarytides.com/linux-ss-command/)
- [Viewing HAProxy Statistics](http://www.networkinghowtos.com/howto/viewing-haproxy-statistics/)
- [List all IP addresses connected to your Server](https://www.mkyong.com/linux/list-all-ip-addresses-connected-to-your-server/)
- [howmanypeoplearearound](https://github.com/schollz/howmanypeoplearearound): Count the number of people around you ￼ by monitoring wifi signals ￼
  
### NetServices

- [salmon](https://github.com/moggers87/salmon): Pythonic Mail Application Server forked from the last GPL'd release of Lamson
- [fast-cli](https://github.com/sindresorhus/fast-cli): Test your download speed using fast.com
- [speedtest-linux](https://github.com/rsvp/speedtest-linux): Get download/upload speeds via speedtest.net or fast.com from command line using Bash script -- suitable for logs. POSIX OSX Linux
- [speedtest-cli](https://github.com/sivel/speedtest-cli): Command line interface for testing internet bandwidth using speedtest.net
- [lwan](https://github.com/lpereira/lwan): Experimental, scalable, high performance HTTP server
- [tus resumable upload protocol](https://github.com/tus/tus-resumable-upload-protocol): Open Protocol for Resumable File Uploads
- [websocketd](https://github.com/joewalnes/websocketd): Turn any program that uses STDIN/STDOUT into a WebSocket server. Like inetd, but for WebSockets.

#### Email

- [jmap](https://github.com/jmapio/jmap): JSON Meta Application Protocol Specification (JMAP)
- [Cypht](https://github.com/jasonmunro/cypht): Lightweight Open Source webmail written in PHP and JavaScript

### DNS

- [lexicon](https://github.com/AnalogJ/lexicon): Manipulate DNS records on various DNS providers in a standardized way.
- [DNS flag day](https://dnsflagday.net/): The current DNS is unnecessarily slow and suffers from inability to deploy new features. To remediate these problems, vendors of DNS software and also big public DNS providers are going to remove certain workarounds on February 1st, 2019.
- [DNS Servers You Should Have Memorized](https://danielmiessler.com/blog/dns-servers-you-should-have-memorized/): The latest DNS server IPs are easier to remember and offer privacy and filtering functionality
- [BeGoneAds](https://github.com/anned20/begoneads) is a script that puts some popular hosts file lists into the systems hosts file as a adblocker measure.
- [PR-DNSd](https://github.com/korc/PR-DNSd): Passive-Recursive DNS daemon

### LoadBalancers

- [glb-director](https://github.com/github/glb-director): GitHub Load Balancer Director and supporting tooling.
- [Introduction to HAProxy ACLs](https://www.haproxy.com/blog/introduction-to-haproxy-acls/): HAProxy Technologies
- [skipper](https://github.com/zalando/skipper): An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress
- [memcached](https://github.com/memcached/memcached/wiki/Extstore): Memcached is a high performance multithreaded event-based key/value cache store intended to be used in a distributed system. Nice discussion about: [Caching beyond RAM: Riding the cliff](https://memcached.org/blog/nvm-multidisk/)

### Browsers

- [Firefox about:config privacy settings](https://gist.github.com/0XDE57/fbd302cef7693e62c769)
- [puppeteer-recorder](https://github.com/checkly/puppeteer-recorder): Puppeteer recorder is a Chrome extension that records your browser interactions and generat
- [ungoogled-chromium](https://github.com/Eloston/ungoogled-chromium): Modifications to Google Chromium for removing Google integration and enhancing privacy, control, and transparency
  - [Chromium & Netflix (and other DRM video websites)](https://ubuntu-mate.community/t/tutorial-chromium-netflix-and-other-drm-video-websites/7185)
- [DuckDuckGo Browser Extensions](https://github.com/duckduckgo/duckduckgo-privacy-extension): DuckDuckGo Privacy Essentials browser extension for Firefox, Chrome, Safari.
- [Firefox Profilemaker](https://ffprofile.com/)
- [Otter Browser](https://otter-browser.org/): Otter Browser aims to recreate the best aspects of the classic Opera (12.x) UI using Qt5.
- [thor](https://github.com/cisco/thor): Cisco's Thor Video Codec
- [OctoLinker](https://github.com/OctoLinker/OctoLinker): Links together, what belongs together

## Shell

<img src="https://www.cyberciti.biz/files/Linux%20Bash%20Shell%20Poster.jpg"  width="100" height="140"/>

- [Linux Shell Poster](https://www.cyberciti.biz/files/Linux%20Bash%20Shell%20Poster.jpg)
- [Software development using Bash](https://oscarforner.com/2018/02/24/Software_development_using_Bash)
- [Ten Things I Wish I’d Known About bash](https://zwischenzugs.com/2018/01/06/ten-things-i-wish-id-known-about-bash/)
- [cheat.sh](https://cheat.sh/) The only cheat sheet you need, Unified access to the best community driven documentation repositories of the world
- [cheatsheets](https://github.com/rstacruz/cheatsheets), and [bash](https://devhints.io/bash.html)
- [bash-oo-framework](https://github.com/niieani/bash-oo-framework): Bash Infinity is a modern boilerplate / framework / standard library for bash
- [sensible bash](https://github.com/mrzool/bash-sensible)
- [How to Jazz Up Your Bash Terminal](https://medium.freecodecamp.org/jazz-up-your-bash-terminal-a-step-by-step-guide-with-pictures-80267554cb22): A Step By Step Guide With Pictures
- Bashrc files:
  - [Paul's .bashrc](https://github.com/paulkaefer/.bashrc)
  - [rkirti/bashrc](https://github.com/rkirti/bashrc)
- DotFiles:
  - Amazing collection by [jessfraz](https://github.com/jessfraz/dotfiles/)
  - Some [dotfile](https://github.com/maitesin/dot-files) by maitesin
  - [pedrohenriquebr](https://github.com/pedrohenriquebr/dotfiles)
  - [chezmoi](https://github.com/twpayne/chezmoi): Manage your dotfiles securely across multiple machines.
- Powerline:
  - [Powerline Gitstatus](https://github.com/jaspernbrouwer/powerline-gitstatus)
  - [How to Jazz Up Your Bash Terminal](https://medium.freecodecamp.org/jazz-up-your-bash-terminal-a-step-by-step-guide-with-pictures-80267554cb22)— A Step By Step Guide With Pictures
  - [powerline-shell](https://github.com/b-ryan/powerline-shell): A beautiful and useful prompt for your shell
- Zsh files:
  - [Zim](https://github.com/zimfw/zimfw/) is a Zsh configuration framework with blazing speed and modular extensions.
  - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh): A delightful community-driven (with 1,100+ contributors) framework for managing your zsh configuration.
  - [powerlevel9k](https://github.com/bhilburn/powerlevel9k): The most awesome Powerline theme for ZSH around!
- Fish:
  - [fish-shell](https://github.com/fish-shell/fish-shell): The user-friendly command line shell.
  - [fisherman](https://github.com/fisherman/fisherman): The fish-shell plugin manager.  
- [15 Tips On How to Use 'Curl' Command in Linux](https://www.tecmint.com/linux-curl-command-examples/)
- [GoAWK](https://github.com/benhoyt/goawk): an AWK interpreter written in Go
- [Lambda Shell](http://www.lambdashell.com/)
- [Understanding Bash fork() Bomb ~ :(){ :|:& };:](https://www.cyberciti.biz/faq/understanding-bash-fork-bomb/)
- [bat](https://github.com/sharkdp/bat): A cat(1) clone with wings.
- [30 Handy Bash Shell Aliases For Linux / Unix / Mac OS X](https://www.cyberciti.biz/tips/bash-aliases-mac-centos-linux-unix.html)
- [kitty](https://sw.kovidgoyal.net/kitty/) - the fast, featureful, GPU based terminal emulator. [github](https://github.com/kovidgoyal/kitty)
- [xsv](https://github.com/BurntSushi/xsv): A fast CSV command line toolkit written in Rust.
- [PaperTTY](https://github.com/joukos/PaperTTY): PaperTTY - Python module to render a TTY on e-ink
- [smenu](https://github.com/p-gen/smenu): Terminal utility that allows you to use words coming from the standard input to create a nice selection wi
- [shark](https://github.com/satyarohith/shark): A CLI to Interact with DigitalOcean
- [t](https://github.com/sferik/t): A command-line power tool for Twitter.
- [up](https://github.com/akavel/up): Ultimate Plumber is a tool for writing Linux pipes with instant live preview
- [tztail](https://github.com/thecasualcoder/tztail): tztail (TimeZoneTAIL) allows you to view logs in the timezone you want.
- [Command-Line Snippets](https://snippets.shodan.io/): A place to share useful, one-line commands that make your life easier.
- [Writing Safe Shell Scripts](https://sipb.mit.edu/doc/safe-shell/): Writing shell scripts leaves a lot of room to make mistakes, in ways that will cause your scripts to break on certain input, or (if some input is untrusted) open up security vulnerabilities. Here are some tips on how to make your shell scripts safer.
- [funky](https://github.com/bbugyi200/funky):Funky takes shell functions to the next level by making them easier to define, more flexible, and more interactive.
- [Google Shell Style Guide](https://google.github.io/styleguide/shell.xml).
- [hexyl](https://github.com/sharkdp/hexyl): A command-line hex viewer.
- [Bass](https://github.com/edc/bass): Make Bash utilities usable in Fish shell.
- [Bash scripting cheatsheet](https://devhints.io/bash.html).
- [Problem solving with Unix commands](http://vegardstikbakke.com/unix/): I am starting to realize that the Unix command-line toolbox can fix absolutely any problem related to text wrangling. Let me tell you about a problem I had, and how I used some Unix command-line utilities to solve it.
- [Testing Bash with BATS](https://opensource.com/article/19/2/testing-bash-bats): The Bash Automated Testing System puts Bash code through the same types of testing processes used by Java, Ruby, and Python developers.
- [How to remove duplicate lines from files keeping the original order](https://iridakos.com/how-to/2019/05/16/remove-duplicate-lines-preserving-order-linux.html)
- [4 cool terminal multiplexers](https://fedoramagazine.org/4-cool-terminal-multiplexers/)
- [Set your terminal to automatically use tmux](https://fedoramagazine.org/4-tips-better-tmux-sessions/)
- [Pretty PuTTY](https://github.com/jacktrocinski/pretty-putty): Make PuTTY pretty and apply modern PuTTY settings.
- Getopts:
  - [Parsing bash script options with getopts](https://sookocheff.com/post/bash/parsing-bash-script-arguments-with-shopts/)
  - [Bash Getopts](https://linuxhint.com/bash_getopts_example/)
  - [Com getopts, seus scripts ficam mais profissionais](https://www.ibm.com/developerworks/community/blogs/752a690f-8e93-4948-b7a3-c060117e8665/entry/getopts_scripts_mais_profissionais?lang=en)
  - [Fatiando opções com o getopts](https://www.dicas-l.com.br/arquivo/fatiando_opcoes_com_o_getopts.php)
  - [Getopts - Opções em bash script](http://www.dicas-l.com.br/arquivo/getopts_opcoes_em_bash_script.php)
- [arg_parse_example](https://github.com/mattbryson/bash-arg-parse/blob/master/arg_parse_example)
- [How Bash completion works](https://tuzz.tech/blog/how-bash-completion-works)
 
### Regex

- [The true power of regular expressions](https://nikic.github.io/2012/06/15/The-true-power-of-regular-expressions.html)
- [TRE](http://ducktape.blot.im/tre-a-regex-engine-with-approximate-matching): A Regex Engine with Approximate Matching
- [Deu match](http://turicas.info/slides/expressoes-regulares/): limpando dados com expressões regulares
- [Rant](https://github.com/TheBerkin/rant): The all-purpose procedural text library

### Editors

- [vscode-cpptools](https://github.com/Microsoft/vscode-cpptools): Official repository for filing issues against and getting support for the Microsoft C/C++ extension for VS Code
- [SubEthaEdit](https://github.com/kubernetes-sigs/kind): Code, Write, Edit. Together. [github](https://github.com/subethaedit/SubEthaEdit)
- [Open source collaborative text editors](https://juretriglav.si/open-source-collaborative-text-editors/)

#### Vim/vi

- [Spotify integration for vim](https://github.com/mattpenney89/vimify)
- [Vim plugin](https://github.com/mechatroner/rainbow_csv): Highlight columns in CSV and TSV files and run queries in SQL-like language
- [vim-prettier](https://github.com/prettier/vim-prettier): A Vim plugin for Prettier
- [vimium](https://github.com/philc/vimium):  Vimium is a Chrome extension that provides keyboard-based navigation and control of the web in the spirit of the Vim editor.
- [vimari](https://github.com/guyht/vimari): Safari port of vimium
- [vim-plug](https://github.com/junegunn/vim-plug): hibiscus Minimalist Vim Plugin Manager
- [gruvbox](https://github.com/morhetz/gruvbox): Retro groove color scheme for Vim
- [vim-hue](https://foolcontrol.org/?p=3051): Thus “vim-hue” was born, featuring “vim-hue” dark Vim colorscheme and complete Vim configuration. Ideal for anyone using Vim and any of the following on daily basis: Shell (Bash), Golang, Python, Terraform, Ansible, Docker (Dockerfile), et cetera ... [github](https://github.com/AdnanHodzic/vim-hue)

## Other Resources

- [16 Linux Books and Videos for System Administrator](https://geekflare.com/linux-books-videos/)
- [open-guides/og-aws: 📙 Amazon Web Services — a practical guide](https://github.com/open-guides/og-aws)
- [Maintaining your AWS infrastructure](https://medium.com/faun/maintaining-your-aws-infrastructure-a4ae6ced8a74)
- [lerna](https://github.com/lerna/lerna): A tool for managing JavaScript projects with multiple packages.
- [SSH Examples, Tips & Tunnels](https://hackertarget.com/ssh-examples-tunnels/)
- [Power of SSH Tunneling](https://medium.com/tarkalabs/power-of-ssh-tunneling-cf82bc56da67)
- [Fighting complexity in software development](https://github.com/atsapura/CardManagement/blob/master/article/Fighting%20complexity%20in%20software%20development.md)

### Books

- [BPF Performance Tools](http://www.brendangregg.com/blog/2019-07-15/bpf-performance-tools-book.html): Linux System and Application Observability (book)

## Filesystems

- [diskover](https://n0where.net/file-system-crawler-diskover): File System Crawler. [github](https://github.com/shirosaidev/diskover)
- [BetrFS](http://www.betrfs.org): The Bε-tree File System, or BetrFS, is an in-kernel file system that uses Bε trees to organize on-disk storage. Bε trees are a write-optimized dictionary, and offer the same asymptotic behavior for sequential I/O and point queries as a B-tree. [github](https://github.com/oscarlab/betrfs).
- [exFAT](https://github.com/relan/exfat): Free exFAT file system implementation
- [Share NFS Home Directories Securely with Kerberos](https://fedoramagazine.org/secure-nfs-home-directories-kerberos/)
- [folderstats](https://github.com/njanakiev/folderstats): Python module that creates statistics from a folder structure
- [Rethinking files](https://www.devever.net/~hl/objectworld)

## Unix

- [UNIX Syscalls](https://john-millikin.com/unix-syscalls)
- [KVM virt-install: Install OpenBSD As Guest Operating System - nixCraft](https://www.cyberciti.biz/faq/kvmvirtualization-virt-install-openbsd-unix-guest/)
- [SCCS](http://sccs.sourceforge.net): is an implementation of the POSIX standard Source Code Control System. It provides actively maintained code based on the original UNIX SCCS code OpenSourced by Sun as part of OpenSolaris and was made portable to other platforms.
- (pt-br) [hoc](https://github.com/ramalho/hoc): A mini-linguagem do livro 'The Unix Programming Environment", com explicações em PT-BR
- [s-tui](https://amanusk.github.io/s-tui/): s-tui is a terminal UI for monitoring your computer. [github](https://github.com/amanusk/s-tui), [news](https://www.cyberciti.biz/python-tutorials/monitor-linux-cpu-temperature-frequency-power-in-a-graphical-way/)
- [unix-history-repo](https://github.com/dspinellis/unix-history-repo): Continuous Unix commit history from 1970 until today.

## Virtualization

- [OSX-KVM: Run El Capitan, macOS Sierra, High Sierra and Mojave on QEMU/KVM. No support is provided at the moment.](https://github.com/kholia/OSX-KVM)
- [macOS-Simple-KVM](https://github.com/foxlet/macOS-Simple-KVM/): Tools to set up a quick macOS VM in QEMU, accelerated by KVM.
- [Windows 2000 on your browser](https://bellard.org/jslinux/vm.html?url=https://bellard.org/jslinux/win2k.cfg&mem=192&graphic=1&w=1024&h=768)
- [hvpp](https://github.com/wbenny/hvpp) is a lightweight Intel x64/VT-x hypervisor written in C++ focused primarily on virtualization of already running operating system
- [Windows 95](https://github.com/felixrieseberg/windows95) in Electron. Runs on macOS, Linux, and Windows.
- [q3vm](https://github.com/jnz/q3vm): Q3VM - Embeddable bytecode virtual machine/interpreter for C-language input
- [Hypervisor From Scratch – Part 1: Basic Concepts & Configure Testing Environment](https://rayanfam.com/topics/hypervisor-from-scratch-part-1/)
- [anbox](https://github.com/anbox/anbox): Anbox is a container-based approach to boot a full Android system on a regular GNU/Linux system
- [UNSAT](https://unsat.cs.washington.edu/projects/hyperkernel/): Hyperkernel
- [Largest small system emulator](http://ioccc.org/2013/cable3/hint.html)
- [Intel Virtualisation](https://binarydebt.wordpress.com/2018/10/14/intel-virtualisation-how-vt-x-kvm-and-qemu-work-together/): How VT-x, KVM and QEMU Work Together
- [IncludeOS](https://github.com/hioa-cs/IncludeOS): is an includable, minimal unikernel operating system for C++ services running in the cloud.
- [kubectl trace](https://github.com/fntlnz/kubectl-trace): Schedule bpftrace programs on your kubernetes cluster using the kubectl
- [dive](https://github.com/wagoodman/dive): A tool for exploring each layer in a docker image
- [Firecracker](https://github.com/firecracker-microvm/firecracker): Secure and fast microVMs for serverless computing.
- [kind](https://github.com/kubernetes-sigs/kind): Kubernetes IN Docker - local clusters for testing Kubernetes
- [Introducing Crossplane](https://blog.upbound.io/introducing-crossplane-open-source-multicloud-control-plane/): Open Source Multicloud Control Plane. [github](https://github.com/crossplaneio/crossplane)
- [Write your Own Virtual Machine](https://justinmeiners.github.io/lc3-vm/) with [code repo](https://github.com/justinmeiners/lc3-vm)
- [Running FreeBSD on OSX using](https://dan.langille.org/2018/10/02/running-freebsd-on-osx-using-xhyve-a-port-of-bhyve/) [xhyve](https://github.com/machyve/xhyve), a port of [bhyve](http://www.bhyve.org/)
- [applepie](https://github.com/gamozolabs/applepie): A hypervisor for fuzzing built with WHVP and Bochs.
- [V3VEE](http://v3vee.org/) - An Open Source Virtual Machine Monitor Framework For Modern Architectures
- [IceBox](https://github.com/thalium/icebox): Icebox is a Virtual Machine Introspection solution that enable you to stealthily trace and debug any process (kernel or user). It's based on project Winbagility.

### VMware

- [The ghettoVCB](https://github.com/lamw/ghettoVCB) script performs backups of virtual machines residing. Here on [VMware Communities](https://code.vmware.com/samples/822/ghetto-vcb?h=Sample)
- [Concord-BFT](https://github.com/vmware/concord-bft): a Distributed Trust Infrastructure

### Containers

- [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)
- [Imagem CentOS7 com firefox ESR e warsaw configurado.](https://github.com/jsalatiel/wsbb-docker) (pt-BR) and [other](https://gist.github.com/dmouse/e76ce3d8dde00fe496da)
- [google chrome](https://github.com/c0b/chrome-in-docker) dockerized and [headless google chrome](https://github.com/eirslett/chrome-karma-docker), [another](https://github.com/miyakogi/pyppeteer)
- Some [fedora](https://github.com/fedora-cloud/docker-brew-fedora/) and [docker](https://docs.docker.com/samples/) links:
  - [Webapps with Docker](https://github.com/docker/labs/blob/master/beginner/chapters/webapps.md)
  - Various great [Dockerfiles](https://github.com/jessfraz/dockerfiles) by jessfraz (as usual)
- [Running a GUI application in a Docker container](https://linuxmeerkat.wordpress.com/2014/10/17/running-a-gui-application-in-a-docker-container/)
- [img](https://github.com/genuinetools/img): Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.
- [Test containers with Python and Conu](https://fedoramagazine.org/test-containers-python-conu/)
- [landrush](https://github.com/vagrant-landrush/landrush): A Vagrant plugin that provides a simple DNS server for Vagrant guests
- [rubber-docker](https://github.com/Fewbytes/rubber-docker): A workshop on Linux containers: Rebuild Docker from Scratch
- [tsuru](https://github.com/tsuru/tsuru): Open source, extensible and Docker-based Platform as a Service (PaaS).
- [awesome-tsuru](https://github.com/rafaeleyng/awesome-tsuru): Curated extensions and resources for Tsuru, the open source, extensible and Docker-based PaaS
- [You might not need Kubernetes](https://blog.jessfraz.com/post/you-might-not-need-k8s/)
- [etcd](https://github.com/etcd-io/etcd): Distributed reliable key-value store for the most critical data of a distributed system
- [Goldpinger](https://github.com/bloomberg/goldpinger): Debugging tool for Kubernetes which tests and displays connectivity between nodes in the cluster.
- [Docker Immutable Workstation](https://github.com/mikadosoftware/workstation): Docker based portable Workstation
- [9 Kubernetes Security Best Practices Everyone Must Follow](https://www.cncf.io/blog/2019/01/14/9-kubernetes-security-best-practices-everyone-must-follow/)
- [cilium](https://github.com/cilium/cilium/): API Aware Networking and Security using BPF and XDP
- [slim](https://github.com/ottomatica/slim): Build and run tiny vms from Dockerfiles. Small and sleek.
- [Intro Guide to Dockerfile Best Practices](https://blog.docker.com/2019/07/intro-guide-to-dockerfile-best-practices/)

#### Lambda

- [Cloud Computing without Containers](https://blog.cloudflare.com/cloud-computing-without-containers/?hH)
- [The Global Serverless Platform](https://zeit.co), [demo](https://serverless-bash.now.sh/)

## Android

- Android Developers Blog - [Introducing Oboe](https://android-developers.googleblog.com/2018/10/introducing-oboe-c-library-for-low.html): A C++ library for low latency audio
- [My Homeassistant configuration](https://github.com/eifinger/homeassistant-config)
- [Don't kill my app!](https://dontkillmyapp.com/): To squeeze a little extra battery out of your phone, Android device vendors listed below (with their bad vendor score) cripple apps and make them useless.

## Mac

- [Using AppleScript how do I click a button in a dialog within a window that has no name/title?](https://stackoverflow.com/questions/7355763/using-applescript-how-do-i-click-a-button-in-a-dialog-within-a-window-that-has-n)
- [Making the Touch Bar finally useful](http://vas3k.com/blog/touchbar/)
- [iTerm2](https://github.com/gnachman/iTerm2) is a terminal emulator for Mac OS X that does amazing things.
- [kemon](https://github.com/didi/kemon): An Open-Source Pre and Post Callback-Based Framework for macOS Kernel Monitoring.
- [linuxify](https://github.com/fabiomaia/linuxify): 🍏🐧 Transparently transform the macOS CLI into a fresh GNU/Linux CLI experience.
- [MicroMDM](https://micromdm.io/)
- [Package Config](https://github.com/orta/PackageConfig): A Swift Package that allows you to define configuration settings inside a Package.swift
- [iSh](https://github.com/tbodt/ish): Linux shell for iOS
- [osxfuse](https://github.com/osxfuse/osxfuse): FUSE extends macOS by adding support for user space file systems
- [MacPass](https://github.com/MacPass/MacPass): A native OS X KeePass client
- [CoreXLSX](https://github.com/MaxDesiatov/CoreXLSX): Excel spreadsheet (XLSX) format support in pure Swift, by [max desiatov](https://desiatov.com/swift-codable-xlsx/#title)
- [istatserverlinux](https://github.com/bjango/istatserverlinux): A system monitoring daemon that sends stats to Send stats to iStat View for iOS and iStat View for macOS.
- [istatserver-dsm](https://bitbucket.org/jpboivin/istatserver-dsm): iStatserver for Synology DSM.
- [Shell scripts for customized macOS machine setup and configuration.](https://github.com/bkuhlmann/mac_os-config)
- [SourceKit-LSP](https://github.com/apple/sourcekit-lsp): Language Server Protocol implementation for Swift and C-based languages.
- [apple libc uses perl](https://github.com/Apple-FOSS-Mirror/Libc/blob/2ca2ae74647714acfc18674c3114b1a5d3325d7d/gen/wordexp.c#L192)
- [Sloth](https://github.com/sveinbjornt/Sloth): Mac app that shows all open files and sockets in use by all running processes. Nice GUI for lsof.
- [insert_dylib](https://github.com/Tyilo/insert_dylib): Command line utility for inserting a dylib load command into a Mach-O binary
- [ds_store](https://github.com/al45tair/ds_store): lets you examine and modify .DS_Store files from Python code; since it is written in pure Python, it is portable and will run on any platform, not just Mac OS X.

## Windows

- [coreclr](https://github.com/dotnet/coreclr): This repo contains the .NET Core runtime, called CoreCLR, and the base library, called System.Private.Corelib (or mscorlib).
- [Monitoring and Observability in the .NET Runtime](http://mattwarren.org/2018/08/21/Monitoring-and-Observability-in-the-.NET-Runtime/)
- [Powershell-SSHTools](https://github.com/fridgehead/Powershell-SSHTools): A bunch of useful SSH tools for powershell
- [PowerShellAtomicHarness](https://github.com/caseysmithrc/PowerShellAtomicHarness): Execute Test Cases In PowerShell
- [The early history of Windows file attributes, and why there is a gap between System and Directory](https://blogs.msdn.microsoft.com/oldnewthing/20180830-00/?p=99615)
- [SysmonTools](https://github.com/nshalabi/SysmonTools): Utilities for Sysmon
- [WoW64 internals](https://wbenny.github.io/2018/11/04/wow64-internals.html): aka Windows (32-bit) on Windows (64-bit) - is a subsystem that enables 32-bit Windows applications to run on 64-bit Windows.
- [Installing sqlcmd without SQL Server](http://daveslog.com/2017/03/19/installing-sqlcmd-without-sql-server/)
- [Running vROpsCLI on Windows](http://www.vmspot.com/vropscli-on-windows/)
- [windows-dev-box-setup-scripts](https://github.com/Microsoft/windows-dev-box-setup-scripts)
- [qemu-img for WIndows](https://cloudbase.it/qemu-img-windows/)
- [OrgKit](https://github.com/SwiftOnSecurity/OrgKit): Provision a brand-new company with proper defaults in Windows, Offic365, and Azure
- [example-azure-node](https://github.com/sdras/example-azure-node): An example Node webapp deployed with GitHub actions.
- [Reset a Windows 10 password](https://4sysops.com/archives/reset-a-windows-10-password/): The method to reset a Windows 10 password depends on the account type. A Microsoft account requires a different procedure than a local account requires.
- [Get SID from Linux ldapsearch in Active Directory](https://bgstack15.wordpress.com/2018/02/26/get-sid-from-linux-ldapsearch-in-active-directory/)
- [ObjectSID Trouble](https://ldapwiki.com/wiki/ObjectSID)
- [Gmail on NT 3.51 with IE 1.5](https://virtuallyfun.com/wordpress/2019/07/12/gmail-on-nt-3-51-with-ie1-5-via-wrp-4-1/) via [WRP](https://github.com/tenox7/wrp)
- [Modifying Windows local accounts with Fedora and chntpw](https://fedoramagazine.org/modifying-windows-local-accounts-with-fedora-and-chntpw/)
- [Enabling Windows' DNS Server to Validate DNSSEC](https://blog.cdemi.io/enabling-windows-dns-server-to-validate-dnssec/)
  
---

## Datacenter

- [The Datacenter as a Computer: Designing Warehouse-Scale Machines, Third Edition](https://www.morganclaypool.com/doi/10.2200/S00874ED3V01Y201809CAC046)
- [Automating Datacenter Operations at Dropbox](https://blogs.dropbox.com/tech/2019/01/automating-datacenter-operations-at-dropbox/)

## Support

- [Open MCT](https://nasa.github.io/openmct/): is a next-generation mission control framework for visualization of data on desktop and mobile devices - [github](https://github.com/nasa/openmct)

### Video Conference

- [Hublin](https://github.com/linagora/hublin): An easy and free video conference service based on WebRTC
- [PeerTube](https://github.com/Chocobozzz/PeerTube): Federated (ActivityPub) video streaming platform using P2P (BitTorrent) directly in the web browser with WebTorrent and Angular.
- [Vialer-js](https://github.com/vialer/vialer-js): Open-source WebRTC communication platform.
- [Jitsi](https://jitsi.org/): Multi-platform open-source [video conferencing](https://github.com/jitsi/jitsi-meet)
- [webtty](https://github.com/maxmcd/webtty): Share a terminal session over WebRTC
- [webrtc-qr](https://github.com/AquiGorka/webrtc-qr): WebRTC Connect [Experiment](https://webrtc-qr.surge.sh/)

## Management

- [8 Patterns for Decentralised Organising](https://standupdev.com/wiki/doku.php?id=patterns_for_decentralised_organising)
- [Zulip server](https://github.com/zulip/zulip/) - powerful open source team chat
- [awesome-leading-and-managing](https://github.com/LappleApple/awesome-leading-and-managing): Awesome List of resources on leading people and being a manager. Geared toward tech, but potentially useful to anyone.
- [Agile Lite](https://github.com/davebs/AgileLite): Agile without all the burnout.
- [7 rules of hiring a remote team for your project](https://cvcompiler.com/blog/7-rules-of-hiring-a-remote-team-for-your-project/)

## Career

- [A Career Cold Start Algorithm](http://boz.com/articles/career-cold-start.html)
- [How to say “no” to your boss, your boss’s boss, and even the CEO](https://codewithoutrules.com/2018/08/16/how-to-say-no/)
- [test-your-sysadmin-skills](https://github.com/trimstray/test-your-sysadmin-skills): A collection of *nix Sysadmin Test Questions and Answers for Interview/Exam (2018 Edition).
- [Careers outside of academia with a PhD in volcanology](https://volcanologistsoutsideacademia.wordpress.com/2018/08/29/spotlight-john-a-stevenson-ph-d/)
- [ToolsOfTheTrade](https://github.com/cjbarber/ToolsOfTheTrade): Tools of The Trade, from Hacker News.
- [test-your-sysadmin-skills](https://github.com/trimstray/test-your-sysadmin-skills): A collection of *nix Sysadmin Test Questions and Answers for Interview/Exam (2018 Edition). Test your knowledge in different fields with these Q/A.
- [Don’t work “remotely”](http://blairreeves.me/2018/11/09/dont-work-remotely/)
- [The First 100 Course](https://docs.google.com/document/d/104qgagSsp2rQQEDORGbYC0uqt0neYHCPxu-aUl4CuSQ/): Measure the strength of your idea with real customers.
- [20 Questions To Ask Before Joining A Startup](https://hharnisc.github.io/2018/11/25/twenty-questions-to-ask-before-joining-a-startup.html)
- [4 Mentorship Archetypes](https://g-rand.com/2018/12/04/4-mentorship-archetypes/)
- [On Shutting Down](https://blog.ycombinator.com/shutting-down/).
- [How I Built A $5,000 Per Month Side Project](https://campfirelabs.co/blog-1/2019/1/10/how-i-built-a-5000-per-month-side-project)
- [The Future of Work Framework](https://blogs.nasa.gov/futureofwork/2018/11/15/the-future-of-work-framework/)
- [Why work at Stripe when you could run your own business?](https://www.kalzumeus.com/2019/3/18/two-years-at-stripe/)
- [Defining a Distinguished Engineer](https://blog.jessfraz.com/post/defining-a-distinguished-engineer/)
- [working for a startup makes increasingly less sense](https://jatins.gitlab.io/me/why-startup/)
- [on internal engineering practices at amazon](https://jatins.gitlab.io/me/amazon-internal-tools/)
- [Your Network Determines Success More than You Realize](https://medium.com/swlh/your-network-determines-success-more-than-you-realize-41a3e889ecea)
- [How NOT to hire a software engineer](http://tonsky.me/blog/hiring/)  
- [Productivity Isn’t About Time Management. It’s About Attention Management.](https://www.nytimes.com/2019/03/28/smarter-living/productivity-isnt-about-time-management-its-about-attention-management.html)
- [Things I Learnt The Hard Way (in 30 Years of Software Development)](https://blog.juliobiason.net/thoughts/things-i-learnt-the-hard-way/)
- [What is a 1x Engineer?](https://1x.engineer/) - [github](https://github.com/cutenode/1x.engineer)
- [No CS Degree](https://www.nocsdegree.com/about/)
- [Want to hire the best programmers? Offer growth.](https://triplebyte.com/blog/want-hire-best-programmers-offer-growth)
- [All the best engineering advice I stole from non-technical people](https://medium.com/@bellmar/all-the-best-engineering-advice-i-stole-from-non-technical-people-eb7f90ca2f5f)
  
## Presentations

- [How to import an SVG into Powerpoint or Keynote](https://medium.com/@kyleledbetter/how-to-import-an-svg-into-powerpoint-or-keynote-8d3d70f347a7)
- (pt-br) [Guia para eventos acessíveis](https://medium.com/uxconfbr/guia-para-eventos-acessiveis-como-fazer-apresentacoes-parte-i-137317610631): como fazer apresentações (parte I)
- (pt-br) [Guia para eventos acessíveis](https://medium.com/uxconfbr/guia-para-eventos-acess%C3%ADveis-como-fazer-apresenta%C3%A7%C3%B5es-parte-ii-ab84932bd8a2): como fazer apresentações (parte II)
- [fusuma](https://github.com/hiroppy/fusuma): ✍️Fusuma makes slides with Markdown easily.

---

## Organization

- [Shiori](https://github.com/RadhiFadlillah/shiori) is a simple bookmarks manager written in Go language
- [reminiscence](https://github.com/kanishka-linux/reminiscence): Self-Hosted Bookmark and Archive Manager
- [Photograph Your Work](https://etbe.coker.com.au/2019/01/06/photograph-your-work/)
- [How I Manage My Time](https://zwischenzugs.com/2017/12/03/how-i-manage-my-time/): by zwischenzugs
- [Ask HN: How do you keep track of your creative thoughts? | Hacker News](https://news.ycombinator.com/item?id=18837345)

## Knowlegde

- [trilium](https://github.com/zadam/trilium): Build your personal knowledge base with Trilium Notes

---

## Tools

- [qr-filetransfer](https://github.com/claudiodangelis/qr-filetransfer):Transfer files over wifi from your computer to your mobile device by scanning a QR code without leaving the terminal.
- [robotjs](https://github.com/octalmage/robotjs): Node.js Desktop Automation.
- [Whatsapp Automation](https://github.com/mnkgrover08/whatsapp_automation) is a collection of APIs that interact with WhatsApp messenger runn
- [pbec](https://github.com/wilvk/pbec): Polaris Bios Editor for the Console
- [zero](https://github.com/KonstantinSchubert/zero): Local file system transparently swapping to the cloud
- [pdiary](https://github.com/manipuladordedados/pdiary)
- [jabcode](https://github.com/jabcode/jabcode): color bar code.
- [elasticsearch-dump](https://github.com/taskrabbit/elasticsearch-dump): Import and export tools for elasticsearch
- [How to merge or split pdf files using convert](https://linuxcommando.blogspot.com/2015/03/how-to-merge-or-split-pdf-files-using.html)
- [rga](https://phiresky.github.io/blog/2019/rga--ripgrep-for-zip-targz-docx-odt-epub-jpg/):ripgrep, but also search in PDFs, E-Books, Office documents, zip, tar.gz, etc. [github repo](https://github.com/phiresky/ripgrep-all)
- [GNU GREP and RIPGREP](https://github.com/learnbyexample/learn_gnugrep_ripgrep): Example based guide to mastering GNU grep and ripgrep.
- [Leon](https://github.com/leon-ai/leon): is your open-source personal assistant.
- [Code Shelter](https://www.codeshelter.co/): Code Shelter is a collective of volunteer software developers that aims to help with maintaining popular open source projects whose authors need a hand or don't have the time to maintain them any more.
- [github personal-website](https://github.com/github/personal-website): Code that'll help you kickstart a personal website that showcases your work as a software developer.
- [code-server](https://github.com/codercom/code-server): Run VS Code on a remote server.
- [awesome-python-login-model](https://github.com/CriseLYJ/awesome-python-login-model): login access for webscrapping.
- [Bloom](https://www.kerkour.fr/blog/bloom-a-free-and-open-source-google/): a free and open source Google
- [baxx.dev](https://txt.black/~jack/baxx-dev.txt): It is a backup service with unix philosophy in mind, and curl as main interface and (soon) machine learning alerting.
- [3 cool text-based email clients](https://fedoramagazine.org/3-cool-text-based-email-clients/): The Fedora OS provides a large choice of email clients and among these are text-based email applications.
- [Setting kernel command line arguments with Fedora 30](https://fedoramagazine.org/setting-kernel-command-line-arguments-with-fedora-30/).
- [Pattern-dreamer](https://github.com/Andrew-Kang-G/pattern-dreamer): Get urls with missing protocol & uris with missing domain & emails etc. in texts and parse them.
- [Customizing pandoc to generate beautiful pdfs from markdown](https://learnbyexample.github.io/tutorial/ebook-generation/customizing-pandoc/).
- [Jeffrey's Image Metadata Viewer](http://exif.regex.info/exif.cgi): This tool remains available so long as I can keep it free and the bandwidth doesn't cost me too much.
- [OpenPDF](https://github.com/LibrePDF/OpenPDF): is a free Java library for creating and editing PDF files with a LGPL and MPL open source license. OpenPDF is based on a fork of iText. We welcome contributions from other developers. Please feel free to submit pull-requests and bugreports to this GitHub repository.

### JSON

- [gron](https://github.com/tomnomnom/gron/): Make JSON greppable!
- [JSON Web Tokens (JWT)](https://github.com/dwyl/learn-json-web-tokens): 🔐 Learn how to use JSON Web Token (JWT) to secure your next Web App! (Tutorial/Example with Tests!!)
- [simdjson](https://github.com/lemire/simdjson): Parsing gigabytes of JSON per second.

### WebTools

- [The new Turtl server](https://github.com/turtl/server): evernote [alternative](https://tavernalinux.com/turtl-alternativa-open-source-ao-evernote-instalação-e-review-e84f7aa2d483) free software.
- [OPENBAZAAR](https://www.openbazaar.org/): decentralized marketplace server in go ([repo](https://github.com/OpenBazaar/openbazaar-go))
- [octalmage/robotjs: Node.js Desktop Automation.](https://github.com/octalmage/robotjs)
- [MapTiler - map overlay, cut map tiles for Google Maps, GIS layers and mobile apps – MapTiler](https://www.maptiler.com/)
- [typegram](http://pt.tgr.am/)
- [Ultralight](https://ultralig.ht/)- HTML UI Engine
- [Retool](https://tryretool.com/): Custom internal tools have the same building blocks. Retool gives you those building blocks, so you can build them much faster.
- [GRID: A simple visual cheatsheet for CSS Grid Layout](http://grid.malven.co/)
- [PyPy.js](https://pypyjs.org/) is an experiment in building a fast and compliant python environment for the web. [github](https://github.com/pypyjs/pypyjs)
- [strest](https://github.com/eykhagen/strest): ⚡️ Set up tests for REST in seconds with YAML
- [StaticGen](https://www.staticgen.com/): Top Open Source Static Site Generators
- [responder](https://github.com/kennethreitz/responder): a Sorta Familar HTTP Framework for Python (prototype)
- [Design faster web pages, part 1: Image compression](https://fedoramagazine.org/design-faster-web-pages-part-1-image-compression/)
- [Nebular](https://github.com/akveo/nebular): Angular 6 Components, Auth and Security
- [sourcegraph](https://github.com/sourcegraph/sourcegraph): Code search and intelligence, self-hosted and scalable
- [md-page](https://github.com/oscarmorrison/md-page): 📝 create a webpage with just markdown
- [Avatars, identicons, and hash visualization](https://barro.github.io/2018/02/avatars-identicons-and-hash-visualization/)
- [Plus codes](https://plus.codes/)
- [share and discover links - appread.me](http://appread.me/)
- [PyRoles](https://github.com/juditecypreste/PyRoles): Este é um bot no Telegram que faz upload automático de todas as fotos dos rolês que rolaram durante a PyBR!
- [Twitter-Bots](https://github.com/internetlab-br/Twitter-Bots): Códigos utilizados para pesquisar sobre bots em perfis do Twitter
- [thelounge](https://github.com/thelounge/thelounge): Modern, responsive, cross-platform, self-hosted web IRC client.
- [qr-image](https://github.com/alexeyten/qr-image): This is yet another QR Code generator.
- [gogs](https://github.com/gogs/gogs): Gogs is a painless self-hosted Git service.
- [bitwarden](https://bitwarden.com/): online and free password manager. [core](https://github.com/bitwarden/core) on github.
- [writefreely](https://github.com/writeas/writefreely): A painless, simple, federated blogging platform.
- [markdownlint](https://github.com/DavidAnson/markdownlint): A Node.js style checker and lint tool for Markdown/CommonMark files.
- [Notepin](https://notepin.co/): Extremely simple note taking
- [Startpage](https://www.startpage.com/): privacy search.
- [Next](https://next.atlas.engineer/) Browser: Be Productive. [github](https://github.com/atlas-engineer/next)
- [ulid](https://github.com/ulid/spec): The canonical spec for ulid - Universally Unique Lexicographically Sortable Identifier.
- [MKCERT](https://blog.filippo.io/mkcert-valid-https-certificates-for-localhost/): VALID HTTPS CERTIFICATES FOR LOCALHOST, [github](https://github.com/FiloSottile/mkcert).
- [uncaptcha2](https://github.com/ecthros/uncaptcha2): defeating the latest version of ReCaptcha with 91% accuracy
- [DeleteFB](https://github.com/weskerfoot/DeleteFB): A Selenium script to delete your Facebook content.
- [TicketLens](https://www.ticketlens.com/en): Find the best tickets, tours, and activities and compare prices from different websites.
- [WeasyPrint](https://github.com/Kozea/WeasyPrint): WeasyPrint converts web documents (HTML with CSS, SVG, …) to PDF.
- [grid-kiss playground](https://sylvainpolletvillard.github.io/grid-kiss-playground/index.html#multiple-span-zones)
- [OpenTeams](https://openteam.info/): Quick organizational mapping with email and survey data
- [Protocol buffers](https://developers.google.com/protocol-buffers/) are a language-neutral, platform-neutral extensible mechanism for serializing structured data.
- [FeaturePeek](https://featurepeek.com/): Front-end review for the whole team.

#### Domains

- [Check domain name availability with bash and whois](https://linuxconfig.org/check-domain-name-availability-with-bash-and-whois)
- [namegrep](https://namegrep.com/)
- [10 Fantastic Tools to Find Smart Domain Name for Your Business](https://geekflare.com/find-domain-name/)
- [dnstwist](https://github.com/elceef/dnstwist): Domain name permutation engine for detecting typo squatting, phishing and corporate espionage
- [Dictionary Domains](http://www.dictionarydomains.co/)
- [Python Script for Getting Data You Need From Domain Names Lists](https://domains-index.com/tips-using-domains-indexs-lists/)
- [Creating python dictionary that maps each domain to multiple coded values in File Geodatabase?](https://gis.stackexchange.com/questions/197834/creating-python-dictionary-that-maps-each-domain-to-multiple-coded-values-in-fil)
- [dnsimple-python](https://github.com/onlyhavecans/dnsimple-python): Python API client for DNSimple's Domain Management Automation

#### Webdev

- [Always. Own. Your platform.](http://www.alwaysownyourplatform.com/)
- [HTTP/3](https://blog.cloudflare.com/http-3-from-root-to-tip/): From root to tip
- [30-seconds-of-code](https://github.com/30-seconds/30-seconds-of-code): Curated collection of useful JavaScript snippets that you can understand in 30 seconds or less.
- [css-html-js-minify](https://github.com/juancarlospaco/css-html-js-minify): StandAlone Async cross-platform Minifier for the Web.
- [fontello](https://github.com/fontello/fontello):Iconic fonts scissors
- [Automate a web browser with Selenium](https://fedoramagazine.org/automate-web-browser-selenium/)
- [Spectre.css](https://github.com/picturepan2/spectre): A Lightweight, Responsive and Modern CSS Framework
- [Google Optmize](https://marketingplatform.google.com/about/optimize/): Your website is your store window.
- [Google web.dev](https://web.dev/measure): Review performance and get detailed guidance on how to improve it. Sign-in to monitor your progress over time.
- [VisBug](https://github.com/GoogleChromeLabs/projectvisbug): 🎨 Make any webpage feel like an artboard, download extension here
- [DoodleMaster](https://github.com/karanchahal/DoodleMaster): The Doodle Master seeks to turn your UI mockups into real code. Currently this repository just serves to demonstrate a Proof Of Concept of Artificially Intelligent Design Tools.
- [Themes for Pelican](https://github.com/getpelican/pelican-themes)
- [Pelican theme based on html5-dopetrope design.](https://github.com/PierrePaul/html5-dopetrope)
- [Flex](https://github.com/alexandrevicenzi/Flex): The minimalist Pelican theme.
- [pelican theme Dev-Random3](https://github.com/22decembre/dev-random3)
- [HOW TO CENTER IN CSS](http://howtocenterincss.com/): Centering in CSS is a pain in the ass. There seems to be a gazillion ways to do it, depending on a variety of factors. This consolidates them and gives you the code you need for each situation.
- [Vaadin Tutorial application](https://github.com/vaadin/tutorial): Introduction to Vaadin Framework 8
- [NES.css](https://bcrikko.github.io/NES.css/) - [github](https://github.com/BcRikko/NES.css)
- [wedding-website](https://github.com/rampatra/wedding-website)
- [Favicon Generator](https://realfavicongenerator.net/). For real.
- [Are You a Blogger or Publisher?](https://websitevoice.com/): Turn your articles to high-quality audio for your audience to listen while they’re busy multitasking or on the go.
- [Inside look at modern web browser (part 1)](https://developers.google.com/web/updates/2018/09/inside-browser-part1): In this 4-part blog series, we’ll look inside the Chrome browser from high-level architecture to the specifics of the rendering pipeline.
- Forms:
  - [react-jsonschema-form](https://github.com/mozilla-services/react-jsonschema-form): A React component for building Web forms from JSON Schema.
  - [json-forms](https://github.com/brutusin/json-forms): JSON Schema to HTML form generator, supporting dynamic subschemas (on the fly resolution). Extensible and customizable library with zero dependencies. Bootstrap add-ons provided.
  - [schemaform](http://schemaform.io/): Generate forms from a JSON schema, with AngularJS! [github](https://github.com/json-schema-form/angular-schema-form)
  - [Formasaurus](https://github.com/TeamHG-Memex/Formasaurus): Formasaurus tells you the type of an HTML form and its fields using machine learning.
- Presentantions:
  - [markdeck](https://github.com/arnehilmann/markdeck): presentations as code - author cool slide decks, text-only, offline-ready, collaborative.
- PHP:
  - [A curated list of bookmarks, packages, tutorials, videos and other cool resources from the Laravel ecosystem](https://github.com/chiraggude/awesome-laravel)
  - [PHP Apprentice](https://phpapprentice.com/): An online book for learning PHP. [github](https://github.com/restoreddev/phpapprentice)
  - [JHRW](https://github.com/galvao/JHRW): JavaScript HTTP Request Wrapper.  A wrapper for so-called "AJAX" Requests.
  - [My Modern PHP Development Setup](https://johnmackenzie.co.uk/post/my-modern-php-development-setup/): With this combination of formatters, linters and build tools I am able to create a fully testible, completely portable solution with adheres to PSR coding standards.
- [shiny](https://github.com/rikschennink/shiny): Shiny reflections for mobile websites.
- [splinter](https://github.com/cobrateam/splinter): python test framework for web applications.
- [revery](https://github.com/revery-ui/revery): ⚡️ Native, high-performance, cross-platform desktop apps - built with Reason!
- [2 Colors-Gradient Generator](https://www.colorffy.com/generator/gradients)
- [tellform](https://github.com/tellform/tellform): ✏️ Free Opensource Alternative to TypeForm or Google Forms ⛺. [site](https://tellform.com/)
- [material-kit](https://github.com/creativetimofficial/material-kit): Free and Open Source UI Kit for Bootstrap 4, React, Vue.js, React Native and Sketch based on Google's Material Design.
- [Flexible data tables with CSS Grid](https://adamlynch.com/flexible-data-tables-with-css-grid/?1)
- [Sites inclusivos a pessoas com autismo](https://gaia.wiki.br/): O GAIA é um conjunto aberto e colaborativo de 28 recomendações de acessibilidade web focado nos aspectos do autismo, abordando desde a escrita de conteúdo até recursos programáveis.
- [Banish the � with Unifont](https://shkspr.mobi/blog/2019/04/banish-the-%EF%BF%BD-with-unifont/).
- [Handsontable](https://github.com/handsontable/handsontable): JavaScript/HTML5 Data Grid Component with Spreadsheet Look & Feel. Available for React, Vue and Angular.
- [Web development, illustrated.](https://illustrated.dev/)
- [339 bytes of responsive CSS](https://blog.koley.in/2019/339-bytes-of-responsive-css)
- [Making Tables Responsive With Minimal CSS](https://bradleytaunt.com/2019/06/11/responsive-tables/)
- [JSON-SERVER With Authorization JWT](https://github.com/valmirphp/json-server): sample json-server authorization token.
- [css-components](https://github.com/felipefialho/css-components): A set of common UI Components using the power of CSS and without Javascript.
- [User Inyerface](https://userinyerface.com/): Hi and welcome to User Inyerface, a challenging exploration of user interactions and design patterns.
- [gradient-path](https://github.com/mnsht/gradient-path): A small library to have any gradient follow along any SVG path.
- [hostyoself](https://github.com/schollz/hostyoself): Host yo' self from your computer, your browser, your phone, etc.
- [How SAML 2.0 Authentication Works](https://gravitational.com/blog/how-saml-authentication-works/)
- [web design tool](https://www.thewebdesigntool.com/) is a free online bootstrap css grid layout generator. Make Responsive web design with Top css frameworks without learn them.
- [CSS Grid Generator](https://cssgrid-generator.netlify.com/)
- [Super Tiny Social Icons](https://github.com/edent/SuperTinyIcons): Under 1KB each! Super Tiny Icons are miniscule SVG versions of your favourite website and app logos.

##### REST API

- [REST API Testing Tutorial](https://www.guru99.com/testing-rest-api-manually.html): Sample Manual Test Case
- [The Web API Checklist](https://mathieu.fenniak.net/the-api-checklist/): 43 Things To Think About When Designing, Testing, and Releasing your API
- [API-Security-Checklist](https://github.com/shieldfy/API-Security-Checklist): Checklist of the most important security countermeasures when designing, testing, and releasing your API
- [REST API Checklist](https://www.kennethlange.com/rest-api-checklist/)
- [Your Comprehensive Web API Design Checklist](https://www.phase2technology.com/blog/your-comprehensive-web-api-design-checklist)
- [REST Security Cheat Sheet](https://github.com/OWASP/CheatSheetSeries/blob/master/cheatsheets/REST_Security_Cheat_Sheet.md): CheatSheetSeries
- [API Security Testing](https://www.testbytes.net/blog/api-security-testing-rules-and-checklist/): Rules And Checklist
- [Penetration Testing RESTful Web Services](http://blog.isecurion.com/2017/10/10/penetration-testing-restful-web-services/)
- [RESTful web services penetation testing](https://hydrasky.com/network-security/restful-web-services-penetation-testing/)
- [Astra](https://tech.flipkart.com/astra-automated-security-testing-for-rest-apis-a54b999dbfe9?gi=2af3bebcabc8): Automated Security Testing for REST API’s

### Web Services

- [Notion](https://www.notion.so/): Write, plan, collaborate, and get organized.
- [Postmake](https://postmake.io/): A directory of the best tools and resources for your projects
- [nuclear](https://github.com/nukeop/nuclear): Popcorn Time for music. [github](https://github.com/nukeop/nuclear)
- [TERRAPATTERN](http://www.terrapattern.com/): This is the alpha version of Terrapattern, a visual search tool for satellite imagery. The project provides journalists, citizen scientists, and other researchers with the ability to quickly scan large geographical regions for specific visual features.
- [Pixelfed](https://pixelfed.social/) is an image sharing platform, an ethical alternative to centralized platforms.
- [The IA Client](http://blog.archive.org/2019/06/05/the-ia-client-the-swiss-army-knife-of-internet-archive/): The Swiss Army Knife of Internet Archive. [python library](https://archive.org/services/docs/api/internetarchive/)
- [HTTP Security Headers](https://nullsweep.com/http-security-headers-a-complete-guide/) - A Complete Guide
- [HTML is the Web](https://www.petelambert.com/journal/html-is-the-web)
- [The New Able Editor](https://able.bio/rhett/the-new-able-editor--596ha6x). [suggestion-box](https://github.com/able-bio/suggestion-box): A place to submit issues for bugs, feature requests and other ideas related to Able.



#### Graphics

- [Upscale bitmap images with better results](https://fedoramagazine.org/upscale-bitmap-images-better-results/), [simila](https://github.com/lupoDharkael/smilla-enlarger).
- [Rexpaint](https://www.gridsagegames.com/rexpaint/): is a powerful and user-friendly ASCII art editor. Use a wide variety of tools to create ANSI block/line art, roguelike mockups and maps, UI layouts, and for other game development needs.

#### CMS

- [Tale](https://github.com/chesterhow/tale) is a minimal Jekyll theme curated for storytellers.
- [pH7-Social-Dating-CMS](https://github.com/pH7Software/pH7-Social-Dating-CMS)
- [VuePress](https://forestry.io/blog/vuepress-brings-your-documentation-to-life/) is a static site generator based on Vue JavaScript framework.
- [Publii](https://github.com/GetPublii/Publii) is a desktop-based CMS for Windows and Mac that makes creating static websites fast and hassle-free, even for beginners.
- (pt-br) [Civitas](https://github.com/CivitasOrg/): Civitas é um projeto para organização de comunidades de desenvolvimento.

## Journalism

- (pt-br) [Jornalismo Guiado por Dados 1](https://rodrigomenegat.github.io/jgd-1/).
- [SourcedFact](https://sourcedfact.com/): Journalism with Open Sourced Fact Checking

---

### Little notes

- [Auto index html bash script](http://www.alecjacobson.com/weblog/?p=192)

```bash
#!/bin/bash
# usage: auto-index [dir]
INDEX=`ls -1 $1 | sed "s/^.*/      <li\>\<a\ href=\"&\"\>&\<\\/a\>\<\\/li\>/"`
echo "<html>
  <head><title>Index of $1</title></head>
  <body>
    <h2>Index of $1</h2>
    <hr>
    <ui>
$INDEX
    <ui>
  </body>
</html>"
```

- Run it as:

```bash
 ./auto-index.sh [path to dir] > index.html
```

---

## Cloud

- [no more google](https://nomoregoogle.com)
- [Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)
- [CloudMapper](https://github.com/duo-labs/cloudmapper): CloudMapper helps you analyze your Amazon Web Services (AWS) environments.

### Nextcloud

- [How to save LibreOffice documents to your Nextcloud server](https://www.techrepublic.com/article/how-to-save-libreoffice-documents-to-your-nextcloud-server/)
- [LibreOffice NextCloud WebDAV Configuration](https://hitman101.wordpress.com/2018/04/09/libreoffice-nextcloud-webdav-configuration/)
- [NextCloud on OpenBSD](https://h3artbl33d.nl/blog/nextcloud-on-openbsd)
- [Improved AppPasswords in Nextcloud 14](https://rullzer.com/2018/09/05/improved-apppasswords-in-nextcloud-14/): rullzers blog
- [Installing Integration Edition Document Server for Docker on a local server](https://helpcenter.onlyoffice.com/server/integration-edition/docker/docker-installation.aspx)
- [How to fix PHP 7 bash error to update Nextcloud on Synology?](https://hackabee.fr/2018/12/12/how-to-solve-php-7-bash-error-to-update-nextcloud-on-synology/)
- [Nextcloud With Cloudflare SSL Easy Install Bash script](https://github.com/bajpangosh/Nextcloud-With-Cloudflare-SSL-Easy-Install-script)

---

## IoT

- [Introduction to MQTT](https://blog.teserakt.io/2018/11/01/introduction-to-mqtt/)
- [VerneMQ](https://github.com/vernemq/vernemq): A Distributed MQTT Broker
- [EMQ X Broker](https://github.com/emqx/emqx) - Scalable Distributed MQTT Message Broker for IoT in 5G Era. [site](https://emqx.io)
- (pt-br) [A Internet das Coisas no Brasil](https://igarape.org.br/a-internet-das-coisas-no-brasil/) - Instituto Igarapé
- [jerryscript](https://github.com/jerryscript-project/jerryscript): Ultra-lightweight JavaScript engine for the Internet of Things.
- [UNDERCLOCKING THE ESP8266 LEADS TO WIFI WEIRDNESS](https://hackaday.com/2019/01/04/underclocking-the-esp8266-leads-to-wifi-weirdness/): Sometimes the best hacks come from the most basic of questions. In this case, [CNLohr] was wondering what would happen if he started to reduce the clock speed of the ESP8266’s Baseband PLL (BBPLL) while still trying to communicate with it.
- [Saleae](https://www.saleae.com/): Saleae builds the world’s most loved logic analyzers.
- [openedge](https://github.com/baidu/openedge): Extend cloud computing, data and service seamlessly to edge devices.
- [OpenChirp](https://openchirp.io/): An Open Source Platform for IoT with support for LoRaWAN
- [FindChips](https://www.findchips.com/): Get instant insight into any electronic component
Access price, inventory, unique market intelligence and advanced analytics for all your parts.
- Fedora's [InternetOfThings](https://fedoraproject.org/wiki/InternetOfThings)
- [Connected camera cock up](https://www.pentestpartners.com/security-blog/connected-camera-cock-up/)

### RFID

- [RFIDler](http://adamsblog.aperturelabs.com/2013/08/rfidler-open-source-software-defined.html?m=0) - An open source Software Defined RFID Reader/Writer/Emulator. [github](https://github.com/ApertureLabsLtd/RFIDler)

---

## Fun

- [VIM Clutch](https://github.com/alevchuk/vim-clutch) is a hardware pedal for improved text editing speed for users of the magnificent VIM text editor
- [wtf](https://github.com/senorprogrammer/wtf): The personal information dashboard for your terminal.
- [lolcat](https://github.com/jaseg/lolcat): High-performance implementation of lolcat
- (pt-br) [ligar-cobranca](https://github.com/GtOkAi/ligar-cobranca): Ligue automaticamente para empresas de cobrança e deixe uma voz falando "Alô?" sem parar.
- [Trump2Ca$h](https://github.com/maxbbraun/trump2cash): A stock trading bot powered by Trump tweets
- [paint 16b](http://www.sizecoding.org/wiki/Paint16b): was created by Hellmood and is 16 bytes in size. paint16b implements a mouse-driven drawing program which has the ability to exit back to DOS and also display the mouse cursor, [screenshot](http://www.pouet.net/prod.php?which=63826).
- [Boss as a Service](https://bossasaservice.life/): Hire a boss, get stuff done
- [Craft Crown SDK](https://github.com/Logitech/logi_craft_sdk): Provide (API) SDK specifications to map your app functions to Logitech Craft dial controller called "Crown".
- [Check out these projects featuring your favorite Cartoon Network characters and start making!](http://www.createwithcn.com/). [Cartoon Network + Ada Fruit](https://makecode.adafruit.com/projects/cartoon-network)
- [fx_cast](https://hensm.github.io/fx_cast/): chromecast for firefox. Enables Chromecast support for casting web apps (like Netflix or BBC iPlayer), HTML5 video and screen/tab sharing. [github](https://github.com/hensm/fx_cast)
- [srsLTE](https://github.com/srsLTE/srsLTE): Open source SDR LTE software suite from Software Radio Systems (SRS)
- [List of software-defined radios](https://en.wikipedia.org/wiki/List_of_software-defined_radios)
- [IP over Avian Carriers](https://en.wikipedia.org/wiki/IP_over_Avian_Carriers)

## Stuff

- [The Free Stack](http://p.agnihotry.com/post/the_free_stack_aws/): Running your application for free on AWS
- [The unreasonable effectiveness of Soccermatics?](https://www.interaliamag.org/articles/david-sumpter-unreasonable-effectiveness-soccermatics/)
- [Productive Procrastination](https://nickwignall.com/productive-procrastination/): How to Get More Done by Procrastinating on Purpose
- [olive](https://github.com/olive-editor/olive/): Professional open-source NLE video editor
- [Ask HN: What should a systems/low-level software engineer know?](https://news.ycombinator.com/item?id=18881649)
- [German for Programmers](https://wickedchicken.github.io/post/german-for-programmers/)
- [Seeking the Productive Life](https://blog.stephenwolfram.com/2019/02/seeking-the-productive-life-some-details-of-my-personal-infrastructure/): Some Details of My Personal Infrastructure
- [Como contribuir com projetos de código aberto sem precisar entender de programação](https://medium.com/@talitapagani/como-contribuir-com-projetos-de-c%C3%B3digo-aberto-sem-precisar-entender-de-programa%C3%A7%C3%A3o-318f94c6e2d3)
- [The DevOps Phenomenon](https://queue.acm.org/detail.cfm?id=3338532)
- (pt-br) [Como contribuir com projetos de código aberto sem precisar entender de programação](https://medium.com/@talitapagani/como-contribuir-com-projetos-de-c%C3%B3digo-aberto-sem-precisar-entender-de-programa%C3%A7%C3%A3o-318f94c6e2d3)

## News

- [GitNews](https://git.news/)
- [Systemd's DynamicUser feature is (currently) dangerous](https://utcc.utoronto.ca/~cks/space/blog/linux/SystemdDynamicUserDangerous)
- [Open Source is Not About You](https://gist.github.com/richhickey/1563cddea1002958f96e7ba9519972d9)
- [600 days of postmarketOS](https://postmarketos.org/blog/2019/01/16/600-days-of-postmarketOS/)
- [Physicists reverse time using quantum computer](https://phys.org/news/2019-03-physicists-reverse-quantum.html)
- [AN EXCLUSIVE LOOK AT AN ORIGINAL IPHONE PROTOTYPE](https://www.theverge.com/2019/3/19/18263844/apple-iphone-prototype-m68-original-development-board-red)
- [Open Source Doesn’t Make Money Because It Isn’t Designed To Make Money](http://www.ianbicking.org/blog/2019/03/open-source-doesnt-make-money-by-design.html)
- [STORING UTC IS NOT A SILVER BULLET](https://codeblog.jonskeet.uk/2019/03/27/storing-utc-is-not-a-silver-bullet/)
- [Patent exhaustion and open source](https://lwn.net/Articles/780078/)
- [Adventures of putting 16 GB of RAM in a motherboard that doesn’t support it](https://www.downtowndougbrown.com/2019/04/adventures-of-putting-16-gb-of-ram-in-a-motherboard-that-doesnt-support-it/)
- [Upgrade Arbitrage](https://tedium.co/2019/06/04/used-workstation-computer-buying-strategy/): The charm of buying old workstation hardware on the cheap to support your modern computing needs. If it doesn’t work for them, it might just work for you.

## Making Conferences

- [python-organizers](https://github.com/python-organizers/resources): Share docs, tools, lists and whatnot for organizing a Python conference

## Articles

- [Serverless Computing: One Step Forward, Two Steps Back](https://arxiv.org/abs/1812.03651)
