# 🐟 DryFishLicense

[![License: Dryfish v1.1.2](https://img.shields.io/badge/License-Dryfish--1.1.2-blue.svg)](https://github.com/dryfish09/DryFishLicense)
[![GitHub stars](https://img.shields.io/github/stars/dryfish09/DryFishLicense)](https://github.com/dryfish09/DryFishLicense/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/dryfish09/DryFishLicense)](https://github.com/dryfish09/DryFishLicense/network)

**Brand Protection Meets Open Source Freedom**

---

## 📖 What is DryFishLicense?

The **DryFishLicense** is a permissive open-source license that bridges the gap between:

- **MIT/BSD**: Freedom to use, modify, and distribute
- **Apache-2.0**: Patent protection
- **Unique**: Mandatory renaming of standalone forks to protect the original author's brand identity

### Key Features

- ✅ **Freedom to use, modify, and distribute** - For any purpose, commercial or non-commercial
- ✅ **Proprietary integration** - Use in closed-source projects without disclosing source code
- ✅ **Commercial redistribution** - Sell and distribute the Software freely
- ✅ **Patent Grant** - Contributors grant patent licenses (like Apache-2.0)
- ✅ **Brand protection** - Mandatory renaming of standalone forks
- ✅ **Practical exceptions** - No renaming for libraries, internal use, or unmodified copies
- ✅ **License versioning** - SPDX identifier `Dryfish-1.1.2`

---

## 🆕 What's New in v1.1.2?

| Feature | v1.0 | v1.1 | v1.1.1 | **v1.1.2** |
|---------|------|------|--------|------------|
| MIT-style permissions | ✅ | ✅ | ✅ | ✅ |
| Attribution required | ✅ | ✅ | ✅ | ✅ |
| Mandatory renaming | ✅ | ✅ | ✅ | ✅ |
| Library exception | ❌ | ✅ | ✅ | ✅ |
| Internal use exception | ❌ | ❌ | ✅ | ✅ |
| Unmodified distribution exception | ❌ | ❌ | ✅ | ✅ |
| Patent Grant | ❌ | ❌ | ✅ | ✅ |
| License Versioning | ❌ | ❌ | ✅ | ✅ |
| SPDX Identifier | ❌ | ❌ | ✅ | ✅ |
| "PROJECT NAME" definition | ❌ | ❌ | ✅ | ✅ |
| Violation/Compliance examples | ❌ | ❌ | ✅ | ❌ (removed - simplified) |
| Streamlined renaming section | ❌ | ❌ | ❌ | ✅ |
| Simplified Important Reminders | ❌ | ❌ | ❌ | ✅ |

### What Changed in v1.1.2?

**Simplified Section III (Project Renaming Obligation):**
- Reduced from 8 items to 3 key items (Repository, Binary/Executable, Logo)
- Removed overly detailed violation/compliance examples
- Cleaner, more readable, easier to understand

**Clarified Important Reminders:**
- Fixed confusing wording in reminder #1
- Now clearly states: "If you are using this software as a library dependency within your project, you do NOT need to rename anything. The renaming requirement only applies if you distribute the library itself as a standalone product."

---

## 📋 When Do You Need to Rename?

### ✅ You MUST Rename When:

You create a **STANDALONE FORKED PROJECT** distributed as a separate product.

**What MUST be renamed:**

| Category | Example (Original → Compliant) | Example (Original → Violation) |
|----------|-------------------------------|-------------------------------|
| Repository name | `DryFishLib` → `WetFishLib` ✓ | `DryFishLib` → `DRYFISH` ✗ |
| Binary/Executable | `dryfish-cli` → `wetfish-cli` ✓ | `dryfish-cli` → `DRYFISH-CLI` ✗ |
| Logo/Branding | Visually distinct ✓ | Only color change ✗ |

**"Clearly different" means:**
- Different root words (e.g., "Fish" → "Shark")
- Distinct visual identity
- NOT just changing case, punctuation, spacing, or adding numbers/suffixes

---

## 🔓 When You Do NOT Need to Rename

| Scenario | Renaming Required? |
|----------|-------------------|
| Using as a library within your project | ❌ No |
| Modifying for internal use only | ❌ No |
| Distributing unmodified copies | ❌ No |
| Forking and distributing modified standalone project | ✅ Yes |

---

## 📄 Full License Text

The complete license text is available in [LICENSE](LICENSE) file.

SPDX-License-Identifier: Dryfish-1.1.2

---

## 🚀 Why DryFishLicense?

### The Problem
Traditional permissive licenses (MIT, BSD) allow anyone to fork your project, modify it, and redistribute it under the same or different name - potentially confusing users and damaging your brand.

### The Solution
DryFishLicense solves this by requiring standalone forks to use a clearly different name, while still allowing:
- Libraries to be used without renaming
- Internal modifications without renaming
- Unmodified redistribution without renaming

---

## 🆚 Comparison with Other Licenses

| Feature | MIT | BSD | Apache-2.0 | GPL | **DryFish** |
|---------|-----|-----|------------|-----|-------------|
| Commercial use | ✅ | ✅ | ✅ | ✅ | ✅ |
| Proprietary use | ✅ | ✅ | ✅ | ❌ | ✅ |
| Patent grant | ❌ | ❌ | ✅ | ❌ | ✅ |
| Brand protection | ❌ | ❌ | ✅ | ❌ | ✅ |
| Standalone fork renaming | ❌ | ❌ | ❌ | ❌ | ✅ |
| Library exception | N/A | N/A | N/A | N/A | ✅ |
| Internal use exception | N/A | N/A | N/A | N/A | ✅ |
| Copyleft | ❌ | ❌ | ❌ | ✅ | ❌ |

---

## 📝 How to Use

### For Software Authors

1. Copy the [LICENSE](LICENSE) file to your project
2. Replace `[YEAR]` with the current year
3. Replace `[AUTHOR NAME]` with your name or organization
4. Add SPDX identifier to your files: `SPDX-License-Identifier: Dryfish-1.1.2`

### For Users

- Read the full license text
- Follow the attribution requirement (Section II)
- Rename if you create a standalone forked project (Section III)
- Contact the original author if unsure

---

## ❓ FAQ

**Q: Do I need to rename if I use DryFish-licensed code as a library?**

A: No. Internal package names, class names, and namespaces can remain unchanged. Only the distribution name must be renamed if you distribute the library itself as a standalone product.

**Q: Do I need to rename if I modify the code for internal use?**

A: No. Internal modifications within your organization do not require renaming.

**Q: Do I need to rename if I distribute unmodified copies?**

A: No. You can distribute verbatim copies without renaming.

**Q: What exactly must be renamed?**

A: Repository name, binary/executable name, and logo/visual branding must be clearly different.

**Q: What if I'm unsure whether my use case requires renaming?**

A: Contact the original author for clarification.

---

## 📞 Contact

- **Issues**: [GitHub Issues](https://github.com/dryfish09/DryFishLicense/issues)
- **Discussions**: [GitHub Discussions](https://github.com/dryfish09/DryFishLicense/discussions)

---

## 📜 License

This repository (the license text itself) is under DryFish License

---

**Made with ❤️ by [dryfish09](https://github.com/dryfish09)**

---

*"Dryfish" is the name of this license, not the name of the software.*
