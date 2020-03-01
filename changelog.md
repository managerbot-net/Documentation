# Changelog

## Update 2.2.0 beta - Research update

**NEWS**  
 💠 Logic of the main process segmented into smaller logical parts  
 ⚜️ Add reset profile command  
 💠 Gamesales command now allows mentioning a different author  
 ⚜️ Guild customizable gamesales  
 💠 Role related commands moved to RoleModule  
 ⚜️ GuildModerationModule grouped to categories  
 💠 UserModerationModule grouped to categories  
 ⚜️ Command Help - fixed command searching -&gt; highest hierarchy rank being propagated  
 💠 Introduced online ManagerBot documentation  
 ⚜️ Reworked output of not enough permission - added required rank  
 💠 HelpModule - Add maybe you meant clues when wrong command name is inserted  
 ⚜️ HelpModule - Order commands ascending and highlight sub-category commands  
 💠 Server customizable afk settings  
 ⚜️ Automatically add leveling role when user doesn't have one  
   


**BUG FIXES**  
 💮 Gamesales url validation error  
 ⭕️ Empty embed error  
 💮 UserLeftGuild logging error  
 ⭕️ Testing mode error  
 💮 Showing bot profile prevented  
 ⭕️ Rejoin guild and get previous data fixed  
 💮 Help command output fixed  
 ⭕️ Cryptomodule not showing bug fixed  
 💮 Command weather bug fixed  
 ⭕️ Profile showing bug fixed  
 💮 Promoting/Demoting user moderation role  
 ⭕️ Logging wrong commands output fixed  
 💮 Maximal rank adding playtime bug fixed  
   


**COMING SOON**  
 ✔️ Economy system  
 ✔️ Shop  
 ✔️ Rework saving data - use DB  
 ✔️ Bot's Website  
 ✔️ Separation of Core and UI  
 ✔️ Unit testing  

## Update 0.2.3

💎 **Novinky** 💎
- Změna ukládání dat, momentálně se data ukládají pohromadě do Databáze
- Předělání SelfAssignableRolí – změna v syntaxi
- Upravení výstupů mnoha příkazů
- Upraven systém indexování
- Vytvoření více konfigurací pro bota
- Vytvořeno oddělené testovací prostředí
- Seskupování příkazů do kategorií, ty jsou zvýrazněny v nápovědě
- Přidání úpravy vstupní přihlašovací brány
- Přidáno zobrazení výchozích zpráv a gamesales nastavení
- Optimalizace a upravení generování profilu - trojnásobné zrychlení generování
- Upravení výstupu audit values
- Vytvoření automatického přidávání dj rolí
- Vytvoření PipeLine pro správu bota
- Přidání automatických testů
- Aplikace programovacích vzorů

**Opravy chyb**
-🐛Opravení chyby, kdy se nepřiřazovala role Dj Automaticky
-🐛Opravena chyba při získávání DjSettings
-🐛Opravena chyba při nastavování afk channelu
-🐛Opravena chyba při kontrole leveling role uživatele
-🐛Opravena chyba při nenalezení příkazu
-🐛Opravena chyba, když nebyla nalezena zpráva pro reakci
-🐛Opravena chyba v právech pro přidávání rolí
-🐛Opravena chyba posílání prázdné zprávy, když uživatel opustil server
-🐛Opravena chyba při zobrazení Komunikačních kanálů
-🐛Opravena změna nicknamu
-🐛Opravena chyba při získávání playtimu
-🐛Opravena chyba při zavírání a odměňování reportů
-🐛Opravena chyba při generování profilu
-🐛Opravena chyba při odebírání warnings

## Update 0.2.4 - Activity Update

🧿 **NOVINKY**🧿
✎ Upraven příkaz /role - nově zobrazí list selfassignable rolí
✎ Přidáno sledování aktivity - denní, týdení, měsíční. Příkaz: /activity <daily/weekly/monthly>
✎ Přidány možnosti pro smazání reportu a zobrazení reportů
✎ Předěláno ukládání profilových obrázků
✎ Přidání možnosti ukládání YES/NO emotikonů
✎ Vylepšen hlasovací systém
✎ Přidána vizualizace herních statistik příkazy v /activity

🧧 BUG FIXES 🧧
🧯 Opravena chyba ve výpisu, pokud je popis prázdný
🧯 Opravena chyba v /topusers - přidáno srovnávání dle aktuálního času
🧯 Opravena závažná chyba s AFK kanálem
🧯 Opravena chyba s vykreslováním nápovědy a duplicitními jmény
🧯 Opravena chyba v rolích
🧯 Opraveno /requestmute
🧯 Opravena chyba s nevykreslením profilového obrázku při změně nicknamu
🧯 Opravena chyba s neukládáním specifického nicknamu do databáze
🧯 Opravena chyba s /afk enable a disable