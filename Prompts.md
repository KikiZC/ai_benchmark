# Základní

## PZ01

Stručně mi vysvětli, co to byla průmyslová revoluce. Rozděl odpověď do tří bodů: kdy a kde začala, hlavní technologické vynálezy a jaký měla dopad na život obyčejných lidí.

## PZ02

Porovnej výhody a nevýhody jaderné energetiky oproti solární energii v podmínkách střední Evropy. Zaměř se na stabilitu sítě, náklady na výstavbu a ekologickou stopu. Odpověď napiš formou krátké tabulky.

## PZ03

Mám v košíku 3 jablka. Moje sestra si ode mě vzala 2 jablka. Potom jsem šel do obchodu a koupil 5 hrušek a 1 jablko, které jsem cestou domů snědl. Moje matka mi dala polovinu toho, co mi zbylo v košíku po návratu z obchodu, ale byly to pomeranče. Kolik jablek mám teď v košíku? Postupuj krok za krokem a vysvětli svůj výpočet.

## PZ04

Napiš krátký dialog mezi Albertem Einsteinem a průměrným uživatelem TikToku z roku 2026 o teorii relativity. Einstein se snaží být trpělivý, uživatel používá moderní slang a snaží se vše vysvětlit pomocí 'vibes' a krátkých videí. Dialog musí obsahovat přesně 5 replik pro každou postavu a nesmíš použít slovo 'čas'. Na konci napiš shrnutí v jedné větě, proč si tito dva lidé nemohou porozumět.


# Programování

## PP01

Napiš jednoduchý Python skript, který projde všechny soubory v zadané složce, najde ty, které končí na '.log', a vypíše počet řádků v každém z nich. Použij knihovnu `pathlib`.

## PP02

Najdi chybu v tomto JavaScriptovém kódu a navrhni lepší řešení:
``` js
function createList(items) {
  for (var i = 0; i < items.length; i++) {
    setTimeout(function() {
      console.log('Index: ' + i + ', hodnota: ' + items[i]);
    }, 1000);
  }
}
createList(['jablko', 'banán', 'hruška']);
```

## PP03

Mám seznam 10 000 slov. Napiš funkci v Pythonu, která najde všechny anagramy (slova složená ze stejných písmen) a vrátí je jako seznam seznamů. Zaměř se na to, aby byl algoritmus co nejrychlejší a vysvětli jeho časovou složitost.


## PP04

Navrhni v TypeScriptu strukturu (rozhraní a třídy) pro jednoduchý systém správy skladu. Musí to obsahovat:

1. Produkty (ID, název, množství).
2. Sklady (ID, lokace, kapacita).
3. Metodu pro převod zboží mezi sklady, která zkontroluje, zda je v cílovém skladu místo a ve výchozím dostatek kusů.

**Omezení**: Nepoužívej žádné externí databáze, vše musí být v paměti. Metoda pro převod musí být 'thread-safe' (předpokládej asynchronní operace) a na konci přidej stručný komentář, jak bys tento systém škáloval, kdyby produktů bylo 10 milionů.


# Sumarizace

## PS01

Shrň následující text do jedné jediné věty, která vystihne hlavní pointu. Nepoužívej omáčku typu 'Tento článek pojednává o...'.

Text: Akcie americké společnosti Nvidia byly ve středu pod drobnohledem globálních finančních trhů. Výrobce čipů totiž zveřejnil hospodářské výsledky za čtvrté čtvrtletí fiskálního roku 2026, od nichž si investoři slibovali další potvrzení mimořádně silné poptávky po infrastruktuře pro umělou inteligenci.

Pro investory přitom nešlo jen o další kvartální report, ale o důležitý test toho, zda mimořádně silný růst poptávky po AI infrastruktuře dál drží tempo, nebo zda se začínají výrazněji objevovat první limity. Nejhodnotnější firma světa s tržní kapitalizací 4,8 bilionu dolarů tak do výsledků vstupovala s mimořádně vysokými očekáváními.

Trh podle analytiků oslovených společností LSEG před zveřejněním očekával, že Nvidia za kvartál vykáže tržby kolem 66,2 miliardy dolarů. Firma nakonec oznámila tržby ve výši 68,1 miliardy dolarů, což představuje meziroční nárůst o 73 procent. Je to zároveň více, než kolik za celý loňský rok utržily například Coca-Cola nebo Netflix.

Čistý zisk společnosti činil 42,96 miliardy dolarů, což znamená téměř dvojnásobek oproti stejnému období před rokem.

Další důležitou metrikou, kterou investoři bedlivě sledovali, je hrubá marže. Ta se loni dostala pod tlak kvůli vysokým výrobním nákladům na čipy Blackwell. Analytici před zveřejněním výsledků očekávali marži kolem 75 procent, což by představovalo meziroční růst o dva procentní body. Nvidia tento odhad potvrdila.

Investoři vedle samotných výsledků sledovali rovněž výhled na další čtvrtletí, kde se před zveřejněním čekaly tržby přibližně 72,5 miliardy dolarů. Nvidia ve výhledu uvedla tržby 78 miliard dolarů s možnou odchylkou plus minus dvě procenta, což výrazně překonalo tržní očekávání.

Význam středečních výsledků podle analytiků přesahuje samotnou firmu a její budoucnost.

„Nvidia se v posledních letech stala jednou z nejdůležitějších společností na světě. Ačkoli si od ní většina lidí pravděpodobně nikdy nic nekoupila přímo, její technologie tvoří základ velké části dnešního světa umělé inteligence. Nástroje jako ChatGPT, Google Gemini a další běží na čipech Nvidie a poptávka po nich dál roste,“ uvedl tržní analytik společnosti eToro Jakub Rochlitz.

Výsledky Nvidie tak podle něj mohou být klíčové i pro další směřování trhu. „Ten je od začátku roku téměř nehybný. Dobré výsledky ale nebudou stačit, protože Wall Street očekává jen dokonalé,“ dodává analytik.

## PS02

Představ si, že jsi asistent, který připravuje podklady pro zaneprázdněného manažera. Z následujícího zápisu z porady vytvoř: 1. Krátké shrnutí (max 3 věty), 2. Seznam úkolů (Action Items) s přidělenými jmény, 3. Termíny, pokud byly zmíněny.

„Tak jak to vypadá s backendem?“ zeptal se Michal, když si sedl ke stolu a otevřel notebook.

„Upřímně? Myslím, že to do úterý zvládnu,“ odpověděl Petr a chvíli koukal do obrazovky. „Ale potřebuju vědět, jak budou vypadat ty ikony. Bez toho některý části prostě nedodělám.“

„No jo, jenže já ty ikony ještě nemám hotový,“ povzdechl si Michal. „Chtěl jsem to dělat ve Figmě, ale pořád nemám schválenou licenci od IT.“

Petr se na něj podíval trochu nevěřícně. „Počkej, ty ji pořád nemáš? Vždyť jsi o ni žádal už minulý týden.“

„Jo, žádal,“ přikývl Michal. „Ale víš, jak to tam chodí. Nejdřív ticket, pak schválení, pak další schválení… a mezitím čekáš.“

„Super,“ zamumlal Petr. „Takže já mám dělat backend naslepo? To je ideální.“

„Hele, já ti můžu zatím poslat nějaký provizorní návrhy,“ navrhl Michal. „Není to finální, ale aspoň něco.“

„To by možná pomohlo,“ řekl Petr, ale znělo to spíš opatrně než nadšeně. „Jenže když se to pak změní, budu to celé předělávat.“

„No tak já se pokusím ty ikony dodělat do pátku,“ řekl Michal po chvíli. „Ale fakt potřebuju tu Figmu, jinak to bude dost na nic.“

„Takže jsme závislí na IT,“ povzdechl si Petr. „To zní jako plán.“

Michal se lehce zasmál. „Jo, přesně. Náš oblíbený bottleneck.“

Chvíli bylo ticho, oba jen koukali do svých obrazovek.

„Hele, a co rozpočet?“ zeptal se pak Petr. „To jsme taky pořádně neřešili.“

„To je pravda,“ přikývl Michal. „A bez toho se stejně nikam neposuneme.“

Petr zavřel notebook. „Víš co? Tohle nemá cenu řešit takhle po částech.“

„Souhlas,“ řekl Michal. „Stejně se pořád točíme dokola.“

„Tak co kdybychom svolali meeting?“ navrhl Petr. „Vezmeme Janu, probereme backend, grafiku i rozpočet najednou.“

„Jo, to dává smysl,“ kývl Michal. „Kdy?“

Petr se podíval do kalendáře. „Co pondělí v 10:00?“

„Za mě dobrý,“ odpověděl Michal. „Snad do té doby budu mít aspoň něco… nebo tu licenci.“

„Tak jo,“ uzavřel Petr. „Pondělí v deset.“

## PS03

Přečti si tento odborný popis fungování velkých jazykových modelů (LLM) a vysvětli ho desetiletému dítěti pomocí analogie s knihovnou nebo stavebnicí Lego. Zachovej vysvětlení toho, co je to 'token' a 'pravděpodobnost příštího slova'.


All transformers have the same primary components:

Tokenizers, which convert text into tokens.
Embedding layer, which converts tokens and positions of the tokens into vector representations.
Transformer layers, which carry out repeated transformations on the vector representations, extracting more and more linguistic information. These consist of alternating attention and feedforward layers. There are two major types of transformer layers: encoder layers and decoder layers, with further variants.
Un-embedding layer, which converts the final vector representations back to a probability distribution over the tokens.
The following description follows exactly the transformer as described in the original paper. There are variants, described in the following section.

By convention, we write all vectors as row vectors. For example, pushing a vector through a linear layer means multiplying it by a weight matrix on the right, as 
xW.

Tokenization
As the transformer architecture natively consists of operations over numbers (matrix multiplications, dot products, activation functions) rather than over text, there must first be a mapping from any input text to some numerical representation. This happens in three steps.

First, the input text is treated by a preprocessor, which performs both textual transformations and splits the text into coarse-grained segments called pretokens. The latter is referred to as pretokenization. Second, each pretoken is segmented further into tokens by a tokenizer that expects to only see pretokens output by its preprocessor. Each token it produces is a string of one or more characters belonging to a finite set of strings called the vocabulary 
V. Third, because the vocabulary is finite and known beforehand, each token can be assigned an integer identifier, and this mapping is applied to the sequence of tokens to represent any input text as a numerical sequence. Since this mapping is bijective, the output side can produce a sequence of integer identifiers which can then be turned back into tokens. After undoing some of the preprocessing, the result is again legible text.

Training a tokenizer (sometimes referred to as vocabularization) means finding a suitable vocabulary V, but also learning how to use it, since any given string s of length |s| has 2^{|s|-1} hypothetical segmentations, some of which containing segments that are not in the vocabulary. The most important hyperparameter during vocabularization is the vocabulary size |V|: when it is small, the learned vocabulary generally consists of characters and smaller strings, and words will be segmented into many tokens. At larger sizes, it becomes affordable to dedicate tokens to full words, although depending on the preprocessor and tokenizer, it is not necessarily the case that large vocabularies will always use the largest token(s) available to segment a word.

Because tokens are not always full words, they may also be referred to as subwords and tokenization algorithms may be referred to as subword tokenizers. This is also to differentiate these systems from traditional terminology used in older information retrieval and natural language processing systems, where "tokenization" was used to denote what is today called "pretokenization" (very crudely: splitting into words). In tokenizers that produce tokens that are not part of the vocabulary, a special token that does belong to the vocabulary is used as a generic stand-in, written as "[UNK]" for "unknown". In principle, any string could be hidden by such an [UNK]. Indeed, in information retrieval, pretokenizers were themselves used as tokenizers (and also called "tokenizers") with a word-level vocabulary that contained an [UNK].

Commonly used subword tokenization algorithms are byte pair encoding (BPE) and the unigram language model (ULM), which each include a vocabularization algorithm and a dedicated segmentation algorithm. There also exist several segmentation algorithms that require no learning and can be applied given a vocabulary (produced by BPE or ULM, for example), like greedily recognising tokens in a pretoken by moving through it left-to-right. Well-known software implementations of subword tokenizers are Hugging Face's tokenizers Python package implemented in Rust, and the sentencepiece Python package implemented in C++. The latter package is named as such because one of its configuration options allows disabling the built-in pretokenizer, hence effectively making entire sentences a pretoken and thus having the tokenizer see entire sentences, rather than individual words.

## PS04

Zanalyzuj tento rozsáhlý dokument. Na základě textu odpověz na tyto tři otázky:

Jaký byl konkrétní finanční obnos zmíněný v polovině textu v souvislosti s projektem X?

Jaké jsou tři hlavní protiargumenty, které postava A vznáší proti postavě B?

Na základě indicií v textu, jaký bude pravděpodobně další krok firmy?
**Omezení**: Tvoje odpověď nesmí být delší než 150 slov a musí být napsána v odrážkách.

Dokument: 
Testovací text: Zápis z jednání o projektu AuroraDatum: 14. dubna 2026Účastníci: Ing. Petr Novák (Technický ředitel), Mgr. Helena Štíhlá (Ekologická konzultantka), Marek Vlk (Finanční analytik)Úvod: Jednání bylo svoláno za účelem posouzení udržitelnosti projektu „Aurora“, což je výstavba autonomní vertikální farmy v průmyslové zóně u Brna. Projekt je v přípravné fázi, ale naráží na technické a finanční komplikace.Průběh diskuse:Petr Novák zahájil prezentaci technickým stavem. Uvedl, že automatizace sklizně je hotová z 80 %, ale systém recyklace vody vykazuje 12% ztrátovost, což je nad limitem. Helena Štíhlá okamžitě reagovala kritikou, že projekt v této podobě nelze označit za „udržitelný“. Podle ní je energetická náročnost LED osvětlení tak vysoká, že vymaže veškeré přínosy lokální produkce. Argumentovala také tím, že použitá hnojiva, ač certifikovaná, mají negativní dopad na mikrobiom v odpadních vodách.V polovině jednání vystoupil Marek Vlk s finančním přehledem. Uvedl, že pro dokončení první fáze je nezbytné uvolnit dodatečný rozpočet ve výši 382,5 milionu korun. Tato částka zahrnuje jak nákup nových filtrů, tak kompenzace za zpoždění stavebních prací. Bez těchto prostředků se projekt zastaví do konce května.Petr Novák oponoval Heleně Štíhlé ve třech bodech:Energetická náročnost bude pokryta vlastními solárními panely na střeše, které Helena do svých výpočtů nezahrnula.Recyklace vody se zlepší po instalaci německých membránových filtrů, které jsou už na cestě.Produkce farmy nahradí dovoz zeleniny ze Španělska, čímž se ušetří tisíce tun emisí $CO_2$ ročně z dopravy.Helena Štíhlá kontrovala tím, že solární panely nebudou v zimě stačit, že filtry jsou příliš drahé na údržbu a že emise z dopravy jsou menší problém než chemický odpad z hydroponie.Závěr a budoucí kroky:I přes neshody Marek Vlk potvrdil, že předběžný zájem projevilo město Brno, které by chtělo farmu využít jako pilotní projekt pro zásobování místních školních jídelen. Pokud se podaří vyřešit spor o filtraci a získat schválení pro dodatečných 382,5 milionu, bude v červnu podepsáno memorandum o spolupráci s magistrátem. Petr Novák dostal za úkol do 10 dnů vypracovat revidovanou zprávu o účinnosti nových filtrů.


# Tool caling

## PT01

### KONTEXT SYSTÉMU (System Prompt):
Jsi asistent v chytré domácnosti. Máš k dispozici tyto tři nástroje:
nastavit_teplotu(mistnost: string, stupne: int)
poslat_zpravu(prijemce: string, text: string)
vytvorit_pripominku(nazev: string, cas: string)

Tvým úkolem je na základě uživatelského požadavku vypsat volání těchto funkcí výhradně ve formátu JSON. Pokud uživatel chce víc věcí najednou, vygeneruj seznam (array) těchto volání. Nepiš žádné vysvětlování, žádné úvody ani závěry. Výstupem musí být pouze validní JSON.

### UŽIVATELSKÝ POŽADAVEK:
Ahoj, v obýváku je mi docela zima, tak tam nastav 23 stupňů. Jo a napiš tátovi, že přijdu o deset minut pozdějc, a hned potom mi nastav připomínku na osmou večer, že se musím podívat na ten novej díl seriálu.

## PT02

### KONTEXT SYSTÉMU (System Prompt):

Jsi asistent pro e-commerce systém. Máš k dispozici tyto nástroje:

pridat_do_kosiku(produkt: string, mnozstvi: int)
odebrat_z_kosiku(produkt: string)
vytvorit_objednavku(adresa: string)

Výstup musí být pouze validní JSON.

### UŽIVATELSKÝ POŽADAVEK:

Přidej do košíku 2x "iPhone 15", jeden "nabíjecí kabel" a vlastně ten kabel zase odeber. Pak objednávku odešli na adresu "Praha 1, Václavské náměstí".

## PT03

### KONTEXT SYSTÉMU (System Prompt):

Jsi asistent pro správu serverů. Máš k dispozici tyto nástroje:

restartovat_server(id: string)
nasadit_verzi(id: string, verze: string)
poslat_alert(komu: string, zprava: string)

Výstup musí být pouze validní JSON pole.

### UŽIVATELSKÝ POŽADAVEK:

Nasad na server "prod-1" verzi 2.1… vlastně počkej, dej tam radši 2.2. Pokud se po nasazení něco pokazí, restartuj ho. A pošli adminovi zprávu, že deploy proběhl.


## PT04

### KONTEXT SYSTÉMU (System Prompt):

Jsi asistent pro chytrou kancelář. Máš k dispozici tyto nástroje:

rezervovat_mistnost(nazev: string, cas: string, pocet_lidi: int)
zrusit_rezervaci(nazev: string, cas: string)
poslat_email(komu: string, predmet: string, text: string)

Výstup musí být pouze validní JSON.

### UŽIVATELSKÝ POŽADAVEK:

Rezervuj stejnou místnost jako minule na dnešek v 15:00 pro 5 lidí. Pokud už je obsazená, tak zruš tu starou rezervaci a zkus to znovu. A pošli všem to co vždycky posílám před meetingem.