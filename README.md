# Mirai BotNet
Leaked Linux.Mirai Source Code for Research/IoT Development Purposes

Uploaded for research purposes and so we can develop IoT and such.

See "ForumPost.txt" or [ForumPost.md](ForumPost.md) for the post in which it
leaks, if you want to know how it is all set up and the likes.

## This Fork

This is a fork of Mirai that uses [papaw](http://github.com/dimkr/papaw) to
compress the malware binaries, make them harder to research (by providing some
basic means of anti-debugging) and allow fileless execution.

It's useful for testing anti-virus software for Linux, which is supposed to
detect at least the original Mirai binaries as malicious. Is that anti-virus
smart enough to deal with unknown packers and this kind of self-extractors?

## Requirements
* gcc
* golang
* electric-fence
* mysql-server
* mysql-client

## Credits
[Anna-senpai](https://hackforums.net/showthread.php?tid=5420472)

## Disclaimer
This repository is for academic purposes, the use of this software is your
responsibility.

## Warning
The [zip file](https://www.virustotal.com/en/file/f10667215040e87dae62dd48a5405b3b1b0fe7dbbfbf790d5300f3cd54893333/analysis/1477822491/) for this repo is being identified by some AV programs as malware.  Please take caution.
