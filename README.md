## Personal Website Creation Guide

Created this project for fun over winter break of 2025. Please enjoy! The website is linked below:

Website Link(s): 

github pages: https://gpeng23.github.io/Fun-Personal-Website-Project/

Linked personal website: gregorypeng.net

## Overview

* Below is the cheapest and most efficient way to create a personal website for under $12 for one year.

*  Time Commitment: 15 minutes (if experienced) - 2 hours (if doing it for the first time).

* Don’t worry—this process is not computationally expensive for your brain, and it's quite fun by the end of the day!

### Step 1: Watch the Tutorial Video (10 min)

Video Link: www.youtube.com/watch?v=gwUz3E9AW0w

### Step 2: Create a GitHub Page and Format the HTML (5-20 min)

Get an AI Tool (such as ChatGPT or Gemini) to show you the basics of HTML formatting.

Create a simple GitHub Page and play around with HTML elements to personalize your site.

Rename your main HTML file to index.html.

Enable GitHub Pages

Go to your repository’s Settings tab.

Scroll down to the Pages section (left sidebar).

Under Source, select Deploy from a branch.

Select the main branch and set the folder as / (root).

Click Save.

After a few seconds, GitHub will provide a link to your live website (e.g., https://username.github.io/repository-name).

### Step 3: Rent a Domain on Namecheap

Create an account on Namecheap.

Rent a domain for the cost of one Chipotle burrito (~$10/year).

Tip: Try to catch a good deal during holidays, such as New Year's promotions.

Time Estimate: 5-15 minutes.

### Step 4: Link Your GitHub Pages Site to Your Custom Domain

After renting the domain, link your GitHub Pages site to your custom domain.

#### Step 4a: Configure Your Custom Domain in GitHub (~10-30 min, 1 day of waiting if extremely unlucky)

Go to your repository’s Settings > Pages section.

In the Custom domain box, enter your custom domain (e.g., www.yourdomain.com).

Check the box "Enforce HTTPS" (if available).

Click Save.

Note: If you get an error saying your custom domain is "incompatible," that’s fine! Move on to step 4b.

#### Step 4b: Configure DNS Settings in Namecheap

Log in to Namecheap and go to your Domain List.

Click Manage next to your domain.

Navigate to the Advanced DNS tab.

Add the following DNS records:

A Records (for root domain, e.g., example.com)

Type: A Record
Host: @
Value: 185.199.108.153
TTL: Auto

(Repeat for the following IP addresses):

185.199.109.153

185.199.110.153

185.199.111.153

CNAME Record (for www.example.com)

Type: CNAME Record
Host: www
Value: username.github.io (replace with your GitHub username)
TTL: Auto

<img width="1100" alt="image" src="https://github.com/user-attachments/assets/ae668357-8da9-454a-9b72-c1f352dc4492" />


### Step 5: You're Done!

Enjoy your new website! Make edits, personalize it, and don't forget to start blogging!



### Final Tips:

If errors persist, use an AI tool for troubleshooting (this helped me when I got the "incompatible domain" error).

Experiment with HTML/CSS to improve your site’s design.

Congratulations on building your personal website!




5) You are done! Enjoy and edit the website! Make sure to blog!


