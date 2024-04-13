STEAM (2023-12)
<br/>
https://github.com/hornster02/Cold_War-2005-CZ/raw/main/_cz.rar

Postup
<br/>
-spustit původní hru bez češtiny (je potřeba nahrát výchozí data do registru a bez nich by pokus o spuštění hry skončil hláškou že není správně nainstalovaná) a poté ideálně donastavit v menu hry*

-přejmenovat původní herní soubory (celkem by jich mělo být 25) z ```_en_``` na ```_cs_``` - ideálně metodou najít/nahradit (hromadné přejmenování se snadno během 5 vteřin provede třeba v programu Total Commander - CTRL+M)

-aplikovat CZ patch

-někde v dokumentech najít složku "Cold War" a v ní soubor "Config.txt" ten nakopírovat (bez toho nejde hrát ve vysokých rozlišeních) do složky s hrou a pak v něm upravit řádky ```window_width = ``` a ```window_height = ``` na požadované rozlišení např.
<br/>
```window_width = 1920 ;```
<br/>
```window_height = 1080 ;```

-hra se spouští přes "_spustit.exe" - Steam klient je zbytečný. Drobný problém* je v tom, že pokud se hra nebude spouštět přes konfigurační okno ("coldwar.exe" nebo "_nastaveni.exe"), tak případné změny nastavení v menu hry budou pouze dočasné. Pokud se přes ně bude spouštět, tak není možné mít vysoká rozlišení. Řešení je jednoduché - nastavení hry provést přes "coldwar.exe" nebo "_nastaveni.exe" a hrát přes "_spustit.exe"
