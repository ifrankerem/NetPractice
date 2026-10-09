<div align="center">

# 🌐 NetPractice

**Ten small broken networks. Fix them with IP addressing, masks and gateways.**

![42](https://img.shields.io/badge/42-Common%20Core-000000?style=flat-square)
![Networking](https://img.shields.io/badge/TCP%2FIP-subnetting-0078D7?style=flat-square)
![Levels](https://img.shields.io/badge/levels-10-2b9348?style=flat-square)
![Stars](https://img.shields.io/github/stars/ifrankerem/NetPractice?style=flat-square)

</div>

---

## 📋 Table of Contents

- [About](#about)
- [Concepts You Need](#concepts-you-need)
- [Workflow](#workflow)
- [Submission](#submission)
- [Reference Material](#reference-material)
- [Author](#author)

---

## 📖 About

**NetPractice** is the 42 networking exercise: you get a simulated network
diagram that doesn't work, and you have to make it work by configuring IP
addresses, subnet masks and default gateways. Ten levels, each one a little
bigger than the last.

The networks are simulated — you solve them in a local browser training
interface, and the whole thing is about building instinct for addressing rather
than clicking through a GUI.

---

## 🧩 Concepts You Need

- **IP address** — a 32-bit number identifying a device on a network.
- **Subnet mask** — splits the address into network part and host part.
- **Subnet** — a network nested inside another network.
- **Default gateway** — where a host sends traffic destined outside its own network.
- **Switch** — forwards frames inside one local network, using MAC addresses.
- **Router** — connects different networks and routes packets between them.
- **MAC address** — hardware address identifying a NIC inside a LAN.
- **Modem** — converts digital data into signals and back.
- **Repeater / hub / bridge** — signal extension and network segmentation.

---

## 🔄 Workflow

1. Open the training interface (`index.html`, Chrome/Chromium recommended) and
   pick **Training** using your intranet login.
2. Read the goal at the top of the page.
3. Edit only the **unshaded** fields — IPs, masks, gateways.
4. Hit **Check again** to validate, and read the **Logs** to see what broke
   (invalid IP, wrong mask, missing gateway).
5. When the level is green, click **Get my config** and export it.
6. Repeat for all ten levels.

**Evaluation mode** generates random levels for the defense — the same skill,
random input.

---

## 📦 Submission

The ten exported configuration files, one per level, sit at the root of this
repository:

```
level1.json … level10.json
```

---

## 📚 Reference Material

Networking fundamentals playlist used while learning the basics:

- TCP/IP addressing
- default gateways
- repeaters, hubs, bridges, switches, routers
- OSI layers
- how a host communicates inside and outside its own network

[Playlist](https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)

---

## 👤 Author

**İrfan Kerem Arslan** — [@ifrankerem](https://github.com/ifrankerem)

*This project has been created as part of the 42 curriculum by iarslan.*

---

## 📄 License

Built for the **42 Common Core** curriculum. Shared for learning and portfolio purposes.

---

## 🙏 Acknowledgements

- [awesome-readme](https://github.com/matiassingers/awesome-readme) — structure inspiration for this README