# Awesome I2P

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome I2P implementations, libraries, resources, projects, and shiny things. Inspired by [awesome-tor](https://github.com/ajvb/awesome-tor) and [awesome-cpp](https://github.com/fffaraz/awesome-cpp) and other awesome lists.

### What is I2P?

I2P is an anonymous overlay network - a network within a network. It is intended to protect communication from dragnet surveillance and monitoring by third parties such as ISPs.
I2P is used by many people who care about their privacy: activists, oppressed people, journalists and whistleblowers, as well as the average person.

### Contents
- [The I2P Project](#the-i2p-project)
- [Implementations](#implementations)
    - [I2P (Java)](#i2p)
    - [I2Pd (C++)](#i2pd)
    - [Unfinished](#unfinished-routers)
- [Projects using I2P](#projects-using-i2p)
    - [Cryptocurrencies](#cryptocurrencies)
    - [Chat](#chat)
    - [E-mail](#e-mail)
    - [Tools](#tools)
    - [Torrents](#torrents)
    - [Web](#web)
    - [Unfinished](#unfinished)
- [Libraries](#libraries)
    - [BOB](#bob)
    - [SAM](#sam)
    - [Other](#other)
- [Automation](#automation)
- [Guides](#guides)
- [Publications](#publications)

## The I2P Project

#### [geti2p.net](http://geti2p.net/)

#### [i2pforum.net](https://i2pforum.net/)

## Implementations

### I2P

* [I2P](https://github.com/i2p/i2p.i2p) - The first implementation. Written in Java.
* [I2P Android](https://play.google.com/store/apps/details?id=net.i2p.android) - Android release of the I2P router. (Google play).
* [I2P Android](https://f-droid.org/packages/net.i2p.android.router/) - Android release of the I2P router. (F-Droid).
* [I2P+](https://gitlab.com/i2pplus/I2P.Plus/) - I2P+ is a soft-fork of the Java I2P Anonymizing Network Layer.

### I2Pd

* [I2Pd](https://github.com/PurpleI2P/i2pd) - A C++ implementation of a I2P router.
* [Kovri](https://gitlab.com/kovri-project/kovri) - The Kovri I2P Router Project, a fork of I2Pd by the Monero project.

### Unfinished routers

* [go-i2p](https://github.com/hkparker/go-i2p) - ![GitHub last commit](https://img.shields.io/github/last-commit/hkparker/go-i2p) A pure Go implementation of the I2P router.
* [i2p-cs](https://github.com/PeterZander/i2p-cs) - ![GitHub last commit](https://img.shields.io/github/last-commit/PeterZander/i2p-cs) I2P router in C#.
* [i2pcpp](https://github.com/majestrate/i2pcpp) - ![GitHub last commit](https://img.shields.io/github/last-commit/majestrate/i2pcpp) i2p c++ implementation.
* [i2p-lite](https://github.com/i2p-lite/i2p-lite) - ![GitHub last commit](https://img.shields.io/github/last-commit/i2p-lite/i2p-lite) i2p router implementation in C11.
* [i2pd-rs](https://github.com/jacklund/i2pd-rs) - ![GitHub last commit](https://img.shields.io/github/last-commit/jacklund/i2pd-rs) I2P Daemon written in Rust.
* [ire](https://github.com/str4d/ire) - ![GitHub last commit](https://img.shields.io/github/last-commit/str4d/ire) I2P router implementation in Rust.

## Docker images

* [i2p-docker](https://github.com/hkparker/i2p-docker) - Java I2P router in Docker.
* [i2pd-docker](https://github.com/hexaedron/i2pd-docker) - Dockerfile and some scripts to run i2pd in a container.
* [meeh/i2p.i2p](https://hub.docker.com/r/meeh/i2p.i2p/) - Prebuilt i2p docker image.
* [meeh/i2pd](https://hub.docker.com/r/meeh/i2pd/) - Prebuilt i2pd docker image.

## Projects using I2P

### Cryptocurrencies

* [Anoncoin](https://anoncoin.net/) - The Anoncoin project.
* [GOSTCoin](https://github.com/GOSTSec/gostcoin) - GOSTCoin (GST) is a digital currency based on blockchain technology. It allows instant payments worldwide with focus on privacy and security of its users.
* [Monero](https://getmonero.org/) - Monero is a secure, private, and untraceable cryptocurrency. It is open-source and accessible to all. With Monero, you are your own bank. Only you control and are responsible for your funds. Your accounts and transactions are kept private from prying eyes.

### Blog / Forum

* [i2p.syndie](https://github.com/i2p/i2p.syndie) - Syndie is an open source system for operating distributed forums, offering a secure and consistent interface to various anonymous and non-anonymous content networks.
* [cliqueclique](https://github.com/redhog/cliqueclique) - P2P forum on top of i2p.
* [railroad](https://github.com/eyedeekay/railroad) - A simple, single-user, self-hosted blogging system for I2P.

### Chat

* [MaladaN-Messenger-Client](https://github.com/MaladaN/MaladaN-Messenger-Client) - An end to end encrypted Messenger that uses the signal protocol over the I2P network.
* [MaladaN-Messenger-Server](https://github.com/MaladaN/MaladaN-Messenger-Server) - MaladaN Messenger Server end, for messaging using the signal protocol through I2P.
* [i2pchat](https://github.com/hypnosis-i2p/i2pchat) - I2PChat. Previously I2P Qt Messenger.

### E-mail
* [bdsmail](https://github.com/majestrate/bdsmail) - Brain Dead Simple Mail Server.
* [i2p.i2p-bote](https://github.com/i2p/i2p.i2p-bote) - I2P-Bote is a plugin for I2P that allows users to send and receive emails while preserving privacy. It does not need a mail server because emails are stored in a distributed hash table. They are automatically encrypted and digitally signed, which ensures no one but the intended recipient can read the email, and third parties cannot forge them.
* [pboted](https://github.com/PurpleBote/pboted) - Standalone C++ client for I2P/Bote e-mail exchange protocol.

### Files / Sharing

* [muwire](https://github.com/zlatinb/muwire) - MuWire file sharing client for I2P.
* [tahoe-lafs-i2p](https://github.com/chris-barry/tahoe-lafs-i2p) - Tahoe-LAFS is a Free and Open decentralized cloud storage system. It distributes your data across multiple servers. Even if some of the servers fail or are taken over by an attacker, the entire file store continues to function correctly, preserving your privacy and security.

### Tools

* [I2PMonitor](https://github.com/miximka/I2PMonitor) - I2P monitor and control application for Mac OS X.
* [darkweb-everywhere](https://github.com/chris-barry/darkweb-everywhere) - HTTPS Everywhere rulesets for hidden services and eepsites.
* [fl](https://gitlab.com/opennota/fl) - Reverse proxy to Flibusta via Tor or I2P.
* [i2p-control](https://github.com/eyedeekay/i2p-control) - Go terminal application for talking to i2pcontrol.
* [i2p-reseeder](https://github.com/torbjo/i2p-reseeder) - I2P Reseeder written in Python (WSGI).
* [i2p-tools](https://github.com/MDrollette/i2p-tools) - This tool provides a secure and efficient reseed server for the I2P network. There are several utility commands to create, sign, and validate SU3 files.
* [i2p-tools](https://github.com/majestrate/i2p-tools) - Assorted I2P tools and scripts.
* [i2p.to-web](https://github.com/hilbix/i2p.to-web) - Web portion of i2p.to, an I2P inProxy.
* [i2pberry](https://github.com/m6urns/i2pberry) - I2Pberry - I2P for the Raspberry Pi.
* [i2pd-tools](https://github.com/PurpleI2P/i2pd-tools) - Some useful tools for I2P.
* [i2pjump](https://github.com/robertfoss/i2pjump) - I2P jump service. A sort of slave DNS server for I2P.
* [i2spy](https://github.com/chris-barry/i2spy) - Takes stats from many i2p nodes, and holds them in a centralized location.
* [py-i2phosts](https://github.com/i2phosts/py-i2phosts) - py-i2phosts is a hostnames registration engine for I2P.
* [pyreseeder](https://github.com/PurpleI2P/pyseeder) - Reseed data managment tools for I2P.
* [si-i2p-plugin](https://github.com/eyedeekay/si-i2p-plugin) - An experimental approach to provide a destination-isolating mechanism for http-over-i2p.
* [transi2p](https://github.com/rbif/transi2p) - Transparent proxying for I2P and forwarding other addresses to Tor or clearnet.

### Torrents

* [Transmission-I2P](https://github.com/l-n-s/transmission-i2p) - Anonymous torrent client Transmission-I2P.
* [XD](https://github.com/majestrate/XD) - BitTorrent Client written in Go.
* [samtracker](https://github.com/eyedeekay/samtracker) - HTTP Bittorrent tracker with automatic port-forwarding to I2P.

### Web

* [i2pd-webui](https://github.com/l-n-s/i2pd-webui) - Fancy i2pd web user interface.
* [i2pdbrowser](https://github.com/PurpleI2P/i2pdbrowser) - i2pd browser bundle.

### Unfinished

* [i2pfsd](https://github.com/i2pfs/i2pfsd) - I2P-based high available shared filesystem server (doesn't work, yet).
* [i2pboted](https://github.com/majestrate/i2pboted) - Go implementation of I2P/Bote.
* syndie-go:
    * [libsyndie](https://github.com/kpetku/libsyndie) - Syndie library written in Go (see also: syndie-gui or syndie-core).
    * [syndie-core](https://github.com/kpetku/syndie-core) - CLI, network, and database backend for syndie-gui.
    * [syndie-gui](https://github.com/kpetku/syndie-gui) - Syndie GUI frontend for syndie-core.

## Libraries

### BOB

* [bobcpp](https://gitlab.com/rszibele/bobcpp) - C++ BOB library.
* [i2p.rb](https://github.com/dryruby/i2p.rb) - I2P.rb is a Ruby library for interacting with the I2P anonymity network. SAM and BOB. (last update 2010).
* [txi2p](https://github.com/str4d/txi2p) - I2P bindings for Twisted. SAM and BOB.

### SAM

* [goSam](https://github.com/cryptix/goSam) - A go library for using the I2P Simple Anonymous Messaging (SAM version 3.0) bridge.
* [i2p-rs](https://github.com/i2p/i2p-rs) - Rust client library for interacting with I2P.
* [i2pdotnet](https://github.com/SamuelFisher/i2pdotnet) - .NET library for using the I2P Simple Anonymous Messaging (SAM v3.0) bridge.
* [i2plib](https://github.com/l-n-s/i2plib) - Python bindings for SAMv3.
* [i2psam](https://github.com/i2p/i2psam) - C++ SAMv3 library.
* [libsam3](https://github.com/i2p/libsam3) - C SAMv3 library.
* [node-i2p](https://github.com/redhog/node-i2p) - NodeJS api for communicating over i2p (SAMv3 client).
* [php-sam](https://github.com/theimpossibleastronaut/php-sam) - Basic SAMv3 implementation in PHP.

### Other

* [haskell-network-anonymous-i2p](https://github.com/solatis/haskell-network-anonymous-i2p) - Haskell API for I2P anonymous networking.
* [i2p.socket](https://github.com/majestrate/i2p.socket) - drop in python socket module that uses i2p.
* [libtorrent-i2p](https://github.com/l-n-s/libtorrent-i2p) - libtorrent modified to download torrents anonymously.
* [samrtc](https://github.com/eyedeekay/samrtc) - webRTC over I2P via SAM.

### Unfinished

* [solitude](https://github.com/syvita/solitude) - I2P SAMv3 library in Rust (WIP).

## Automation

* [anonym8](https://github.com/HiroshiManRise/anonym8) - Sets Transparent proxy tunnel through Tor, I2P, Privoxy, Polipo and modify DNS; Include Anonymizing Relay Monitor (arm), macchanger and wipe (Cleans ram/cache & swap-space) features, ID spoofing has never been so easy.
* [i2phosts](https://github.com/tailot/i2phosts) - Automatic I2P Hosts synchronization I2P to Internet.
* [i2pbootstrap](https://github.com/TheTinHat/i2pbootstrap) - I2P Bootstrap script to automate much of the router setup process on remote servers.
* [nginx-i2p Cookbook](https://github.com/i2phosts/cookbook-nginx-i2p) - This Chef cookbook contains i2p-specifig config for logging i2p-desthashes.

## Guides

* [tutorial-darknet](https://github.com/ReK2Fernandez/tutorial-darknet) - Follow up files/scripts for i2pd+vpn+ubuntu remote i2p router setup.

## Publications

* [Peer Profiling and Selection in the I2P Anonymous Network](https://geti2p.net/_static/pdf/I2P-PET-CON-2009.1.pdf)
* [Anonymity Techniques - Usability Tests of Major Anonymity Networks](https://people.torproject.org/~karsten/petcon-proceedings-2009.1.pdf)
* [Darknets and hidden servers: Identifying the true IP/network identity of I2P service hosts](http://www.irongeek.com/downloads/Identifying%20the%20true%20IP%20of%20I2P%20service%20hosts.pdf)
* [Privacy-Implications of Performance-Based Peer Selection by Onion-Routers: A Real-World Case Study using I2P](https://gnunet.org/sites/default/files/herrmann2011mt.pdf)
* [I2P Usability vs. Tor Usability A Bandwidth and Latency Comparison](http://userpage.fu-berlin.de/~semu/docs/2011_seminar_ehlert_i2p.pdf)
* [Monitoring the I2P network](http://hal.inria.fr/inria-00632259/PDF/TMA2012-LNCS.pdf)
* [I2P's Usage Characterization](https://hal.inria.fr/hal-00744902/PDF/TMA2012-LNCS.pdf)
* [A survey on solutions and main free tools for privacy enhancing Web communications](https://www.freehaven.net/anonbib/cache/Ruiz-Martinez_2012.pdf)
* [A Bird's Eye View on the I2P Anonymous File-sharing Environment](http://hal.inria.fr/hal-00744919/PDF/A_Birda_s_Eye_View_on_the_I2P_Anonymous_0AFile-sharing_Environment_0A.pdf)
* [Improving Content Availability in the I2P Anonymous File-Sharing Environment](http://hal.inria.fr/hal-00744922/PDF/Improving_Content_Availability_in_the_I2P_0AAnonymous_File-Sharing_Environment_0A.pdf)
* [Practical Attacks Against the I2P Network](https://wwwcip.informatik.uni-erlangen.de/~spjsschl/i2p.pdf)
