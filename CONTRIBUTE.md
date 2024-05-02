# Contributing to the Helios GitHub Pages Repository

This guide will walk you through the process of adding posts to the Helios GitHub Pages repository.

## Prerequisites

Before you begin, make sure you have the following:

- [Visual Studio Code](https://code.visualstudio.com/) installed
- A Markdown extension installed in Visual Studio Code (e.g., [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one))

## Cloning the Repository

1. Open Visual Studio Code.
2. Click on the "Source Control" icon in the left sidebar (or press `Ctrl+Shift+G`).
3. Click on the "Clone Repository" button.
4. Enter the URL of the Helios GitHub Pages repository: "https://github.com/Ztarbox/Helios" and choose a local directory to clone it into.
5. Click "Clone" to clone the repository.

## Adding a Post

1. In Visual Studio Code, open the cloned Helios repository folder.
2. Navigate to the `_posts` directory.
3. Create a new Markdown file with the following naming convention: `YYYY-MM-DD-post-title.md`, where `YYYY-MM-DD` is the date and `post-title` is the title of your post.
4. Open the newly created Markdown file.
5. Add a YAML frontmatter to the top of the file, including the post's title enclosed in quotation marks, the date and time for the post in YYYY-MM-DD hh:mm:ss -0000 format, and as many categories as you want for your post.

   - `layout`: The layout that should be used for thi   post. Typically, this will be `post`.
   - `title`: The title of the post.
   - `date`: The date of the post, typically in th   format `YYYY-MM-DD HH:MM:SS`.
   - `categories`: The categories to which the pos   belongs. This can be a single category, or a list o   categories.
   - `tags`: The tags to apply to the post. This can b   a single tag, or a list of tags.
   - `author`: The author of the post

   ``` yaml
   ---
   layout: post
   title: "My First Post"
   date: 2023-11-14 14:35:00
   categories: [blog, tutorial]
   tags: [coding, python]
   author: John Doe
   ---
   ```

6. Write your post using Markdown syntax ([Markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/)). You can include images by placing them in the `assets/images` directory and referencing them using relative paths (`![Image tool tip\](assets/images/example.jpg)`)

7. Save the file.

see also [Adding content to your GitHub Pages site using Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll#adding-a-new-post-to-your-site)

## Pushing Changes to the Repository

1. Click on the "Source Control" icon in the left sidebar (or press `Ctrl+Shift+G`).
2. Review the changes you made in the "Changes" tab.
3. Enter a commit message describing your changes in the text box at the top of the "Changes" tab. For example, "Added new post about Markdown syntax".
4. Click the checkmark icon to commit the changes.
5. Click the ellipsis icon (⋯) next to the checkmark icon and select "Push" to push the changes to the remote Helios repository.

That's it! Your post should now be added to the Helios GitHub Pages repository. Thank you for contributing!
