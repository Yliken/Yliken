## Hi there 👋

<!--
**Yliken/Yliken** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Yliken

**红豆藏于南枝深处**

> 红豆藏于南枝深处，相思缠绕心头不息，纵使山河阻隔千里，愿化清风伴君身侧。

> 他说你任何为人称道的美丽 不及他第一次遇到你

[![GitHub](https://img.shields.io/badge/GitHub-Yliken-181717?style=for-the-badge&logo=github)](https://github.com/Yliken)  
[![Blog](https://img.shields.io/badge/Blog-yliken.github.io-000000?style=for-the-badge&logo=gitbook)](https://yliken.github.io/)

网络安全爱好者，专注渗透测试、云安全、靶机复现、CVE 分析与 Pwn 学习。

## 最新文章

- [mazesec-BabyShell](https://yliken.github.io/posts/mazesec-babyshell/) — 2025-11-09  
  Linux 靶机复现，涉及主机发现与 arp-scan 技巧。
  
- [【Pwnedlabs】Exploit Jenkins in the Cloud](https://yliken.github.io/posts/pwnedlabs-jenkins/) — 2025-10-08  
  云环境 Jenkins 无认证漏洞利用实践。
  
- [【Pwnedlabs】Exploit Kubernetes Overly Permissive RBAC](https://yliken.github.io/posts/pwnedlabs-k8s-rbac/) — 2025-09-26  
  Kubernetes RBAC 过度权限与 SSTI 漏洞链。
  
- [【Pwnedlabs&WIZ】Abuse OpenID Connect and GitLab for AWS Access](https://yliken.github.io/posts/pwnedlabs-oidc-gitlab/) — 2025-09-23  
  OIDC 信任链滥用实现 AWS 权限提升。
  
- [hackmyvm-Democracy](https://yliken.github.io/posts/hackmyvm-democracy/) — 2025-09-18  
  创新 SQL 注入利用的靶机复现。

更多文章 → [我的博客](https://yliken.github.io/)

## 兴趣领域 & 分类

- **Linux 靶机**：HackMyVM、MazeSec 等复现
- **云安全**：AWS、Jenkins、GitLab 漏洞实践
- **云原生**：Kubernetes、Helm、RBAC 权限滥用
- **CVE 复现**：Helm 代码注入、Gogs RCE 等
- **Pwn 入门**：BUUCTF 栈溢出、基础二进制利用

常用标签：`aws` `k8s` `pwnedlabs` `nmap` `ssti` `oidc`

## 常用工具

```bash
┌──(kali㉿kali)-[~]
└─$ nmap -sV -p- <target>
┌──(kali㉿kali)-[~]
└─$ arp-scan --localnet
┌──(kali㉿kali)-[~]
└─$ sudo -l | exploit
