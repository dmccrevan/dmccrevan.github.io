+++
title = "Update on Netting + new projects"
date = 2020-07-10
[taxonomies]
tags=["Netting", "Development", "Embedded"]
+++

In my first post, I introduced [Netting](https://github.com/Netting-Mesh/netting) and spoke about keeping dev blogs here to go
along with my development. Sadly, Netting was put to hold for a few reasons. The main one is that I think I was a bit in
over my head when choosing to write an entire service mesh from scratch. I feel like writing a large project like that requires me to
understand the concepts of existing ones in a deeper detail as well as being much more familiar with the language I am writing
the project in. I had a general/somewhat deep understanding of [Istio](https://istio.io), but I didn't really dive into [Linkerd](https://linkerd.io)
or [Consul](https://consul.io) as I should've. Along with that, I feel I am just now becoming intermediately skilled at Rust, but
for a project large like a service mesh, I should have more experience writing in the language of choice.

So to pivot in my free-time coding, I bought a Raspberry Pi 3 A+ for my own self-learning experience in embedded/systems programming. I plan to
do a variety of different things with this such as writing some low overhead projects to run on this, learn more about linux (maybe do a LFS to deploy onto this), and other projects in that area. The reason being is I am getting more interested in the lower level area with things such as operating systems, compilers, embedded development, and lower level languages.

To start in this area, I've been refreshing my memory on C++, learning how to compile to ARM, and starting a mini project to deploy onto the Pi. The project I am writing now is a simple agnostic statistic collector to run on the Pi. The main process is being written in Rust. It is configured with plugins (which can be written in any language), then it'll scan to see if these plugins have any statistics to produce, and if so build an email report of these statistics to email them off to my personal email. It is a fairly simple project, but I have found it to be a great learning experience so far.

Things I want to understand better for next time are:

   * Difference between `gnuabi` and `gnuabihf`
   * Some basic conceptual differences between x86 & ARM
   * How to produce a production ready Rust binary


Also a quick shout-out to [Cross](https://github.com/rust-embedded/cross). This is an **amazing** tool that makes building Rust to other platforms seamless. Highly recommend.


Until next time,

~ Dan
