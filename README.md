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
- ✅ **Concise and readable** - Clear, short, and easy to understand

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
| Concise renaming section | ❌ | ❌ | ❌ | ✅ |
| Removed GPL compatibility section | ❌ | ❌ | ❌ | ✅ |
| Clearer reminders | ❌ | ❌ | ❌ | ✅ |

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

### ❌ You Do NOT Need to Rename When:

| Scenario | Example |
|----------|---------|
| **Library/Dependency usage** | Using `DryFishLib` as a dependency in your app. No renaming needed. |
| **Internal use** | Modifying the software for internal tools. No renaming needed. |
| **Unmodified distribution** | Distributing verbatim copies. No renaming needed. |

---

## 🚀 Quick Start

### For Users (Using the Software)

Simply use, modify, and distribute the Software as you wish. Just remember:

1. **Keep the copyright notice** (Section II)
2. **Rename if you create a standalone fork** (Section III)
3. **That's it!**

### For Contributors

When contributing to a project under DryFishLicense:

1. Your contributions are covered by the Patent Grant (Section IV)
2. You grant patent licenses to all users automatically
3. You retain copyright of your contributions

### For Project Maintainers

If you adopt DryFishLicense for your project:

1. Copy the full license text to your `LICENSE` file
2. Replace `[YEAR]` and `[AUTHOR NAME]`
3. Specify the version: `Dryfish-1.1.2`

---

## 📚 Comparison with Other Licenses

| Feature | MIT | BSD | Apache-2.0 | GPL-3.0 | **DryFish** |
|---------|-----|-----|------------|---------|-------------|
| Commercial use | ✅ | ✅ | ✅ | ✅ | ✅ |
| Modify source | ✅ | ✅ | ✅ | ✅ | ✅ |
| Distribute | ✅ | ✅ | ✅ | ✅ | ✅ |
| Sublicense | ✅ | ✅ | ✅ | ❌ | ✅ |
| Private use | ✅ | ✅ | ✅ | ✅ | ✅ |
| Patent protection | ❌ | ❌ | ✅ | ✅ | ✅ |
| Brand protection | ❌ | ❌ | ❌ | ❌ | ✅ |
| Source disclosure | ❌ | ❌ | ❌ | ✅ | ❌ |

---

## 💡 Philosophy

The DryFishLicense was created to solve a common problem in open source:

> "I want to share my code freely, but I don't want others to create confusing forks that damage my brand."

**The solution is simple:**
- Use it freely as a library → no renaming needed
- Fork it internally → no renaming needed
- Distribute it unchanged → no renaming needed
- **Only when you create a standalone forked product** → rename it

This protects both the original author's reputation and the user's freedom.

---

## 📄 License Versions

| Version | Release Date | Changes |
|---------|--------------|---------|
| v1.0 | [Date] | Initial release |
| v1.1 | [Date] | Added library exception |
| v1.1.1 | June 2026 | Added internal use & unmodified distribution exceptions, Patent Grant, SPDX, examples |
| **v1.1.2** | **June 2026** | **Concise renaming section, removed GPL compatibility section, clearer reminders** |

---

## 🤝 Contributing

We welcome contributions to improve this license! Please:

1. Fork the repository
2. Make your changes
3. Submit a pull request

### Suggested Improvements

- Clarify edge cases
- Add more real-world examples
- Translate to other languages

---

## ⚖️ Disclaimer

This license is provided "as is" without warranty of any kind. The authors and copyright holders are not liable for any claims, damages, or other liabilities arising from the use of this license.

**This is not legal advice.** Consult a lawyer for legal advice regarding licensing.

---

## 🌟 Support

If you find this license useful, please:

- ⭐ Star the repository
- 🍴 Fork the repository
- 📣 Share with others
- ✍️ Use it in your projects

---

**DryFishLicense** - *Brand Protection Meets Open Source Freedom*
