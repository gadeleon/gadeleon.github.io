---
layout: post
date: 2018-06-01 13:01:55 -0400
categories: problemsolving
tags: predator ssd acer raid0 kuso g9-593 g9-793 s-m-r-t
introduction: |
  An unwanted RAID0 setup walks into a gaming laptop and some someone impatient 
  thinks they can breeze through the solution.
---

Having spent the weekend troubleshooting and reading _other_ blogs about how to
solve my recent Linux woes. I'm going to outline the solutions NOW for any other
wayward Acer Predator 15 (and presumably 17) user who wants to do what I just did 
\-- skip the narrative and just getting to the important parts first.

**NOTE:** Some of these solutions I haven't tested because I blew away the RAID0
configuration, but, on paper, should work. Here's the Acer Predator Laptop I have:

**Acer Predator 15 (G9-593-71EH)**
* Nvidia Geforce GTX 1070 
* Intel Core i7 7th Gen 7700HQ (2.80 GHz)
* 256GB (2x 128GB RAID0)
* insydeH20 Rev 5.0 (This is the BIOS, this will be relevant too)

If you encounter any of the three problems here, then continue reading for the solutions.
1. _Install Alongside Windows 10/Windows Boot Manager_ won't appear when trying 
to install Ubuntu.
1. The live Ubuntu Media (USB/CD/DVD) goes blank after starting to boot.
1. After installing Linux, GRUB won't be an available option when you select Boot Options via the BIOS. 


# Install a Separate Drive with Linux on an Acer Predator 15 to Dual Boot Ubuntu 18.04
## With the out-of-the-box RAID0 configuration
## Without the RAID0 Configuration (ie. Remove the RAID0)

# Tell the BIOS that GRUB exists.

# Prevent Blank Screens after logging into Ubuntu. 