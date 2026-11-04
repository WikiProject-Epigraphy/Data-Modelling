
# Matching Wikidata to EAGLE (EDR)

| Fields label in EDR.it | Fields label in EDR (csv) | Wikidata Property |
| --- | --- | --- |
| Urbs antiqua | fo_antik | [P1071](https://www.wikidata.org/wiki/Property:P1071) |
| Rerum inscriptarum distributio | denkmaltyp | [P31](https://www.wikidata.org/wiki/Property:P31) = type of artefact |
| Locus inventionis | fundstelle | [P189](https://www.wikidata.org/wiki/Property:P189) |
| Locus adservationis | aufbewahrung | [P195](https://www.wikidata.org/wiki/Property:P195) with qualifier [P217](https://www.wikidata.org/wiki/Property:P217) |
| Rei materia | material | [P186](https://www.wikidata.org/wiki/Property:P186) |
| Mensurae | mis_alto, mis_largo, mis_spess, mis_lettere | [P2048](https://www.wikidata.org/wiki/Property:P2048), [P2049](https://www.wikidata.org/wiki/Property:P2049), [P5524](https://www.wikidata.org/wiki/Property:P5524), [P12549](https://www.wikidata.org/wiki/Property:P12549); with qualifiers for value ranges ([P2313](https://www.wikidata.org/wiki/Property:P2313) and [P2312](https://www.wikidata.org/wiki/Property:P2312)) |
| Lingua | lingua | [P407](https://www.wikidata.org/wiki/Property:P407) = [Q397](https://www.wikidata.org/wiki/Q397) |
| */* | */* | [P282](https://www.wikidata.org/wiki/Property:P282): [Q8229](https://www.wikidata.org/wiki/Q8229) o [Q8216](https://www.wikidata.org/wiki/Q8216) (absent in EDR, to be deduced from the language) |
| Titulorum distributio | i_gattung | [P31](https://www.wikidata.org/wiki/Property:P31) = type of inscription |
| Virorum distributio | livellosocialeTot | *[P3716](https://www.wikidata.org/wiki/Property:P3716) (not to be imported and added in persons)* |
| Status tituli | status_tituli | [P12020](https://www.wikidata.org/wiki/Property:P12020) |
| Religio | religio | [P140](https://www.wikidata.org/wiki/Property:P140) |
| ID EDR | id_nr | [P12495](https://www.wikidata.org/wiki/Property:P12495) |
| ID CIL | Bibliografia | <br>[P195](https://www.wikidata.org/wiki/Property:P195) = [Q691007](https://www.wikidata.org/wiki/Q691007) with qualifier [P217](https://www.wikidata.org/wiki/Property:P217) |
| EDCS | Bibliografia | [P11656](https://www.wikidata.org/wiki/Property:P11656) |
| EDH | Bibliografia | [P11273](https://www.wikidata.org/wiki/Property:P11273) |
| TM | Bibliografia | [P8532](https://www.wikidata.org/wiki/Property:P8532) |
| lupa.at | Bibliografia | *to be created* |
| arachne | Bibliografia | [P10510](https://www.wikidata.org/wiki/Property:P10510) |
| Textus | testo_epigr | [P1684](https://www.wikidata.org/wiki/Property:P1684) (with possible addition of qualifier [P7008](https://www.wikidata.org/wiki/Property:P7008)); both have a limit of 1500 characters |
| Editiones | Bibliografia | To be inserted [P195](https://www.wikidata.org/wiki/Property:P195) = [Q691007](https://www.wikidata.org/wiki/Q691007) with qualifier [P217](https://www.wikidata.org/wiki/Property:P217) |
| Tempus | dat_jahr_a, dat_jahr_e | [P571](https://www.wikidata.org/wiki/Property:P571) with start ([P1319](https://www.wikidata.org/wiki/Property:P1319)) and end ([P1326](https://www.wikidata.org/wiki/Property:P1326)) interval qualifiers - cf. [Help:Dates](https://www.wikidata.org/wiki/Help:Dates)\|- |
| Media | / | [P18](https://www.wikidata.org/wiki/Property:P18) after importing images from EDR to Wikimedia Commons |
| Scriptura | scriptura | [P12876](https://www.wikidata.org/wiki/Property:P12876) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| cinerarium | [Q960844](https://www.wikidata.org/wiki/Q960844) |
| stela | [Q178743](https://www.wikidata.org/wiki/Q178743) |
| [clipeus](https://www.eagle-network.eu/voc/objtyp/lod/94.html) | [Q1101789](https://www.wikidata.org/wiki/Q1101789) |
| tabula | [Q27624922](https://www.wikidata.org/wiki/Q27624922) |
| cippus | [Q1752223](https://www.wikidata.org/wiki/Q1752223) |
| cippus, terminus | [Q921099](https://www.wikidata.org/wiki/Q921099) |
| ara (- sepulcrum) | [Q19702902](https://www.wikidata.org/wiki/Q19702902) |
| ara + sepulcrum | [Q98929156](https://www.wikidata.org/wiki/Q98929156) |
| basis | [Q12014132](https://www.wikidata.org/wiki/Q12014132) |
| statua | [Q179700](https://www.wikidata.org/wiki/Q179700) |
| sarcophagus | [Q48634](https://www.wikidata.org/wiki/Q48634) |
| operculum (+ cinerarium) | [Q2488579](https://www.wikidata.org/wiki/Q2488579) + qualificatore [P642](https://www.wikidata.org/wiki/Property:P642) = [Q960844](https://www.wikidata.org/wiki/Q960844) |
| operculum (+ sarcophagus) | [Q2488579](https://www.wikidata.org/wiki/Q2488579) + qualificatore [P642](https://www.wikidata.org/wiki/Property:P642) = [Q48634](https://www.wikidata.org/wiki/Q48634) |
| pavimentum | [Q125225990](https://www.wikidata.org/wiki/Q125225990) |
| miliarium | [Q13360570](https://www.wikidata.org/wiki/Q13360570) |
| parallelepipedum | [Q63917312](https://www.wikidata.org/wiki/Q63917312) |
| epistylium | [Q183448](https://www.wikidata.org/wiki/Q183448) |
| fragmentum | [Q11086567](https://www.wikidata.org/wiki/Q11086567) |
| later | [Q40089](https://www.wikidata.org/wiki/Q40089) |
| vas | [Q191851](https://www.wikidata.org/wiki/Q191851) |
| ollarium | [Q125316718](https://www.wikidata.org/wiki/Q125316718) |
| aedicula | [Q507286](https://www.wikidata.org/wiki/Q507286) |
| defixio | [Q1430557](https://www.wikidata.org/wiki/Q1430557) |
| *ignoratur* | [Q111326612](https://www.wikidata.org/wiki/Q111326612) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| honorarius | [Q125323109](https://www.wikidata.org/wiki/Q125323109) |
| oper. publ. priv.que | [Q90766967](https://www.wikidata.org/wiki/Q90766967) |
| sacer | [Q125323760](https://www.wikidata.org/wiki/Q125323760) |
| sacer formula | *dubbio* |
| sepulcralis | [Q121614747](https://www.wikidata.org/wiki/Q121614747) |
| term. non sep. | [Q125323565](https://www.wikidata.org/wiki/Q125323565) |
| term. non sep. honorarius | *dubbio* |
| *ignoratur* | [Q1640824](https://www.wikidata.org/wiki/Q1640824) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| aes | [Q34095](https://www.wikidata.org/wiki/Q34095) oppure [Q753](https://www.wikidata.org/wiki/Q753) |
| alabaster | [Q143447](https://www.wikidata.org/wiki/Q143447) |
| os | [Q265868](https://www.wikidata.org/wiki/Q265868) |
| creta | [Q45621](https://www.wikidata.org/wiki/Q45621) oppure [Q1377111](https://www.wikidata.org/wiki/Q1377111) |
| lapis | [Q22731](https://www.wikidata.org/wiki/Q22731) |
| lapis calcar | [Q23757](https://www.wikidata.org/wiki/Q23757) |
| lapis calcar aurisina | [Q48809314](https://www.wikidata.org/wiki/Q48809314) |
| lapis trach. euganea | [Q3997130](https://www.wikidata.org/wiki/Q3997130) |
| lapis, trachite | [Q332748](https://www.wikidata.org/wiki/Q332748) |
| marmor | [Q40861](https://www.wikidata.org/wiki/Q40861) |
| marmor rosso di Verona | [Q928240](https://www.wikidata.org/wiki/Q928240) |
| musivum | [Q2484793](https://www.wikidata.org/wiki/Q2484793) |
| plumbum | [Q708](https://www.wikidata.org/wiki/Q708) |
| lapis molassa | [Q304080](https://www.wikidata.org/wiki/Q304080) |
| vitrum | [Q11469](https://www.wikidata.org/wiki/Q11469) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| Pagana | [Q29536](https://www.wikidata.org/wiki/Q29536) |
| Christiana | [Q5043](https://www.wikidata.org/wiki/Q5043) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| caelo | [Q20557963](https://www.wikidata.org/wiki/Q20557963) |
| litt. ex forma | [Q125418677](https://www.wikidata.org/wiki/Q125418677) |
| litt. scariph. | [Q125653002](https://www.wikidata.org/wiki/Q125653002) |
| punctim | [Q125418266](https://www.wikidata.org/wiki/Q125418266) |
| scalpro | [Q125418433](https://www.wikidata.org/wiki/Q125418433) |
| scalpro solco profondo | [Q125418433](https://www.wikidata.org/wiki/Q125418433) + qualificatore [P1552](https://www.wikidata.org/wiki/Property:P1552) = [Q3250078](https://www.wikidata.org/wiki/Q3250078) |
| tessellis | [Q133067](https://www.wikidata.org/wiki/Q133067) |

| Value name in EDR (csv) | Wikidata item |
| --- | --- |
| tit. integer | [Q122238694](https://www.wikidata.org/wiki/Q122238694) |
| tit. mutilus | [Q122238702](https://www.wikidata.org/wiki/Q122238702) |
| tit. fragmentum | [Q122238708](https://www.wikidata.org/wiki/Q122238708) |
