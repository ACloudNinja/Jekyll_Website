---
layout: post
title: "How to install Packetbeat on macOS using Homebrew"
date: 2019-07-10 00:00:00 +0200
tags: brew elasticstack packetbeat homebrew macOS
categories: [Homebrew]
author: "andre_mare"
post_image: "/assets/img/my_images/blog/feature-image-homebrew.png"
---

This post provides a step-by-step guide with a list of commands on how to install Packetbeat on macOS using Homebrew. Packetbeat is a real-time network packet analyzer that you can use with Elasticsearch.

#### What is Packetbeat?
>“Packetbeat is a real-time network packet analyzer that you can use with Elasticsearch to provide an application monitoring and performance analytics system. Packetbeat completes the Beats platform by providing visibility between the servers of your network. Packetbeat works by capturing the network traffic between your application servers, decoding the application layer protocols (HTTP, MySQL, Redis, and so on), correlating the requests with the responses, and recording the interesting fields for each transaction.” ~ [Packetbeat Documentation][1]

#### What is Homebrew?
Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple’s macOS operating system. It is known as the missing package manager for macOS.

#### Quick Commands
The following is the single command required to install Packetbeat on macOS using Homebrew.
<pre style="background-color:black;color:white;padding:10px;">
$ brew install packetbeat 
</pre>

#### Brew Commands
This section provide a quick set of commands on how to install Packetbeat on macOS using Homebrew. It is assumed that Homebrew is already installed. If not, please follow this [link][2].

{% highlight shell %}
$ brew update                  # Fetch latest version of homebrew and formula.
$ brew search packetbeat       # Searches for formula called packetbeat
$ brew info packetbeat         # Displays information about packetbeat
$ brew install packetbeat      # Install the packetbeat formulae.
$ brew cleanup                 # Remove any older versions of any formula
{% endhighlight %}

#### Summary
Congratulations! You have successfully installed Packetbeat on macOS making use of Homebrew. Follow me on any of the different social media platforms and feel free to leave comments.

[1]:https://www.elastic.co/guide/en/beats/packetbeat/current/packetbeat-overview.html
[2]:href="https://brew.sh/