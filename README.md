# cnnrshd

Background in Cyber Security, currently working on Sysmon-related automation and testing.

[My personal website](https://connorshade.com) will have more info.

## Currently Working On

It's all Sysmon. I'm trying to improve coverage and verify reported coverage with Atomic-RedTeam and Security-Datasets.

- [Sysmon-Modular improvements](https://github.com/cnnrshd/sysmon-modular)
- [Atomic-RedTeam automated data collection](https://github.com/cnnrshd/atomic-datasets-utils)
- [Sysmon Utilities w/ Python](https://github.com/cnnrshd/sysmon_utils)

## Previously Worked On

- [Hashicorp-Packer Onion-style images for Windows](https://github.com/cnnrshd/packer-templates) - Old, a test on using multi-stage builds with Packer as DRY as possible. I think the idea is cool and I might return to it later. The key feature is that after an initial build and bootstrapping process, you can iteratively call `packer` with `increment` and just pass in the variable file, which allows for great template and artifact reuse (Base install -> Update -> 10 different images, only install and update once, then tune for other uses).
