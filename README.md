mkdir app-dev
cd app-dev
git init
git checkout -b readme-edits
echo "# My Favorite Series" > README.md
echo "" >> README.md
echo "My favorite series is The Walking Dead. I like it because it has an exciting story and interesting characters. The suspense keeps me engaged and makes every episode feel dramatic." >> README.md
git add README.md
git commit -m "Add favorite series information"
git remote add origin https://github.com/Taguragi/app-dev.git
git push -u origin readme-edits
