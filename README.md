

# 🐟 DryFishLicense

[![License: Dryfish v1.1.1](https://img.shields.io/badge/License-Dryfish--1.1.1-blue.svg)](https://github.com/dryfish09/DryFishLicense)
[![GitHub stars](https://img.shields.io/github/stars/dryfish09/DryFishLicense)](https://github.com/dryfish09/DryFishLicense/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/dryfish09/DryFishLicense)](https://github.com/dryfish09/DryFishLicense/network)

**Brand Protection Meets Open Source Freedom**

---

## 📖 What is DryFishLicense?

The **DryFishLicense** is a permissive open-source license that bridges the gap between:

- **MIT/BSD**: Freedom to use, modify, and distribute
- **Apache-2.0**: Patent protection and brand protection
- **Unique**: Mandatory renaming of standalone forks to protect the original author's brand identity

### Key Features

- ✅ **Freedom to use, modify, and distribute** - For any purpose, commercial or non-commercial
- ✅ **Proprietary integration** - Use in closed-source projects without disclosing source code
- ✅ **Commercial redistribution** - Sell and distribute the Software freely
- ✅ **Patent Grant** - Contributors grant patent licenses (like Apache-2.0)
- ✅ **Brand protection** - Mandatory renaming of standalone forks
- ✅ **Practical exceptions** - No renaming for libraries, internal use, or unmodified copies
- ✅ **License versioning** - SPDX identifier `Dryfish-1.1.1`

---

## 🆕 What's New in v1.1.1?

| Feature | v1.0 | v1.1 | **v1.1.1** |
|---------|------|------|------------|
| MIT-style permissions | ✅ | ✅ | ✅ |
| Attribution required | ✅ | ✅ | ✅ |
| Mandatory renaming | ✅ | ✅ | ✅ |
| Library exception | ❌ | ✅ | ✅ |
| Internal use exception | ❌ | ❌ | ✅ |
| Unmodified distribution exception | ❌ | ❌ | ✅ |
| Patent Grant | ❌ | ❌ | ✅ |
| License Versioning | ❌ | ❌ | ✅ |
| SPDX Identifier | ❌ | ❌ | ✅ |
| "PROJECT NAME" definition | ❌ | ❌ | ✅ |
| Violation/Compliance examples | ❌ | ❌ | ✅ |

---

## 📋 When Do You Need to Rename?

### ✅ You MUST Rename When:

You create a **STANDALONE FORKED PROJECT** distributed as a separate product.

**What MUST be renamed:**

| Category | Example (Original → Compliant) | Example (Original → Violation) |
|----------|-------------------------------|-------------------------------|
| Repository name | `DryFishLib` → `WetFishLib` ✓ | `DryFishLib` → `DRYFISH` ✗ |
| Package/Namespace | `com.dryfish.core` → `com.wetfish.core` ✓ | `com.dryfish.core` → `com.dryfish.core2` ✗ |
| Binary/Executable | `dryfish-cli` → `wetfish-cli` ✓ | `dryfish-cli` → `DRYFISH-CLI` ✗ |
| Display name | `DryFish Library` → `WetFish Library` ✓ | `DryFish Library` → `DryFish-Library` ✗ |
| Logo/Branding | Visually distinct ✓ | Only color change ✗ |
| Marketing terms | Must be different | Must be different |
| Domain/URLs | Must be different | Must be different |
| Social media | Must be different | Must be different |

### ❌ Examples of VIOLATION

| Original | Modified (Violation) | Why? |
|----------|---------------------|------|
| `DryFishLib` | `dryfishlib` | Only case change |
| `DryFishLib` | `DRYFISHLIB` | Only case change |
| `DryFishLib` | `Dry-Fish-Lib` | Only punctuation added |
| `DryFishLib` | `DryFishLib2` | Only number added |
| `DryFishLib` | `DFL` | Abbreviation of original |
| `DryFishLib` | `SuperDryFishLib` | Prefix doesn't change core identity |

### ✅ Examples of COMPLIANCE

| Original | Modified (Compliant) | Why? |
|----------|---------------------|------|
| `DryFishLib` | `WetFishLib` | Different root word |
| `DryFishLib` | `SuperLogger` | Completely different name |
| `DryFishLib` | `BlueOcean` | Different branding concept |

---

## 🛡️ Three Exceptions - When You DON'T Need to Rename

### Exception 1: Library/Dependency Usage

```kotlin
// build.gradle.kts
dependencies {
    implementation("com.dryfish09:superlib:1.0.0")
}
```

```java
// Your code - package name stays the same
import com.dryfish09.superlib.SuperClass;  // ✅ No renaming needed
```

**Result:** ✅ NO renaming needed. Just use it as a dependency.

---

### Exception 2: Internal Use Only

```bash
git clone https://github.com/dryfish09/superlib.git
cd superlib
# Fix a bug for internal company tool
# Add custom features for internal use
# Use within your organization only - NEVER distributed outside
```

**Result:** ✅ NO renaming needed. Internal use is exempt.

---

### Exception 3: Unmodified Distribution

```bash
# Download and distribute verbatim copies
wget https://github.com/dryfish09/superlib/releases/v1.0.0/superlib.jar
# Distribute superlib.jar as-is
```

**Result:** ✅ NO renaming needed. Keep all notices intact.

---

## 🔒 Patent Grant

Unlike MIT, DryFishLicense includes a **Patent Grant** (similar to Apache-2.0):

- ✅ Each contributor grants you a patent license for their contributions
- ✅ Worldwide, royalty-free, irrevocable
- ✅ Covers making, using, selling, importing the Software
- ✅ Applies to patent claims necessarily infringed by the contribution(s)
- ⚠️ Patent litigation against the Software terminates your rights

This protects you from patent lawsuits related to the Software.

---

## 📊 Comparison with Other Licenses

| Feature | MIT | GPL-3.0 | Apache-2.0 | **DryFish** |
|---------|-----|---------|------------|-------------|
| Commercial use | ✅ | ✅ | ✅ | ✅ |
| Proprietary integration | ✅ | ❌ | ✅ | ✅ |
| Attribution required | ⚠️ | ✅ | ✅ | ✅ |
| Source disclosure required | ❌ | ✅ | ❌ | ❌ |
| Mandatory renaming (standalone) | ❌ | ❌ | ❌ | ✅ |
| Mandatory renaming (library) | ❌ | ❌ | ❌ | ❌ |
| Internal use renaming | ❌ | ❌ | ❌ | ❌ |
| Brand protection | ❌ | ❌ | ✅ (trademark) | ✅ (renaming) |
| Patent grant | ❌ | ✅ | ✅ | ✅ |
| SPDX identifier | ✅ | ✅ | ✅ | ✅ |

### Compatibility

| License | Compatible? | Notes |
|---------|-------------|-------|
| MIT | ✅ Yes | Both permissive |
| BSD | ✅ Yes | Both permissive |
| Apache-2.0 | ✅ Yes | Both permissive |
| GPL-2.0 | ❌ No | Conflict with proprietary allowance |
| GPL-3.0 | ❌ No | Conflict with proprietary allowance |
| AGPL-3.0 | ❌ No | Conflict with proprietary allowance |

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/dryfish09/DryFishLicense.git
cd DryFishLicense
```

### 2. Use in Your Project

Copy the license file to your project:

```bash
cp licenses/Dryfish-1.1.1.txt /path/to/your/project/LICENSE
```

### 3. Update Your Project's README

```markdown
## License

This project is licensed under the [Dryfish License v1.1.1](https://github.com/dryfish09/DryFishLicense).
```

### 4. Add SPDX-License-Identifier (Recommended)

In your source files:

```c
/* SPDX-License-Identifier: Dryfish-1.1.1 */
```

```python
# SPDX-License-Identifier: Dryfish-1.1.1
```

```javascript
// SPDX-License-Identifier: Dryfish-1.1.1
```

---

## 📁 Repository Structure

```
DryFishLicense/
├── README.md                          # This file
├── LICENSE                            # Full license text
├── CONTRIBUTING.md                    # Contribution guidelines
├── CHANGELOG.md                       # Version history
├── licenses/
│   ├── Dryfish-1.1.1.txt             # Full license
│   └── Dryfish-1.1.1-short.txt       # Short summary (for embedding)
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── license-request.md
└── website/
    └── index.html                     # Landing page (GitHub Pages)
```

---

## 📝 License Summary (Short Version)

```text
DRYFISH LICENSE v1.1.1 (Short Summary)

Copyright (c) [YEAR] [AUTHOR NAME]
SPDX-License-Identifier: Dryfish-1.1.1

✅ GRANT OF RIGHTS:
- Use, modify, distribute freely
- Commercial use allowed
- Proprietary integration allowed

✅ ATTRIBUTION REQUIRED:
- Must retain copyright notice and permission notice

✅ PATENT GRANT:
- Contributors grant patent license for their contributions
- Terminates if you sue for patent infringement

✅ STANDALONE FORK - MUST rename:
- Repository name, package, binary, display name, logo, branding
- Domains, URLs, social media handles
- ❌ Violations: only case change, punctuation, numbers, abbreviations
- ✅ Compliant: different root word, completely different name

✅ EXCEPTIONS - NO renaming required:
- Using as a library/dependency
- Internal use only (within your organization)
- Unmodified distribution (verbatim copies)

✅ LICENSE VERSIONING:
- SPDX: Dryfish-1.1.1
- May use any version, no forced upgrade

⚠️ NO WARRANTY - Use at your own risk

Full license: https://github.com/dryfish09/DryFishLicense
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- 🐛 Report bugs or issues in the license text
- 💡 Suggest improvements or clarifications
- 🌍 Translate the license into other languages (Vietnamese, Chinese, Japanese, etc.)
- 📝 Improve documentation and examples
- ⭐ Star the repository to show support
- 📣 Spread the word about DryFishLicense

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 🗺️ Roadmap

- [x] v1.0 - Initial release by dryfish09
- [x] v1.1 - Added library exception clause
- [x] v1.1.1 - Expanded "PROJECT NAME" definition; added Patent Grant, Internal Use Exception, Unmodified Distribution Exception, License Versioning
- [ ] v1.2 - International translations (Vietnamese, Chinese, etc.)
- [ ] v1.3 - OSI (Open Source Initiative) submission
- [ ] v2.0 - SPDX official registration

---

## 📜 Version History

| Version | Date | Changes |
|---------|------|---------|
| **v1.1.1** | June 2026 | ✅ Patent Grant added; Internal Use Exception; Unmodified Distribution Exception; License Versioning; Expanded PROJECT NAME definition; SPDX identifier |
| **v1.1** | June 2026 | ✅ Library Exception Clause added |
| **v1.0** | June 2026 | Initial release by dryfish09 |

Full changelog: [CHANGELOG.md](CHANGELOG.md)

---

## 📄 Full License Text

The full license text is available in:

- [LICENSE](LICENSE) - Root directory
---

## ⚖️ Legal Disclaimer

This license is provided **"as is"** without any warranty. While we have made every effort to ensure it is legally sound, you should consult with a qualified attorney if you have specific legal concerns.

**This is not legal advice.**

---

## 📚 Additional Resources

- [Open Source Initiative (OSI)](https://opensource.org/)
- [SPDX License List](https://spdx.org/licenses/)
- [Choose a License](https://choosealicense.com/)
- [Understanding Open Source Licenses](https://opensource.guide/legal/)

---

## 🌟 Spread the Word

- ⭐ Star this repository on GitHub
- 🐟 Use DryFishLicense in your projects
- 📣 Share with developers who need brand protection
- 🔗 Link to: `https://github.com/dryfish09/DryFishLicense`
- 📝 Write blog posts about your experience

---

## 💬 Questions?

- Open an [issue](https://github.com/dryfish09/DryFishLicense/issues)
- Start a [discussion](https://github.com/dryfish09/DryFishLicense/discussions)
- Contact the author: [@dryfish09](https://github.com/dryfish09)

---

## 🙏 Acknowledgments

- The open source community for inspiration
- Contributors who help improve this license
- Everyone who uses DryFishLicense in their projects

---

**DryFishLicense** - Because open source shouldn't mean losing your brand identity. 🐟

---

*Made with ❤️ by [dryfish09](https://github.com/dryfish09) and the Dryfish community*

---

## 🏷️ Badges (Copy these for your project)

If you use DryFishLicense in your project, add these badges:

### Markdown

```markdown
[![License: Dryfish v1.1.1](https://img.shields.io/badge/License-Dryfish--1.1.1-blue.svg)](https://github.com/dryfish09/DryFishLicense)
```

### HTML

```html
<a href="https://github.com/dryfish09/DryFishLicense">
    <img src="https://img.shields.io/badge/License-Dryfish--1.1.1-blue.svg" alt="License: Dryfish v1.1.1">
</a>
```

### RST (reStructuredText)

```rst
.. image:: https://img.shields.io/badge/License-Dryfish--1.1.1-blue.svg
    :target: https://github.com/dryfish09/DryFishLicense
    :alt: License: Dryfish v1.1.1
```

---

## 🔗 Quick Links

- [View License](LICENSE)
- [Short Summary](licenses/Dryfish-1.1.1-short.txt)
- [Changelog](CHANGELOG.md)
- [Contributing](CONTRIBUTING.md)
- [Issues](https://github.com/dryfish09/DryFishLicense/issues)
- [Discussions](https://github.com/dryfish09/DryFishLicense/discussions)

---

**DryFishLicense v1.1.1** - June 2026


