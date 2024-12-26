---
layout: page
permalink: /blogs/index.html
title: Blogs
---

## **Welcome to My Blog Space!**

This is my little corner of the web dedicated to documenting my journey of learning, creating, and sharing. Whether it’s diving into the intricacies of programming, exploring tools and technologies, or reflecting on personal projects and experiences, I strive to make this space a treasure trove of insights and inspiration.

Blogging, for me, is not just about recording knowledge — it's a way to consolidate my thoughts, share lessons learned, and spark meaningful conversations with others. In these posts, you might find solutions to problems you've encountered, new perspectives on familiar topics, or even the motivation to embark on your own creative journey.

I believe that growth stems from curiosity, exploration, and sharing, and this blog is my humble contribution to that ongoing process. Whether you stumbled upon this page by chance or are a regular visitor, I'm delighted to have you here. I hope these blogs bring value to your day and encourage you to explore the fascinating world of ideas.

This space will continue to grow with each post, and I look forward to meeting you again in a future article. If you find something particularly interesting or have thoughts to share, don't hesitate to leave a comment—I'd love to hear from you!

- [Blog updates in progress ~](https://houlinzhi.com/files/404)

## 2024  

- [Bomblab](https://houlinzhi.com/blogs/bomblab)  
  *A hands-on journey through the Binary Bomb Lab from CMU, where we defuse a binary 'bomb' through reverse engineering and assembly code analysis. Perfect for learning x86 assembly, GDB debugging, and binary analysis.*
 
- [VAE](https://houlinzhi.com/blogs/VAE)  
  *A comprehensive guide to Variational Autoencoders (VAEs), covering theory, implementation, and applications in deep learning.*  

- [Differentiable Rendering](https://houlinzhi.com/blogs/differentiable_rendering)  
  *A deep dive into differentiable rendering techniques, exploring how to integrate advanced lighting models into neural networks for more realistic image synthesis.*  

- [Makefile Tutorial By Example](https://houlinzhi.com/blogs/makefile_tutorial)  
  *A step-by-step guide to mastering Makefiles with practical examples for seamless project management.*  

- [MIT Missing Semester](https://houlinzhi.com/blogs/mit_missing_semester)  
  *Reflections and key takeaways from the MIT Missing Semester course — a must-read for developers seeking to enhance their software engineering skills.*  

- [Data Structure and Algorithm](https://houlinzhi.com/blogs/data_structure_and_algorithm)  
  *Breaking down complex data structures and algorithms into digestible concepts with practical implementations.*  

- [Personal Website Setup Guide](https://houlinzhi.com/blogs/personal_website_guide)  
  *A complete walkthrough of setting up your own personal website from scratch — empowering you to showcase your work and ideas online.*  

---

## Thank you for visiting my blog space!  

If you enjoy the content or find it helpful, consider leaving a star and supporting my work:  

- [Leave a star if you like it](https://github.com/Zenith-Hlz/Zenith-Hlz.github.io)  

---

<div style="text-align: center; margin-top: 20px;">
  <a href="javascript:void(0)" onclick="randomBlog()" style="display: inline-block; padding: 5px 10px; background-color: #000000; color: white; border-radius: 5px; text-decoration: none; font-size: 16px;">
    Random Blog
  </a>
</div>

<script>
  const blogLinks = [
    "/blogs/VAE/index.html",
    "/blogs/differentiable_rendering/index.html",
    "/blogs/bomblab/index.html",
    "/blogs/mit_missing_semester/index.html",
    "/blogs/data_structure_and_algorithm/index.html",
    "/blogs/personal_website_guide/index.html",
    "/blogs/makefile_tutorial/index.html",
    "/blogs/mit_missing_semester/7. Debugging and Profiling/index.html",
    "/blogs/mit_missing_semester/10. Potpourri/index.html",
    "/blogs/mit_missing_semester/3. Editors (Vim)/index.html",
    "/blogs/mit_missing_semester/8. Metaprogramming/index.html",
    "/blogs/mit_missing_semester/9. Security and Cryptography/index.html",
    "/blogs/mit_missing_semester/4. Data Wrangling/index.html",
    "/blogs/mit_missing_semester/1. Course overview + the shell/index.html",
    "/blogs/mit_missing_semester/2. Shell Tools and Scripting/index.html",
    "/blogs/mit_missing_semester/5. Command-line Environment/index.html",
    "/blogs/mit_missing_semester/6. Version Control (Git)/index.html",
    "/blogs/data_structure_and_algorithm/string_kmp/index.html",
    "/blogs/data_structure_and_algorithm/string_bm/index.html"
  ];

  function randomBlog() {
    const randomIndex = Math.floor(Math.random() * blogLinks.length);
    const randomLink = blogLinks[randomIndex];
    window.location.href = randomLink;
  }
</script>