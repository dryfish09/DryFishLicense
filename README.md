
# 🐟 Dryfish License

[![License: Dryfish v1.1](https://img.shields.io/badge/License-Dryfish--1.1-blue.svg)](https://github.com/dryfish09/DryFishLicense)


**Brand Protection Meets Open Source Freedom**

---

## 📖 What is Dryfish License?

The **Dryfish License** is a permissive open-source license that:

- ✅ Grants you full freedom to use, modify, and distribute software
- ✅ Allows integration into proprietary (closed-source) projects
- ✅ Permits commercial use and redistribution
- ✅ Protects the original author's brand through mandatory renaming of standalone forks
- ✅ Does NOT require renaming when using as a library/dependency

It sits between the permissiveness of MIT and the brand protection of Apache, but with a unique approach: **rename the project, not the package.**

---

## 🆕 What's New in v1.1?

| Issue in v1.0 | Fixed in v1.1 |
|---------------|---------------|
| Required renaming of package names (e.g., `com.example.lib`) when using as a library | ✅ **NO** renaming required for libraries/dependencies |
| Required renaming of internal class/namespace names | ✅ Internal names can stay the same |
| Unclear whether modified libraries need renaming | ✅ Clearly stated: modifications for internal use need NO renaming |

**In short:** v1.1 is **practical**. You only rename when creating a **standalone forked project**, not when using or modifying a library.

---

## 📋 When Do You Need to Rename?

| Scenario | Rename Required? | Details |
|----------|------------------|---------|
| 📦 Using as a dependency (e.g., `import com.example.lib`) | ❌ **NO** | Just use it. No changes needed. |
| 🔧 Modifying a library and using it in your project | ❌ **NO** | Document your changes in README, but no renaming required. |
| 🚀 Forking and building a standalone application | ✅ **YES** | Rename the project, directory, and executable. Package names can stay. |
| 📚 Forking and distributing as a separate library | ✅ **YES** | Rename the project and groupId (if publishing). Package names can stay. |

---

## 💡 Examples

### ✅ OK: Using as a Library

```kotlin
// build.gradle.kts
dependencies {
    implementation("com.tentacgiacu:superlib:1.0.0")
}
```

```java
// Your code
import com.tentacgiacu.superlib.SuperClass;  // ✅ No renaming needed
```

**Result:** You're compliant. No changes required.

---

### ✅ OK: Modifying a Library for Internal Use

```bash
git clone https://github.com/tentacgiacu/superlib
cd superlib
# Fix a bug, add a feature
./gradlew build
# Use the modified JAR in your project
```

**Result:** No renaming needed. Just add a note in your project's README:  
> *"Includes a modified version of SuperLib (original by tentacgiacu) with additional fixes."*

---

### ❌ NOT OK: Forking a Standalone App Without Renaming

```bash
git clone https://github.com/tentacgiacu/super-app
# Build and distribute as "Super-App" (same name)
```

**Result:** ❌ **Violation!** You MUST rename the standalone project.

---

### ✅ OK: Forking a Standalone App With Renaming

```bash
git clone https://github.com/tentacgiacu/super-app
mv super-app my-awesome-app
cd my-awesome-app
# Build and distribute as "MyAwesomeApp"
```

**Result:** ✅ **Compliant!** You renamed the project.  
Package names (e.g., `com.tentacgiacu.superapp.core`) may remain unchanged.

---

### ✅ OK: Forking and Distributing as a Separate Library

```bash
git clone https://github.com/tentacgiacu/superlib
mv superlib megalib
cd megalib
# Add new features
./gradlew build
# Publish to Maven Central as com.megacorp:megalib:2.0.0
```

**Result:** ✅ **Compliant!**  
- Project renamed: `superlib` → `megalib`  
- groupId changed: `com.tentacgiacu` → `com.megacorp`  
- Package names (e.g., `com.tentacgiacu.superlib.core`) may stay unchanged ✅

---

## 📊 Comparison with Other Licenses

| Feature | MIT | GPL-3.0 | Apache-2.0 | **Dryfish** |
|---------|-----|---------|------------|-------------|
| Commercial use | ✅ | ✅ | ✅ | ✅ |
| Proprietary integration | ✅ | ❌ | ✅ | ✅ |
| Attribution required | ⚠️ | ✅ | ✅ | ✅ |
| Source disclosure required | ❌ | ✅ | ❌ | ❌ |
| Mandatory renaming (standalone) | ❌ | ❌ | ❌ | ✅ |
| Mandatory renaming (library) | ❌ | ❌ | ❌ | ❌ |
| Brand protection | ❌ | ❌ | ✅ (trademark) | ✅ (renaming) |
| Patent grant | ❌ | ✅ | ✅ | ❌ |

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
cp LICENSE <ur/path>
```

### 3. Update Your Project's README

```markdown
## License

This project is licensed under the [Dryfish License v1.1](https://github.com/yourname/dryfish-license).
```

### 4. Add SPDX-License-Identifier (Optional)

In your source files:

```c
/* SPDX-License-Identifier: Dryfish-1.1 */
```

---



## 📝 License Summary (Short Version)

```text
DRYFISH LICENSE v1.1 (Short Summary)

✅ You may use, modify, and distribute this software freely
✅ Commercial use and proprietary integration are allowed
✅ You MUST give credit to the original author
✅ You MUST rename ONLY if creating a standalone forked project
✅ NO renaming required when using as a library/dependency
⚠️ NO WARRANTY - Use at your own risk

Full license: https://github.com/dryfish09/DryFishLicense
```

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- 🐛 Report bugs or issues
- 💡 Suggest improvements or clarifications
- 🌍 Translate the license into other languages
- 📢 Spread the word about Dryfish License


---

## 🗺️ Roadmap

- [x] v1.0 - Initial release
- [x] v1.1 - Fixed library/dependency issue
- [ ] v1.2 - International translations (Vietnamese, Chinese, etc.)
- [ ] v1.3 - OSI (Open Source Initiative) submission
- [ ] v2.0 - SPDX official registration

---

## 📜 Version History

| Version | Date | Changes |
|---------|------|---------|
| **v1.1** | June 2026 | ✅ Fixed library/dependency issue; no renaming required for packages |
| **v1.0** | June 2026 | Initial release |

---

## ⚖️ Legal Disclaimer

This license is provided "as is" without any warranty. While we have made every effort to ensure it is legally sound, you should consult with a qualified attorney if you have specific legal concerns.

**This is not legal advice.**

---

## 🌟 Spread the Word

- ⭐ Star this repository on GitHub
- 🐟 Use Dryfish License in your projects
- 📣 Share with developers who need brand protection
- 🔗 Link to: `https://github.com/dryfish09/DryFishLicense`

---

## 📄 Full License Text

The full license text is available in [LICENSE](LICENSE)

---

## 💬 Questions?

Open an [issue](https://github.com/dryfish09/DryFishLicense/issues) or start a [discussion](https://github.com/dryfish09/DryFishLicense/discussions).

---

**Dryfish License** - Because open source shouldn't mean losing your brand identity. 🐟

---

*Made with ❤️ by the Dryfish community*
