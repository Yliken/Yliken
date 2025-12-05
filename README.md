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

网络安全爱好者，专注渗透测试、云安全、靶机复现与 CVE 分析。

## 博客技术文章分类概括

我的博客目前聚焦以下技术领域（排除 Pwn 相关内容）：

| 分类              | 文章数 | 主要内容                                                                 |
|-------------------|--------|--------------------------------------------------------------------------|
| **靶机复现**     | 5 篇   | Linux 靶机实践，如 MazeSec 和 HackMyVM 系列，涉及主机发现、SQL 注入等技巧 |
| **云安全**       | 3 篇   | AWS、Jenkins、GitLab、OIDC 等漏洞利用与权限提升实践（包含 Pwnedlabs 系列） |
| **云原生安全**   | 1 篇   | Kubernetes RBAC 过度权限、SSTI 等云原生环境攻击链                        |
| **CVE 复现与分析** | 2 篇   | Helm 代码注入、Gogs RCE 等漏洞深度复现与思考                             |

更多文章 → [我的博客](https://yliken.github.io/)

## 兴趣领域 & 分类

- **云安全**：AWS、Jenkins、GitLab、OIDC 漏洞实践
- **云原生**：Kubernetes、Helm、RBAC 权限滥用
- **CVE 复现**：Helm 代码注入等漏洞分析
- **渗透测试**：靶机复现、主机发现技巧

常用标签：`aws` `k8s` `pwnedlabs` `cve` `jenkins` `helm` `oidc`

```bash
┌──(kali㉿kali)-[~]
└─$ nmap -sV -p- <target>          # 服务扫描，发现开放端口与版本
┌──(kali㉿kali)-[~]
└─$ arp-scan --localnet            # 局域网主机发现神器
┌──(kali㉿kali)-[~]
└─$ kubectl auth can-i --list      # 检查 Kubernetes RBAC 权限
