<!-- pam:product-page:start -->
<div align="center">

# PAM HTTP PSR

**Bring PSR-7, PSR-15, and PSR-17 software to PAM HTTP.**

Translate between PAM-native requests and the PHP-FIG interfaces at an explicit interoperability boundary.

[![Release](https://img.shields.io/github/v/release/push-in/pam-http-psr?style=flat-square&label=stable)](https://github.com/push-in/pam-http-psr/releases)
[![CI](https://img.shields.io/github/actions/workflow/status/push-in/pam-http-psr/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/push-in/pam-http-psr/actions)
![PHP](https://img.shields.io/badge/PHP-8.5-777BB4?style=flat-square&logo=php&logoColor=white)
![License](https://img.shields.io/github/license/push-in/pam-http-psr?style=flat-square)

**[Documentation](https://push-in.github.io/pam-docs/packages/http/) · [Why this exists](#why-this-exists) · [What you can build](#what-you-can-build) · [Quick start](#quick-start) · [Issues](https://github.com/push-in/pam-http-psr/issues)**

</div>

---

## Why this exists

Translate between PAM-native requests and the PHP-FIG interfaces at an explicit interoperability boundary.

| | |
| --- | --- |
| **Role** | HTTP interoperability adapter |
| **Execution path** | PHP-FIG PSR interfaces · PAM HTTP |
| **This repository owns** | Request, response, middleware, and factory adaptation |
| **Boundary** | Not a server or router; conversion has a measurable boundary cost |

## What you can build

- Running PSR-15 middleware in a PAM application
- Adapting libraries that require PSR-7 values
- Migrating existing PSR-based HTTP code incrementally

## Quick start

```bash
pam composer require pushinbr/pam-http-psr
```

The **[PAM documentation](https://push-in.github.io/pam-docs/packages/http/)** covers prerequisites, production setup, and the complete workflow. PAM projects keep normal manifests and lockfiles; product features stay in the package that owns them.
<!-- pam:product-page:end -->

PSR-7, PSR-15 and PSR-17 interoperability for Pam using the official PHP-FIG
interfaces.

## License

Free and open-source under the [Apache License 2.0](LICENSE). You may use,
modify, and distribute this package for any purpose, including commercially.
