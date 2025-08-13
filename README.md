## Task6-my-static-website
Create an index.html file: Start by creating a simple HTML file. This file will be the homepage of your website\

##Create a New GitHub Repository
Go to your GitHub account and create a new public repository. You can name it whatever you like, for example, my-static-website.

#Push your index.html file
Upload the index.html file you created to this new repository. You can do this directly on the GitHub website or by using Git commands.

#Enable GitHub Pages
Navigate to your repository's main page.

Click on Settings.

In the left-hand menu, select Pages.

Under the "Build and deployment" section, click the dropdown menu for Source and select Deploy from a branch.

Under the Branch section, select main (or whatever your default branch is named) and ensure the folder is set to / (root).

Click Save. 

#Access Your Live Website
After a few minutes, GitHub will build and deploy your site. A link to your live website will appear at the top of the Pages settings page. It will typically be in the format of https://[your-username].github.io/[repository-name].

#Customize with CSS
o customize your site's appearance, you can add CSS directly to the <style> tags in your index.html file or link to a separate .css file. Simply create a style.css file in your repository and link to it from your HTML.

#Purchase a Domain Name
First, you need to buy a domain from a domain registrar like GoDaddy, Namecheap, or Google Domains.

#Add Your Domain to GitHub Pages
Go to your GitHub repository.

Click on Settings, then navigate to Pages on the left-hand menu.

Under the "Custom domain" section, type in your domain name (e.g., www.your-website.com) and click Save. This action automatically creates a CNAME file in your repository's root.

#Configure DNS Records with Your Domain Registrar
This is the most crucial step. You need to tell your domain provider that your domain should point to your GitHub Pages site.

#Enforce HTTPS
After your DNS records have propagated (this can take a few minutes to up to 24 hours), go back to your GitHub Pages settings and check the box for "Enforce HTTPS". This ensures your site is secure and accessible via a secure connection.
