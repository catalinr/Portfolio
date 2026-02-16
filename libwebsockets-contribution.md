## [<img src="https://avatars.githubusercontent.com/u/1497695?s=200&v=4" width="32" />](https://libwebsockets.org/) Libwebsockets feature contribution: TLS session caching and reuse support

🏦 **Purpose:** Reduce `TLS` handshake overhead through session caching and reuse

⚙️ **Tech stack:** `C`

🔒 **Source code:** Open source,
[warmcat/libwebsockets](https://github.com/warmcat/libwebsockets/tree/main/include/libwebsockets)

🧑‍💻 **Role:** Contributor

🚀 **Outcome:** New APIs: `lws_tls_session_dump_save()`, `lws_tls_session_dump_load()`, `lws_tls_session_is_reused()`.

---

#### Online Mentions and Literature 🔗

- Detailed description [1]
- Mention in Changelog for `v4.2.0` [2]
- Relevant commits: [3].
- Initial github issue [4]

[1]: https://libwebsockets.org/lws-api-doc-main/html/md_READMEs_README_tls_sessions.html
[2]: https://github.com/warmcat/libwebsockets/blob/main/changelog
[3]: https://github.com/search?q=repo%3Awarmcat%2Flibwebsockets+d5753b6+33f5bf2+80ca71d+d2a40a1+373b50d+cf867fa&type=commits&s=author-date&o=desc
[4]: https://github.com/warmcat/libwebsockets/issues/1387#issuecomment-806226152

---

###### ← Back to [Portfolio Home](./README.md)
