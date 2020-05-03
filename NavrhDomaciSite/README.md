# Dokumentace návrhu sítě

# Popis sítě
### Má síť začíná bezdrátovým příjmačem <br> (v mém případě je to třeba SXT Lite5 od firmy MikroTik, který mi doporučil Michael Petro, však ve výsledku je jedno jaké zařízení bude na začátku sítě)
### Dále se má síť vede lištami k routeru umístěnému u televize.
### Na router je napojena přes UTP televize, dále je na router napojen switch, který poté rozvede síť do dalších zařízení.
### Ne vždy je dáno, že zařízení musí být připojena drátově, avšak projistotu zde zavedeme pevnou kabeláž, protože né každé zařízení může fungovat na bezdrátu, my se ovšem snažíme vyhnout takovýmto problémům do budoucna.
### Na router jsou a mohou být připojeny zařízení jako mobilní telefony tablety... atp.

# Zde je návrh mnou vytvořenné sítě
![1.PNG](Screenshots/1.PNG)

# Prvky sítě 

### Přijímač: MikroTik RouterBOARD RBSXTG-5HPacD-SA, SXT SA5 ac, L4 
### Router: Router MikroTik hAP ac2 RBD52G-5HacD2HnD-TC (RBD52G-5HacD2HnD-TC)
### Switch: Switch Mikrotik CSS106-1G-4P-1S (RB260GSP)

# Kabeláž
#### Data budeme vést v klasickém UTP kabelu, který povedeme skrz lišty, budeme upřednostňovat měkkou soklovou lištu (gumová páska), protože v budoucnu se s ní bude lépe manipulovat.
#### kabel: PATCH kabel UTP 5E, 25m
#### Lišty: Soklová lišta Fatra 1363 PVC 112
## Propočty UTP kabelu

#### Vycházel jsem z toho, že od obýváku do pokoje je to 11 metrů (obávák je široký 3,5 metrů)
### 5 metrů kabelu od antény k routeru (vedeno lištou)
### 1 metr od routeru do televize
### 7,5 metrů od routeru do pokoje (započetl jsem i rezervu)
### 2x 2 metry kabelu jeden je od switche do pc druhý od switche do tv
### dohromady toto činí 17,5 metrů, ale my však chceme i rezervu, tudíž poskytneme zakázníkovi 25 metrů kabelu za cca 180 Kč

## Propočty lišt

#### Lišty budou hlavně pokrývat náš UTP kabel od antény po switch, dále už toto záleží na našem zákazníkovi.
### Dohromady toto činí 14 metrů lišt (bez rezervy)
# Ceník
## Ceny jsou čistě orientační, protože ne vždy zboží najdete za tuto cenu.
### Přijímač: 2 898 Kč,- 
### Router: 1 830 Kč,-
### Switch: 1 407 Kč,-
### Kabeláž: 180 Kč,-
### lišty: 290 Kč,-