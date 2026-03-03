<p align="center">
  <img src="https://raw.githubusercontent.com/modulino-lab/.github/refs/heads/main/assets/logo/logo.svg" width="100" alt="Logo for modulino">
</p>

<h1 align="center">modulino</h1>

<p align="center">
  Plug-and-play 3D printer accessories,
  <br/>
  designed for seamless performance and compatibility.
</p>

<p align="center">
  <a href="https://www.instagram.com/team.modulino?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw=">
    <img src="https://img.shields.io/badge/instagram-%23FF0069.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram badge">
  </a>&nbsp;
  <a href="mailto:teammodulino@gmail.com">
    <img src="https://img.shields.io/badge/mail_us-%23EA4335.svg?&style=for-the-badge&logo=gmail&logoColor=white" alt="Email badge">
  </a>
</p>

## modulino.lab

### Problem

The traditional method of production, which involves manufacturing molds before
production, has high initial costs. As production volume increases, the unit
cost of production decreases, making it suitable for mass production rather than
small-batch manufacturing. In contrast, the 3D printing method has low initial
costs and shows high efficiency in multi-variety, small-lot production.

As a result, the frequency of using maker spaces or outsourced printing services
for small-scale production and prototyping purposes has increased. With the
expansion of this market, there has also been a growing trend toward
establishing 3D printer farms.

But nothing is perfect. To really make 3D printer farms industry-ready, every
farm needs a way of managing the whole farm as one system. In the case of maker
spaces or outsourced printing services, **a small number of personnel are
typically responsible for managing multiple printers**. However, since printing
is often done with models that have different conditions each time, there are no
standardized operating parameters, and as a result, a wide range of potential
issues can arise.

And the real issue is, that **a farm may require some specific functions**,
which in many cases will not be included in the 3D printer, especially those
that are not the flagships of one brand.

To add that one last piece of the puzzle, there are two options:

- Use a high-end flagship printer
  - Advantage:
    - Additional functions can be used immediately without modification
  - Disadvantage:
    - The cost of purchasing the printer is high
    - Functions are tied to specific models
    - Financial burden

- Use optional expansion kits
  - Advantage:
    - Desired functions can be added separately
  - Disadvantage:
    - Compatibility issues may arise between the expansion kit and the 3D
      printer
    - The modification process requires technical expertise
    - There is a risk of device malfunction during modification

As seen above, **both are not a real trustworthy solution** for maker spaces and
outsourced printing services.

Compatibility is a huge problem. It is truly hard to make those changes yourself
one by one, and they break the warranty. It is hard to manage the printers as
one farm. It is hard to troubleshoot if anything goes wrong.

### Goal

**Meet modulino — the unified control system for your 3D printer farm.**

Managing multiple printers individually wastes time and introduces errors.
modulino centralizes every printer into a **single dashboard** — track jobs,
monitor runtime, assign tasks, and identify issues instantly.

modulino works with your existing printers through a USB hardware module. **No
proprietary hardware required.** Add functions, automate prints, receive alerts
the moment something fails — all from one interface.

### Main Features

- 3D printer farm management on web-based dashboard
- Ability to add/delete printers to the system with carefully designed PnP
  experience
- Ability to fluently add/delete new features to nearly every printer in the
  market
- Notifications and automated initial response right at the time when something
  goes wrong

## Development

### Hardware

The hardware, **modulino-hub**, is a plug-and-play integrated control hub that
adds smart functionality to existing 3D printers through a simple USB
connection.

It provides universal compatibility without complex installation or printer
modification, and its modular expandable architecture allows for custom feature
configuration based on user needs.

The system aims to simultaneously enhance the safety, efficiency, and
convenience of 3D printer farm operations.

Peripheral hardwares designed for the modulino-hub, **modulino-parts** are what
makes these special. They are the modules that provide additional feauters to
the printers. Plug them into modulino-hub, and right away you have a new feature
to your existing printer.

### Software

The software, **modulino-system**, is a local server-based control program
designed to efficiently integrate and monitor multiple distributed hub modules
(hereafter “devices”) through a single unified interface.

It ensures stable operation even in complex network environments and aims to
eliminate device management complexity and maximize operational efficiency
through an intuitive user experience.

modulino-system is designed as **dashboard-first UI**, providing printer
management team a simple but powerful set of features just a click away.

## Customer Segment

The core target market for modulino is **maker spaces within universities**.

This market, characterized by a **B2G (Business-to-Government)** nature, is
continuously expanding, driven by government policies supporting
entrepreneurship and technical education.\
As a key infrastructure enabling students to realize creative ideas and
supporting prototype production for aspiring entrepreneurs, there is a **strong
demand for enhanced operational efficiency and advanced management**.

## Team

- [Midori](https://github.com/faransansj)
  - Team leader
  - Leading the **hardware** development team for several months
  - Contributed to the software with feature list-up

- [7591yj](https://github.com/7591yj)
  - Leading the **software** development team for several months
  - Designed and developing the frontend
  - Contributed to the backend architecture with Socket.IO implementation
  - Designed and implemented required types for the frontend/backend/firmware

- [cici](https://github.com/kaman-cici)
  - Developing the **hardware**
  - Contributed to the design/marketing of modulino

- Louis
  - Leading the **business/financial** developments for modulino
  - Generated the basic outline for Financial & Business Model Analysis
  - Contributed to the design/marketing of modulino

- SayWorld
  - Coordinating event participation
