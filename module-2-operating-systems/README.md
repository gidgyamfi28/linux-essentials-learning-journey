# Module 2: Operating Systems

Module 2 helped me look at operating systems from a broader perspective. Instead of focusing only on Linux, I learned more about what an operating system actually does, the factors that can influence the choice of an operating system, and some of the differences between Windows, macOS, and Linux.

One thing I took from this module is that choosing an operating system is not simply about which one a person prefers. The purpose of the system, the applications it needs to run, hardware compatibility, stability, support, cost, and the people who will manage it can all influence that decision.

## 2.1 Understanding Operating Systems

I understood an operating system before mainly as the software that allows me to use and interact with a computer. This module helped me look deeper into what is actually happening behind the interface.

The operating system manages the computer's hardware and provides an environment for applications to run. It helps manage resources such as the processor, memory, storage, files, and connected devices.

For example, I can have a web browser, a code editor, and other applications running at the same time. These applications all need access to system resources. The operating system helps coordinate those resources so that the applications can run without each one directly taking control of the hardware.

This also helped me understand that the graphical interface I see on my computer is only one part of the operating system. A lot of resource management and other activities are taking place behind the scenes.

### 2.1.1 Choosing an Operating System

Another thing I learned was that choosing an operating system involves more than deciding between Windows, macOS, or Linux. The environment where the system will be used and what it is expected to do are important parts of the decision.

Some of the main factors I learned to consider are:

- **Role:** The operating system may be needed for a personal computer, workstation, or server. The role of the computer can affect which operating system is more suitable.

- **Function:** The applications and services that need to run on the system also matter. An operating system has to support the software and tasks it is being selected for.

- **Life cycle:** I learned that operating systems and their versions have support periods. For an organisation, it is important to consider how long a particular version will continue receiving updates and support before an upgrade becomes necessary.

- **Stability:** A newer release may provide new features, but that does not always make it suitable for every environment. A production system may require a stable and well-supported release rather than an experimental or beta version.

- **Compatibility:** The operating system should be compatible with the hardware, applications, and other systems that an organisation already uses.

- **Cost:** The cost is not limited to purchasing or licensing the operating system. Support, maintenance, hardware requirements, training, and future upgrades can also contribute to the overall cost.

- **Interface:** Depending on the users and the work being done, the system may be managed through a graphical user interface, a command-line interface, or a combination of both.

I found this useful because it changed the way I think about operating systems. Instead of asking which operating system is generally better, it makes more sense to first ask what the system is going to be used for and what requirements it needs to meet.

## 2.2 Microsoft Windows

Windows is the operating system I am most familiar with from everyday computer use, but this section helped me look at it more from a system administration point of view.

I learned that Microsoft provides Windows for both desktop and server environments. One important consideration with Windows is backward compatibility, because organisations may still depend on older applications and systems when moving to newer versions of the operating system.

I also learned more about the command-line tools available in Windows. Although Windows is commonly associated with its graphical interface, administrators can use tools such as PowerShell to manage and automate different tasks.

### Connecting Windows and Linux with WSL

One part that became more practical for me was Windows Subsystem for Linux, which I am currently using on my own computer. WSL allows me to run a Linux environment directly on Windows without having to set up a separate physical Linux computer.

I am currently using WSL 2 with Ubuntu 24.04.2 LTS for my hands-on practice. This is the environment where I have been practising the Linux commands documented in this repository.

What I found interesting about this is that I can continue using Windows as my main operating system while also having access to a Linux environment for learning and practical work. It has given me a convenient way to become more comfortable with Linux while still working from my Windows computer.

## 2.3 macOS

This section introduced me to macOS from more of a technical point of view. I mostly knew macOS as the operating system used on Apple computers, but I learned that there is more to it than the graphical interface that users normally see.

macOS has a UNIX foundation and is a UNIX-certified operating system. This means that although its interface is quite different from Linux, it also provides access to UNIX command-line tools through the Terminal.

I also learned that Apple develops macOS specifically for its own hardware. This allows Apple to have greater control over how the hardware and operating system work together.

One thing I found interesting was the connection between macOS and the command line. It showed me that working with commands is not something that belongs only to Linux. Command-line tools are also important in other operating systems, especially for development and system administration.

## 2.4 Linux

This section helped me understand Linux beyond the basic idea of it being an operating system. From Module 1, I had already learned that Linux technically refers to the kernel. In practice, however, we normally work with complete Linux distributions that combine the kernel with system utilities, applications, libraries, and other tools.

One thing that stood out to me is the amount of choice available with Linux. There is no single Linux distribution that everyone has to use. Different distributions are built with different users and purposes in mind. Some focus on stability and long-term support for organisations, while others introduce newer technologies more quickly or are designed for particular types of users.

This also made me understand why choosing a Linux distribution should depend on what I actually want to use the system for rather than simply choosing the most popular one.

### Community and Enterprise Distributions

I learned that Linux distributions can also differ in the way they are developed and supported. Some are mainly community-driven, while others have commercial organisations behind them that provide professional support and services.

For example, Fedora is a community distribution associated with Red Hat, while Red Hat Enterprise Linux is designed more specifically for enterprise environments. Ubuntu is developed by Canonical and is based on Debian, while SUSE also provides Linux distributions for enterprise environments.

For organisations, things such as stability, security updates, technical support, compatibility, and the length of time a release will be maintained can be very important. This helped me understand why an organisation may choose a long-term support release instead of always using the newest available version.

### Linux Distribution Families

Another thing I learned is that Linux distributions can be related to one another through distribution families.

Some examples I came across include:

- Debian, Ubuntu, and Linux Mint
- Red Hat Enterprise Linux and Fedora
- SUSE Linux Enterprise and openSUSE

These relationships matter because distributions from the same family often share certain tools, package formats, and ways of managing software.

For example, Ubuntu belongs to the Debian family and uses Debian packages. This is directly relevant to the Ubuntu environment I am currently using because I work with APT when managing software packages.

### Terminal and Shell

One distinction that became clearer to me in this section was the difference between a terminal and a shell. I previously tended to think of them as basically the same thing, but they perform different roles.

The terminal provides the interface where I can type commands and view their output. The shell is the program that receives those commands, interprets them, and allows me to interact with the operating system.

In my current setup, I use Windows Terminal to access my Ubuntu environment through WSL 2, while Bash is the shell I use inside that Linux environment.

Understanding this difference helped me make more sense of what is actually happening when I open a terminal and begin entering Linux commands.

### Embedded Linux

I also learned that Linux is not limited to desktop computers and servers. Because Linux can run on different hardware architectures and can be adapted for systems with limited resources, it is also widely used in embedded systems.

These can include networking devices, smart televisions, industrial systems, small computers, and Internet of Things devices. Devices such as the Raspberry Pi also provide a practical example of how Linux can be used on smaller hardware for learning, development, automation, and different projects.

This brought me back to one of the first ideas from Module 1: Linux really is used in many more places than I originally realised.