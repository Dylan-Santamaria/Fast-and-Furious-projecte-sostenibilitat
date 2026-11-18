# Activitat 1.6.
## 1. Noms i rols: 
- Aquesta activitat l'ha fet el Dylan.

## 2. Identificació dels aspectes ambientals, socials i de governança.
### Aspectes Ambientals:
**1. Reducció d'emissions de $CO_2$ i millora de la qualitat de l'aire:** En fomentar els desplaçaments a peu, en bicicleta i en transport públic en lloc del vehicle privat, disminueix la contaminació atmosfèrica i acústica a la ciutat.
- Oportunitat

**2. Consum energètic dels servidors i rastreig GPS continu:** El funcionament constant de l'aplicació en segon pla per registrar ubicacions genera un consum de bateria als dispositius i una petjada de carboni associada al processament de dades al núvol.
- Risc

### Aspectes Socials:
**3. Bretxa digital i falta d'accessibilitat:** El fet que l'aplicació requereixi un telèfon intel·ligent compatible, connexió permanent a Internet i que la primera versió no inclogui adaptacions per a persones amb discapacitat visual o motriu pot excloure col·lectius vulnerables.
- Risc

**4. Impuls al comerç local i millora de la salut pública:** El sistema de punts bescanviables dinamitza l'economia de proximitat i promou hàbits de vida més actius i saludables entre la ciutadania.
- Oportunitat

### Aspectes de Governança:
**5. Privacitat, protecció de dades i ús comercial:** La recollida d'historial de trajectes en segon pla i la futura cessió d'estadístiques a comerços patrocinadors pot generar desconfiança o exposar informació sensible si es produeix una filtració de dades.
- Risc i oportunitat alhora (és un risc greu si falla la seguretat o la transparència, però una oportunitat per millorar la planificació urbana de l'Ajuntament si es gestiona amb dades obertes i anonimitzades).

**6. Transparència en els càlculs i responsabilitat legal:** La manca de verificació externa sobre com es calculen les emissions evitades i l'absència d'un responsable clar en cas que l'app recomani una ruta poc segura poden danyar la credibilitat del projecte.
- Risc


## 3. Matriu de riscos i oportunitats ASG.
![Matriu d'aspecte](Matriu%20d'aspecte.jpg)

## 4. Justificació de la probabilitat i de l’impacte.
### 1. Reducció d'emissions de $CO_2$ (Oportunitat):
- **Freqüència:** Freqüent. Cada trajecte sostenible registrat evita directament emissions respecte al cotxe privat.
- **Impacte:** Major. Contribueix directament als objectius climàtics municipals i a la salut respiratòria de tota la població.

### 2. Consum energètic dels servidors i GPS (Risc):
- **Freqüència:** Probable. El rastreig en segon pla funciona de manera contínua mentre l'usuari es mou.
- **Impacte:** Menor. L'impacte ambiental dels servidors és molt inferior a l'estalvi generat per la reducció del trànsit i es pot corregir optimitzant el codi.

### 3. Bretxa digital i falta d'accessibilitat (Risc):
- **Freqüència:** Freqüent. L'enunciat confirma que la primera versió no incorpora opcions d'accessibilitat i que hi ha ciutadans sense accés tecnològic adequat.
- **Impacte:** Moderat. Limita l'equitat social del projecte, tot i que es pot gestionar mitjançant actualitzacions i alternatives físiques.

### 4. Impuls al comerç local i salut pública (Oportunitat):
- **Freqüència:** Probable. El sistema de gamificació i descomptes incentiva el consum regular als establiments adherits.
- **Impacte:** Moderat. Aporta beneficis econòmics i de benestar importants als barris participants.

### 5. Privacitat i protecció de dades (Risc / Oportunitat):
- **Freqüència:** Ocasional. Un ciberatac o un mal ús comercial no passa cada dia, però és una amenaça real en aplicacions de geolocalització.
- **Impacte:** Catastròfic. Una filtració de dades d'ubicació afectaria milers de ciutadans, comportaria sancions legals greus (RGPD) i provocaria l'abandonament immediat de l'app.

### 6. Transparència en els càlculs i responsabilitat legal (Risc):
- **Freqüència:** Possible. És probable que l'algoritme recomani alguna via en obres o poc il·luminada si no s'actualitza sovint, o que es qüestionin les xifres d'emissions.
- **Impacte:** Major. Pot provocar accidents de trànsit als usuaris (ciclistes o vianants) i pèrdua de confiança institucional.

## 5. Selecció dels riscos i les oportunitats prioritaris amb les mesures proposades.
### Risc prioritari seleccionat: Vulneració de la privacitat i filtració de dades d'ubicació (Governança)
**Per què l'hem escollit:** Tot i que la seva freqüència és ocasional, el seu impacte seria catastròfic. L'aplicació registra rutines diàries en segon pla (on viu, treballa o compra cada persona) i ja existeix preocupació social sobre qui consultarà aquestes dades i com s'utilitzaran amb futurs patrocinadors.

**Mesures per evitar-lo o reduir-ne les conseqüències:**
1. Aplicar la anonimització i agregació de dades des del moment de la recollida, de manera que ni l'Ajuntament ni els comerços patrocinadors puguin identificar persones individuals.
2. Establir un termini màxim de conservació de l'historial de trajectes (per exemple, esborrar les dades brutes cada 30 dies) i complir estrictament el Reglament General de Protecció de Dades (RGPD).
3. Permetre que l'usuari activi o desactivi el seguiment en segon pla manualment i signar un contracte clar de responsabilitat civil i ciberseguretat entre l'Ajuntament i l'empresa tecnològica.
### Oportunitat prioritària seleccionada: Reducció d'emissions de $CO_2$ i millora de la mobilitat urbana (Ambiental) 
**Per què l'hem escollit:** És l'objectiu central del projecte i presenta la freqüència i l'impacte positiu més alts. Transformar els desplaçaments curts en cotxe per rutes a peu, en bici o en transport públic té un efecte directe i mesurable en la descarbonització i la qualitat de vida de la ciutat.

**Mesures per aprofitar-la o augmentar-ne els beneficis:**
1. Integrar dades en temps real dels operadors de transport públic i carrils bici per oferir rutes intermodals molt precises i ràpides.
2. Crear reptes comunitaris per barris o centres educatius per multiplicar l'efecte de la gamificació.
3. Utilitzar els mapes de calor anonimitzats perquè l'Ajuntament construeixi nous carrils bici i aparcaments just als punts on es detecti més demanda real.

## 6. Canvis que s’introduiran en el projecte després de l’anàlisi.
Després de fer l'anàlisi ASG, introduirem les següents millores en el disseny inicial del projecte perquè sigui més sostenible, inclusiu i responsable:

**1. Accessibilitat universal des de la versió 1.0:** Incorporar lectura de pantalla per a persones amb discapacitat visual, interfícies d'alt contrast i un filtre específic per recomanar rutes 100 % accessibles (sense escales ni voreres estretes) per a persones amb mobilitat reduïda.

**2. Inclusió contra la bretxa digital:** Crear una targeta física vinculada al carnet municipal o biblioteca per a la gent gran o persones sense telèfon intel·ligent, permetent-los acumular punts sostenibles en validar el transport públic o comprar al comerç local.

**3. Auditoria independent i transparència algorítmica:** Publicar obertament la metodologia científica utilitzada per calcular l'estalvi de $CO_2$ i encarregar a una universitat o entitat ambiental externa la verificació anual dels informes.

**4. Protocol de seguretat viària i responsabilitat clara:** Definir legalment que l'empresa tecnològica i l'Ajuntament corresponen a la gestió de dades i la seguretat de les rutes, afegint un botó d'avís ciutadà dins l'app per reportar carrers insegurs, mal il·luminats o en obres en temps real.

**5. Model de patrocini ètic:** Establir que els comerços patrocinadors només rebran informes estadístics generals per barris (mai dades personals) i prioritzar l'adhesió de comerços locals sostenibles (mercats municipals, botigues de proximitat, tallers de bicicletes).

## 7. Les fonts d’informació consultades.
- https://eur-lex.europa.eu/legal-content/ES/TXT/?uri=CELEX%3A32016R0679
- https://web.gencat.cat/ca/generalitat/accio-govern/transformacio-administracio/accessibilitat-digital
- https://www.miteco.gob.es/es/cambio-climatico/temas/mitigacion-politicas-y-medidas/calculadoras.html
- https://www.globalreporting.org/standards/
