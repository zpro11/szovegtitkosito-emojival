# Emoji kódoló / dekódoló

Ez egy webes alkalmazás, amely lehetővé teszi szövegek titkosítását és
visszafejtését emojik segítségével.

## Használat

1.  Nyisd meg a `index.html` fájlt böngészőben.
2.  Válassz módot:
    -   **Kódolás**: adj meg egy szöveget, válassz emojikat, majd
        kattints a *Kódol* gombra.
    -   **Dekódolás**: illeszd be az emojikkal kódolt szöveget, majd
        kattints a *Dekódol* gombra.
3.  A kimeneti szöveget a *Másol* gombbal vágólapra másolhatod.

## Kulcs beállítása

Nyisd meg az index.html kódot szövegszerkesztőben.
A 124.  sorban lehet megadni a kulcsot a kettő "" közé.
A program ez alapján dekódol és kódol.
Ide megadhatsz bármilyen, legalább 40 karakter hosszú kulcsot, a két idézőjel közé.
pl.: "w6#n=#VB6)Yu2%lve,_8W0n;6oKRr=p}HIbh>.nJ" és ha küldesz valakinek ilyen emojit,
akkor ő csak akkor tudja dekódolni ha nála is ugyanaz a kulcs van beállítva mint nálad.


Fontos: ugyanazt a kulcsot kell használnod neked, és a másik
szeméynek is akinek küldöd az emoji-t.

## Funkciók

-   AES-GCM titkosítás
-   Emojik testreszabható palettája
-   Null-width karakterekkel való bináris rejtés
-   Másolás gomb a kimenetekhez
-   Kereshető emoji paletta
