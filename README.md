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

### hur man hämtar branch innerhåll
1. `git checkout`

### hur man hämtar dom senaste ändringarna

1. `git pull` hämtar alla ändringar

### hur man uppdaterar ett befintligt projekt

2. `git add .` punkten lägger till allt i mappen
3. `git commit -m "mitt meddelande"` uppdaterings meddelande
4. `git push` uppdaterar github repot

### hur man tar bort lokal git

1. `rm -rf .git` tar bort sync från git & github
