---
layout: post
title: "How to install Auditbeat on macOS using Homebrew"
date: 2019-07-09 00:00:00 +0200
tags: brew elasticstack auditbeat homebrew macOS
categories: [Homebrew]
author: "andre_mare"
post_image: "/assets/img/my_images/feature-images/feature-image-homebrew.png"
---

This post provides a step-by-step guide with a list of commands on how to install Auditbeat on macOS using Homebrew. Auditbeat is a lightweight shipper that you can install on your servers to audit the activities of users and processes on your systems.

#### What is Auditbeat?
“Auditbeat is a lightweight shipper that you can install on your servers to audit the activities of users and processes on your systems. For example, you can use Auditbeat to collect and centralize audit events from the Linux Audit Framework. You can also use Auditbeat to detect changes to critical files, like binaries and configuration files, and identify potential security policy violations.” ~ [Auditbeat Documentation][1]

#### What is Homebrew?
Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple’s macOS operating system. It is known as the missing package manager for macOS.

#### Quick Commands
The following is the single command required to install Auditbeat on macOS using Homebrew.
<pre style="background-color:black;color:white;padding:10px;">
$ brew install auditbeat 
</pre>

#### Brew Commands
This section provide a quick set of commands on how to install Auditbeat on macOS using Homebrew. It is assumed that Homebrew is already installed. If not, please follow this [link][2].

{% highlight shell %}
$ brew update                 # Fetch latest version of homebrew and formula.
$ brew search auditbeat       # Searches for formula called auditbeat
$ brew info auditbeat         # Displays information about auditbeat
$ brew install auditbeat      # Install the auditbeat formulae.
$ brew cleanup                # Remove any older versions of any formula
{% endhighlight %}

#### Summary
Congratulations! You have successfully installed Auditbeat on macOS making use of Homebrew. Follow me on any of the different social media platforms and feel free to leave comments.

[1]:https://www.elastic.co/guide/en/beats/auditbeat/current/auditbeat-overview.html
[2]:href="https://brew.sh/