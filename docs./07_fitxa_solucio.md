# Activitat 1.8. Disseny de la solució sostenible

## Part 1. Fitxa de la solució

### 1. Identificació del projecte

- **Nom provisional de l’aplicació:** MouBcn.
- **Problema que vol abordar:** A Barcelona, l’ús excessiu del cotxe i la moto particulars contribueix a les emissions contaminants, la mala qualitat de l’aire i els efectes del trànsit sobre la salut i l’espai públic. A moltes persones els costa trobar una alternativa sostenible que sigui pràctica per al seu trajecte concret.
- **Entorn d’aplicació:** Barcelona, amb una primera prova pilot.
- **Persones usuàries i beneficiàries:** Les persones usuàries principals serien conductors habituals de transport individual i altres persones que es desplacen per la ciutat. També se’n beneficiarien la ciutadania en general, especialment les persones exposades a la contaminació, encara que no utilitzin l’aplicació.
- **Proposta de valor:** L’aplicació web ajudaria a comparar rutes a peu, en bicicleta i en transport públic, i mostraria l’estalvi estimat d’emissions respecte d’un trajecte equivalent en vehicle privat. Així facilitaria la tria d’alternatives sostenibles.

### 2. Funcionament

La persona usuària introdueix l’origen i la destinació (o, si ho vol, comparteix la ubicació mentre utilitza l’aplicació), consulta les alternatives disponibles i tria una ruta segons el temps, el mitjà de transport i les seves necessitats d’accessibilitat. En acabar, pot consultar l’estalvi estimat d’emissions i, si hi ha acords amb comerços, participar en el sistema de punts.

| Funcionalitat | Què permet fer? | A qui beneficia? | És imprescindible en una primera versió? |
| --- | --- | --- | --- |
| Planificació de rutes sostenibles | Consultar opcions a peu, en bicicleta i en transport públic entre un origen i una destinació, utilitzant dades cartogràfiques i de transport disponibles. | Persones que es desplacen per Barcelona, especialment conductors que busquen alternatives. | Sí |
| Preferències d’accessibilitat i avisos | Filtrar les rutes segons les necessitats d’accessibilitat quan les dades ho permetin i comunicar incidències com obres o trams insegurs. | Persones amb mobilitat reduïda, vianants, ciclistes i ciutadania en general. | Sí |
| Estimació d’emissions evitades | Comparar l’estimació de CO₂ d’una ruta sostenible amb la d’un trajecte equivalent en cotxe, mostrant la metodologia i els factors utilitzats. | Persones usuàries i entitats que vulguin avaluar el projecte. | Sí |
| Privacitat i gestió de dades | Permetre introduir la ruta manualment; demanar permís abans d’utilitzar la ubicació, fer anonim i esborrar les dades brutes de trajectes en un màxim de 30 dies. | Totes les persones usuàries. | Sí |
| Punts i recompenses locals | Acumular punts per trajectes sostenibles i bescanviar-los en comerços adherits, si s’han formalitzat els acords necessaris. | Persones usuàries i comerços locals sostenibles. | No |


### 3. Sostenibilitat i viabilitat

| Dimensió | Valoració |
| --- | --- |
| **Ambiental** | Pot afavorir que alguns trajectes en vehicle privat es facin a peu, en bicicleta o en transport públic, contribuint potencialment a reduir emissions i contaminació. L’aplicació també consumirà energia als dispositius i als servidors, i pot dependre de serveis cartogràfics. Es limitaria aquest impacte evitant el GPS continu, optimitzant el servei i prioritzant dades obertes i eines eficients. |
| **Social** | Pot beneficiar les persones que busquen alternatives al vehicle privat i, indirectament, la ciutadania exposada a la contaminació. El disseny hauria d’incloure compatibilitat amb lectors de pantalla, contrast adequat i opcions d’accessibilitat. |
| **Econòmica** | No s’ha elaborat encara un pressupost. Els costos previsibles són les hores de desenvolupament i proves, l’allotjament web, el domini, el manteniment, la protecció de dades, l’accessibilitat i les API de pagament. Es poden reduir l’abast inicial i les despeses utilitzant dades obertes. L’Ajuntament podria estudiar suport econòmic o en espècie, i els operadors aportar dades. |
| **Tècnica** | És possible plantejar un prototip web amb dades obertes de transport i cartografia, però la qualitat i actualització de les dades condicionaran les rutes. La integració amb dos operadors, els càlculs d’emissions i les funcions d’accessibilitat s’haurien de provar abans d’ampliar el servei. La prova pilot de tres mesos permetria detectar limitacions.|

### 4. Relació amb les pràctiques anteriors

| Element | Decisió del projecte |
| --- | --- |
| **ODS i metes** | **ODS 11, meta 11.6:** contribuir a reduir l’impacte ambiental de les ciutats, inclosa la contaminació de l’aire. **ODS 13, meta 13.3:** afavorir la sensibilització i la capacitat d’actuar davant el canvi climàtic. L’aplicació hi podria contribuir indirectament si facilita canvis de mobilitat; no garanteix per si sola assolir les metes. Vegeu [02_repte_i_ODS.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./02_repte_i_ODS.md). |
| **Beneficis ambientals i socials esperats** | Afavorir trajectes menys dependents del vehicle privat, promoure la mobilitat activa i oferir informació útil sobre alternatives. La millora real de la qualitat de l’aire i sonor no s’atribuirà directament a l’aplicació sense dades que ho demostrin. Vegeu [01_necessitats.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./01_necessitats.md) i [03_causes_i_impactes.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./03_causes_i_impactes.md). |
| **Risc ASG prioritari i prevenció** | La filtració o l’ús inadequat de dades de localització pot exposar rutines personals. Es minimitzaran les dades recollides, la ubicació serà opcional i limitada a l’ús de l’aplicació, els resultats es publicaran agregats i les dades brutes de trajectes s’esborraran en un màxim de 30 dies. També es publicarà la metodologia d’emissions i es revisaran les recomanacions de rutes. Vegeu [05_analisi_ASG.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./05_analisi_ASG.md). |
| **Indicadors** | 1) Percentatge de trajectes registrats que són sostenibles: objectiu provisional d’almenys el **60 % després de tres mesos**. 2) Operadors i comerços locals adherits: objectiu de **2 operadors i 15 comerços en tres mesos**. 3) CO₂ estimat evitat: objectiu provisional de **1.500 kg acumulats en tres mesos**, calculats amb distàncies i factors oficials. La línia base s’ha de recollir abans de valorar els resultats. Vegeu [06_indicadors.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./06_indicadors.md). |
| **Grups d’interès principals** | Persones usuàries i conductors habituals, ciutadania, Ajuntament i autoritats de transport, operadors de transport públic, comerços locals i equip desenvolupador. Vegeu [04_grups_interes.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./04_grups_interes.md). |
| **Aliances potencials** | Col·laboració amb l’Ajuntament i els operadors per accedir a dades obertes. Amb comerços locals per a les recompenses. També amb empreses de mapes i aplicacions com UBER o iniciatives com MUV per a possibles recursos o col·laboracions. Vegeu [04_grups_interes.md](https://github.com/Dylan-Santamaria/Fast-and-Furious-projecte-sostenibilitat/blob/main/docs./04_grups_interes.md). |

### 5. Accions a diferents nivells

| Nivell | Acció concreta i relació amb l’aplicació |
| --- | --- |
| **Personal** | Una persona pot provar de substituir alguns trajectes curts en cotxe per caminar, anar en bicicleta o utilitzar el transport públic, i indicar a l’aplicació si la ruta proposada li ha resultat útil o tenia alguna incidència. |
| **Professional o empresarial** | L’equip desenvolupador pot construir i mantenir una aplicació accessible, reduir la recollida de dades personals i publicar com calcula les emissions. Els operadors i els comerços col·laboradors poden aportar informació actualitzada o oferir incentius, sempre amb acords i sense rebre dades personals de les persones usuàries. |
| **Institucional** | L’Ajuntament i les autoritats o operadors de transport poden facilitar dades obertes actualitzades, donar suport a una prova pilot i coordinar-se per millorar les connexions i la infraestructura ciclista. Els mapes de mobilitat que es comparteixin serien agregats i anonimitzats, no trajectes identificables. |

## Part 2. Suport al projecte i inversió responsable

### 1. Entitat que podria donar suport

L’entitat principal a qui presentaríem la proposta és l’**Ajuntament de Barcelona**, perquè treballa en la mobilitat urbana i podria tenir interès en provar mesures que facilitin alternatives al vehicle privat. També caldria coordinar-se amb els operadors de transport i, si escau, amb altres autoritats competents. No pressuposem que l’Ajuntament hagi acceptat donar suport al projecte.

### 2. Suport que demanaríem i justificació responsable

Demanaríem suport per a una prova pilot de tres mesos: assessorament tècnic, accés a dades obertes de transport i mobilitat, ajuda per contactar amb dos operadors i comerços locals, difusió entre possibles participants i, si és possible, suport per cobrir allotjament web i desenvolupament. També consultaríem si es pot oferir una alternativa física per a persones que no utilitzen telèfon intel·ligent.

Això es podria considerar suport socialment responsable perquè es destinaria a una prova acotada, amb objectius mesurables, seguiment transparent i salvaguardes de privacitat i accessibilitat. Abans d’ampliar el projecte, l’entitat podria revisar els resultats, els costos i els efectes no desitjats. No es demana una inversió basada en resultats que encara no s’han obtingut.

### 3. Evidències que presentaríem

- **Repte i treball previ:** el projecte ha identificat l’excés de gasos del transport individual a Barcelona com a repte i n’ha descrit causes, impactes i grups afectats ([repte i ODS](02_repte_i_ODS.md), [causes i impactes](03_causes_i_impactes.md) i [grups d’interès](04_grups_interes.md)).
- **Fonts consultades:** informació sobre qualitat de l’aire de la Generalitat de Catalunya, transport i mobilitat de l’Agència Europea de Medi Ambient, efectes de la contaminació de l’aire en la salut segons l’OMS, i factors d’emissió i calculadores del MITECO. Aquestes fonts contextualitzen el problema; no demostren per si soles l’impacte de l’aplicació a Barcelona.
- **Comprovació del pilot:** presentaríem la línia base i l’evolució dels tres indicadors acordats: percentatge de trajectes sostenibles, nombre d’operadors i comerços adherits, i quilograms de CO₂ estimats com a evitats ([indicadors](06_indicadors.md)). Els càlculs d’emissions s’identificarien com a estimacions i se n’explicaria el mètode.

Fonts:
- [Generalitat de Catalunya: qualitat de l’aire](https://mediambient.gencat.cat/ca/05_ambits_dactuacio/atmosfera/qualitat_de_laire/)
- [Agència Europea de Medi Ambient: transport i mobilitat](https://www.eea.europa.eu/en/topics/in-depth/transport-and-mobility)
- [OMS: qualitat de l’aire ambient i salut](https://www.who.int/es/news-room/fact-sheets/detail/ambient-(outdoor)-air-quality-and-health)
- [MITECO: transport i mitigació del canvi climàtic](https://www.miteco.gob.es/es/cambio-climatico/temas/mitigacion-politicas-y-medidas/transporte.html)
- [MITECO: calculadores d’emissions](https://www.miteco.gob.es/es/cambio-climatico/temas/mitigacion-politicas-y-medidas/calculadoras.html)

### 4. Riscos, costos i limitacions

- Les dades de rutes, horaris o accessibilitat poden ser incompletes o quedar desactualitzades; per això les recomanacions dependran de la cobertura i actualització de les fonts i permetran comunicar incidències.
- La localització i els hàbits de mobilitat són dades sensibles. La ubicació serà opcional, es recolliran només les dades necessàries, es publicaran resultats agregats i s’esborraran les dades brutes de trajectes en un màxim de 30 dies.
- El càlcul de CO₂ serà una estimació basada en distàncies i factors d’emissió, no una mesura directa de la qualitat de l’aire ni una prova que cada quilogram s’hagi evitat realment.
- El desenvolupament, l’allotjament, el manteniment, l’accessibilitat i les possibles API de pagament tenen costos que encara no s’han pressupostat. La participació d’usuaris, operadors i comerços tampoc no està garantida; si és baixa, els objectius de la prova pilot podrien no assolir-se.
- Una ruta recomanada no garanteix que el carrer sigui segur o accessible en tot moment. Les dades i els avisos ciutadans poden ajudar, però caldrà comunicar aquesta limitació i revisar les incidències.

### 5. Com comprovaríem la prova pilot

La prova duraria **tres mesos**. Abans de començar, es recolliria una línia base mitjançant una enquesta voluntària sobre hàbits de mobilitat; els acords actius i els quilograms de CO₂ estimats evitats començarien a zero. Es revisaria mensualment l’evolució i al final es compararia amb els objectius provisionals:

| Indicador principal | Objectiu provisional al cap de tres mesos | Com es comprovaria |
| --- | --- | --- |
| Percentatge de trajectes registrats que són sostenibles | Almenys el **60 %** dels trajectes registrats per les persones usuàries actives. | Registres agregats i anonimitzats de l’aplicació, comparats amb la línia base de l’enquesta voluntària. |
| Operadors de transport i comerços locals adherits | Almenys **2 operadors** i **15 comerços locals sostenibles**. | Convenis o acords actius i registre d’ús agregat dels descomptes, si s’implanten. |
| Quilograms de CO₂ estimats com a evitats | Almenys **1.500 kg acumulats**, com a objectiu inicial revisable. | Distàncies de trajectes sostenibles multiplicades pels factors oficials d’emissió, explicant la metodologia i les seves limitacions. |

Les dades es presentarien de manera agregada, sense historial de trajectes identificable. Si no s’assolissin els objectius, se n’explicarien les limitacions i les causes observades abans de proposar una ampliació. L’estimació de CO₂ no es presentaria com una mesura directa de la qualitat de l’aire de Barcelona.
