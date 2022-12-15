# ZPI - Prezentace Home Assistenta

## Základní informace
> Home Assistant je dost podobný například softwaru Google Home.
> -> je to software, který se stará o automatizaci domácnosti a je základním jádrem toho
>
> Výhody: 
>  - Je open source
>  - Běží na lokální síti bez potřeby internetu
>  - Jde nainstalovat na jakýkoliv počítač (Win, Mac, Lin), nejčastěji je instalován na Raspberry Pi (díky kompaktnosti a výkonu je RPI plně dostačující)
>  - Podpora hromady zařízení
>  - Při troše snahy jde vybudovat celý vlastní design UI
>
> Nevýhody:
>  - Když budeme chtít k HA přistupovat vzdáleně musíme buď zaplatit vývojářům měsíčně, nebo mít od providera pronajatou veřejnou IP
>    (To ale vše jde lehce obejít a nic neplatit :-) )
>  - Integrace některých zařízení, které nejsou plně podporovaný, je trochu složitější dosáhnou plné podpory (ale jde to)


## Instalace
> Instalace Home Assistenta je snadná a lze ji provést pomocí několika jednoduchých kroků. 
>  - Nejprve si musíme promyslet jakou verzi budeme instalovat (HA OS, HA Container, HA Core, HA Supervised)
>  - Na přednášce si ukážeme instalaci HA OS do Virtual Boxu, za mě nejlepší je HA Supervised, protože tam mi fungovalo vše (na HA OS nefunguje dobře rozšíření HACS)
>  - Zde si stáhneme image s HA https://www.home-assistant.io/installation/windows
>  - Poté vytvoříme ve VirtualBoxu nový stroj s Linuxem
>  - Vybereme existující virtualní HD soubor (ten co jsme stáhli)
>  - Přejdeme do nastavení stroje a zapneme EFI a v nastavení sítě vybereme most (Bridged Adapter)
>   (Velká nevýhoda běhu HA ve VirtualBoxu je, že PC musí být připojen k LAN síti pomocí kabelu...)
>  - Teď můžeme spustit stroj a počkat cca 5 minut něž HA naběhne
>  - Půjdeme na stránku homeassistant.local:8123 nebo <IP zařízení>:8123 (např localhost:8123)
>  - První konfigurace je velmi jednoduchá, vytvoříte si účet pro přihlášení do UI a nastavíte základní informace o domově


## Integrace zařízení


## Vysvětlení UI a ovládání
