---
title: "Mastering the Beautiful Hugo Theme"
subtitle: "A comprehensive guide to code blocks, info blocks, and advanced layout features"
date: 2026-05-20
author: "Nico"
tags: ["hugo", "theme", "guide"]
categories: ["tutorial"]
---

Welcome to your new blog! This post will guide you through the powerful features of the **Beautiful Hugo** theme. Whether you're a developer sharing code or a writer organizing complex information, these tools will help you create stunning content.

## 1. Code Blocks

Standard Markdown code blocks are fully supported with syntax highlighting.

```python
def hello_world():
    print("Hello, Beautiful Hugo!")
```

You can also specify line numbers or highlight specific lines if configured in your `hugo.toml`.

## 2. Info Blocks (Callouts)

Use the `callout` shortcode to highlight important information, warnings, or tips.

{{< callout info "Pro Tip" >}}
This is an information block. It's great for helpful tips!
{{< /callout >}}

{{< callout warning "Warning" >}}
Be careful when modifying system files!
{{< /callout >}}

{{< callout danger "Critical" >}}
This is a danger block for urgent alerts.
{{< /callout >}}

{{< callout success "Success" >}}
You've successfully set up your blog!
{{< /callout >}}

## 3. Tabs

Organize related content into tabs to save space and reduce scrolling.

{{< tabs >}}
  {{< tab "Python" >}}
  ```python
  print("Hello from Python")
  ```
  {{< /tab >}}
  {{< tab "JavaScript" >}}
  ```javascript
  console.log("Hello from JavaScript");
  ```
  {{< /tab >}}
{{< /tabs >}}

## 4. Mermaid Diagrams

Create diagrams and flowcharts using simple text with Mermaid.

{{< mermaid >}}
graph TD;
    A[Start] --> B{Is it working?};
    B -- Yes --> C[Celebrate];
    B -- No --> D[Check documentation];
    D --> B;
{{< /mermaid >}}

## 5. Columns

Split your content into two columns for side-by-side comparisons.

{{< columns >}}
### Left Column
This content appears on the left side of the page.
{{< column >}}
### Right Column
This content appears on the right side of the page.
{{< /columns >}}

## 6. Details (Accordion)

Hide long sections of content behind a clickable toggle.

{{< details "Click to expand more information" >}}
This content is hidden by default. It's perfect for FAQs or technical deep-dives that might overwhelm the casual reader.
{{< /details >}}

## 7. Images and Figures

Enhance your images with captions and effects using the `beautifulfigure` shortcode.

{{< beautifulfigure src="/img/path.jpg" title="A Beautiful Path" caption="Walking through the woods" alt="Path in woods" >}}

## 8. Photo Gallery

You can even create full-screen galleries by wrapping multiple figures in a `gallery` shortcode.

{{< gallery >}}
  {{< beautifulfigure src="/img/hexagon.jpg" thumb="/img/hexagon-thumb.jpg" title="Hexagon" >}}
  {{< beautifulfigure src="/img/sphere.jpg" thumb="/img/sphere-thumb.jpg" title="Sphere" >}}
  {{< beautifulfigure src="/img/triangle.jpg" thumb="/img/triangle-thumb.jpg" title="Triangle" >}}
{{< /gallery >}}

---

Enjoy building your site with Beautiful Hugo!
