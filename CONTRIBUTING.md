
---

# 📄 CONTRIBUTING.md  

```markdown
# 🤝 Contributing Guidelines

Thank you for your interest in contributing 🎉  
We welcome both **developers** and **non-developers**.  

---

## 📝 For Content Writers (Non-Developers)

- **Where to write:** Only in the `content/` folder.  
- **Folder Naming:** Your `/index.md` folder will be the blog URL.  
  Example: `content/my-first-post/index.md` → `https://site.com/my-first-post/`  

- **Cover Image (Mandatory):**  
  - Add a cover image for each blog post.  
  - Image must be **optimized, compressed, and small in size**.  

- **Content Rules:**  
  - Must be original (not AI-generated).  
  - If writing on an existing topic:  
    - Add references to sources.  
    - Provide **better quality, research, or more details** than the original.  
  - Must add these at top in .md file:
    ```bash
    ---
  title: "Title"
  date: Date
  coverImage: "Image Name"
  author: "Author Name"
  tags: Tags(type String[])
  description: "Description"
  ---
    ```

- **Format:**  
  - Markdown format (`.md`).  
  - Check existing blogs for formatting style.  

---

## 💻 For Developers

You can contribute in the following areas:
- UI/UX fixes (layout, styling, accessibility).  
- SEO improvements (meta tags, OpenGraph, schema).  
- Code optimizations for performance.  

### Workflow
1. Fork the repository.  
2. Create a branch:  
   ```bash
   git checkout -b new_branch_name
