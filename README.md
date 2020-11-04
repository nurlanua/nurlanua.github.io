# How to host an online Resume?

## Purpose

**What is this product? Why would anyone want it?**: This is a short guide on how to host an online resume. By hosting an online resume, Employers will know your knowledge and skill with using GitHub, Markdown, and Jekyll. This is a simple guide on how to get started to acquire these skills.  
**How does this product fit into a broader ecosystem, if at all? Does it have any dependencies?**: In the future, with the acquired skills you can write documentations and design websites. In terms of dependencies, Markdown and Jekyll depend on Github and HTML.  
**Where can I acquire this product? If there are multiple distribution packages, which should I choose and why?**: You can start learning Markdown and Github online. You don't have to download any programs. Personally, I prefer Visual Studio Code (VS Code) or use [Markdown Live Preview](https://markdownlivepreview.com).
  
## Prerequisites
  - Resume
  - [GitHub](#what-is-github)
  - [Markdown](#what-is-markdown)
  - [Jekyll](#what-is-jekyll)

### What is GitHub?

GitHub is a platform for software developers to share the code and get help from other users. 
It lets you and teams collaborate efficiently from everywhere around the world.
GitHub also allows users to create their static websites for no additional costs.  
To get started with the GitHub, you will need to complete a [GitHub tutorial](https://guides.github.com/activities/hello-world/).

### What is Markdown?

Markdown is a text editing lightweight markup language. 
It is usually used to create README documents for online forums.
You can think of it as a lighter version of HTML.  
To get started with the Markdown, you will need to complete a [Markdown tutorial](https://www.markdowntutorial.com).  
To implement markdown with GitHub you might need to review the [GitHub tutorial](https://guides.github.com/features/mastering-markdown/) on Markdown.


### What is Jekyll?

Jekyll is a generator that allows you to style your website.
You can think of it as a CSS.  
You do not have to know Jekyll for this type of example. You just need to know what type of Jekyll themes are supported by GitHub. More on this later.

## Instructions

These instructions will let you host your resume on GitHub using Jekyll and Markdown.
  #### 1. Create an account on [GitHub](https://github.com)     
      
  #### 2. Create a repository named [your_account].gitgub.io 

  #### 3. Add README.md, index.md, \_config.yml
   
  - **README.md**  
      README.md is usually used to explain what other files do, how they are used, and why do we need them. In this case, we can write a cover letter, explain what our skills are in more details, show some projects that we have made, and many more that are relevant to the position you are applying for.  
      </br>
      I want to teach you Andrew Etter's principles on technical writing.  
> 1. **Research**: Research about what you need to write about. Look at other's examples of cover letters. Surf the internet.  
>  Write down key points that you want to include.    
> 2. **Write**: Start with writing everything down for a draft. Read everything through and think "Does Employer need to know this information?",
>"How would that information help you get the job?", "Is it too wordy?".  
> 3. **Design**: Use tools to make your reading easy to follow. Use some .gif to make your instructions more clear. Provide some visuals  
> to lessen the number of words.   
> 4. **Read**: Read through your document many times over. Show it to your friends and see if they can understand your README.md file.  
> 5. **Pull requests**: Try getting insight from other users.   

I am not going over the last point, because if you do, you will be sharing your private information with other people. Be careful with what you are sharing, because people might use it against you. As Andrew Etter says:  
> In short, assholes ruin everything.
      </br>
  - **index.md**   
  index.md is usually displayed on your static website. In this case, we are displaying our resume profile. We follow the same steps that we followed in README.md.   
  1. Research about the job. Find out job descriptions. Look for resume applications for the same type of job.  
  2. Start writing. Write all relevant skills the job posting is looking for.  
  3. Design. Put your skills first, your experience second, and education third.
  4. Get some advice. Show it to your friends, relatives, or coworkers. Run it through Grammarly or other syntax checking machines.  
  
  - **\_config.io**  
    \_config.io is used to set up a Jekyll theme of your static website. You can choose any theme from [Supported themes](https://pages.github.com/themes/).  
    To use any of the themes, you can read their README.md files. You can usually make it work with a single line in the \_config.yml file. 
    
    ![demonstration](img/show.gif)

  #### More resources
 - [Markdown tutorial](https://www.markdowntutorial.com)
 - [GitHub's Markdown tutorial](https://guides.github.com/features/mastering-markdown/)
 - [Modern Technical Writing: An Introduction to Software Documentation by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/ref=sr_1_1?crid=3U5MQMA2GZJD&dchild=1&keywords=modern+technical+writing+by+andrew+etter&qid=1604367457&sprefix=Andrew+etter%2Caps%2C202&sr=8-1)
 - [Supported themes](https://pages.github.com/themes/)  

## Built With

  - Markdown
  - Jekyll
  - GitHub

## Authors and Acknowledgments

  - Azat Nurlan Uulu (nurlanua@myumanitoba.ca)
  - Group members
    * Ahmed Kidwai
    * Jane Tang
    * Theo Gerwing
  - Jekyll theme by GitHub

## FAQ
1. **Why is Markdown better than a word processor?** Markdown is more flexible than a word processor. If we need to design a static website, we can put an already written Markdown file, whereas for word processing we will need to convert it to Markdown or HTML file. Markdown is easy to use. it has 6 main font sizes. We can refer to some headings and make shortcuts inside the file. It does everything a developer needs.
2.  **Why is my resume not showing up?** There might be several reasons why the resume is not showing up. To name a few: improper naming of a repository, improper naming of an index.md, reloading time for a website to update, and might be some problems with the \_config.yml.  

## Summary
  - [Purpose](#purpose)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
  - [Authors and Acknowledgements](#authors_and_acknowledgements)
  
