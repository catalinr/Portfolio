## [<img src="https://mega.io/wp-content/themes/megapages/megalib/icons/logos/mega.svg" width="24" />](https://mega.io) Mega, SDK [<img src="https://cdn.simpleicons.org/github/000000/ffffff" width="24" />](https://github.com/meganz/sdk)

🏦 **Purpose:** cross-platform SDK that powers all Mega (commercial) products; they are all built on top of it.

🚀 **Functionality:** provides secure access to Mega Cloud Storage via `MegaApi` interface; functionality like complete end-to-end encryption for secure file storage / backup / synchronization, control and observability for file transfers, searching & filtering & pagination, shared file access, account management, subscribing to backend updates, events, notifications and alerts, commercial support for adds, pricing and discounts, and a plethora of other options. Built for Windows, Linux, MacOS, iOS and Android, for all architectures that each supported, out of x86-64, x86, arm64, arm. [<img src="https://cdn.simpleicons.org/github/000000/ffffff" width="20" />](https://github.com/meganz/sdk/commits/master/?author=cra%40mega.nz)

⚙️ **Tech stack:** `C++` · `C++ 11/14/17/20` · `Multi-threading` · `Cross-platform` · `Cross-architecture` · `Python` · `SQL` · `shell` · `cmake` · `Docker` ·· `GoogleTest` · `win32` · `WMI` · `libudev` · `libwebsockets` · `curl` · `Qt5` ·· `OOP` · `synchronization` · `memory management` ·· `Visual Studio` · `gcc` · `VCPKG` · `git` ·· `Windows` · `Linux` ·· `Github` · `GitLab` · `JIRA` · `Jenkins` CI/CD · `Confluence` · `Slack`.

🔓 **Source code:** Open source, public git repository.

🧑‍💻 **Role:** Senior SDK Engineer.

---

#### Notable contributions 🔗

- Complete design and implementation of cross-platform multi-process runner for integration tests. It was implemented with GoogleTest for running tests in parallel, via Jenkins CI/CD. It handled individual test outcome, crashes, logging, clean-up etc.
- Complete design and implementation of removable drive handling, for Windows and Linux.
- Complete design and implementation of enhanced search, allowing multiple and extendable filtering while keeping a stable API.
- Main design and implementation for "sets and elements", for allowing implementation of new features like photo albums, playlists etc.
- Main design and implementation for automatic release process of new SDK versions. It was written in Python and integrated communication with local git instance, and remote tools like GitLab, Github, JIRA and Slack.
- Automatic build scripts for Windows, Linux, MacOS, iOS, Android targets for all supported architectures out of x86-64, x86, arm64, arm, using Docker, Cmake, VCPKG.

---

###### ← Back to [Portfolio Home](./README.md)
