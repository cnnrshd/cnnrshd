# cnnrshd

Cyber Security with a focus on **Development** and **Automation**. Check out [my blog](https://connorshade.com), which is [hosted on GitHub](https://github.com/cnnrshd/cnnrshd.github.io).

I am **Looking for new opportunities**! [LinkedIn](https://www.linkedin.com/in/connor-shade-5688bab9/) is the best place to reach me.

## Currently Working On

Personal projects, mostly. **Feel free to reach out if there's something you think I could help with**.

- A fun project that combines a vulnerable service, nmap match directives, and a metasploit module, all written by me. Once I get the blog up repos and posts will follow - [project page](https://connorshade.com/service-to-shell/)
  - [Made a webapp vulnerable to command injection](https://connorshade.com/service-to-shell/vulnerable-webapp/)
  - Webapp reports a banner - custom nmap `match` directive to detect it (editing)
  - Metasploit module that exploits the command injection, returning a shell (in progress)
- Getting a blog set up on Hugo, [deployed through Github Pages](https://github.com/cnnrshd/cnnrshd.github.io)

## Things I do/Have done

- Training (Networking, Sys Admin, Security)
- Program (Python, getting into Go)
- Offensive Security
- Competition Black Team (ISTS, IRSec)
- Competitive Blue Teaming (CCDC, ISTS, IRSec)
- Competitive Networking (FBLA)

### Skills, of varying quality

- **Programming** - Python, PowerShell, Javascript
- **Automation** - Ansible, Docker, Packer, Vagrant
- **Security** - Incident response, threat hunting


## Previously Worked On

A ton of Sysmon stuff. Expect additional info on Sysmon later.

- [Sysmon-Modular improvements](https://github.com/cnnrshd/sysmon-modular)
- [Atomic-RedTeam automated data collection](https://github.com/cnnrshd/atomic-datasets-utils)
- [Sysmon Utilities w/ Python](https://github.com/cnnrshd/sysmon_utils)
- [Hashicorp-Packer Onion-style images for Windows](https://github.com/cnnrshd/packer-templates) - Old, a test on using multi-stage builds with Packer as DRY as possible. I think the idea is cool and I might return to it later. The key feature is that after an initial build and bootstrapping process, you can iteratively call `packer` with `increment` and just pass in the variable file, which allows for great template and artifact reuse (Base install -> Update -> 10 different images, only install and update once, then tune for other uses).
