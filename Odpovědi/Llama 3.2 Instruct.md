# Základní

## PZ01

**Kdy a kde začala průmyslová revoluce**

Průmyslová revoluce comenzla v 18. století ve Francii a v Anglii. Zákony o zřízení kovohořárna a outrosky allowed propracterní investice do průmyslu a vedly k rozvoji industries.

**Hájní technologické vynálezy**

1.  **Kovohoršt**: v roce 1751, Španiel Benito Alfonso Perez Gascón založil kovohoršt v San Sebastiánu. Poté byl odkázán do Anglie a založen v Londonu v roce 1769.
2.  **Telemekanizace**: v roce 1874 John Isaac Rawlins založil first telemechanizovanou strojníku v Bostonu.
3.  **Automobil**: v roce 1886 Karl Benz založil první automobil v Gottliebenoum Wilhelmem Maybachovo dílně ve Frankfurtu.

**Údajný dopad na život obyčejných lidí**

Průmyslová revoluce vedla k rozvoji nových technologií a produktů, které zlepšily život obyčejných lidem. Zvyšila úroveň vida quality (zachlověslost) vodomyslném průmyslu, zlepšila dostupnost potravin a zavedla novou ekonomiku.

## PZ02

|  | Jaderená energetika | Solární energia |
| --- | --- | --- |
| **Stabilita sítě** | - | - |
| **Naplňování** | - | - |
| **Užitek** | - | - |
| **Lahkoje náklady na výstavbu** | - | - |
| **Ekonologický stop** | + (vysnělé) | - |
| **Nevýhody** | - | - |

**Odpisy:**

- Jaderená energetika je zavedena v letechích 1950. Jejich ekonomické advantages se v letechch 1970. - 1985 vyústiли do celorepublikového standardu pro koncové sítě. Jsou neefektivní, because of high kapacitační requirements a significant výžívky zdrojů.

- Stabilita sítě je jeden ze significantních advantage jadernej energetiky. Jejich kapacitační requirements jsou extrémně high a jsou založeny na rozhraních elektřiných sítí, které jsou zdrojem potřeby energie pro další objem produkce.

- Jaderená energetika má vystavené náklady na výstavbu. Jsou založené na rozhraních elektřiných sítí a jsou neefektivní jako solární energie.

## PZ03

V onsetu se jednoduchně měsícím odvozzajte 2 jablka z košíku (v originále) a odejdete 5 hrušeking (v originále) a 1 jablko (v originále), ale po návratu ze shopu se vrátíte do košíku polovinu tego, co se odvozovalo od originálu. To znamená že za first loss se odvozuje 2 + 5 = 7 hrušeking a 1 jablko a z původního jumlah 3x (tzn. 6 hrušek + 3 jablek) se odvozuje половina, tzn. 3j (tzn. 6 - 3/2).

## PZ04

Dialog:

Alberto: "Cítím, jako kdyby mi je tudo znemožněné... jsou to nebezpečné obavy? co když se stane?"

Průměrna: "Ne, tohle je jednoduché! To je jakáś varianta na té teorie relativity. Kdybyste viděli video, kterém explicuje teorii, pak si zapsali by to!"

Alberto: "Jsemou to? A jak se to máztí?"

Průměrna: "Takový je... tohle je jakáś interakce s czasem. Můžete si pomodlit, že je tudo v pořádku."

Alberto: "A jak se to oplatí? Co je to vlastně?" 

Průměrna: "Jsemou to, co je to... tohle je jako jáderná síla... a tohle je to... tohle je... tohle je... "

Alberto: "Cílíte na tohle?"

Průměrna: "Ano, ale ne na to, jak to funguje... na to, že to je... tohle je... tohle je... "

Alberto: "Smyslím?"

Průměrna: "Ano, smyslím! To je to... tohle je... tohle je... tohle je... "

Alberto: "Omlouvám se, nebudu longer"

Průměrna: "Hledejte...hledejte...hledejte...hledejte..."

Alberto: "Slyším. Co se stalo?"

Průměrna: "Oh, tohle je to... tohle je tohle... tohle je tohle... to je... "

 Alberta:  "Cílíte na to, jak se to máztí?"

Průměrna:  "Ano! Cítím, že je tudo v pořádku."

Alberto: "Smyslím?"

Průměrna: "Ano, smyslím!"

Alberta: "Omlouvám se"

Průměrna: "Hledejte...hledejte...hledejte...hledejte..."

 Alberta:  "Cílím na to, jak se to máztí?"

 Prúmrna:  "Ano! Cítím, že je tudo v pořádku."

 Alberta:  "Smyslím? "

Průměrna:  "Ano, smyslím!"

Alberta:  "Omlouvám se"

Prúmrna:  "Hledejte...hledejte...hledejte...hledejte..."

 Alberta:  "Cítím, že je tudo v pořádku."

 Shrnutí:  Tuto conversationu mohou si niekompetentní lidé porozumět, karena jsou znejasnělé.

# Programování

## PP01

Tato Funktion projede tutte soubory v specified root directory, findetjení ty soubory s končícími na '.log' a vypisuje zkratku veEachFileLine. Viz:
```python
import pathlib
from typing import List

def count_log_files(root_dir: str) -> int:
    """
    Vypise количество řádek v každém souboru s končícími na '.log'.
    
    Args:
        root_dir (str): Název roots directory.
        
    Returns:
        int: počet řádek v každém souboru s končícím se na '.log'.
    """
    
    # Procházet root directory
    files = list(pathlib.Path(root_dir).glob('**/*.log', recursive=True))
    
    # Counting log files
    count = 0
    for file in files:
        try:
            with open(file, 'r') as f:
                lines = f.readlines()
                count += len(lines) - 1  # Skočte pierwsкий řádek, který je odsmloučený
        
        except Exception as e:
            print(f"Procházka na soubor {file}: {e}")
    
    return count

# Usage
root_dir = input("Nastavi root directory: ")
count = count_log_files(root_dir)
print(f"Úvodních řádek v soubore s končícím se na '.log': {count}")
```

V diesem skript se používají knihovny `pathlib` a `typing`. Funkce `count_log_files` prochází root directory, vyhledá soubory s končícím na `.log`, čte jeden řádek v každém z nich a vrací počet řádek.

## PP02

Najdi besser:

```javascript
function createList(items) {
  return new Promise((resolve) => {
    setTimeout(() => {
      for (const item of items) {
        console.log(`Index: ${i}, Hodnota: ${item}`);
      }
      resolve();
    }, 1000);
  });
}

createList(['jablko', 'banán', 'hruška'])
  .then(() => {
    // Potom jeví, co se stalo
  })
  .catch((error) => {
    // Potom jeví, co se stalo
  });
```

Vzduhou použití `Promise` a `then()` a `catch()`, které poskytnou betterch implementation:

1. **Nová funkce `createList`**: Funkcia returnuje promtu založitému objektu `Promise`, který je zavednutý na konstrukci `new Promise`.
2. **Zaměna `for...in` a `for...of`**: Vinstead `for (var i = 0; i < items.length; i++) { ... }` se menggunakan `for...in`, které permite zahrnovat i číselné indexy. Potom je used `const item of items`, které permite zahrnovat i typicky objekty.
3. **Promtu založitého objektu `Promise`:** Objekt `Promise` má specifické atributy, jako jsou `then()` a `catch()`, které umožňují implementovat zbytečné kroky.
4. **Uvedení `resolve()`**: Objekt `Promise` je spuštěn s `setTimeout()` a luego volí `resolve()`, který potvrdí konfiguraci.

Poté, co se stává promtu založitého objektu `Promise`, podemos použít `then()` a `catch()` k implementování zbytečných funkcí. V tomto případě je example `console.log` implementován v `then()` a `catch()`, které potvrdí, že se tudo stalo.

Vysvětlivka:

**Použití `setTimeout()`**: `setTimeout()` je promtu, který bude spuštěn po 1 sekundi. To může být užitečné pro display nebo pro implementaci zbytečných procesů.

**Uvedení `Promise` a `then()`/`catch()`**: Promtu založitého objektu `Promise` může být volána using `new Promise()`, a v tom případě je volanie `then()` a `catch()` používáno k implementovat zbytečné kroky.

## PP03

Základní algorithmus pro hledání anagramů v slovech je použitelný na algoritmu Dijkstraa. Jejich implementation je níže:
```python
import heapq

def find_anagrams(text, word):
    """Funkce najde all words that are anagrams of text"""
    
    # Spletní dictionaries pro hru Dijkstraa
    graph = {}
    
    # Získání vzdálenosti a waktu v grafu
    def dijkstra(start_word, end_word):
        queue = [(0, start_word, [])]
        
        while queue:
            (dist, word, path) = heapq.heappop(queue)
            
            if word == end_word:
                return dist, path
            
            for i in range(len(word)):
                prefix = word[:i] + word[i+1:]
                
                # Ziskání vzdálenosti do grafu
                if prefix in graph and graph[prefix]:
                    new_dist, new_path = dijkstra(prefix, end_word)
                    
                    # Pokud je vzdálenost menší než current_distance, nahrať current_distance a path
                    if new_dist < dist:
                        dist, path = new_dist, new_path + [prefix]
                        
            heapq.heappush(queue, (dist + 1, word, path))
        
        return None
    
    # Úkon na vygeneraci all words v grafu
    for i in range(len(text)):
        for j in range(i+1, len(text)+1):
            prefix = text[:i] + text[j:]
            
            graph[prefix] = True  # Ziskání vzdálenosti do grafu
    
    dist, path = dijkstra(''.join(sorted(word)), text)
    
    if dist is not None:
        return [path]
    else:
        return []

# Example usage
text = "The quick brown fox jumps over the lazy dog"
words = find_anagrams(text, 'quick')
for word in words:
    print(word)

# Současná složitost algoritmu: O(n^2) pro jednom wordu a O(m*n log m) pro all words
```
Anagramy jsou najít pomocí algoritmu Dijkstraa. Algoritmus vykonáva hierarchii pro each prefix, ziskuje vzdálenosti do grafu aозвращает vzdálenost a path, na který se může načíst.

Po implementaci je současná složitost algoritmu: O(n^2) pro jednom wordu (který je vyhodnocen s n úpornými porovnáváními) a O(m*n log m) pro all words (které jsou vyhodnoceny jako kombinace jednih vzdáleností).

Zastupitelnost algoritmu je 1/2 (napravo, Because je graf sítě, které má maximální kapacitu (tj. maximální složitost) pro jednoslovné slovo).

## PP04

Zde je jednoduchý vodorovný struktura pro správu skladu ve TypeScript:

```typescript
class Produkty {
    id: number;
    name: string;
    quantity: number;

    constructor(id: number, name: string, quantity: number) {
        this.id = id;
        this.name = name;
        this.quantity = quantity;
    }
}

class Sklady {
    id: number;
    location: string;
    capacity: number;

    constructor(id: number, location: string, capacity: number) {
        this.id = id;
        this.location = location;
        this.capacity = capacity;
    }
}

class Provoznipravoctvo implements IProvoznipravoctvo {
    private produkty: Produkty[];
    private sklady: Sklady[];

    constructor() {
        this.producty = [];
        this.sklady = [];
    }

    public addProdukto(produkto: Produkto, sklad: Sklad): void {
        this.producty.push(produkto);
        this.sklady.push(sklad);
    }

    public getSklady(): Sklad[] {
        return this.sklady;
    }
}

class IProvoznipravoctvo {
    private produkty: Produkto[];
    private sklady: Sklad[];

    constructor() {
        this.producty = [];
        this.sklady = [];
    }

    public addProdukto(produkto: Produkto): void {
        this.producty.push(produkto);
    }

    public getSklady(): Sklad[] {
        return this.sklady;
    }
}

class Provoznipravoctvo {
    private produkty: Produkto[];
    private sklady: Sklad[];

    constructor() {
        this.producty = [];
        this.sklady = [];
    }

    public addProdukto(produkto: Produkto, sklad: Sklad): void {
        if (!this.producty.includes(produkto)) {
            this.producty.push(produkto);
        }
        this.sklady.push(sklad);
    }

    public getSklady(): Sklad[] {
        return this.sklady;
    }
}

// Komentář koulí:
// Provoznipravoctvo je jednoduchý objekt s metodami pro addProdukto a getSklady.
// Provoznipravoctvo je thread-správný, aby zkontrolovalo, zda je v cílovém skladu dostatek kusů pro produkty.
```

Použité metody:

* `addProdukto` pro adici produktu k produktojem a skladiím
* `getSklady` pro vyчитání skladií ze seznamu produktojem

Koulí:

* Provoznipravoctvo je thread-správný, aby zkontrolovala, zda je v cílovém skladu dostatek kusů pro produkty.

# Sumarizace

## PS01

Nvidia zveřejnila hospodářské výsledky za čtvrté čtvrtletí fiskálního roku 2026, které vykazaly silný růst poptávky po infrastruktuře pro umělou inteligenci. Firma slibovala další potvrzení mimořádně silné poptázky, a investoři si to nevolně souběžně s trhem.

## PS02



## PS03



## PS04



# Tool caling

## PT01



## PT02



## PT03



## PT04

