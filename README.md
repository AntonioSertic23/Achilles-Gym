# Achilles Gym

## Wordpress tema za teretanu

Projekt Achilles Gym je nastao na faksu kao projekt za konstrukcijske vježbe iz predmeta **CMS sustavi**.

Tema projekta je bila kreirati wordpress temu za teretanu koristeći custom post type-ove, taksonomije i custom meta box-ove.

Stranica prikazuje sva naučena znanja o korišenju **Wordpress** tehnologijom koja koristi **PHP** programski jezik i **MySQL** za bazu podataka.

[![My Skills](https://skills.thijs.gg/icons?i=wordpress,php,mysql)](https://skills.thijs.gg)

---

### Administrativno sučelje

- cpt **Program** sadrži cpt **Sprava** povezan preko custom meta box-a
- cpt **Trener** sadrži cpt **Program** isto povezan preko custom meta box-a
- tu je još i cpt **Zanimljivost**
- svaki cpt također ima i svoju jedinstvenu taksonomiju

---

### Na starnici je moguće:

- pregledati zanimljivosti
- pregledati programe, njihove trenere i sprave
- pregledati trenere i njihove programe
- pregledati sprave i njihove programe
- pronaći lokacije na karti

---

## Pokretanje projekta

Potrebno je instalirati [XAMPP](https://www.apachefriends.org), te preko toga pokrenuti **Apache** i **MySQL**.

Potom zalijepiti mapu **Achilles-Gym** u `C:\xampp\htdocs\` i promjeniti joj ime u `achilles_gym`.

Link za pristup bazi: [http://localhost/phpmyadmin/index.php](http://localhost/phpmyadmin/index.php).

Zatim u **phpmyadmin** kreirati bazu koja se zove `achilles_gym`(Character Set neka bude **Collation**) te potom importati `achilles_gym_final.sql` koji se nalazi ovdje u root-u projekta.

Link za pristup aplikaciji: [http://localhost/achilles_gym/wp-admin/](http://localhost/achilles_gym/wp-admin/).
