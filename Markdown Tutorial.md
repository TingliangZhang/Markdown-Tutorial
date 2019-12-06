# Markdown Tutorial

[The *Markdown Guide*](https://www.markdownguide.org/)

[Markdown Guide in GitLab](https://about.gitlab.com/handbook/engineering/technical-writing/markdown-guide/)

[Mastering Markdown in GitHub](https://guides.github.com/features/mastering-markdown/)

## Editor/Tools

### online Markdown editors

[Dillinger](https://dillinger.io/) is one of the best online Markdown editors

------

### [Typora](https://www.typora.io/)  / [Bear](https://bear.app/)

![Typora](.\Fig\Typora.png)

------

### [VS code](https://code.visualstudio.com/)

![VScode](.\Fig\VScode.png)

**VS Code Keyboard Shortcuts**

[https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

- Ctrl+Shift+P, F1 Show Command Palette
- Ctrl+, User Settings
- Ctrl+K Ctrl+S Keyboard Shortcuts

Install VS Code Extension [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

**Available Commands**

- Markdown: Create Table of Contents
- Markdown: Update Table of Contents
- Markdown: Toggle code span
- Markdown: Print current document to HTML
- Markdown: Toggle math environment
- Markdown: Toggle list

**Keyboard Shortcuts**

Ctrl + Shift + V Toggle preview

------



## Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

| Element                                                      | Markdown Syntax                            |
| ------------------------------------------------------------ | ------------------------------------------ |
| [Heading](https://www.markdownguide.org/basic-syntax/#headings) | `# H1## H2### H3`                          |
| [Bold](https://www.markdownguide.org/basic-syntax/#bold)     | `**bold text**`                            |
| [Italic](https://www.markdownguide.org/basic-syntax/#italic) | `*italicized text*`                        |
| [Blockquote](https://www.markdownguide.org/basic-syntax/#blockquotes-1) | `> blockquote`                             |
| [Ordered List](https://www.markdownguide.org/basic-syntax/#ordered-lists) | `1. First item2. Second item3. Third item` |
| [Unordered List](https://www.markdownguide.org/basic-syntax/#unordered-lists) | `- First item- Second item- Third item`    |
| [Code](https://www.markdownguide.org/basic-syntax/#code)     | ``code``                                   |
| [Horizontal Rule](https://www.markdownguide.org/basic-syntax/#horizontal-rules) | `---`                                      |
| [Link](https://www.markdownguide.org/basic-syntax/#links)    | `[title](https://www.example.com)`         |
| [Image](https://www.markdownguide.org/basic-syntax/#images-1) | `![alt text](image.jpg)`                   |

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

| Element                                                      | Markdown Syntax                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Table](https://www.markdownguide.org/extended-syntax/#tables) | `| Syntax | Description || ----------- | ----------- || Header | Title || Paragraph | Text |` |
| [Fenced Code Block](https://www.markdownguide.org/extended-syntax/#fenced-code-blocks) | ````{ "firstName": "John", "lastName": "Smith", "age": 25}```` |
| [Footnote](https://www.markdownguide.org/extended-syntax/#footnotes) | `Here's a sentence with a footnote. [^1][^1]: This is the footnote.` |
| [Heading ID](https://www.markdownguide.org/extended-syntax/#heading-ids) | `### My Great Heading {#custom-id}`                          |
| [Definition List](https://www.markdownguide.org/extended-syntax/#definition-lists) | `term: definition`                                           |
| [Strikethrough](https://www.markdownguide.org/extended-syntax/#strikethrough) | `~~The world is flat.~~`                                     |
| [Task List](https://www.markdownguide.org/extended-syntax/#task-lists) | `- [x] Write the press release- [ ] Update the website- [ ] Contact the media` |



----



## Using Markdown to build Website

### The simplest possible way

If you’re looking for the simplest possible way to create a website with Markdown files, check out [blot.im](https://blot.im/) and [smallvictori.es](https://smallvictori.es/). After you sign up for one of these services, they create a Dropbox folder on your computer. Just drag and drop your Markdown files into the folder and — poof! — they’re on your website. It couldn’t be easier.

### For GitLab

- [**Part 1: Dynamic x Static Websites**](https://about.gitlab.com/2016/06/03/ssg-overview-gitlab-pages-part-1-dynamic-x-static/)

- **[Part 2: Modern Static Site Generators](https://about.gitlab.com/2016/06/10/ssg-overview-gitlab-pages-part-2/)**
- **[Part 3: Build any SSG site with GitLab Pages](https://about.gitlab.com/2016/06/17/ssg-overview-gitlab-pages-part-3-examples-ci/)**

### For GitHub

- https://jekyllrb.com/
- https://pages.github.com/
- [Setting up a GitHub Pages site with Jekyll](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll)
- If you’re familiar with HTML, CSS, and version control, check out [Jekyll](https://www.markdownguide.org/tools/jekyll/), a popular static site generator that takes Markdown files and builds an HTML website. One advantage to this approach is that [GitHub Pages](https://www.markdownguide.org/tools/github-pages/) provides free hosting for Jekyll-generated websites. If Jekyll isn’t your cup of tea, just pick one of the [many other static site generators available](https://www.staticgen.com/).

### CMS Users

If you’d like to use a content management system (CMS) to power your website, take a look at [Ghost](https://www.markdownguide.org/tools/ghost/). It’s a free and open-source blogging platform with a nice Markdown editor. If you’re a WordPress user, you’ll be happy to know there’s [Markdown support](https://en.support.wordpress.com/markdown/) for websites hosted on WordPress.com. Self-hosted WordPress sites can use the [Jetpack plugin](https://jetpack.com/support/markdown/).

### Examples

[TsinghuaUniv.github.io](https://tsinghuauniv.github.io/)

