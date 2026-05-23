# Academic website guide

I am grateful to <a href="https://xinyue-lin.com/">Xinyue Lin</a> for creating and <a href="https://gautam-rao.com/">Gautam Rao</a> for sharing.

Follow the link below:

https://github.com/gautamrao/gautamrao.github.io

Make sure to make a copy of "academimal @ acf9ebb" in gautamrao.github.io/themes too after downloading the repository.

Install hugo via terminal: 

pip3 install hugo

One might need to add the hugo location to PATH.

Then run "hugo server" to locally test before launch. The "public" folder is created via hugo.

Then run the following:

cd public

git init

git add .

git commit -m "Deploy my Hugo site"

git branch -M main

git remote add origin https://github.com/YourGitHubName/YourGitHubName.github.io.git

git push -f origin main

Finally, make sure the setting for the YourGitHubName/github.io.git is correct, i.e. using the correct branch to produce the website.

The only thing to run in the future after making edits is:

cd public

git add .

git commit -m "Message"

git push -f origin main
