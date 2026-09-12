---

title: "Website How-To"
date: 2022-11-10T10:33:21-05:00
draft: false
type: "docs"
---

- Facebook is terrible for discoverability.
  - Facebook makes it hard to find what you need.
  - Facebook makes it hard to know who is interested versus who just wants to browse.
- A real website feels professional.

## Accounts to Create

### Netlify

- <https://app.netlify.com/signup>

### GitHub

- <https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account>

## Software to Install

### Install GitHub Desktop

- <https://desktop.github.com>

### Install Typora

- <https://typora.io>
- $15 to purchase. I recommend it.
- <https://support.typora.io/Install-and-Use-Pandoc>
  - <https://github.com/jgm/pandoc/releases/tag/2.19.2>

### Install Notepad++

- <https://notepad-plus-plus.org/downloads>

### Install Git

- <https://git-scm.com/downloads>

### Install Go

- <https://go.dev/doc/install>

### Install Python

This is optional; it is really just for yamllint, which you can also use at yamllint.com. I don't think you really need it unless you are doing a lot of YAML.

- <https://www.python.org/downloads/>
- <https://www.python.org/ftp/python/3.11.1/python-3.11.1-amd64.exe>
- Install yamllint
  - <https://sourcelevel.io/blog/what-is-a-linter-and-why-your-team-should-use-it>
  - pip install yamllint

### Install Node.js

- <https://nodejs.org/en/download>

### Install Hugo

- <https://gohugo.io/installation>
- <https://github.com/gohugoio/hugo/releases/download/v0.109.0/hugo_extended_0.109.0_windows-amd64.zip>

### Install Additional NPM Packages for the Docsy Theme

- npm install autoprefixer
- npm install postcss-cli
- npm install postcss

### Install Netlify CLI

- <https://docs.netlify.com/cli/get-started>
- npm install netlify-cli -g

## Discussion

### Open Source

- Freely distributed software with a permissive license

### Markdown

- <https://commonmark.org/help>
- Why use Markdown?
  - Easy to read.
  - Good editors.
  - Converts to other formats.
    - Converting from Word using Typora.
    - Exporting to PDF with Typora.

### YAML

- Configuration language.
- <https://yaml.org>
- Use yamllint to check that everything is correct.
  - <https://sourcelevel.io/blog/what-is-a-linter-and-why-your-team-should-use-it>
  - <https://pypi.org/project/yamllint/>
  - <https://www.yamllint.com/>
- Sometimes I have seen Hugo use TOML. It is fine, but I would prefer everything to be in YAML.
  - <https://www.convertsimple.com/convert-toml-to-yaml/>

### Hugo

- <https://gohugo.io>
- <https://www.youtube.com/watch?v=ZFL09qhKi5I>
- Static site generator
  - Converts Markdown to HTML.
  - Fast as hell.
  - No need to be a programmer to get off the ground.

### Hugo Front Matter

- You are not just writing Markdown. There is a metadata component that goes with your documents.
- <https://gohugo.io/content-management/front-matter/>

### Docsy Hugo Theme

- It is not a small part; it is half of the puzzle.
- It is not easily switched out, despite what the documentation leads you to believe.
- <https://www.docsy.dev/>
- Docsy Example Site
  - <https://github.com/google/docsy-example>
  - <https://example.docsy.dev/>

### Running Hugo Locally

- Why do this?
  - Test changes before sending them to the website.
  - Run the site at the campsite.

- How do you do this?
  - Run it from the root of the website folder.
  - `hugo server -D`
  - <http://localhost:1313/>

### Git

- Commits and changes
- Local and remote
- GitHub Desktop application
  - <https://desktop.github.com/>

- GitHub web user interface
  - <https://www.github.com>

- Command Line Interface
  - `git add .;git commit -m 'updates'; git push`

- Branches - Make a version of the site for staff, NPCs, or testing.
- Blame/Annotate - See who made a change and when.
- Binary files - Use large file storage. This is only for text, not binary files.
- Triggered "build"
  - Netlify does not deploy if the build fails!

### Netlify

- <https://docs.netlify.com/integrations/frameworks/hugo/>
- Hosting platform with a very generous free tier.
- Domain Setup
- Special features!
  - Password protection for the site with the Pro plan.
  - Redirects.

---

# Let's Make This Website

## Before we get started

- This process is as easy as it can be, but this is NOT a novice process. It is technical and intimidating. If you decide this is too much for your needs, thank you for your time. I can either configure this for you, or we can find a tool that works better for you, such as Squarespace or Wix.
- We will be using the command line and you will need to take notes.
- We will go as slow as the slowest person on the call.
- If you have any questions, ask, and we will talk them through. There is no need to stay confused.
  - If you want to go over this again, please let me know. We can go through any parts you have had problems with.

## Configure Local Hugo Instance

- Hugo has steps at <https://gohugo.io/getting-started/quick-start/>. We are not following those steps; we are going to take a slightly different approach.
  
- Clone the Docsy Example site with GitHub Desktop.
  - <https://github.com/google/docsy-example>
- Confirm that it runs locally.
  - `hugo server -D`
  - <http://localhost:1313/>

- Create a new repository on GitHub as a target.

![image-20221225121301263](C:\Users\deadk\AppData\Roaming\Typora\typora-user-images\image-20221225121301263.png)

- Point the local Docsy Example site to the remote Crestfallen repository.
- ![image-20221225204655204](C:\Users\deadk\AppData\Roaming\Typora\typora-user-images\image-20221225204655204.png)

## Configure Netlify Integration

- Add the GitHub repository in the Netlify UI.
- Pick a subdomain.
- Redirects:
  - I use one for Discord and the Google feedback form.
  - `public/_redirects`
- Configure the Netlify CLI.
- Confirm that the build and deployment worked correctly.

## Configure Site URL in Hugo Setup File

- Update the configuration file.
- Push the changes.
- Confirm that everything is working. Watch the site build.

## Configure Search in Hugo Setup File

-

-

## Configure GitHub in Hugo Setup File

## Configure Favicon
<https://www.docsy.dev/docs/adding-content/iconsimages/>

<https://cthedot.de/icongen/#output>

## Configure Large Media Setup

- <https://docs.netlify.com/large-media/setup/>

## Static Resources

- Static resources folder:
  - PDF
    - Layout with Affinity Designer
  - EPUB
    - Convert with Typora / Pandoc
  - Maps / large images
