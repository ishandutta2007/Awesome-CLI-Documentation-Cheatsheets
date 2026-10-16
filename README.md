# Awesome-CLI-Documentation-Cheatsheets

# Top CLI Documentation & Cheatsheets Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Simplified Man Pages, Interactive Cheatsheets & Offline Documentation Browsers*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CLI Documentation & Cheatsheets**. These tools enable developers to quickly recall command syntax and flags without wading through dense manual pages—from crowdsourced simplified examples to offline documentation browsers that work without an internet connection.

**Examples** include Man pages, TLDR pages, Cheat.sh, ExplainShell, DevDocs, Dash (Kapeli), Zeal, Command-line-fu, Bro pages, and Navi (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, community-maintained examples, and offline documentation access—ideal for developers, system administrators, and organizations seeking transparent, vendor-independent CLI knowledge management.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Dash (Kapeli)](https://kapeli.com/dash)**  
  **The gold standard for offline documentation browsers on macOS** . Features **200+ docsets** covering programming languages, frameworks, and APIs . **Instant search** with fuzzy matching and symbol navigation . **Integration with Xcode, Alfred, and other macOS tools** . **The premium choice** for macOS developers who want a polished, native documentation experience.

- **[DevDocs](https://devdocs.io/)**  
  **Fast, offline, and free documentation browser for developers** . Features **100+ documentation sets** in a unified web interface . **Works offline via PWA**—once loaded, documentation is available without internet . **The most accessible online/offline documentation browser**—no installation required.

- **[ExplainShell](https://explainshell.com/)**  
  **Web-based tool that breaks down shell commands into their component parts** . Type or paste a command and see **every flag, argument, and subcommand explained** based on man page content . **The most educational tool for learning command syntax** . **Note**: Web-only, not self-hostable.

- **[Command-line-fu](https://www.commandlinefu.com/)**  
  **Community-driven repository of command-line snippets** . Features **voting system** to surface the best commands . **The original social cheatsheet** for command-line one-liners.

## Open-Source GitHub Projects

- **[tldr-pages](https://github.com/tldr-pages/tldr)**  
  **Collaborative cheatsheets for console commands** (ISC) . **61,746+ GitHub stars** . **The most widely adopted open-source cheatsheet project**—**community-maintained help pages for command-line tools that aim to be a simpler, more approachable complement to traditional man pages**  . **The core insight**: man pages are thorough but often hard to digest; **there is room for simpler help pages focused on practical examples**  . **Features**: **simplified, practical command examples**, **translation into multiple languages**, **Markdown-based pages** that are easy to contribute to, and **official clients** for Python (`pipx install tldr`), Rust (`brew install tlrc`), and Node.js (`npm install -g tldr`)  . **The web client at tldr.inbrowser.app works without installation** with offline support via PWA  . **The reference implementation for simplified command documentation** .

- **[cheat.sh](https://github.com/chubin/cheat.sh)**  
  **The only cheat sheet you need** (MIT) . **41,000+ GitHub stars** . **Aggregates cheat sheets from multiple sources (including tldr-pages) into one unified interface**  . **Query via `curl cht.sh/command`** —returns static examples curated by contributors  . **The most comprehensive cheatsheet library**—covers **56+ programming languages, command-line tools, and UNIX utilities**  . **The best choice for looking up syntax for programming languages** (Python, Go, JavaScript) or getting comprehensive command examples (tar, rsync, ffmpeg)  .

- **[cheat](https://github.com/cheat/cheat)**  
  **Create and view interactive cheatsheets on the command-line** (MIT) . **13,000+ GitHub stars** . **The self-hosted approach to cheatsheets**—**designed to help remind Unix system administrators of options for commands that they use frequently, but not frequently enough to remember**  . **Features**: **cheatsheets are plain text files without extensions**, **nested sheets** (`cheat foo/bar`), **multiple cheatpaths** for personal/team/community separation, **autocompletion for bash, fish, and zsh**, **fzf integration for searching**, and **community cheatsheet downloads on first run**  . **The best choice for teams that want to maintain their own internal cheatsheet collection** .

- **[navi](https://github.com/denisidoro/navi)**  
  **An interactive cheatsheet tool for the command-line** (Apache-2.0) . **16,000+ GitHub stars** . **The most interactive cheatsheet experience**—**allows you to browse through cheatsheets and execute commands**  . **Suggested values for arguments are dynamically displayed in a list**—spares you from knowing CLIs by heart, copy-pasting output from intermediate commands, and makes you type less  . **Features**: **fuzzy search**, **dynamic argument suggestions**, **works with your own cheatsheets or community ones** . **The best choice for developers who want interactive command discovery** .

- **[Zeal](https://github.com/zealdocs/zeal)**  
  **Simple offline documentation browser inspired by Dash** (GPL-3.0) . **The open-source alternative to Dash**—**offers access to over 200 docsets covering various libraries and APIs**  . **Features**: **offline access to documentation**, **instant search**, **docset filtering with `:` syntax** (e.g., `java:BaseDAO`), **command-line query support** (`zeal python:pprint`), and **Dash docset compatibility**  . **The standard offline documentation browser for Linux and Windows** .

- **[Zealpy](https://pypi.org/project/zealpy/)**  
  **Lightweight, zero-dependency offline documentation browser and CLI for Dash and Zeal docsets** (GPL-3.0) . **Runs anywhere without compiling C++ code**—launches in milliseconds  . **Features**: **terminal CLI for instant symbol search**, **modern Dark Mode Web UI**, **official docset downloader for Python, Qt, PyQt, Pandas, NumPy, Flask, Django, PostgreSQL, and 20+ other popular stacks**, **auto-detection of existing Zeal docsets**  . **The most accessible offline documentation tool**—pure Python standard library, perfect for offline environments and exams  .

- **[bropages](https://github.com/ethanschoonover/bropages)**  
  **Highly readable supplement to man pages** (deprecated) . **Shows concise, common-case examples for Unix commands**—examples are submitted by the user base, and can be voted up or down  . **The original crowdsourced man page alternative**—now deprecated but historically important.

### Additional Strong Open-Source Options

- **[Command Line Interface Pages](https://github.com/commandlineinterfacepages/clip)** — Standardized help pages for CLI, directories, and configs  .
- **[devhints (Rico's cheatsheets)](https://devhints.io/)** — Not just focused on the command-line; includes cheatsheets related to programming  .
- **[eg](https://github.com/srsudar/eg)** — Provides detailed examples with explanations on the command-line  .
- **[kb](https://github.com/gnebbia/kb)** — Minimalist command-line knowledge base manager  .
- **[noman](https://pypi.org/project/noman-cli/)** — AI-powered, human-friendly man pages (MIT) . **Pre-generated, simplified documentation with real-world examples and FAQs**  .
- **[xpln](https://pypi.org/project/xpln2me/)** — CLI tool that explains terminal commands before you execute them  .
- **[arsenal-ng](https://github.com/halilkirazkaya/arsenal-ng)** — Modern pentest command launcher and cheatsheet manager (MIT) . **150+ cybersecurity cheatsheets with TUI**  .
- **[awesome-cheatsheets](https://github.com/skywind3000/awesome-cheatsheets)** — Programming language and developer tool cheatsheets (MIT) . **12,000+ GitHub stars**  .
- **[clishe](https://pypi.org/project/clishe/)** — Natural language to command-line tool with local AI (open-source)  .
- Community **n8n** workflows for cheatsheet synchronization and documentation alerting.

**Frameworks for building custom systems**: Combine **tldr-pages** for simplified command examples with **cheat** for team-maintained cheatsheets, **navi** for interactive discovery, **Zeal** or **Zealpy** for offline documentation browsing, and **cheat.sh** for comprehensive language reference—creating a complete CLI knowledge management stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CLI documentation tools handling command examples must ensure examples are safe and don't include destructive commands without clear warnings.
- **Open-source CLI documentation is mature and community-driven.** tldr-pages (61K+ stars) provides simplified command examples across languages  . cheat.sh aggregates multiple sources into one interface  . Zeal offers 200+ offline docsets  . **These are genuine alternatives to commercial documentation browsers.**
- **The tldr vs man page distinction matters.** Man pages are thorough but dense; **tldr focuses on the most common use cases with practical examples**  . **Neither replaces the other**—tldr for quick syntax recall, man pages for complete reference.
- **Offline access is the differentiator.** Zeal and Zealpy provide **offline documentation browsing**  . **This matters for air-gapped environments, exams, and unreliable internet connections.**
- **Interactive tools change the workflow.** navi's dynamic argument suggestions and fuzzy search **spare you from knowing CLIs by heart**  . **This is a fundamentally different experience from static lookup**—exploration versus reference.
- Self-hosted open-source solutions require proper cheatsheet curation and ongoing maintenance. **Cheatsheets are only as good as their examples**—outdated or incorrect examples undermine trust in the tool.

---

**Made for developers, system administrators, and organizations building transparent CLI knowledge solutions.**  
Let's make CLI Documentation & Cheatsheets more open, data-driven, and accessible.
