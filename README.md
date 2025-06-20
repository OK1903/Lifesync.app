# Klonen Sie ein neues leeres Repository
git clone https://github.com/OK1903/lifesync-app.git
cd lifesync-app

# Kopieren Sie die Build-Dateien in dieses Verzeichnis
cp -r /pfad/zu/heruntergeladenen/dist/* .

# Erstellen Sie eine .nojekyll Datei
touch .nojekyll

# Commit und Push der Änderungen
git add .
git commit -m "Initial deployment"
git push origin main
