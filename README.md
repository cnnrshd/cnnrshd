# cnnrshd

Cyber Security with a focus on **Development** and **Automation**.

## Currently Working On

Personal projects, mostly.

- Getting my blog up (Hugo - possibly)
- A fun project that combines a vulnerable service, nmap match directives, and a metasploit module, all written by me. Once I get the blog up repos and posts will follow
  - Made a webapp vulnerable to command injection (finishing writing)
  - Webapp reports a banner - custom nmap `match` directive to detect it (finishing writing)
  - Metasploit module that exploits the command injection, returning a shell (in progress)

## Things I do/Have done

- Training (Networking, Sys Admin, Security)
- Program (Python, getting into Go)
- Offensive Security
- Competitive Blue Teaming (CCDC)
- Competitive Networking (FBLA)

## Previously Worked On

A ton of Sysmon stuff. Expect additional info on Sysmon later.

- [Sysmon-Modular improvements](https://github.com/cnnrshd/sysmon-modular)
- [Atomic-RedTeam automated data collection](https://github.com/cnnrshd/atomic-datasets-utils)
- [Sysmon Utilities w/ Python](https://github.com/cnnrshd/sysmon_utils)
- [Hashicorp-Packer Onion-style images for Windows](https://github.com/cnnrshd/packer-templates) - Old, a test on using multi-stage builds with Packer as DRY as possible. I think the idea is cool and I might return to it later. The key feature is that after an initial build and bootstrapping process, you can iteratively call `packer` with `increment` and just pass in the variable file, which allows for great template and artifact reuse (Base install -> Update -> 10 different images, only install and update once, then tune for other uses).
