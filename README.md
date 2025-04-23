# Starter Prompts for v0 Projects

Welcome to the **Starter Prompts for v0 Projects** repository! This repo collects initial prompt templates, guidelines, and examples to help you kick off your v0 explorations across different domains.

---

## 📁 Repository Structure

```
/prompts/                   # Root folder for all prompt files
  /v0/                      # Version 0 initial prompts
    /project-a/             # Prompts and assets for Project A
      ├── readme.md         # Starter prompt stored in Markdown
      ├── attachments.zip   # Supporting assets provided as a zip archive
    /project-b/             # Prompts and assets for Project B
      ├── readme.md
      ├── attachments.zip
    /template.md            # Blank template for new v0 prompt directories

README.md                   # This file
CONTRIBUTING.md             # Contribution guidelines
LICENSE                     # License for this repository
```

Each project directory under `prompts/v0/` now contains:

- **`readme.md`**: the primary prompt definition and usage instructions.
- **`attachments.zip`**: any supplementary files (e.g., data samples, images, code snippets) bundled for easy download.

## 🚀 Getting Started

1. **Browse existing prompts** in `prompts/v0/project-*/readme.md` to find inspiration for your project.
2. **Copy `prompts/v0/template.md`** into a new directory named after your project (e.g. `prompts/v0/my-new-project/`).
3. **Create** within that directory:
   - `readme.md` with your customized prompt content.
   - `attachments.zip` bundling any required assets.
4. **Test** your prompt interactively with your preferred LLM or playground.

## 📝 Prompt Directory Guidelines

Each project folder (e.g. `prompts/v0/project-a/`) should include:

```markdown
# Project Name

## Context
- A brief description of the problem or scenario

## Instructions
1. Step-by-step guidance the model should follow
2. Key deliverables and formatting requirements

## Examples (Optional)
- **Input example:** ...
- **Expected output:** ...

## Variables
- `{{query}}`: Description of variable to interpolate
- `{{user_name}}`: Description of variable to interpolate
```

Place additional resources—datasets, images, code snippets, etc.—inside `attachments.zip`. Users can download this archive to access all supporting files in one go.

Use `template.md` as a reference when creating new v0 prompt directories.

## 🤝 Contributing

Contributions are welcome! To add or improve prompts:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/add-v0-prompt`
3. Add or update your project folder in `prompts/v0/`
4. Commit your changes: `git commit -m "Add v0 prompt for my-project with attachments"`
5. Push to your fork: `git push origin feature/add-v0-prompt`
6. Open a Pull Request and fill in the PR template

Please review our [CONTRIBUTING.md](CONTRIBUTING.md) for more details.

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

*Happy prompting!*

