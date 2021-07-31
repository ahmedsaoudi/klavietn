# Zid el klavie et Tunsi l Ubuntu 20.04

El ktiba bet Tunsi testħaq klavie fih el ħuruf ellezma, khasatan el 'Ħ' wel 'Ɛ'. Hadheka
εlech 5demt εal klavie hedha. 

El klavie mjarreb εal Ubuntu 20.04, ama mafamech εlech bech mayemchich mεa el OSet eli
kharjin mel Ubuntu wala εal versionet lokhrin mteε el OS. 

## Chnawa fih el klavie hedha? 

Hedha klavie AZERTY, kima el klaviet el AZERTY lkol. Fih ħajtin bark mbadlin: zedneh el
'Ħ' wel 'Ɛ'.

Ki tenstali el klavie (chuf elluta bech taεref kifech), haw kifech tektebhom: 
 - ε: `Alt Gr` + `e`
 - Ɛ: `Alt Gr` + `Shift` + `e`
 - ħ: `Alt Gr` + `h`
 - Ħ: `Alt Gr` + `Shift` + `h`

## El instalasion

Bech tzid el klavie et Tunsi, lezmek: 
 1. Et telicharji el ficha `tn`;
 2. T'hez thot'ha fi ed dusi `/usr/share/X11/xkb/symbols/`; 
 3. Fel ficha `/usr/share/X11/xkb/rules/evdev.xml`, zid el kod hedha baεd ay
    `</layout>`:
    ```
      <layout>
         <configItem>
           <name>tn</name>
           <shortDescription>tn</shortDescription>
           <description>Tunisian</description>
           <languageList>
             <iso639Id>aeb</iso639Id>
           </languageList>
         </configItem>
         <variantList/>
      </layout>
    ```

 4. Hakka el klavie tzed fel system. Tawa bech ennajmu nektbu bih, lezem yetaktiva fel
    reglaj mteε el Ubuntu. (Fi "Region & Language", neklikiew εle el '+' fi ekher "Input
    Sources", mbaεed εle "Other" w ghadi nalqaw "Tunisian");
 5. Idha ken el klavie mazel mahuch maħloul, aεmel refresh lil Gnome (`Alt` + 'F2',
    mbaεed ekteb 'r' wenzel εal entre.);
