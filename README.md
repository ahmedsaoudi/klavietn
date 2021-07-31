# Zid el klavie et Tunsi l Ubuntu 20.04

El ktiba bet Tunsi testħaq klavie fih el ħuruf ellezma, khasatan el 'Ħ' wel 'Ɛ'. Hadheka
εlech 5demt εal klavie hedha. 

El Klavie hedha maεmul bech ytabeq el qawaεed elli mawjudin εala
[tunsi.tn](https://tunsi.tn).

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

Haw el klavie chnawa fih:

 ```
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│ ³ ¸ │ 1 ̨  │ 2 É │ 3 ˘ │ 4 — │ 5 – │ 6 ‑ │ 7 È │ 8 ™ │ 9 Ç │ 0 À │ ° ≠ │ + ± ┃ ⌫       ┃
│ ² ¹ │ & ˇ │ é ~ │ " # │ ' { │ ( [ │ - | │ è ` │ _ \ │ ç ^ │ à @ │ ) ] │ = } ┃         ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃ A Æ │ Z Â │ E Ɛ │ R Ê │ T Þ │ Y Ÿ │ U Û │ I Î │ O Œ │ P Ô │ ¨ ˚ │ £ Ø ┃       ┃
┃Tab ↹  ┃ a æ │ z â │ e ε │ r ê │ t þ │ y ÿ │ u û │ i î │ o œ │ p ô │ ^ ~ │ $ ø ┃   ⏎   ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃ Q Ä │ S „ │ D Ë │ F ‚ │ G ¥ │ H Ħ │ J Ü │ K Ï │ L Ŀ │ M Ö │ % Ù │ µ ̄  ┃      ┃
┃Maj ⇬   ┃ q ä │ s ß │ d ë │ f ‘ │ g ’ │ h ħ │ j ü │ k ï │ l ŀ │ m ö │ ù ' │ * ` ┃      ┃
┣━━━━━━━┳┹────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┷━━━━━┻━━━━━━┫
┃       ┃ > ≥ │ W “ │ X ” │ C ® │ V ← │ B ↑ │ N → │ ? … │ . . │ / ∕ │ § − ┃             ┃
┃Shift ⇧┃ < ≤ │ w « │ x » │ c © │ v ⍽ │ b ↓ │ n ¬ │ , ¿ │ ; × │ : ÷ │ ! ¡ ┃Shift ⇧      ┃
┣━━━━━━━╋━━━━━┷━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴───┲━┷━━━━━╈━━━━━┻━┳━━━━━━━┳━━━┛
┃       ┃       ┃       ┃ ␣                               ⍽ ┃       ┃       ┃       ┃
┃Ctrl   ┃Meta   ┃Alt    ┃ ␣ Space                         ⍽ ┃AltGr ⇮┃Menu   ┃Ctrl   ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━━━━┛
 ```

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
