# Module 1: Linux Foundations

Module 1 helped me understand what Linux actually is and why it is used in so many areas of computing. Before going through this module, I mostly associated Linux with an operating system used on servers. As I went through the lessons, I started to understand the role of the Linux kernel, how open-source software works, why there are different Linux distributions, and why the command line is such an important part of working with Linux.

## 1.1 Linux Is Everywhere

One of the first things that stood out to me was how widely Linux is used. I used to associate Linux mainly with computers and servers, but I learned that it can also be found behind cloud services, networking devices, embedded systems, mobile devices, supercomputers, and many other technologies.

This also helped me understand why learning Linux is useful beyond simply knowing how to use another operating system. Linux knowledge is relevant in areas such as system administration, networking, cybersecurity, software development, cloud computing, and DevOps.

## 1.2 Linux Is a Kernel

Before this section, I used the word Linux to refer to the entire operating system. What I learned, however, is that Linux technically refers to the **kernel**, which is the core part of the system that manages communication between the hardware and the software running on the computer.

The kernel manages important system resources such as the processor, memory, storage, and connected devices. Applications do not simply take control of these resources on their own. The kernel helps manage how they are accessed and used by different processes.

I also learned why the term **GNU/Linux** is sometimes used. The Linux kernel by itself does not make up the complete operating environment that we normally use. It is combined with utilities, libraries, applications, and many tools that came from the GNU Project and other open-source projects.

### UNIX, GNU, and Linux

Understanding the history also helped me see how these technologies are connected. UNIX came first and introduced many of the ideas that later influenced other operating systems. The GNU Project was started in 1983 by Richard Stallman with the aim of developing a free UNIX-like operating system and produced many of the tools that are still used in Linux environments today.

The Linux kernel was later started by Linus Torvalds in 1991. Linux follows many UNIX concepts, which is why it is described as a **UNIX-like** system, but Linux itself is not simply UNIX.

## 1.3 Linux Is Open Source

Another important part of this module was understanding what open-source software actually means. I had heard the term "open source" several times before, but this section helped me understand that it is not simply about software being free to download.

With open-source software, the source code is made available under a licence that allows people to study it and, depending on the licence terms, modify and redistribute it. This is different from closed-source software, where the source code is normally controlled by the organisation or developer that owns the software.

I also learned that this development model played an important role in the growth of Linux. Developers and organisations from different parts of the world can contribute to the Linux ecosystem, identify problems, improve existing code, and develop tools around it.

One thing I found interesting was learning that the Linux kernel is primarily written in the C programming language. This also helped me understand why C continues to be important when working closer to operating systems and hardware.

## 1.4 Linux Has Distributions

Another concept that became clearer to me was the meaning of a Linux distribution, often called a distro. Since Linux itself is the kernel, a complete system needs more than just the kernel. A Linux distribution brings the kernel together with system utilities, applications, libraries, a package-management system, and other tools to provide a usable operating system.

There are many Linux distributions because they are built for different purposes and users. Some are designed mainly for servers and enterprise environments, while others focus more on desktop use, development, security, or specialised tasks.

I also learned that distributions can belong to different families. Some of the major ones I came across were Debian, Red Hat, and Slackware. Ubuntu, which I am currently using for my hands-on practice, belongs to the Debian family.

This became more practical for me when I started working with APT on Ubuntu. APT is the package-management tool I can use to find, install, update, and remove software from configured repositories. This helped me see that the choice of distribution can also affect the tools and package-management system I work with.

## 1.5 Linux Embraces the Command Line

The command line was another important part of this module. I was already familiar with graphical user interfaces, where I normally interact with a computer through windows, icons, menus, and buttons. With the command-line interface, I interact with the system by typing commands instead.

What I am beginning to understand is why the command line is so important in Linux. It gives me a direct way of interacting with the system and can be useful for administration, troubleshooting, automation, and working with remote systems. Although it takes some time to become familiar with the commands, I can see why it becomes very useful once you understand what the commands are actually doing.

### My First Command-Line Practice

I practised some basic commands on my Ubuntu environment to understand how I can get information about myself, my current location, the files around me, and the system I am using.

```bash
whoami
pwd
ls
uname -a