# cnnrshd

Cyber Security with a focus on **Development** and **Automation**. Check out [my blog](https://connorshade.com), which is [hosted on GitHub](https://github.com/cnnrshd/cnnrshd.github.io).

## Currently Working On

Personal projects, mostly. **Feel free to reach out if there's something you think I could help with**.

- [Service-To-Shell](https://connorshade.com/service-to-shell/) - A project that combines a vulnerable service, nmap probes, and a metasploit module, all written by me.
  - [Made a webapp vulnerable to command injection](https://connorshade.com/service-to-shell/vulnerable-webapp/)
  - A [custom nmap probe](https://connorshade.com/service-to-shell/writing-nmap-scan/) to detect the webapp
  - A [custom Metasploit Module](https://connorshade.com/service-to-shell/custom-metasploit/) that automatically exploits the service
- **Getting a blog set up** (*Done*) - [Set up a blog](https://connorshade.com), deployed automatically with [Github Actions](https://github.com/cnnrshd/cnnrshd.github.io)

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
