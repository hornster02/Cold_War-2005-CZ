2023-12 STEAM
<br/>
Včetně 16:9 HOR+ upraveného EXE souboru
<br/>
https://drive.google.com/drive/folders/1-UAULs_3Z0yRHfWxrMRglXHpiwflsSyC

Postup
<br/>
-nastavit a poté spustit samotnou hru v EN (je potřeba nahrát výchozí data do registru a bez nich by pokus o spuštění hry skončil hláškou že není správně nainstalovaná)

-ručně smazat všechny soubory bez přípony ve složce hry (pokud nedojde k jejich smazání, tak po aplikování CZ patche hra může i nemusí jít spustit)

-aplikovat CZ patch

-někde v dokumentech najít složku "Cold War" a v ní soubor "Config.txt" ten nakopírovat (bez toho nejde hrát v 16:9 rozlišení) do složky s hrou a pak v něm upravit řádky "window_width = " a "window_height = " na požadované rozlišení např.
<br/>
window_width = 1920 ;
<br/>
window_height = 1080 ;

-hra se spouští přes "_spustit.exe" - Steam klient je zbytečný. Drobný problém je v tom, že pokud se hra nebude spouštět přes konfigurační okno ("coldwar.exe" nebo "_nastaveni.exe"), tak případné změny nastavení v menu hry budou pouze dočasné. Pokud se přes ně bude spouštět, tak není možné mít 16:9 HOR+ rozlišení. Řešení je jednoduché - nastavení hry provést přes "coldwar.exe" nebo "_nastaveni.exe" a hrát přes "_spustit.exe"
