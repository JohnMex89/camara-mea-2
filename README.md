# Cămara Mea 2.0 — ediție locală regenerată

Acest pachet a fost regenerat pe 25 octombrie 2026. Nu reprezintă arhiva originală: conversația disponibilă nu a furnizat codul sau atașamentele originale, iar accesarea repository-ului a eșuat din mediul de lucru. Nu s-au putut verifica tehnologiile sau funcțiile versiunii anterioare.

## Pornire

Dezarhivează ZIP-ul, apoi deschide `index.html` într-un browser modern. Nu ai nevoie de instalare, cont sau chei API. Păstrează toate cele trei fișiere index.html, style.css și app.js în același folder.

## Funcții

- Adăugare și eliminare produse cu cantitate, unitate și termen de expirare.
- Căutare și filtre pentru produse expirate sau care expiră în 7 zile.
- Listă de cumpărături cu bifare și transfer al numelui unui produs din cămară.
- Export și import JSON pentru copii de siguranță.

Datele sunt păstrate în localStorage, în browserul și profilul folosit. Mutarea fișierelor sau schimbarea browserului poate schimba accesul la date. Modul privat sau ștergerea datelor browserului poate elimina datele. Exportă periodic. Importul înlocuiește datele după confirmare.

## Limite

Aceasta este o aplicație locală pentru un singur profil. Nu include autentificare, sincronizare, bază de date online sau notificări când pagina este închisă. Nu este implementată o platformă pentru 250 de utilizatori. Pentru aceasta sunt necesare servicii online, reguli de acces și verificarea limitelor și costurilor furnizorului. Nu introduce parole sau secrete în fișierele publicate.

## Încărcare în GitHub

1. Autentifică-te și deschide https://github.com/JohnMex89/camara-mea-2.
2. Dezarhivează pachetul pe calculator.
3. În repository, folosește **Add file → Upload files**. Dacă repository-ul este gol, folosește **uploading an existing file**.
4. Trage fișierele din interiorul folderului `camara-mea-2` în zona de încărcare. Încarcă fișierele sursă, nu ZIP-ul. `index.html` trebuie să fie la rădăcina proiectului.
5. Dacă există deja fișiere, selectează crearea unei ramuri noi, de exemplu `versiune-regenerata`, pentru a putea compara înainte de înlocuire.
6. Scrie mesajul `Adaugă versiunea locală regenerată Cămara Mea 2.0`, apoi apasă **Commit changes** sau **Propose changes**, în funcție de opțiunea aleasă.

Documentație GitHub: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

Fișierele pot fi încărcate și cu GitHub Desktop: clonează repository-ul, copiază conținutul acestui folder în clonă, verifică modificările, apoi Commit și Push origin. Dacă există deja cod, păstrează o copie și compară-l înainte de înlocuire.
