# repo-test
Repository per prove git

# creazione chiave ssh e abilitazione in github
# il nome del file nella seconda linea è quello definito durante la generazione
ssh-keygen -t ed25519 -C "your_email@example.com"
ssh-add ~/.ssh/id_ed25519

# prelevare il file .pub ed aggiungerlo in 
# settings all'interno del profilo github del repository

# comandi per clonare repo
git clone git@github.com:carmineaurilia/repo-test.git

# cambiare user e name per l'utente del repo
# lanciare in root projec
git config user.mail ""
git config user.name ""

# comandi per le operazioni base
git checkout branch
git add file
git commit -m "messaggio"
git push


# creazione branch develop
git branch develop
git push origin develop

# installazione git flow
sudo apt-get install git-flow

# initialize git flow on repo
# in root project
git flow init


