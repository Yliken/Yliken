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
--><img align="right" src="https://github.com/Yliken.png" width="21%" />

# Yliken

**红豆藏于南枝深处**  
> 红豆藏于南枝深处，相思缠绕心头不息  
> 纵使山河阻隔千里，愿化清风伴君身侧  
> 他说你任何为人称道的美丽 不及他第一次遇到你

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-%40Yliken-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yliken)
[![Blog](https://img.shields.io/badge/Blog-yliken.github.io-4285f4?style=for-the-badge&logo=readthedocs&logoColor=white)](https://yliken.github.io/)

</div>

**网络安全爱好者 | CTF 出题人 | 红队攻防 | 云安全 & 云原生安全研究者**

---

## 🔥 最新力作 · CTF 出题作品

<div align="center">

[![AllCTFGolangTi](https://img.shields.io/badge/CTF-全部_Go_Web_题目合集-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://github.com/Yliken/AllCTFGolangTi)
[![Stars](https://img.shields.io/github/stars/Yliken/AllCTFGolangTi?color=ffcb47&style=for-the-badge)](https://github.com/Yliken/AllCTFGolangTi)

[![QQbotYan](https://img.shields.io8.github.io/badge/QQbotYan-群聊安全审计机器人-EF4E4F?style=for-the-badge&logo=qq&logoColor=white)](https://github.com/Yliken/QQbotYan)
[![Stars](https://img.shields.io/github/stars/Yliken/QQbotYan?color=ffcb47&style=for-the-badge)](https://github.com/Yliken/QQbotYan)

</div>

| 项目 | 简介 | 技术亮点 | 一键启动 |
|------|------|----------|----------|
| **AllCTFGolangTi** | 纯手敲 Go + Gin 框架三道硬核 Web 题 | SSRF + 内网探测、二次 SQL 注入 + 宽字节、MySQL 比较特性利用 | Docker 一键运行 |
| **QQbotYan** | 企业级 QQ 群安全审计机器人（支持 OneBot v11） | 一个集「每日自动天气提醒 + CTF 比赛日程播报 + 豆包大模型实时语音回复 + 违禁词检测 + 一键踢禁管理」于一身的全能 QQ 群管家 |  |

→ 立刻开冲 AllCTFGolangTi：https://github.com/Yliken/AllCTFGolangTi  
→ 立刻部署 QQbotYan：https://github.com/Yliken/QQbotYan

---

## 📚 博客技术文章分类

| 分类         | 文章数 | 代表作 |
|--------------|--------|--------|
| 靶机复现     | 5+     | MazeSec、HackMyVM 全流程实战 |
| 云安全       | 3+     | AWS、Jenkins、GitLab、OIDC 权限提升 |
| 云原生安全   | 1+     | Kubernetes RBAC 滥用 + SSTI 攻击链 |
| CVE 复现     | 2+     | Helm 代码注入、Gogs RCE 深度分析 |

更多干货 → [yliken.github.io](https://yliken.github.io/)

---

## 🛠️ 兴趣领域 & 技术标签

<img src="https://img.shields.io/badge/云安全-FF6F61?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/> <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white"/> <img src="https://img.shields.io/badge/OIDC-4A154B?style=flat-square"/> <img src="https://img.shields.io/badge/CTF出题-00BFFF?style=flat-square&logo=hackthebox&logoColor=white"/> <img src="https://img.shields.io/badge/Go安全开发-00ADD8?style=flat-square&logo=go&logoColor=white"/>

---

## 💻 日常命令（出题人/红队人真实写照）

```bash
┌──(kali㉿Yliken)-[~]
└─$ nmap -sV -p- <target>                     # 经典指纹
┌──(kali㉿Yliken)-[~]
└─$ arp-scan --localnet                       # 局域网发现神器
┌──(kali㉿Yliken)-[~]
└─$ kubectl auth can-i --list --as=attacker   # K8s 权限摸底
┌──(kali㉿Yliken)-[~]
└─$ go run main.go                            # 出题人日常（手动狗头）
┌──(kali㉿Yliken)-[~]
└─$ docker run -d yliken/qqbotyan             # 群聊安全守护者上线
