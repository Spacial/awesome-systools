# systools

Collection of Sysadmins daily handy tools

# Licensing

* [A New Social Contract for Open Source](https://hueniverse.com/a-new-social-contract-for-open-source-86d1fcf3e353)

# Linux

## Kernel

* [Writing a Simple Linux Kernel Module](https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234)
* [eBPF Utilities, Maps, and more](https://github.com/nathanjsweet/ebpf)
* [lsof to graphviz](https://github.com/zevv/lsofgraph) 
* [Making Sense of Hexdump](https://www.suse.com/c/making-sense-hexdump/), [man](https://www.systutorials.com/docs/linux/man/1-hexdump/)
* [Interactive map of Linux Kernel](http://www.makelinux.net/kernel_map/)
 
## Performance

* [Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools](https://github.com/sahilshekhawat/Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools?files=1)
* [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/)

## Red Hat/Fedora

* Yum to DNF [Cheatsheet](https://fedoraproject.org/wiki/Yum_to_DNF_Cheatsheet)
* [How to reset a root password on Fedora](https://fedoramagazine.org/reset-root-password-fedora/)
* [Use restic on Fedora for encrypted backups](https://fedoramagazine.org/use-restic-encrypted-backups/)

### RPM

#### Build

* [Creating RPM Packages with Fedora](https://fedoraproject.org/wiki/How_to_create_an_RPM_package)
* Spec file, to create lsutil rpm: [here](https://github.com/pld-linux/lsiutil)

## Storage

* [Mounting a hard disk image including partitions using Linux](http://www.andremiller.net/content/mounting-hard-disk-image-including-partitions-using-linux)
* [How to full encrypt your linux system with lvm on luks](https://www.linux.com/blog/how-full-encrypt-your-linux-system-lvm-luks)

### Controllers

* LSILogic util: [lsiutil](https://github.com/kojack/lsiutil)

# Automation

* [Script to convert a Debian installation on DigitalOcean to Arch Linux](https://github.com/gh2o/digitalocean-debian-to-arch)

## Ansible

Some usefull ansible scripts and tips on [ansible](./ansible) dir.
* [Playbooks and roles for installing and managing Ansible networking CI](https://github.com/ansible/network-infra-playbooks)
* [Ansible Role: EPEL Repository](https://github.com/geerlingguy/ansible-role-repo-epel)
* [Ansible role to install and manage nginx configuration](https://github.com/jdauphant/ansible-role-nginx)

## Puppet

* [running puppet on openwrt](https://github.com/solarkennedy/puppet-on-openwrt) (dead!)

# Security

## Auditing

* [A UNIX security auditing tool based on several security frameworks](https://github.com/lateralblast/lunar)

## Hardening

* [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html) by [stribika](https://github.com/stribika)
* See your site config with [Hardenize](https://www.hardenize.com/)
* Nice article with a lot of resources: [Common approaches to securing Linux servers and what runs on them.](https://medium.com/@ageis/common-approaches-to-securing-linux-servers-and-what-runs-on-them-dadcacc5388b)
* A lot of good posts by geek flare: 
  * [How to Configure SSL Certificate on Google Cloud Load Balancer?](https://geekflare.com/google-load-balancer-enable-ssl/)
  * [Nginx Web Server Security & Hardening Guide](https://geekflare.com/nginx-webserver-security-hardening-guide/)
  * [IBM HTTP Server Security & Hardening Guide](https://geekflare.com/ibm-http-server-security-guide/)
  * [Apache Tomcat Hardening and Security Guide](https://geekflare.com/apache-tomcat-hardening-and-security-guide/)
  * [How to Enable TLS 1.3 in Nginx, Cloudflare?](https://geekflare.com/enable-tls-1-3/)
  * [Apache Web Server Hardening & Security Guide](https://geekflare.com/apache-web-server-hardening-security/) (broken!??)
* [How do I prevent apache from serving the .git directory?](https://serverfault.com/questions/128069/how-do-i-prevent-apache-from-serving-the-git-directory/128082#128082)

# Containers

* [A Practical Introduction to Container Terminology](https://developers.redhat.com/blog/2018/02/22/container-terminology-practical-introduction/)
* [Imagem CentOS7 com firefox ESR e warsaw configurado.](https://github.com/jsalatiel/wsbb-docker) (pt-BR) and [other](https://gist.github.com/dmouse/e76ce3d8dde00fe496da)
* [google chrome](https://github.com/c0b/chrome-in-docker) dockerized and [headless google chrome](https://github.com/eirslett/chrome-karma-docker), [another](https://github.com/miyakogi/pyppeteer)
* Some [fedora](https://github.com/fedora-cloud/docker-brew-fedora/) and [docker](https://docs.docker.com/samples/) links:
  * [Webapps with Docker](https://github.com/docker/labs/blob/master/beginner/chapters/webapps.md)
  * Various great [Dockerfiles](https://github.com/jessfraz/dockerfiles) by jessfraz (as usual)
* [Running a GUI application in a Docker container](https://linuxmeerkat.wordpress.com/2014/10/17/running-a-gui-application-in-a-docker-container/)
* [img](https://github.com/genuinetools/img): Standalone, daemon-less, unprivileged Dockerfile and OCI compatible container image builder.

# CI

* [Danger](https://github.com/danger/danger) runs after your CI, automating your team's conventions surrounding code review.
* [The centralized Danger server, freeing Danger from running on CI.](https://github.com/danger/peril)
* [OSS-Fuzz](https://github.com/google/oss-fuzz) - Continuous Fuzzing for Open Source Software
* [Fedora's](http://fedoraproject.org/wiki/CI/Standard_Test_Interface) CI/Standard Test Interface
* [Do continuous deployment with Github and Python](https://fedoramagazine.org/continuous-deployment-github-python/)

# Interfaces

* [A sysadmin login session in a web browser](https://github.com/cockpit-project/cockpit)

# Troubleshooting

* [sysdig](https://github.com/draios/sysdig): Linux system exploration and troubleshooting tool with first class support for containers
* [rbspy](https://rbspy.github.io/): Have a running Ruby program that you want to profile without restarting it? Want to profile a Ruby command line program really easily? You want rbspy! rbspy can profile any Ruby program by running 1 command.

## Logs

* [Sigma](https://github.com/Neo23x0/sigma): Generic Signature Format for SIEM Systems
* [fluent-bit](https://github.com/fluent/fluent-bit): Fast and Lightweight Log processor and forwarder for Linux, BSD and OSX 

# Network

* [TCP Tracepoints](http://www.brendangregg.com/blog/2018-03-22/tcp-tracepoints.html)
* [BCC](https://github.com/iovisor/bcc): Tools for BPF-based Linux IO analysis, networking, monitoring, and more
* [dhcpcd](https://roy.marples.name/git/dhcpcd.git/)
* [concurrency-limits](https://github.com/Netflix/concurrency-limits): Java Library that implements and integrates concepts from TCP congestion control to auto-detect concurrency limits to achieve optimal throughput with optimal latency [ [article](https://medium.com/@NetflixTechBlog/performance-under-load-3e6fa9a60581) ].
* [Debugging HTTPS](http://vafer.org/blog/20080221152526/)
  * Some [tcpdump](https://security.stackexchange.com/questions/65178/tcpdump-filter-expression-post-packets) examples.
* [Building my ideal router for $50]( https://blog.tjll.net/building-my-perfect-router/)     

# Shell

* [Software development using Bash](https://oscarforner.com/2018/02/24/Software_development_using_Bash)
* [Ten Things I Wish I’d Known About bash](https://zwischenzugs.com/2018/01/06/ten-things-i-wish-id-known-about-bash/)
* Bashrc files:
   * [Paul's .bashrc](https://github.com/paulkaefer/.bashrc)
   * [rkirti/bashrc](https://github.com/rkirti/bashrc)
* DotFiles: 
   * Amazing collection by [jessfraz](https://github.com/jessfraz/dotfiles/)
   * Some [dotfile](https://github.com/maitesin/dot-files) by maitesin
* Powerline:
   * [Powerline Gitstatus](https://github.com/jaspernbrouwer/powerline-gitstatus)
* Zsh files:
   * [Zim](https://github.com/zimfw/zimfw/) is a Zsh configuration framework with blazing speed and modular extensions.
* [Spotify integration for vim](https://github.com/mattpenney89/vimify)
   
# Other Resources

  * [16 Linux Books and Videos for System Administrator](https://geekflare.com/linux-books-videos/)
  
# VMware

* [The ghettoVCB](https://github.com/lamw/ghettoVCB) script performs backups of virtual machines residing. Here on [VMware Communities](https://code.vmware.com/samples/822/ghetto-vcb?h=Sample)

# Mac

* [Using AppleScript how do I click a button in a dialog within a window that has no name/title?](https://stackoverflow.com/questions/7355763/using-applescript-how-do-i-click-a-button-in-a-dialog-within-a-window-that-has-n)
* [Making the Touch Bar finally useful](http://vas3k.com/blog/touchbar/)

# Support

## Video Conference

* [Hublin](https://github.com/linagora/hublin): An easy and free video conference service based on WebRTC
* [PeerTube](https://github.com/Chocobozzz/PeerTube): Federated (ActivityPub) video streaming platform using P2P (BitTorrent) directly in the web browser with WebTorrent and Angular.

# Management

* [8 Patterns for Decentralised Organising](https://standupdev.com/wiki/doku.php?id=patterns_for_decentralised_organising)

# Career

* [A Career Cold Start Algorithm](http://boz.com/articles/career-cold-start.html)

# Presentations

* [How to import an SVG into Powerpoint or Keynote](https://medium.com/@kyleledbetter/how-to-import-an-svg-into-powerpoint-or-keynote-8d3d70f347a7)

---

# Organization

* [Shiori](https://github.com/RadhiFadlillah/shiori) is a simple bookmarks manager written in Go language

---
# Tools

* [qr-filetransfer](https://github.com/claudiodangelis/qr-filetransfer):Transfer files over wifi from your computer to your mobile device by scanning a QR code without leaving the terminal.
* [gron](https://github.com/tomnomnom/gron/): Make JSON greppable! 

## WebTools

* [Tale](https://github.com/chesterhow/tale) is a minimal Jekyll theme curated for storytellers. 
* [The new Turtl server](https://github.com/turtl/server): evernote [alternative](https://tavernalinux.com/turtl-alternativa-open-source-ao-evernote-instalação-e-review-e84f7aa2d483) free software.
* [OPENBAZAAR](https://www.openbazaar.org/): decentralized marketplace server in go ([repo](https://github.com/OpenBazaar/openbazaar-go))

---

# Fun

* [VIM Clutch](https://github.com/alevchuk/vim-clutch) is a hardware pedal for improved text editing speed for users of the magnificent VIM text editor
