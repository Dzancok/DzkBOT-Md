## HOW TO CONNECT TO MONGODB

* Create account and database in mongodb atlas
* when you already have a database, you just need to take mongourl
* Put mongourl in Procfile `web: node . --db 'mongourl'`
* Example `web: node . -- db 'mongodb+srv://ilman:<password>@cluster0.iiede.mongodb.net/ShiraoriBOT?retryWrites=true&w=majority'`

---------

## UNTUK PENGGUNA TERMUX
```bash
> pkg update && pkg upgrade
> pkg install git
> pkg install nodejs
> pkg install ffmpeg
> pkg install imagemagick
> pkg install yarn
> git clone https://github.com/Dzancok/DzkBOT-Md
> cd DzkBOT-Md
> npm start
```

#### Notes 

Kagak usah lagi ketik npm install 
karena sudah ada node_modules nya 
