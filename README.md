# Yacht Dice — počítadlo

Jednoduchá statická webová aplikace bez frameworků a bez backendu.

## Co umí
- přidávání a odebírání hráčů
- zápis bodů do všech kombinací
- automatický součet číselné části, spodní části a celkového výsledku
- bonus +30 při dosažení 63 bodů v číselné části
- lokální ukládání rozehrané hry
- rekord, průměr, počet výher a počet her pro každého hráče
- export / import dat do JSON

## GitHub Pages
1. Vytvoř nové GitHub repository.
2. Nahraj `index.html` do kořene repozitáře.
3. Otevři **Settings → Pages**.
4. Jako source vyber **Deploy from a branch**.
5. Branch: `main`, folder: `/ (root)`.
6. Ulož. GitHub po chvíli zobrazí adresu stránky.

Aplikace používá pouze `localStorage`, takže statistiky jsou uložené v konkrétním prohlížeči / zařízení. Pro přesun použij Export / Import.
