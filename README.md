# Hi, I'm Yliken 👋

## About Me

- 🔭 building **redbeanshellcore** — a Go SDK for remote node operations
- 🌱 working on security tooling and Go frameworks
- 💬 Ask me about Go, PHP security, web shells
- 📫 [@Yliken](https://github.com/Yliken)

---

## Featured Project

### [redbeanshellcore](https://github.com/Yliken/redbeanshellcore)

> *"红豆生南国，此物最相思。"*

A Go SDK for remote node communication & operations.

```go
client := core.NewClient(
    core.WithSession(&core.Session{...}),
    core.WithTransport(httpform.New("https://lab.example/shell.php")),
)
res, _ := client.Do(ctx, phpshell.NewPhpInfo())
```

**Highlights:**
- Pluggable Transport / Codec / Envelope / Middleware
- Built-in AntSword PHP template adapter
- Readonly / Audit / Timeout / Retry middleware
- Multi-node management with Registry + Manager
- Strongly-typed Results, 12 ErrorKinds

---

## Tech Stack

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white)
![Security](https://img.shields.io/badge/-Security-000000?style=flat)

---

*Built with ❤️ and a touch of red bean poetry.*
