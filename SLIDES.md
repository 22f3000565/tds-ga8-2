---
marp: true
title: Product Documentation Presentation
theme: custom-theme
paginate: true
footer: "© 2025 | Author: 22f3000565@ds.study.iitm.ac.in"
header: "Technical Documentation"
style: |
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
  
  section {
    font-family: "Roboto", "Arial", sans-serif;
    padding: 60px;
    background: #ffffff;
  }
  
  h1, h2, h3 {
    color: #1a73e8;
    font-weight: 700;
  }
  
  h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
  }
  
  h2 {
    font-size: 2em;
    margin-bottom: 30px;
    border-bottom: 3px solid #1a73e8;
    padding-bottom: 10px;
  }
  
  footer {
    font-size: 12px;
    color: #666;
  }
  
  .custom-box {
    background: #e3f2fd;
    padding: 25px;
    border-radius: 12px;
    border-left: 6px solid #1a73e8;
    box-shadow: 0 2px 8px rgba(26, 115, 232, 0.15);
  }
  
  .highlight {
    background: #fef7e0;
    padding: 20px;
    border-radius: 8px;
    border: 2px solid #f59e0b;
  }
  
  code {
    background: #f5f5f5;
    padding: 2px 6px;
    border-radius: 4px;
    font-family: "Courier New", monospace;
    color: #d63384;
  }
  
  pre {
    background: #1e1e1e;
    color: #d4d4d4;
    padding: 20px;
    border-radius: 8px;
    overflow-x: auto;
  }
  
  pre code {
    color: #ce9178;
    background: none;
    padding: 0;
  }
  
  ul, ol {
    font-size: 1.2em;
    line-height: 1.8;
  }
  
  li {
    margin-bottom: 12px;
  }
---

<!-- _class: lead -->
# Product Documentation  
## Using **Marp**

**Email:** 22f3000565@ds.study.iitm.ac.in

---

<!-- _paginate: true -->
<!-- _footer: "Slide 2 | Overview Section" -->
# Overview

- ✅ Version-controlled documentation  
- ✅ Easy multi-format export (PDF, PPTX, HTML)  
- ✅ Custom themes + directives  
- ✅ LaTeX math support  
- ✅ Background images integration

---

<!-- _class: lead -->
<!-- _footer: "Slide 3 | Featured Content" -->
![bg](https://images.unsplash.com/photo-1526378722484-cc5c9c81c1a8?auto=format&fit=crop&w=1350&q=80)

# Background Image Integration  
**Marp's `![bg]()` directive enables responsive background images**

---

<!-- _footer: "Slide 4 | Custom Styling" -->
# Custom Styled Components

<div class="custom-box">
This is a custom component styled using  
<strong>CSS inside Marp directives</strong>.  
All styling is version-controlled and maintainable!
</div>

---

<!-- _footer: "Slide 5 | Key Features" -->
# Key Marp Features

<div class="highlight">
<strong>Marp Directives Used:</strong>
<ul style="margin-top: 15px;">
<li><code>&lt;!-- _class: lead --&gt;</code> - Title slide styling</li>
<li><code>&lt;!-- _footer: ... --&gt;</code> - Custom footer per slide</li>
<li><code>&lt;!-- _paginate: true --&gt;</code> - Page number control</li>
<li><code>style: |</code> - Global CSS styling</li>
</ul>
</div>

---

<!-- _footer: "Slide 6 | Mathematical Complexity" -->
# Algorithm Complexity Analysis

### Time Complexity Example

$$
T(n) = O(n \log n)
$$

### Sigmoid Function (Neural Networks)

$$
\sigma(x) = \frac{1}{1 + e^{-x}}
$$

### Matrix Multiplication Complexity

$$
C_{ij} = \sum_{k=1}^{n} A_{ik} \times B_{kj} \quad \text{where } O(n^3) \text{ for naive approach}
$$

---

<!-- _footer: "Slide 7 | Implementation" -->
# Python Implementation Example

```python
def compute_growth_rate(previous, current):
    """Calculate percentage growth rate"""
    return ((current - previous) / previous) * 100

def time_complexity_demo(n):
    """O(n log n) sorting example"""
    arr = list(range(n))
    return sorted(arr)  # Timsort: O(n log n)

# Usage
growth = compute_growth_rate(100, 120)
print(f"Growth Rate: {growth}%")
```

---

<!-- _class: lead -->
<!-- _footer: "Slide 8 | Contact" -->
# Thank You!

**Contact Information:**

📧 Email: [22f3000565@ds.study.iitm.ac.in](mailto:22f3000565@ds.study.iitm.ac.in)

🔗 GitHub: [github.com/Janesh-e](https://github.com/Janesh-e)

---

<!-- _footer: "Version Control: 1.0 | 2025" -->
# Version Control & Deployment

This presentation is:
- ✅ **Markdown-based** - easy to version control (Git)
- ✅ **Format-agnostic** - converts to PDF, PPTX, HTML
- ✅ **CI/CD ready** - automate builds with GitHub Actions
- ✅ **Maintainable** - update content without rebuilding

**Raw GitHub URL Format:**
```
https://raw.githubusercontent.com/[USER]/[REPO]/main/slides.md
```

Example: `https://raw.githubusercontent.com/Janesh-e/[REPO]/main/slides.md`
