# git cheatsheet

### hur man startar projekt

    gå in i projekt mappen (cd mappnamn)

1. `git init` inne i projektmappen
2. `git add .` punkten lägger till allt i mappen
3. `git commit -m "mitt meddelande"` uppdaterings meddelande
4. skapa nytt repo på github och kopiera länken
5. `git remote add origin _githublänk_` synka med repo på github
6. `git branch -M main` skapa huvudkanal
7. `git push -u origin main` pushar projektet till github(engångsprocess)

### hur man hämtar projekt som finns på github

1. `git clone _githublänk_` klonar repot

### Hur man uppdaterar projekt

1. `git pull` hämtar alla ändringar

##### lägg till existerande projekt

2. `git add .` punkten lägger till allt i mappen
3. `git commit -m "mitt meddelande"` uppdaterings meddelande
4. `git push` uppdaterar github repot
