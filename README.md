# How to host a Resume on GitHub Pages  

## Purpose  

The purpose of this README is to provides a step-by-step guide on how to host a resume on GitHub Pages.  

## Prerequisites  

To get started you will need a few things:  

1) GitHub Account  
    - Create an account on [Github](https://github.com), you will need to provide an email address, username and password.  

2) Markdown Editor 

    - You can use any markdown editor to create a Resume. I personally used [Visual Studio Code](https://code.visualstudio.com/).  

3) Resume  

    - The Resume has to be in Markdown format. If you are not familiar with syntax of Markdown or need a refresher, please refer to [Markdown Tutorial](https://www.markdowntutorial.com/).  

## Instructions  

### 1) Create a new GitHub Repository  

   - Login to Github Account.  

   - Click `+` button on top right corner.  

   - Select `New repository` from the menu.  

   - Set Owner to `your Username` if not already selected.  

   - Enter repository name as `yourUsername.github.io`.  
   - Set who can see your repository by selecting either `Public` or `Private`.
   - Click `Create repository` to confirm your preferences and create the repository.  

![creating repository](gifs/createRepository.gif)  

__By using your username as the repository name, it lets Github know that this repository will be using Github Pages.__  

### 2) Upload Resume file  

   - Rename your resume which is in `.md` format from `currentName.md` to `index.md`.  

   - Click `uploading an existing file` in your GitHub repository.  

   - Click `choose your files`.  

   - Select `index.md` (your resume) from your computer.  

   - Click `open` to confirm your selection of files.  

   - Click `commit changes` to upload files to repository.  

![uploading file](gifs/fileUpload.gif)  

### 3) Apply Jekyll theme to your website  

   - Go to `settings` on your repository.  

   - Scroll down till you see a section called `GitHub Pages`.  

   - Click the link `Check it out here!` to display github pages section.  

   - Click button `Choose a theme`.

   - Select the theme you want to apply to your website.  

   - Click `Select theme` to apply the theme to your website, a `_config.yml` is automatically created for you in your repository.    

![apply theme](gifs/applyTheme.gif)  

### 4) Customizing Jekyll theme applied to Website  

- Open file called `_config.yml`.  

- Edit the file by adding a new line of code `title: YourName`.  

- Commit the new changes to the file.  

## Access hosted Resume  

- Enter `yourName.github.io` to access your hosted resume.  

![Resume gif](gifs/resume.gif)  

**Well Done you have successfully hosted your resume on GitHub Pages!**  

### More Resources  

- [Markdown tutorial](https://www.markdowntutorial.com/)  

- Andrew Etter’s book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)  

- [Cayman](https://github.com/pages-themes/cayman) jekyll theme.  

- Learn more about [Jekyll](https://jekyllrb.com/)  

## Authors and Acknowledgments  

This guide was written by [Antony Anuraj](https://github.com/antonyanuraj)  

Special thanks to my group members: Raman Bhandari, Jason Tran and Shawn Lanting, for peer-reviewing my resume and guide.

## FAQs  

### Why is Markdown better than a word processor?  


### Can I use a custom domain for my Github site?  

  - Yes, to learn about how to use custom domain click [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages)  