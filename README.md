# Hosting and Formatting a Resume on GitHub Pages using Markdown, VS Code, and Jekyll

The purpose of this README is to guide you through the process of hosting and formatting a resume using Markdown, VS Code, GitHub Pages, and Jekyll. We will also relate each practical step to the general principles of current Technical Writing as explained in Andrew Etter's book "Modern Technical Writing."

### Prerequisites
* A Markdown formatted resume
* A GitHub account (If you didn't have yet, click [here](https://github.com/join))
* [Ruby](https://www.ruby-lang.org/en/downloads/)
* [Jekyll](https://jekyllrb.com/docs/installation/)
* Install [markdown editor](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)


---
## Instructions


### Create a Repository 
>By the end of this section, you will have:

> * Created a new repository on your GitHub.

#### Step 1: Creating a New repository

1. Log into your [GitHub](https://GitHub.com) account.![HomePage](image/HomePage.png)

2. At the top right corner of the website, click on the '**+**' symbol
3. Select "**New Repository**".

    ![Step 2 gif](create.gif)

3. Give your repository a name. 

    ![Step 3 gif](image/Name.gif)

4. Choose visibility for your repository. You might set "**Public**" Because you want your employer to be able to see your resume
5. Initialise the repository with a README file.

    ![Step 5 gif](image/Set%20Public.gif)

6. Click on "**Create Repository**" to create.

7. In the newly created repository navigate to **Settings**
![Step 7 gif](image/Find%20Settings.gif)
8. In the sidebar click **Pages**![Step 8 gif](image/Find%20Page.gif)
9. Set the deployment source to *Deploy from a branch* under the **Source** section and set the desired publishing branch under the **Branch** section
    - To keep it simple it is recommended that the main branch and root directory is the publishing branch
![Step 9 gif](image/Main%20Branch.gif)
10. Click Save

---

### Choosing a Jekyll Theme for Your GitHub Page

If you're using GitHub to host your personal website or blog, you might be using Jekyll as your static site generator. Jekyll allows you to easily create and manage a website using plain text files, and there are plenty of pre-made themes available that you can use to customize the look and feel of your site. 

In this guide, we'll go through the steps for choosing a Jekyll theme for your GitHub page.

## Step 1: Determine Your Needs

Before selecting a theme, consider the purpose and content of your GitHub page. Do you need a theme that is focused on blogging or a theme that showcases your portfolio? In this demonstration, I will choose a more concise theme for the resume.

## Step 2: Browse the Supported Jekyll themes

The "GitHub Pages" is a great place to start looking for themes. There are plenty of free themes available that cover a variety of use cases. You can browse the page at [pages.github.com](https://pages.github.com/themes/).

## Step 3: Review the Theme's Documentation

Once you've found your favourite theme, review the documentation to see if it meets your needs. You can find instructions for installation, configuration, and customization. 


---

# Hosting Your Resume on GitHub Pages with the Midnight Theme

This guide will show you how to host your resume on GitHub Pages using the Cayman theme, which is a Jekyll theme created by Jason Long. 
>By the end of this section, you will have:

> * Host your resume on Github Pages with your favourite theme.(This time I will choose Midnight as an example)

## Prerequisites

To follow this guide, you'll need the following:
- Visual Studio Code
- A Resume in Markdown format.
- A repository build by yourselfs.
- The "Midnight theme" repository which you selected.

## Step 1: Copy the URL from your Reponsitory

You need to open your Repository and find the "Code" button. Then copy your URL.
![URL](image/FindURL.gif)

## Step 2: Open the Visual Studio Code

Open Visual Studio Code and select "Clone Git Repository..." on the initial screen.![CloneGit](image/CloneGit.jpg)

## Step 3: Clone Your Repositories
1. Paste in the URL you just copied from your repository and Press " Enter".
![Copy the URL](image/PasteURL.jpg)
2. Select a path to store your files. Then you will see your repository with all your files presented on the left side.![Presented](image/Presented.jpg)

## Step 4: Add file to your repository

1. Click on "New Document" and name your file "_config.yml" ![NameIt](image/createConfig.gif)
2. Copy the code in "_config.yml" from the Midnight theme repository 
```
 remote_theme: jasonlong/Midnight-theme
```
Then paste it into the "--config.yml" file you just created.

3. Drag your Resume into your folder.![Drag](image/AddResume.gif)

## Final Step: 
Save, commit and push into your github repository.

---
### Viewing your GitHub Page

By the end of this section, you have:
* Successfully viewed your resume on your GitHub Page through at least one of two methods

#### Viewing Your GitHub Page By URL
1. Your main GitHub page is ```https://<Your GitHub Username>.github.io/```. 
    * If the repository name is your GitHub username, visiting the URL will let you view your GitHub Page.
2. To view your resume, type ```https://<Your GitHub Username>.github.io/<repository-name>```. 

3. You should be able to see your resume, which is now on GitHub Pages!![webpage](image/ResumeWebsite.gif)

---

### Principle of Technical Writing
The principle of technical writing is to convey complex information in a clear and concise manner that can be easily understood by the intended audience. To achieve this, technical writers follow several principles, including:

1. Know your audience: Technical writers need to understand who their audience is and what their knowledge level is in the subject matter. This information helps them create content that is tailored to their readers' needs.

2. Use clear and concise language: Technical writing requires the use of simple and straightforward language that is easy to understand. Technical writers should avoid jargon and complex terminology that may confuse readers.

3. Organize information logically: Technical writing should be organized in a logical and coherent manner that allows readers to easily follow the flow of information.

4. Use visuals to enhance understanding: Technical writers should use visuals, such as diagrams, charts, and graphs, to help readers understand complex concepts.

5. Edit and proofread carefully: Technical writing must be free from errors and mistakes. Technical writers should carefully edit and proofread their work to ensure that it is accurate, clear, and concise.

By following these principles, technical writers can create effective documentation that helps their readers understand complex information.

---
## More Resources
* [Easy Markdown Tutorial](https://www.markdowntutorial.com)
* [GitHub Flavoured Markdown Reference Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)
* ["Modern Technical Writing" by Andrew Etter](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

---

## Authors and Acknowledgements 
#### **Author**
* [ZHIHAO WANG](https://github.com/Wangz8)  
#### **Group Members/Peer Editors**
* Jakob McKenna

#### **GitHub Page Theme**
*  [Parker Moore](https://github.com/pages-themes/midnight)

---

## FAQs
**Q: What is a Markdown file?**
* A: A Markdown file is a plain text file that uses a simple syntax to format text, add headings, create lists, and include links and images. It is used to create documentation and web content.

**Q: Why use Markdown files instead of Word documents?**
* A: Markdown files have several advantages over Word documents:

1. Portability: Markdown files are plain text files that can be opened and edited with any text editor, regardless of the operating system. They are lightweight and easy to share.

2. Version control: Markdown files can be easily managed with version control systems like Git, allowing you to track changes and collaborate with others.

3. Easy to read: Markdown files use a simple syntax that makes them easy to read and write. You don't have to worry about complex formatting options or hidden code.

4. Better for web content: Markdown files are better suited for creating content for the web. They can be easily converted to HTML and other web formats, and can be used to create blogs, wikis, and other online content.
