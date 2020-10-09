# women-in-stem-site
A site collating information about historically overlooked women in stem

## How to contribute
I wanted this repository to be super easy for first-time github users or hacktoberfest contributors. The first thing you'll need to do is install git onto your computer. Here is a site that demonstrates a few methods to do so, depending on your OS: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

1. On Github, in the top right hand corner of this repository click 'fork'. This will copy a duplicate of the repo to your own repositories. Feel free to also star this repository :)
2. Now in your forked repo, click the green code button. This gives you three options for how to 'clone' this repo to your computer. Since you have Git installed, use HTTPS and click the copy button to the right.
3. Open your command line / terminal. I use a Mac (I know, I know) so these examples will be in terminal. Navigate to where on your computer you want to copy this repo (I have a folder in my documents folder called programming, for example).
4. Type 'git clone 'your forked repo that you just copied the link to here' '
5. Now you will have a copy of the repo on your computer. Open your favoured text editor or IDE (such as VSCode) and start coding! Read the suggestion contributions below to get started.

## Suggested contributions
The main form of contributions we are hoping to get are informative articles about Women in STEM. Please do not copy and paste from other sites and please reference sites you do use. Do a little research about who they were and what amazing things they did that contributed to the world today. You will find in the comments of the code for each page some easy questions to research to get you started.
<br>
Important: pull requests that only fix a small typo or the like do not follow Hacktoberfest's guidelines. To find out more about Hacktoberfest and view their resources click here: https://hacktoberfest.digitalocean.com/details

## Basics of Git
While you are editting your code, in the terminal navigate to the folder contianing your clones git repo. Use `git status` to see if you have any uncomitted changes. If you do, type `git add -a` to add your changes and then `git commit -m 'your message here'` to get it ready. Then, use `git commit origin` to commit your changes to your forked repo on github.

## Adding a new Women in STEM page
1. Go to the folder (Science, Tech, Engineering or Math) and duplicate one of the articles already there.
2. Rename the file to the name of the Women (e.g. marieCurie.html)
3. Go through the file and change their name (id=womenName), fields (id=field), clear the biography and references text but keep the comments (<!- ->). Then, write out the article!
4. Once the article is done, open the relevant page (e.g. sciencePage.html). Navigate to the relevant header and link to the article you just wrote (e.g. <p><a href="science/marieCurie.html">Marie Curie</a></p>)
5. Open index.html and add your name to the contributors table with what discipline you study/work in. If you're a high school student or don't want to say, you can put N/A or a field you're interested in. It doesn't have to be STEM.
6. Push your changes to github (see above for the basics of Git)
7. On Github, go to your repo and click the Pull Requests tab. Then, click new pull request. It should pick up this repo and allow you to submit a Pull Request. Add a descriptive title and submit it!