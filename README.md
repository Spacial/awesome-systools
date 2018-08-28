# systools

Collection of Sysadmins daily handy tools

# Reliability

* [Google - Site Reliability Engineering](https://landing.google.com/sre/book.html)

# Licensing

* [A New Social Contract for Open Source](https://hueniverse.com/a-new-social-contract-for-open-source-86d1fcf3e353)

# Linux

## Kernel

* [Writing a Simple Linux Kernel Module](https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234)
* [eBPF Utilities, Maps, and more](https://github.com/nathanjsweet/ebpf)
* [lsof to graphviz](https://github.com/zevv/lsofgraph) 
* [Making Sense of Hexdump](https://www.suse.com/c/making-sense-hexdump/), [man](https://www.systutorials.com/docs/linux/man/1-hexdump/)
* [Interactive map of Linux Kernel](http://www.makelinux.net/kernel_map/)
* [How to prevent unprivileged users from viewing dmesg command output on Linux](https://www.cyberciti.biz/faq/how-to-prevent-unprivileged-users-from-viewing-dmesg-command-output-on-linux/):
```bash
$ sudo sysctl -w kernel.dmesg_restrict=1
```
* [darling](https://github.com/darlinghq/darling): Darwin/macOS emulation layer for Linux
 
## Performance

* [Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools](https://github.com/sahilshekhawat/Optimizing-Linux-Performance-A-Hands-On-Guide-to-Linux-Performance-Tools?files=1)
* [Why is the kernel community replacing iptables with BPF?](https://cilium.io/blog/2018/04/17/why-is-the-kernel-community-replacing-iptables/)
* [bcc](https://github.com/iovisor/bcc/): Tools for BPF-based Linux IO analysis, networking, monitoring, and more

## Red Hat/Fedora

* Yum to DNF [Cheatsheet](https://fedoraproject.org/wiki/Yum_to_DNF_Cheatsheet)
* [How to reset a root password on Fedora](https://fedoramagazine.org/reset-root-password-fedora/)
* [Use restic on Fedora for encrypted backups](https://fedoramagazine.org/use-restic-encrypted-backups/)
* [Software Galaxies](https://github.com/anvaka/pm): package managers visualization, [see it](https://anvaka.github.io/pm/).

### RPM

#### Build

* [Creating RPM Packages with Fedora](https://fedoraproject.org/wiki/How_to_create_an_RPM_package)
* Spec file, to create lsutil rpm: [here](https://github.com/pld-linux/lsiutil)

## Storage

* [Mounting a hard disk image including partitions using Linux](http://www.andremiller.net/content/mounting-hard-disk-image-including-partitions-using-linux)
* [How to full encrypt your linux system with lvm on luks](https://www.linux.com/blog/how-full-encrypt-your-linux-system-lvm-luks)
* [Tutorial: ClamAV-Antivirus-Scanning in Nextcloud implementieren](https://ollis.blog/tutorial-clamav-antivirus-scanning-in-nextcloud-implementieren/)

### Controllers

* LSILogic util: [lsiutil](https://github.com/kojack/lsiutil)

# Caching

* [Evolution of Application Data Caching : From RAM to SSD](https://medium.com/netflix-techblog/evolution-of-application-data-caching-from-ram-to-ssd-a33d6fa7a690) 
   * [EVCache](https://github.com/Netflix/EVCache): A distributed in-memory data store for the cloud
   * [extstore](https://github.com/memcached/memcached/wiki/Extstore): is an addition to memcached which leaves the hash table and keys in memory, but moves values to external storage (usually flash).

# Automation

* [Script to convert a Debian installation on DigitalOcean to Arch Linux](https://github.com/gh2o/digitalocean-debian-to-arch)

## Ansible

Some usefull ansible scripts and tips on [ansible](./ansible) dir.
* [Playbooks and roles for installing and managing Ansible networking CI](https://github.com/ansible/network-infra-playbooks)
* [Ansible Role: EPEL Repository](https://github.com/geerlingguy/ansible-role-repo-epel)
* [Ansible role to install and manage nginx configuration](https://github.com/jdauphant/ansible-role-nginx)
* [ansible-playbook-gitlab](https://github.com/tingtun/ansible-playbook-gitlab)

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
* [fero](https://github.com/coreos/fero): YubiHSM2-backed signing server 
* [iptables-essentials](https://github.com/trimstray/iptables-essentials): Iptables Essentials: Common Firewall Rules and Commands.

## VPN

* [How I made my own WireGuard VPN server | TechCrunch](https://techcrunch.com/2018/07/28/how-i-made-my-own-wireguard-vpn-server/)

## Messaging

* [Tox](https://tox.chat/): The library provides all of the messaging and encryption facilities, and is completely decoupled from any user-interface; for an end-user to make use of Tox, they need a Tox client. MacOS Clients: [uTox](https://github.com/uTox/uTox/) and [qTox](https://github.com/qTox/qTox/).

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
* [Jenkinsfile](https://github.com/vivitc/learning-jenkinsfile) example by [vivitc](https://github.com/vivitc/)
* [Terraform](https://www.terraform.io/intro/index.html) ([github repo](https://github.com/hashicorp/terraform))
* [Best way to do linux clones for your CI](https://www.kernel.org/best-way-to-do-linux-clones-for-your-ci.html)

# Interfaces

* [A sysadmin login session in a web browser](https://github.com/cockpit-project/cockpit)
* [tinywm](http://incise.org/tinywm.html): The tiniest window manager. [github](https://github.com/mackstann/tinywm)

# Troubleshooting

* [sysdig](https://github.com/draios/sysdig): Linux system exploration and troubleshooting tool with first class support for containers
* [rbspy](https://rbspy.github.io/): Have a running Ruby program that you want to profile without restarting it? Want to profile a Ruby command line program really easily? You want rbspy! rbspy can profile any Ruby program by running 1 command.

## Logs

* [Sigma](https://github.com/Neo23x0/sigma): Generic Signature Format for SIEM Systems
* [fluent-bit](https://github.com/fluent/fluent-bit): Fast and Lightweight Log processor and forwarder for Linux, BSD and OSX 
* [GoAccess - Visual Web Log Analyzer](https://goaccess.io/)
* [Slagg](https://github.com/drrzmr/slagg) - Simple Log Aggregator 
* [The Log File Navigator](https://lnav.org/downloads/) ([github](https://github.com/tstack/lnav))

# Network

* [TCP Tracepoints](http://www.brendangregg.com/blog/2018-03-22/tcp-tracepoints.html)
* [BCC](https://github.com/iovisor/bcc): Tools for BPF-based Linux IO analysis, networking, monitoring, and more
* [dhcpcd](https://roy.marples.name/git/dhcpcd.git/)
* [concurrency-limits](https://github.com/Netflix/concurrency-limits): Java Library that implements and integrates concepts from TCP congestion control to auto-detect concurrency limits to achieve optimal throughput with optimal latency [ [article](https://medium.com/@NetflixTechBlog/performance-under-load-3e6fa9a60581) ].
* [Debugging HTTPS](http://vafer.org/blog/20080221152526/)
  * Some [tcpdump](https://security.stackexchange.com/questions/65178/tcpdump-filter-expression-post-packets) examples.
* [Building my ideal router for $50]( https://blog.tjll.net/building-my-perfect-router/)     
* [Detecting the use of "curl | bash" server side | Application Security](https://www.idontplaydarts.com/2016/04/detecting-curl-pipe-bash-server-side/)
* [Scapy](https://github.com/secdev/scapy/): the Python-based interactive packet manipulation program & library. Supports Python 2 & Python 3. 

## NetServices

* [salmon](https://github.com/moggers87/salmon): Pythonic Mail Application Server forked from the last GPL'd release of Lamson 

## LoadBalancers

* [glb-director](https://github.com/github/glb-director): GitHub Load Balancer Director and supporting tooling. 

# Shell

* [Software development using Bash](https://oscarforner.com/2018/02/24/Software_development_using_Bash)
* [Ten Things I Wish I’d Known About bash](https://zwischenzugs.com/2018/01/06/ten-things-i-wish-id-known-about-bash/)
* [cheat.sh](https://cheat.sh/) The only cheat sheet you need, Unified access to the best community driven documentation repositories of the world
* [bash-oo-framework](https://github.com/niieani/bash-oo-framework): Bash Infinity is a modern boilerplate / framework / standard library for bash
* Bashrc files:
   * [Paul's .bashrc](https://github.com/paulkaefer/.bashrc)
   * [rkirti/bashrc](https://github.com/rkirti/bashrc)
* DotFiles: 
   * Amazing collection by [jessfraz](https://github.com/jessfraz/dotfiles/)
   * Some [dotfile](https://github.com/maitesin/dot-files) by maitesin
   * [pedrohenriquebr](https://github.com/pedrohenriquebr/dotfiles)
* Powerline:
   * [Powerline Gitstatus](https://github.com/jaspernbrouwer/powerline-gitstatus)
* Zsh files:
   * [Zim](https://github.com/zimfw/zimfw/) is a Zsh configuration framework with blazing speed and modular extensions.
   * [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh): A delightful community-driven (with 1,100+ contributors) framework for managing your zsh configuration.
 * Fish:
  * [fish-shell](https://github.com/fish-shell/fish-shell): The user-friendly command line shell.
  * [fisherman](https://github.com/fisherman/fisherman): The fish-shell plugin manager.  
* [15 Tips On How to Use 'Curl' Command in Linux](https://www.tecmint.com/linux-curl-command-examples/)
* [GoAWK](https://github.com/benhoyt/goawk): an AWK interpreter written in Go
* [Lambda Shell](http://www.lambdashell.com/)
* [Understanding Bash fork() Bomb ~ :(){ :|:& };:](https://www.cyberciti.biz/faq/understanding-bash-fork-bomb/)

## Editors

* [vscode-cpptools](https://github.com/Microsoft/vscode-cpptools): Official repository for filing issues against and getting support for the Microsoft C/C++ extension for VS Code 

### Vim/vi 

* [Spotify integration for vim](https://github.com/mattpenney89/vimify)
* [Vim plugin](https://github.com/mechatroner/rainbow_csv): Highlight columns in CSV and TSV files and run queries in SQL-like language
* [vim-prettier](https://github.com/prettier/vim-prettier): A Vim plugin for Prettier 
* [vimium](https://github.com/philc/vimium):  Vimium is a Chrome extension that provides keyboard-based navigation and control of the web in the spirit of the Vim editor.
* [vimari](https://github.com/guyht/vimari): Safari port of vimium 
* [vim-plug](https://github.com/junegunn/vim-plug): hibiscus Minimalist Vim Plugin Manager 
   
   
# Other Resources

* [16 Linux Books and Videos for System Administrator](https://geekflare.com/linux-books-videos/)
* [open-guides/og-aws: 📙 Amazon Web Services — a practical guide](https://github.com/open-guides/og-aws)

# Filesystems

* [diskover](https://n0where.net/file-system-crawler-diskover): File System Crawler. [github](https://github.com/shirosaidev/diskover)

# Unix

* [UNIX Syscalls](https://john-millikin.com/unix-syscalls)
* [KVM virt-install: Install OpenBSD As Guest Operating System - nixCraft](https://www.cyberciti.biz/faq/kvmvirtualization-virt-install-openbsd-unix-guest/)

# Virtualization

* [OSX-KVM: Run El Capitan, macOS Sierra, High Sierra and Mojave on QEMU/KVM. No support is provided at the moment.](https://github.com/kholia/OSX-KVM)
* [Windows 2000 on your browser](https://bellard.org/jslinux/vm.html?url=https://bellard.org/jslinux/win2k.cfg&mem=192&graphic=1&w=1024&h=768)
* [hvpp](https://github.com/wbenny/hvpp) is a lightweight Intel x64/VT-x hypervisor written in C++ focused primarily on virtualization of already running operating system 
* [Windows 95](https://github.com/felixrieseberg/windows95) in Electron. Runs on macOS, Linux, and Windows. 

## VMware

* [The ghettoVCB](https://github.com/lamw/ghettoVCB) script performs backups of virtual machines residing. Here on [VMware Communities](https://code.vmware.com/samples/822/ghetto-vcb?h=Sample)

# Mac

* [Using AppleScript how do I click a button in a dialog within a window that has no name/title?](https://stackoverflow.com/questions/7355763/using-applescript-how-do-i-click-a-button-in-a-dialog-within-a-window-that-has-n)
* [Making the Touch Bar finally useful](http://vas3k.com/blog/touchbar/)
* [iTerm2](https://github.com/gnachman/iTerm2) is a terminal emulator for Mac OS X that does amazing things. 

# Windows 

* [coreclr](https://github.com/dotnet/coreclr): This repo contains the .NET Core runtime, called CoreCLR, and the base library, called System.Private.Corelib (or mscorlib).
* [Monitoring and Observability in the .NET Runtime](http://mattwarren.org/2018/08/21/Monitoring-and-Observability-in-the-.NET-Runtime/)
* [Powershell-SSHTools](https://github.com/fridgehead/Powershell-SSHTools): A bunch of useful SSH tools for powershell 

# Support

## Video Conference

* [Hublin](https://github.com/linagora/hublin): An easy and free video conference service based on WebRTC
* [PeerTube](https://github.com/Chocobozzz/PeerTube): Federated (ActivityPub) video streaming platform using P2P (BitTorrent) directly in the web browser with WebTorrent and Angular.
* [Vialer-js](https://github.com/vialer/vialer-js): Open-source WebRTC communication platform.

# Management

* [8 Patterns for Decentralised Organising](https://standupdev.com/wiki/doku.php?id=patterns_for_decentralised_organising)
* [Zulip server](https://github.com/zulip/zulip/) - powerful open source team chat 

# Career

* [A Career Cold Start Algorithm](http://boz.com/articles/career-cold-start.html)
* [How to say “no” to your boss, your boss’s boss, and even the CEO](https://codewithoutrules.com/2018/08/16/how-to-say-no/)
* [test-your-sysadmin-skills](https://github.com/trimstray/test-your-sysadmin-skills): A collection of *nix Sysadmin Test Questions and Answers for Interview/Exam (2018 Edition). 

# Presentations

* [How to import an SVG into Powerpoint or Keynote](https://medium.com/@kyleledbetter/how-to-import-an-svg-into-powerpoint-or-keynote-8d3d70f347a7)

---

# Organization

* [Shiori](https://github.com/RadhiFadlillah/shiori) is a simple bookmarks manager written in Go language

---
# Tools

* [qr-filetransfer](https://github.com/claudiodangelis/qr-filetransfer):Transfer files over wifi from your computer to your mobile device by scanning a QR code without leaving the terminal.
* [gron](https://github.com/tomnomnom/gron/): Make JSON greppable! 
* [octalmage/robotjs: Node.js Desktop Automation.](https://github.com/octalmage/robotjs)
* [Whatsapp Automation](https://github.com/mnkgrover08/whatsapp_automation) is a collection of APIs that interact with WhatsApp messenger runn

## WebTools

* [The new Turtl server](https://github.com/turtl/server): evernote [alternative](https://tavernalinux.com/turtl-alternativa-open-source-ao-evernote-instalação-e-review-e84f7aa2d483) free software.
* [OPENBAZAAR](https://www.openbazaar.org/): decentralized marketplace server in go ([repo](https://github.com/OpenBazaar/openbazaar-go))
* [octalmage/robotjs: Node.js Desktop Automation.](https://github.com/octalmage/robotjs)
* [MapTiler - map overlay, cut map tiles for Google Maps, GIS layers and mobile apps – MapTiler](https://www.maptiler.com/)
* [typegram](http://pt.tgr.am/)
* [Ultralight](https://ultralig.ht/)-  HTML UI Engine
* [Retool](https://tryretool.com/): Custom internal tools have the same building blocks. Retool gives you those building blocks, so you can build them much faster.
* [GRID: A simple visual cheatsheet for CSS Grid Layout](http://grid.malven.co/)
* [PyPy.js](https://pypyjs.org/) is an experiment in building a fast and compliant python environment for the web. [github](https://github.com/pypyjs/pypyjs)

### CMS

* [Tale](https://github.com/chesterhow/tale) is a minimal Jekyll theme curated for storytellers. 
* [pH7-Social-Dating-CMS](https://github.com/pH7Software/pH7-Social-Dating-CMS)
* [VuePress](https://forestry.io/blog/vuepress-brings-your-documentation-to-life/) is a static site generator based on Vue JavaScript framework. 
* [Publii](https://github.com/GetPublii/Publii) is a desktop-based CMS for Windows and Mac that makes creating static websites fast and hassle-free, even for beginners.

---

## Little notes

* [Auto index html bash script](http://www.alecjacobson.com/weblog/?p=192)
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

Run it as:
  ./auto-index.sh [path to dir] > index.html

---

# Fun

* [VIM Clutch](https://github.com/alevchuk/vim-clutch) is a hardware pedal for improved text editing speed for users of the magnificent VIM text editor
* [wtf](https://github.com/senorprogrammer/wtf): The personal information dashboard for your terminal. 
* [lolcat](https://github.com/jaseg/lolcat): High-performance implementation of lolcat

# Stuff

* [The Free Stack - Running your application for free on AWS](http://p.agnihotry.com/post/the_free_stack_aws/)
* [The unreasonable effectiveness of Soccermatics? - Interalia Magazine](https://www.interaliamag.org/articles/david-sumpter-unreasonable-effectiveness-soccermatics/)

# News

* [Systemd's DynamicUser feature is (currently) dangerous](https://utcc.utoronto.ca/~cks/space/blog/linux/SystemdDynamicUserDangerous)
