---
layout: post
title: "How to install Heartbeat on macOS using Homebrew"
date: 2019-07-08 00:00:00 +0200
tags: brew elasticstack heartbeat homebrew macOS
categories: [Homebrew]
author: "andre_mare"
post_image: "/assets/img/my_images/blog/feature-image-homebrew.png"
---

This post provides a step-by-step guide with a list of commands on how to install Heartbeat on macOS using Homebrew. Heartbeat is a lightweight daemon that you install on a remote server to periodically check the status of your services and determine whether they are available.

#### What is Heartbeat?
“Heartbeat is a lightweight daemon that you install on a remote server to periodically check the status of your services and determine whether they are available. Unlike Metricbeat, which only tells you if your servers are up or down, Heartbeat tells you whether your services are reachable.” ~ [Heartbeat Documentation][1]

#### What is Homebrew?
Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple’s macOS operating system. It is known as the missing package manager for macOS.

#### Quick Commands
The following is the single command required to install Heartbeat on macOS using Homebrew.
<pre style="background-color:black;color:white;padding:10px;">
$ brew install heartbeat
</pre>

#### Brew Commands
This section provide a quick set of commands on how to install Metricbeat on macOS using Homebrew. It is assumed that Homebrew is already installed. If not, please follow this [link][2].

{% highlight shell %}
$ brew update                 # Fetch latest version of homebrew and formula.
$ brew search heartbeat       # Searches for formula called heartbeat
$ brew info heartbeat         # Displays information about heartbeat
$ brew install heartbeat      # Install the heartbeat formulae.
$ brew cleanup                # Remove any older versions of any formula
{% endhighlight %}

#### Summary
Congratulations! You have successfully installed Metricbeat on macOS making use of Homebrew. Follow me on any of the different social media platforms and feel free to leave comments.

[1]:https://www.elastic.co/guide/en/beats/heartbeat/current/heartbeat-overview.html
[2]:href="https://brew.sh/