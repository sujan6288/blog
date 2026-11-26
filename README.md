<p align="center">
  <img src="images/banner.svg" alt="Banner reading Web Servers Explained: Understanding Apache and Nginx, with stylised server racks and network nodes" width="100%">
</p>

<h1 align="center">Web Servers Explained</h1>
<h3 align="center"><em>Understanding Apache and Nginx</em></h3>

<p align="center">
  A beginner-friendly technical blog on how web servers work, and how Apache and Nginx differ.
</p>

<p align="center">
  <a href="index.md"><strong>📖 Read the full article</strong></a>
</p>

---

## About This Project

<table class="split" border="0" cellspacing="0" cellpadding="12">
<tr>
<td width="40%" valign="top" align="center">

<img src="images/fig1-web-server-infrastructure.svg" alt="Diagram of web server infrastructure: a client sends requests to a web server, which reads static files, calls an application, and the application queries a database" width="100%">
<br>
<sub><b>Figure 1.</b> The web server sits between clients and the resources that produce content.</sub>

</td>
<td width="60%" valign="top">

This repository contains a college-level technical blog written for a **BCA (Bachelor of Computer Applications)** assignment. It explains the role of a web server, the basics of HTTP and HTTPS, the internal design of **Apache HTTP Server** and **Nginx**, and how to compare them fairly.

The article is written in GitHub-flavored Markdown with embedded HTML, Mermaid diagrams and original SVG illustrations, so it renders directly on GitHub with no build step.

</td>
</tr>
</table>

## Author

| | |
|---|---|
| **Author** | Sujan |
| **Programme** | Bachelor of Computer Applications (BCA) |
| **College / University** | *[Add your college and university here]* |
| **Semester / Roll No.** | *[Add semester and roll number here]* |
| **Submitted to** | *[Add instructor name here]* |

## Article Contents

1. [Introduction](index.md#1-introduction)
2. [What is a Web Server?](index.md#2-what-is-a-web-server)
3. [How Does a Web Server Work?](index.md#3-how-does-a-web-server-work)
4. [HTTP and HTTPS](index.md#4-http-and-https)
5. [Apache HTTP Server](index.md#5-apache-http-server)
6. [Nginx](index.md#6-nginx)
7. [Apache vs Nginx Comparison](index.md#7-apache-vs-nginx-comparison)
8. [Real-World Applications](index.md#8-real-world-applications)
9. [Conclusion](index.md#9-conclusion)

## Repository Structure

```text
web-server-blog/
├── README.md              Project overview (this file)
├── index.md               The full blog article (GitHub Pages home page)
├── _config.yml            GitHub Pages / Jekyll settings
├── _layouts/
│   └── default.html       Responsive page layout, navigation bar and Mermaid.js
└── images/                Original SVG diagrams and banner
    ├── banner.svg
    ├── fig0-introduction-timeline.svg
    ├── fig1-web-server-infrastructure.svg
    ├── fig2-client-server-communication.svg
    ├── fig3-http-request-response.svg
    ├── fig4-apache-architecture.svg
    ├── fig5-nginx-event-driven.svg
    ├── fig6-apache-vs-nginx.svg
    ├── fig7-reverse-proxy-load-balancing.svg
    └── fig8-choosing-a-server.svg
```

## Technologies Used

| Technology | Purpose |
|---|---|
| GitHub-flavored Markdown | Article text, lists, tables and links |
| HTML (GitHub-supported subset) | Two-column layouts and centred headers |
| Mermaid | Request sequence, request-routing, reverse-proxy and decision flowcharts |
| SVG | Original, relative-path diagrams with alternative text and light animation |
| Jekyll (GitHub Pages) | Renders the article as a responsive website |

## Publishing on GitHub Pages

1. Push the whole folder to a GitHub repository.
2. Open **Settings → Pages**, choose **Deploy from a branch**, select your main branch and the `/ (root)` folder, then save.
3. Wait a minute or two, then open the site URL shown on that page.

Mermaid diagrams are rendered on the website by Mermaid.js, loaded from the jsDelivr CDN in `_layouts/default.html`. On github.com itself, GitHub renders them natively. Do not add a `.nojekyll` file, because the site needs Jekyll to apply the layout.

---

<p align="center">
  <sub>Created by Sujan · BCA Technical Blog Assignment</sub>
</p>
