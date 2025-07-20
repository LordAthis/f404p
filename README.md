# funny 404 pages (f404p)

**Egyszerűen telepíthető vicces 404 oldalak, bárkinek!**

## Telepítés

1. Másold a `f404p_setup.html`, `404.html` és az `images` mappát a saját oldalad gyökérkönyvtárába.
2. Nyisd meg az `f404p_setup.html`-t a böngészőben, válassz ki egy képet.
3. Állítsd be a webszerveredet, hogy a 404 hibák esetén a `404.html`-t jelenítse meg.
   - Pl. Apache esetén `.htaccess`:
     ```
     ErrorDocument 404 /404.html
     ```
4. Kész!

## Új képek hozzáadása

Tegyél új képeket az `images` mappába, frissítsd a `f404p_setup.html` scriptjében az `images` tömböt!

---

**A kiválasztott kép csak akkor töltődik be, amikor valóban szükség van rá!**
