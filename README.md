2023-12 STEAM
<br/>
Včetně 16:9 a 21:9 HOR+ upraveného EXE souboru
<br/>
https://github.com/hornster02/Cold_War-2005-CZ/raw/main/_cz.rar

Postup
<br/>
-nastavit a poté spustit samotnou hru v EN (je potřeba nahrát výchozí data do registru a bez nich by pokus o spuštění hry skončil hláškou že není správně nainstalovaná) a poté ideálně donastavit v menu hry*

-přejmenovat soubory (celkem by jich mělo být 25) EN hry z "_en_" na "_cs_" (hromadné přejmenování se snadno během 5 vteřin provede třeba v programu Total Commander - CTRL+M)

-aplikovat CZ patch

-někde v dokumentech najít složku "Cold War" a v ní soubor "Config.txt" ten nakopírovat (bez toho nejde hrát v 16:9 rozlišení) do složky s hrou a pak v něm upravit řádky "window_width = " a "window_height = " na požadované rozlišení např.
<br/>
window_width = 1920 ;
<br/>
window_height = 1080 ;

-hra se spouští přes "_spustit.exe" - Steam klient je zbytečný. Drobný problém* je v tom, že pokud se hra nebude spouštět přes konfigurační okno ("coldwar.exe" nebo "_nastaveni.exe"), tak případné změny nastavení v menu hry budou pouze dočasné. Pokud se přes ně bude spouštět, tak není možné mít 16:9 HOR+ rozlišení. Řešení je jednoduché - nastavení hry provést přes "coldwar.exe" nebo "_nastaveni.exe" a hrát přes "_spustit.exe"
