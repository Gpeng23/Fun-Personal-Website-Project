Created this project for fun over winter break of 2025. Please enjoy! The website is posted below.

https://gpeng23.github.io/Fun-Personal-Website-Project/

Below is the cheapest and most efficient way of how you can create a personal website for under $12 for one year. Time Committment: 15 min (if experienced) - 2 hours (if doing first time)

Don't be worried though, this is not very computationally expensive for your brain and it is quite fun at the end of the day. 

1) First watch this video: https://www.youtube.com/watch?v=EXfFBEuCAr0 (10 min)

2) Get an AI such as ChatGPT or Gemini to show you the basic formatting of HTML. Make a easy github page for fun and play around with the HTML and adjust it. Rename your HTML file to index.html (15 min)

Specific steps:

Enable GitHub Pages
Go to your repository’s Settings tab.
Scroll down to the Pages section (left sidebar).
Under Source, select Deploy from a branch.
Select the main branch and set the folder as / (root).
Click Save.
After a few seconds, GitHub will provide a link to your live website (e.g., https://username.github.io/repository-name).

3) make an account on namecheap and rent a website for the cost of 1 chipotle for an entire year. Try to get a good deal like new year's time. Namecheap website: https://www.namecheap.com/ (5-15 min)

4) After renting the site for about $10 a year, You need to be able to display your github pages website info to your actual domain name website. (5-30 min or 1 day if very unlucky)

Specific steps:

4a) Configure Your Custom Domain in GitHub

In the same Pages section, find the Custom domain box.
Enter your custom domain (e.g., www.yourdomain.com).
Check the box "Enforce HTTPS" if available.
Save your changes.

**NOTE: If you get an error where it says your custom domain name is "incompatible", this is fine. Move onto step 4b and complete all the steps there. If it STILL doesn't work get an AI to troubleshoot and I guarentee it will work. It gave me this error and I followed the next step and it worked for me.**


4b) **Configure DNS in Namecheap**


Log in to Namecheap and go to your Domain List.

Click Manage next to your domain.

Go to the Advanced DNS tab.

Add the following DNS records and insert it by copy and pasting)

A Records (if using the root domain example.com):

Type: A Record
Host: @
Value: 185.199.108.153
TTL: Auto
(Repeat for 3 more times for values: 185.199.109.153, 185.199.110.153, 185.199.111.153)

CNAME Record (for www.example.com):

Type: CNAME Record
Host: www
Value: username.github.io (replace with your GitHub username)
TTL: Auto


<img width="1100" alt="image" src="https://github.com/user-attachments/assets/ae668357-8da9-454a-9b72-c1f352dc4492" />



5) You are done! Enjoy and edit the website! Make sure to blog!


