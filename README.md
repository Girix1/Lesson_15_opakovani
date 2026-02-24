# Opakování sort uniq cut paste join tr
## Úloha 1 - Hláskovací abeceda.
Pomocí hláskovací abecedy zakódujte libovolné slovo.

Například pro slovo `ahoj` bude výsledek 
``` bash
alfa
hotel
oscar
juliett
```
### Postup:
  1. Vytovříme souobor `slovo.txt` obsahující v každém řádku pořadí a jeden znak našeho slova.
     ```bash
     1;A
     2;h
     3;o
     4;j
     ```
  Lze využít následující script:
Ukázkový postup najdete níže: 
``` bash
echo "Ahoj" | fold -w1 | nl -w1 -s';' > slovo.txt                
```

  
