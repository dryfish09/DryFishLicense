
# 🤝 Contributing to DryFishLicense

First off, thank you for considering contributing to DryFishLicense! 🐟

Your help is essential for making this license better, clearer, and more widely adopted. Whether you're reporting a bug, suggesting improvements, or translating the license, every contribution matters.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Reporting Issues](#reporting-issues)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Pull Requests](#pull-requests)
- [Translation Guidelines](#translation-guidelines)
- [Style Guide](#style-guide)
- [License](#license)
- [Questions?](#questions)

---

## 📜 Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct:

- **Be respectful** - Treat everyone with kindness and respect
- **Be constructive** - Provide helpful, actionable feedback
- **Be inclusive** - Welcome diverse perspectives and backgrounds
- **Be patient** - Not everyone speaks the same language or has the same experience level
- **No harassment** - Harassment, discrimination, or toxic behavior will not be tolerated

Violations of the Code of Conduct may result in being blocked from the repository.

---

## 🎯 How Can I Contribute?

### 1. 🐛 Report Bugs

Found a bug in the license text? Something unclear or contradictory?

- Check if the issue already exists in [Issues](https://github.com/dryfish09/DryFishLicense/issues)
- If not, create a new issue with the **Bug Report** template
- Clearly describe the problem and suggest a fix if possible

### 2. 💡 Suggest Enhancements

Have an idea to improve DryFishLicense?

- Check if your suggestion already exists in [Issues](https://github.com/dryfish09/DryFishLicense/issues)
- If not, create a new issue with the **Enhancement Request** template
- Explain the improvement and why it's needed
- Provide examples if applicable

### 3. 🌍 Translate the License

Help make DryFishLicense accessible to more developers!

- Translate the full license text
- Translate the README.md
- Translate the short summary
- Translate the CONTRIBUTING.md

See [Translation Guidelines](#translation-guidelines) below.

### 4. 📝 Improve Documentation

- Fix typos or grammatical errors
- Clarify confusing sections
- Add more examples
- Improve formatting

### 5. ⭐ Spread the Word

- Star the repository
- Share DryFishLicense on social media
- Write blog posts about it
- Use it in your projects
- Tell other developers about it

### 6. 🧪 Legal Review

If you're a lawyer or legal expert:

- Review the license for legal soundness
- Suggest improvements to make it more enforceable
- Help with OSI (Open Source Initiative) submission

---

## 📝 Reporting Issues

### Before Submitting an Issue

1. **Search** existing issues to avoid duplicates
2. **Check** the latest version to see if the issue is already fixed
3. **Read** the [README.md](README.md) to ensure it's not already addressed

### Bug Report Template

```markdown
**Describe the bug**
A clear and concise description of what the bug is.

**Section affected**
Which section of the license has the issue? (e.g., Section III)

**Current text**
What does the license currently say?

**Suggested fix**
What should it say instead?

**Why is this a bug?**
Explain why the current text is problematic.

**Additional context**
Any other information that might help.
```

### Enhancement Request Template

```markdown
**Describe the enhancement**
A clear and concise description of what you want to add or change.

**Why is this needed?**
Explain the problem this solves or the benefit it provides.

**Suggested implementation**
How should this be implemented? Provide specific wording if possible.

**Examples**
Show examples of how this would work in practice.

**Additional context**
Any other information that might help.
```

---

## 🔧 Pull Requests

### Before Submitting a PR

1. **Fork** the repository
2. **Clone** your fork:
   ```bash
   git clone https://github.com/your-username/DryFishLicense.git
   cd DryFishLicense
   ```
3. **Create a branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** and commit them:
   ```bash
   git add .
   git commit -m "Brief description of your changes"
   ```
5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Open a Pull Request** against the main repository

### PR Guidelines

- **One change per PR** - Keep it focused and easy to review
- **Update the CHANGELOG.md** - Add your change to the appropriate version
- **Update the README.md** - If your change affects documentation
- **Update the short summary** - If your change affects the full license
- **Be clear** - Explain what you changed and why
- **Be patient** - PRs may take time to review

### PR Template

```markdown
**Description**
What does this PR do?

**Related Issue**
Link to the issue this PR addresses (if any).

**Type of Change**
- [ ] Bug fix (non-breaking change)
- [ ] Enhancement (non-breaking change)
- [ ] Breaking change (may affect existing users)
- [ ] Documentation update
- [ ] Translation

**Checklist**
- [ ] I have read the [CONTRIBUTING.md](CONTRIBUTING.md)
- [ ] I have updated the CHANGELOG.md
- [ ] I have updated the README.md (if needed)
- [ ] I have updated the short summary (if needed)
- [ ] I have tested my changes (if applicable)

**Additional Context**
Any other information that might help.
```

---

## 🌍 Translation Guidelines

### What Needs Translation?

1. **Full License Text** (`licenses/Dryfish-1.1.1.txt`)
2. **Short Summary** (`licenses/Dryfish-1.1.1-short.txt`)
3. **README.md**
4. **CONTRIBUTING.md** (this file)
5. **CHANGELOG.md**

### Translation Process

1. **Create a new branch**:
   ```bash
   git checkout -b translation/[language-code]
   ```

2. **Create a new folder** for your translation:
   ```bash
   mkdir translations/[language-code]
   ```

3. **Translate the files** and place them in the folder:
   ```
   translations/
   ├── vi/                           # Vietnamese
   │   ├── Dryfish-1.1.1.txt
   │   ├── Dryfish-1.1.1-short.txt
   │   ├── README.md
   │   ├── CONTRIBUTING.md
   │   └── CHANGELOG.md
   ├── zh/                           # Chinese
   │   └── ...
   ├── ja/                           # Japanese
   │   └── ...
   └── [language-code]/              # Your language
       └── ...
   ```

4. **Add a note in README.md**:
   ```markdown
   ## 🌍 Translations

   - [Vietnamese](translations/vi/README.md)
   - [Chinese](translations/zh/README.md)
   ```

### Translation Guidelines

- **Be accurate** - Translate the legal meaning, not just words
- **Be clear** - Use simple, unambiguous language
- **Be consistent** - Use the same terms throughout
- **Preserve formatting** - Keep the same Markdown structure
- **Keep the SPDX Identifier** - Always include it unchanged
- **Keep the version number** - Always include it unchanged
- **Do NOT change the meaning** - The legal intent must remain the same

### Language Codes

| Language | Code | Language | Code |
|----------|------|----------|------|
| Vietnamese | `vi` | Chinese (Simplified) | `zh-CN` |
| Chinese (Traditional) | `zh-TW` | Japanese | `ja` |
| Korean | `ko` | Spanish | `es` |
| French | `fr` | German | `de` |
| Russian | `ru` | Hindi | `hi` |
| Arabic | `ar` | Portuguese | `pt` |

---

## 📐 Style Guide

### License Text Style

- Use **clear, simple English** (or your target language)
- Use **numbered sections** (I, II, III, IV, ...)
- Use **bold text** for important terms
- Use **capital letters** for emphasis (e.g., "MUST", "SHALL", "PROHIBITED")
- Include **examples** to clarify abstract concepts
- Be **explicit** - Don't leave room for interpretation

### README Style

- Start with a **clear title** and badges
- Use **emojis** for visual appeal (🐟, ✅, ❌, ⚠️)
- Use **tables** for comparisons
- Use **code blocks** for examples
- Use **headers** to organize sections
- Include **links** to relevant sections

### Markdown Guidelines

- Use `#` for main headings
- Use `##` for subheadings
- Use `###` for sub-subheadings
- Use `-` for bullet points
- Use `1.` for numbered lists
- Use ` ``` ` for code blocks with language specification
- Use `**bold**` for emphasis
- Use `*italic*` for less emphasis

---

## 📄 License

By contributing to DryFishLicense, you agree that your contributions will be licensed under the [DryFishLicense](LICENSE) itself.

---

## ❓ Questions?

If you have any questions, feel free to:

- Open an [issue](https://github.com/dryfish09/DryFishLicense/issues)
- Start a [discussion](https://github.com/dryfish09/DryFishLicense/discussions)
- Contact the author: [@dryfish09](https://github.com/dryfish09)

---

## 🙏 Thank You!

Every contribution, no matter how small, helps make DryFishLicense better for everyone.

Thank you for being part of this community! 🐟

---

**DryFishLicense** - Because open source shouldn't mean losing your brand identity.

---

*Made with ❤️ by [dryfish09](https://github.com/dryfish09) and the Dryfish community*
```

---

## 📁 File Structure Update

Với `CONTRIBUTING.md` này, cấu trúc thư mục của repository sẽ là:

```
DryFishLicense/
├── README.md                          # Main documentation
├── LICENSE                            # Full license text
├── CONTRIBUTING.md                    # Contribution guidelines (this file)
├── CHANGELOG.md                       # Version history
├── licenses/
│   ├── Dryfish-1.1.1.txt             # Full license
│   └── Dryfish-1.1.1-short.txt       # Short summary
├── translations/                      # Translations folder
│   ├── vi/                           # Vietnamese
│   │   ├── README.md
│   │   ├── Dryfish-1.1.1.txt
│   │   └── Dryfish-1.1.1-short.txt
│   ├── zh/                           # Chinese
│   │   └── ...
│   └── [language-code]/              # Your language
│       └── ...
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug_report.md
│       ├── enhancement_request.md
│       └── license_request.md
└── website/
    └── index.html                     # Landing page (GitHub Pages)
```

---

## 📝 File `.github/ISSUE_TEMPLATE/bug_report.md`

```markdown
---
name: 🐛 Bug Report
about: Report a bug or issue in the license text
title: '[BUG] '
labels: bug
assignees: dryfish09
---

**Describe the bug**
A clear and concise description of what the bug is.

**Section affected**
Which section of the license has the issue? (e.g., Section III)

**Current text**
What does the license currently say?

**Suggested fix**
What should it say instead?

**Why is this a bug?**
Explain why the current text is problematic.

**Additional context**
Any other information that might help.
```

---

## 📝 File `.github/ISSUE_TEMPLATE/enhancement_request.md`

```markdown
---
name: 💡 Enhancement Request
about: Suggest an improvement to the license
title: '[ENHANCEMENT] '
labels: enhancement
assignees: dryfish09
---

**Describe the enhancement**
A clear and concise description of what you want to add or change.

**Why is this needed?**
Explain the problem this solves or the benefit it provides.

**Suggested implementation**
How should this be implemented? Provide specific wording if possible.

**Examples**
Show examples of how this would work in practice.

**Additional context**
Any other information that might help.
```

---

## 📝 File `.github/ISSUE_TEMPLATE/license_request.md`

```markdown
---
name: 📄 License Request
about: Request to use DryFishLicense in your project
title: '[REQUEST] Using DryFishLicense for '
labels: question
assignees: dryfish09
---

**Project name**
What is the name of your project?

**Project description**
Briefly describe what your project does.

**How will you use DryFishLicense?**
- [ ] As a dependency/library
- [ ] As a standalone fork
- [ ] Modified version (internal use)
- [ ] Modified version (distributed)
- [ ] Other (please specify)

**Will you rename the project?**
- [ ] Yes, I will rename the project name
- [ ] No, I'm using it as a library (no renaming needed)
- [ ] No, I'm using it internally (no renaming needed)
- [ ] Not sure, need clarification

**Additional questions**
Any questions about how to comply with the license?
