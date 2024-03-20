# HERE IS THE WEEK 6 GIT EXERCISE ON "BIRTHDAY PARTY"

## Birthday Party

Here, let's practice some Git branching.  

In this project, Git was used to make a 1-page website for a friend's (Kay's) birthday party.

> [index.html](https://drive.google.com/file/d/1h2IV8AEhavMxGtEZzAkyaY9M3hOv6rtC/view?usp=drive_link) is written in HTML. Don't be afraid! You won't be asked to write any HTML from scratch.

1. From the terminal, list the Git branches.
2. Kay wasn’t sure where she wanted to host the party, so you made several Git branches to explore different locations. (a) Create two new branches “beauty” and “bolu”. These branches are no longer needed. (b) Delete them both.
3. Kay wants to see a version of the webpage that includes an unordered list with bullet points instead of a paragraph to show information about the party. Create a new branch called unordered-list and switch over to it.
4. In index.html replace:  
> &lt;p&gt;Description: Join Kay in celebrating their 29th birthday with free food and beverages, karaoke and a special appearance by Willy Nelson. Also, feel free to explore the Met museum before or after you stop by! Presents for Kay optional.&lt;/p&gt;  

with  

>  &lt;ul&gt; &lt;li&gt;Join Kay in celebrating their 29th birthday with free food and beverages&lt;/li&gt; &lt;li&gt;karaoke and a special appearance by Willy Nelson&lt;/li&gt; &lt;li&gt;explore the Met museum before or after you stop by!&lt;/li&gt; &lt;li&gt;Birthday presents optional&lt;/li&gt; &lt;/ul&gt; then save your file.
5. Add index.html to the staging area.
6. Now make a commit.
7. Kay approves the changes you made in the unordered-list branch. Switch over to master. Then, merge unordered-list into master. This will be a fast forward merge.
8. Kay wants the heading to be way bigger. Create a new branch called big-heading
9. Now, switch over the big-heading branch. 
To make the heading bigger, replace the line below:  
> &lt;h1&gt;Kay's Birthday Party&lt;/h1&gt;  

with the following line:  
> &lt;h1 style="font-size: 72px"&gt;Kay's Birthday Party&lt;/h1&gt;  

then save.
10. Add index.html to the staging area.
11. Make a commit.
12. Kay approves of the giant heading!
Switch back over to the master branch.
Then, merge big-heading into master.

(END)
