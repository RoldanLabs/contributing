# 🚀 Contributing to RoldanLabs 🌟

Thank you for your interest in contributing to **RoldanLabs**! 🎉 This is a space for experimentation, learning, and collaboration. Your contributions help us grow as a community and improve the quality of our resources.

## 🔧 How You Can Contribute

Contributions of all kinds are welcome! Here are some ways you can get involved:

### 1. 📝 Improve Documentation

- Add or refine tutorials, guides, and other learning materials.
- Report typos or suggest better explanations for existing content.

### 2. 🧪 Share Experiments and Prototypes

- Submit experimental projects, notebooks, or scripts that align with our purpose.
- Propose new ideas for prototyping or testing technologies.

### 3. 🐛 Report Issues

If you encounter any problems or have suggestions for improvements:

- **Search existing issues** to ensure your feedback hasn’t already been addressed.
- If new, create an issue describing the problem or idea in detail.

### 4. 📬 Submit Pull Requests

We welcome contributions in the form of code, documentation, or resources. Follow these steps:

1. **🍴 Fork the repository**:

```
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

2. **🏁 Create a new branch**:

```
git checkout -b feature/<your-feature-name>
```

3. **🛠️ Implement your changes** and commit them following our [commit message guidelines](#-commit-guidelines):

```
git commit -m "feat(tutorial): Add new SQL basics tutorial"
```

4. **📤 Push your branch** and open a Pull Request:

```
git push origin feature/<your-feature-name>
```

- Include a clear description of the changes.
- Reference related issues if applicable.

## 📝 Commit Guidelines

We use **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)** and **[Gitmoji](https://gitmoji.dev/)** to maintain a consistent commit history:

**🔖 Format:**

```
<type>(scope): <emoji> <short description>

- Extended description (optional).
```

**Examples:**

- `feat(README): ✨ Add introductory README`
- `fix(data-structures): 🐛 Correct binary tree example`

### Common Commit Types:

- **✨ feat**: Introducing new features.
- **🐞 fix**: Fixing bugs.
- **📝 docs**: Documentation updates.
- **🎨 style**: Code style improvements.
- **🔄 refactor**: Code refactoring.
- **🧪 test**: Adding or updating tests.

## 🌱 Git Workflow for RoldanLabs

To keep things simple and encourage experimentation, we follow a lightweight Git workflow:

1. **Main Branch (`main`):**

- Contains the latest stable state of the repository.
- You can base your contributions directly from `main`.

2. **Feature Branches**:

- Create a branch for your changes:
  - `feature/<your-feature-name>`: For new experiments or tutorials.
  - `fix/<your-fix-name>`: For bug fixes or corrections.
  - `docs/<your-doc-name>`: For documentation updates.

```
git checkout -b feature/<your-feature-name>
```

3. **Pull Requests**:

- Submit your branch as a Pull Request to `main`.
- Include a clear description of your changes and reference any related issues.

4. **Optional: Development Branch**:

When working on larger collaborative projects, use the `development` branch to ensure features are tested and integrated before reaching `main`.

```
Git Workflow (With Development Branch):

[feature/<feature-name>] ---> [development] ---> [main]

1. Create `feature` branches from `development`:
  - Example: feature/add-new-tutorial

2. Merge `feature` branches into `development` via Pull Requests:
  - Review and test changes in the `development` branch.

3. Once all changes in `development` are finalized, merge it into `main`:
  - Ensure everything is stable and ready for release.
```

This flexible workflow allows for quick experimentation while maintaining a collaborative environment.

## 🤝 Code of Conduct

We are committed to providing a welcoming and inclusive environment. Please review our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## 🌟 Thank You!

Your contributions help make **RoldanLabs** a vibrant and innovative space for learning and experimentation. Together, we’re building something amazing! 🚀
