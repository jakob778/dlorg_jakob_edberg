1. skapade dlorg-repo + gitignore, samt vim-fil för dlorg.

2. i vim: 

-lade in Hämtningar som path i början av scriptet 
- en mkdir -p för varje filtyp 
- inotifywait som monitorerar Hämtningar och säger till om filer skapas/flyttas i/till 
Hämtningar samt läser ut filnamnet istället för event
- case för de olika filtyperna och vilket dir de ska hamna i

3. funktionstestade



