Tampilan Web
```bash
https://2025.nfsccxastro.my.id/
```

Buat images docker nya
```bash
docker build -t <name_image> .
```

```bash
docker run -itd --name contoh -p 8128:86 -v /home/directory/mana:/usr/share/www/html:Z <name_image>
```
