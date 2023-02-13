# Distributions

## What is a distribution?
A software distribution or *distro* is a version of that software that has been altered or comes with a collection of predecided and curated components or other software out of the box. Many popular programs from web browser, to text editors, to operating systems have various distros that can be chosen from. The process of creating a distribution of software can be called *forking*, because that software is now forking or branching off into something else. And maybe that fork will be forked itself. This process of creating and forking new distros of software can create a tree like structure with branches spanning out from other branches based on the distros' familial relationships. 

## Linux Distributions
And Linux is definitely no exception. There are countless distros, sometimes referred to as *flavors*, currently in active development and maintenance. The vast amount of distros can be daunting and even paralyzing to a new user, but it seems that these sentiments arise from misconceptions regarding the differences is distros.

![distros](./imgs/distros.svg)
*Depiction of the vast tree of Linux distributions that makes you scroll a lot*

The above image that depicts the family tree of Linux distros lays out multiple *main* or *root* distros, as in they are not based on anything else, and have many descendants. Generally, the most relevant main distros are: 

* Debian
* Arch
* Red Hat

These three distros and their derivatives are widely used by larges enterprises, companies, and individual users. Furthermore, there are *independent* distros that are not based on anything, and have very unique and esoteric quirks. So there are quite a few options, but how do you know which to choose? 

## The Differences
Most distributions are going to have aesthetic and functional differences between the graphical user interfaces that come pre-installed on the system. However, in many cases this is simply an aesthetic difference that can be changed as distros often support multiple graphical environments. You will learn more about graphical user environments or *GUIs* in the later chapter: [Elements of a Linux Graphical User Interface](). This is also true for most software that is installed by default on a distro; it can simply be uninstalled or replaced. Beyond these aesthetic and more ephemeral differences, there are three more non trivial differences between distros:

* Update Delivery
* Package Availability
* Initialization System

### Update Delivery 
There are three types of software update delivery paradigms on Linux. There is *rolling release*, *fixed release*, and *semi-rolling release*. A fixed release distro such as Red Hat or Debian have versions that are updated annually along with software repositories. Usually available software on these distros can be relatively dated. A rolling release distro however does not have versions. Instead the latest software is available as it become available. In this case you have access to the latest versions of software. And a semi-rolling release is a combination of the two, where a major update is rolled out annually, but users have access to the latest software in *most* cases. All this being said, distros that are fixed usually are more *stable* and more free of bugs, issues, and conflicts, and suited for use on servers. 

### Package Availability
Distros differ in that some have more programs or *packages* available for install than other. This is because those who maintain the distro have made that software available within that distro's *repositories*. You will learn more about packages and software repositories in the later chapter [Packaging Systems & Package Management]().

### Initialization Systems
Some distros have different initialization or *init* systems. The most prominent init system is SystemD. Other init systems exist, but are found on systems far less today. You will learn about init systems in the later chapter: []().


## Recommendations
This book will be using Fedora for all examples and snippets. Fedora is an excellent choice because it is well supported semi-rolling distro that has fresh packages and a welcoming graphical user interface by default for new users. However, you can choose any distro you want. Some are less beginner friendly and will differ in a few ways, but the differences won't be vast enough to prevent you from following along using another distro if you refer to that distro's documentation.

Here is a table of some possible options for you.

| Main Distro | Update Delivery | Popular Distros Derived From |
|---------|---------|----------|
| Debian     | Fixed or Rolling| Ubuntu, Linux Mint, Pop OS!, MX Linux|
|Arch|Rolling|Manjaro, Garuda, Arcolinux|
|Red Hat|Fixed|Fedora*, Rocky Linux|
*Fedora is semi-rolling

