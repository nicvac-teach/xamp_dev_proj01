<div style="font-size: 90%;">

# 📦 Installazione (solo la prima volta)

```bash
wget https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run
chmod +x xampp-linux-x64-8.2.12-0-installer.run
sudo ./xampp-linux-x64-8.2.12-0-installer.run --mode unattended
```

## 🚀 Avviare i Servizi XAMPP
```bash
sudo /opt/lampp/lampp status
sudo /opt/lampp/lampp start
```

## 🔌 PORT

Su **PORTS** aggiungi la porta `80`

## 🌐 Apache e phpMyAdmin

Click su icona 🌐 in **PORTS** (Open in Browser)

Si apre la Dashboard XAMPP su un link del tipo:
> https://{codespace}.app.github.dev/dashboard/

Per aprire phpMyAdmin usare un link del tipo:
> https://{codespace}.app.github.dev/phpmyadmin

# 💻 Creare un nuovo progetto (PHP+html+css+js)

```bash
mkdir proj01
sudo ln -sf $PWD/proj01 /opt/lampp/htdocs/dashboard/
```

Creare ad es. il file `hello.php` in `proj01/`

**Eseguire il progetto:**
> https://{codespace}.app.github.dev/dashboard/proj01/hello.php

## ➡️💾 Salvare il Database
- aprire phpMyAdmin
- selezionare il database
- Export in SQL / spostare il file scaricato .sql in db_save / commit e push su github

## 💾➡️ Ripristinare il Database
- aprire phpMyAdmin
- Import / caricare il file .sql presente in db_save

</div>