# bonlp-datasets 
Training data for Tibetan nlp.

# IE (Information Extraction)
## IE Annotated Data (dir/tags)
གཞུང་ཚན་སོ་སོའི་ནང་རྟགས་གང་བརྒྱབ་པ་དེ་ཡིན།
- `/dudra/`
  - `(A <མཚོན་བྱ།>)` what is defined - (Bབློའི་ཡུལ་དུ་བྱ་རུང་)(Aཤེས་བྱ)འི་མཚན་ཉིད། མཚན་གཞི་(Aབུམ་པ)་ལྟ་བུ།
  - `(B <མཚན་ཉིད།>)` definition
  - `(C <མཚན་གཞི།>)` instance
  - `(D <དབྱེ་གཞི།>)` what is enumerated - (Dསྒྲ་ལ་བརྗོད་བྱེད་ཀྱི་སྒྲའི་སྒོས་)དབྱེ་ན་གཉིས་ཡོད་དེ། (Eསེམས་ཅན་ལ་སྟོན་པའི་སྒྲ་དང་། སེམས་ཅན་ལ་མི་སྟོན་པའི་སྒྲ་)གཉིས་ཡོད་པའི་ཕྱིར།
  - `(E <དབྱེ་བ།>)` enumeration
  - `(H <ལུང་ཁུངས།>)` source - (Hམངོན་རྟོགས་རྒྱན་ལས།) (Gའགྲོ་ལ་ཕན་པར་བྱེད་རྣམས་ལམ་ཤེས་ཉིད་ཀྱིས་འཇིག་རྟེན་དོན་སྒྲུབ་མཛད་པ་གང་)ཞེས་གསུངས་པ་ཡིན་པའི་ཕྱིར།
  - `(G <ལུང་ཚིག>)` citation
  - `(I <མཛད་བྱང་།>)` colophon - (I བཤད་སྒྲུབ་བསྟན་པའི་འབྱུང་གནས་དཔལ་ལྡན་བཀྲ་ཤིས་འཁྱིལ་དུ་རབ་བྱུང་བཅུ་བཞི་པའི་ལྕགས་སྤྲེལ་གྱི་ལོར་པར་དུ་བསྐྲུན་པ་དགེ་ལེགས་འཕེལ།  སརྦ་མངྒ་ལཾ། །)
  - `(K <མཚན་བྱང་།>)` title - (K བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པ་བཞུགས་སོ།།)
- `/explanations/`
  - `o <འགྲེལ་གཞི།>` what is explained - (oདལ་བ་)ཞེས་བྱ་བ་ནི་(o** མི་ཁོམ་པ་ལས་ལོག་པ་སྟེ། འདིར་ནི་སྡོམ་པ་འཆགས་པ་ལ་དལ་བ་ཞེས་བྱའོ། །)
  - `o* <འགྲེལ་བཤད།>` explanation - (oརི་བོ་)ནི་(o*ས་འཛིན་ནོ། །)
  - `o** <སྐབས་བསྟུན་འགྲེལ་བཤད།>` context-specific explanation - (oདལ་བ་)ཞེས་བྱ་བ་ནི་(o** མི་ཁོམ་པ་ལས་ལོག་པ་སྟེ། འདིར་ནི་སྡོམ་པ་འཆགས་པ་ལ་དལ་བ་ཞེས་བྱའོ། །)
- `/grammar/`
  - `(A <མཚོན་བྱ།>)` what is defined- (Bརྣམ་དབྱེའི་རྐྱེན་ནམ་ཕྲད་ཀྱི་རྩ་བ་གི་ཀྱི་གྱི་ཡི་འི་ལྔ་པོ་སྦྱོར་ཡུལ་དེས་ལས་སམ་བྱ་བའི་ཡུལ་ལ་བྱ་བ་གཏན་ནས་མི་བྱེད་པར་མིང་ཚིག་སྔ་ཕྱི་གཉིས་འབྲེལ་བྱེད་ཙམ་སྟོན་པར་འཇུག་པ་)ནི་(Aརྣམ་དབྱེ་དྲུག་པ་འབྲེལ་སྒྲ་)ཞེས་བྱ། 
  - `(B <མཚན་ཉིད།>)` definition
  - `(o <འགྲེལ་གཞི།>)` what is explained -  (Oརྣམ་དབྱེ་གསུམ་པ་བྱེད་སྒྲ་ཞེས་བྱ་)སྟེ། (O*སྔར་བཤད་པའི། གི ཀྱི། གྱི། འི། ཡི་ལྔ་པོ་དེ་རྣམས་ལ་རྗེས་འཇུག་ས་ཡིག་སྦྱར་བའི་ས་མཐའ་ཅན་གིས་དང༌། ཀྱིས་དང༌། གྱིས་དང༌། འིས་དང༌། ཡིས་ལྔ་ནི་བྱ་བ་ལ་སྦྱོར་བར་སྟོན་པས་)
  - `(o* <འགྲེལ་བཤད།>)` explanation
  - `(D <དབྱེ་གཞི།>)` what is enumerated - (Dསྔོན་འཇུག་ལྔ་)སྟེ། (Eག་ད་བ་མ་འ་བཅས་ལྔ་)དང༌། 
  - `(E <དབྱེ་བ།>)` enumeration
  - `(H <ལུང་ཁུངས།>)` source - (Hངག་སྒྲོན་)དུ།(Gབརྗོད་དོན་ཀཱ་ལི་སུམ་ཅུ་ལ། །རྐྱང་པ་འཕུལ་དང་མགོ་ཅན་དང༌། །དབྱངས་ལྔ་ཡ་ར་ལ་ཝའི་འདོགས། །རྗེས་འཇུག་དཔེ་སོགས་རིམ་པས་བསྟན། །) ཞེས་གསུངས།
  - `(G <ལུང་ཚིག>)` citation
  - `(N <གོ་བྱ།>)` what is explained - (Nམཐའ་མེད་)ཅེས་པ་ནི། (N*རྗེས་འཇུག་མེད་པའི་ཡི་གེ་ལ་ཟེར།) དཔེར་ན། (N** མཐོ། གྲི། དྲི། བརྒྱ། མཐུ་སོགས་)
  - `(N* <གོ་དོན།>)` meaning
  - `(N** <དཔེར་བརྗོད།>)` example 
  - `(Q <ས་བཅད།>)` outline - (Qགཉིས་པ་བྱེད་པ་པོའི་སྒྲ་བཤད་པ་ལ་གཉིས། རྩ་བ་དང༌། འགྲེལ་པའོ། །)
  - `(R <ངོས་འཛིན་བྱ།>)` what is identified (Rལ་ཞེས་བྱ་བ་)ནི་(R*བདུན་པ་གནས་གཞིའི་སྒྲའོ། །)
  - `(R* <ངོས་འཛིན་བྱེད།>)` identification 
  - `(P <འཇུག་ཡུལ།>)` agreement female (P*དེ་ཞེས་གྲུབ་པ་དེ་ནི། དོན་དགུ་ལ་འཇུག་)སྟེ། (Pཐ་སྙད་ཀྱི་དབང་དུ་བྱས་པ་གསུམ་ལ་འཇུག་ཅིང་། དངོས་པོའ་ིདབང་གིས་བཞི་རུ་འཇུག་པར་འགྱུར་ལ། དུས་ཀྱི་དབང་གིས་གཉིས་ལ་འཇུག་པ་)ཡིན་པའི་ཕྱིར་རོ། །
  - `(P* <འཇུག་བྱ>)` agreement male 
  - `(K <མཚན་བྱང་།>)` title (Kཔྲ་ཏི་རིན་ཆེན་དོན་གྲུབ་ཀྱི་སུམ་རྟགས་དགོངས་འགྲེལ་བཞུགས་སོ། །སུམ་ཅུ་པའི་རྣམ་བཤད་ཀུན་བཟང་དགོངས་རྒྱན།)
  - `(I < མཛད་བྱང་།>)` authorship statement  (Iཅེས་པཎྜི་ཏ་ཆེན་པོ་པྲ་ཏི་དགེ་བཤེས་རིན་ཆེན་དོན་གྲུབ་ཀྱིས་མཛད་པའི་སུམ་ཅུ་པའི་དགོངས་འགྲེལ་འདི་ཉིད་འགྲེལ་བ་གཞན་ལས་ཁྱད་པར་དུ་འཕགས་པར་ཀུན་མཁྱེན་འཇིགས་མེད་དབང་པོ་སོགས་སྔོན་དུས་ཀྱི་མཁས་པ་དུ་མས་བཞེད་འདུག་གཤིས། རྩ་བ་དང་བརྒྱུད་པའི་བླ་མ་དམ་པ་རྣམས་ཀྱི་བཞེད་དགོངས་རྫོགས་ཕྱིར་གང་ཅིའི་ཆ་རྐྱེན་སྦྱར་ཏེ་པར་ཡིག་པ་སྔགས་འཆང་པདྨ་ཐར་དང་། ཞུས་དག་པ་གསེར་ལག་བྱ་བཏང་འཇམ་དབྱངས་རྒྱ་མཚོ། རྐོ་མཁན་སྡེ་དགེའི་བཀྲ་ཤིས་དང་བུ་རྒྱལ་རྣམས་ཀྱིས་ལྕགས་ཁྱི་ལོར་པར་དུ་བསྒྲུབས་པའི་དགེ་བསྔོའ་ིསྨོན་ཚིག་ཏུ་གྱི་ན་པ་དགེ་འདུན་བསྟན་འཛིན་རྒྱ་མཚོས་བྲིས་པའོ། །། །)
- `/རྣམ་གྲངས། enumeration/`
  - `(D <དབྱེ་གཞི།>)` what is enumerated - (Dརྒྱལ་པོ་བྱང་ཆུབ་སེམས་དཔའི་རྩ་ལྟུང་ལྔ་)ནི། (Eདཀོན་མཆོག་གསུམ་གྱི་དཀོར་འཕྲོག་པ་དང༌། ངེས་འབྱུང་གི་ཆོས་སྤང་བ་དང༌། རབ་ཏུ་བྱུང་བ་ལ་ཆད་པ་གཅོད་པ་དང༌། མཚམས་མེད་ཀྱི་ལས་བྱེད་པ་དང༌། ལོག་ལྟས་དགེ་བཅུ་སྤང་བ)འོ། །
  - `(E <དབྱེ་བ།>)` enumeration
- `/མཚན་ཉིད། definition/`
  - `(A <མཚོན་བྱ།>)` what is defined - (Aའབྲས་བུ་ཆོས་ཀྱི་སྐུ་)ལ་གསུམ་ལས། མཚན་ཉིད་ནི་(Bམི་མཐུན་ཕྱོགས་སྤོང་བ་དང༌། ཡོན་ཏན་མངོན་དུ་བྱེད་པའི་རྣལ་འབྱོར་གཉིས་མཐར་ཐུག་པའི་སྟོབས་ཀྱིས་ཐོབ་པའི་རྣམ་སྨིན་)ནོ། །
མཚན་གཞི་ནི། (Cསྒྲིབ་གཉིས་བག་ཆགས་དང་བཅས་པ་མ་ལུས་པར་སྤངས་པས་ཁྱད་པར་དུ་བྱས་པའི་ཡེ་ཤེས་ཀྱི་སྐུ)འོ། །
  - `(B <མཚན་ཉིད།>)` definition
  - `(C <མཚན་གཞི།>)` instance
- `/གོ་དོན། meaning/`
  - `(N <གོ་བྱ།>)` what is explained - གཉིས་པ་(Nཆགས་བྲལ་སྔོན་སོང་)གི་གོ་དོན་ནི། (N*རང་གི་ཐོབ་བྱའི་འབྲས་བུ་དེ་སྒྲིབ་བྱེད་ཀྱི་སྒྲིབ་པ་གང་ཡིན་པ་དེ་ལ་མཐོང་ལམ་གྱི་སྔ་རོལ་དུ་ཆགས་པ་དང་བྲལ་བའི་རིགས་སུ་གནས་པ་)དེ་ནི་ཆགས་བྲལ་སྔོན་སོང་ཞེས་བྱ་ལ།
  - `(N* <གོ་དོན།>)` meaning
- `/འགྲེལ་བཤད། explanation/`
  - `(o <འགྲེལ་གཞི།>)` what is explained - མདོར་ན་(Oའཁོར་བ་དང་མྱང་འདས་)ཞེས་བྱ་བ་ནི་(O*ཀུན་རྫོབ་སྣང་ཙམ་གྱི་ངོ་ནས་བཞག་ཅིང་དེ་གཉིས་ཀའི་རང་བཞིན་སྤྲོས་བྲལ་འོད་གསལ་དེ་ལ་བདེ་གཤེགས་སྙིང་པོ་ཞེས་གསུངས་པས་ངེས་པའི་དོན་དུ་སྣང་ཙམ་དང་དེ་ཡི་རང་བཞིན་ཡང་སོ་སོར་དབྱེ་རྒྱུ་མེད་དེ་མེ་དང་ཚ་བ་ལྟ་བུ)འོ། །
  - `(o* <འགྲེལ་བཤད།>)` explanation
- `/སྒྲ་བཤད། word part explanation/`
  - `(L <སྒྲ་གཞི>)` what is explained - (Lདུར་ཁྲོད་)ཀྱི་སྒྲ་བཤད་ལ། (Fདུར་ཆོས་ཉིད་དང་། ཁྲོད་དེ་རྟོགས་པའི་ཡེ་ཤེས་)ལ་བྱས་པའི་བཤད་པ་ཡོད་པས།
  - `(F <སྒྲ་བཤད།>)` word part explanation - 

  
  
  - `(humanrdr/` 
  - `lighttag/` 
  - `soas-segmentation/`
  - `soas-segmentation-biluo/`
 
## IE Temporary Tags

| བོད། bo                    | ཨིན། en                       | རྟགས། tag        | མཆན། note                          |   |
|---------------------------|------------------------------|-----------------|------------------------------------|---|
| མཚོན་བྱ།                    | what is defined              | (A .......)     |                                    |   |
| མཚན་ཉིད།                   | definition                   | (B .......)     |                                    |   |
| མཚན་གཞི།                   | instance                     | (C .......)     |                                    |   |
| དབྱེ་གཞི།                    | what is enumerated           | (D .......)     |                                    |   |
| དབྱེ་བ།                     | enumeration                  | (E .......)     | རྣམ་གྲངས་འདིར་བསྡུས་ཡོད།                 |   |
| སྒྲ་བཤད།                    | word part explanation        | (F .......)     |                                    |   |
| སྒྲ་གཞི།                     | what is explained            | (L .......)     |                                    |   |
| ལུང་ཚིག                     | citation                     | (G .......)     |                                    |   |
| ལུང་ཁུངས།                   | source                       | (H .......)     |                                    |   |
| མཛད་བྱང་།                  | authorship statement         | (I .......)     |                                    |   |
| བསྒྱུར་བྱང་།                  | translation statement        | (J .......)     |                                    |   |
| མཚན་བྱང་།                  | title                        | (K .......)     |                                    |   |
| མཚོན་བྱ་ཡིན་ལ་དབྱེ་གཞི་ཡང་ཡིན་པ། |                              | (AD......)      | needs to be replaced               |   |
| གོ་བྱ།                      | what is explained            | (N........)     |                                    |   |
| གོ་དོན།                     | meaning                      | (N*........)    |                                    |   |
| དཔེར་བརྗོད།                  | example                      | (N**........)   |                                    |   |
| འགྲེལ་གཞི།                   | what is explained            | (O..........)   |                                    |   |
| འགྲེལ་བཤད།                  | emplanation                  | (O*..........)  |                                    |   |
| སྐབས་བསྟུན་འགྲེལ་བཤད།          | context-specific explanation | (O**..........) |                                    |   |
| འགྲེལ་གཞི་དང་དེའི་དབྱེ་བ།        |                              | (OD.......)     | needs to be replaced               |   |
| འཇུག་ཡུལ།                   | agreement female             | (P........)     | needs a better english translation |   |
| འཇུག་བྱ།                    | agreement male               | (P*........)    | needs a better english translation |   |
| མི་འཇུག་སའི་ཡུལ།              | illegal agreement female     | (PP...)         |                                    |   |
| མི་འཇུག་ས།                  | illegal agreement male       | (PP*...)        |                                    |   |
| ས་བཅད།                    | outline                      | (Q........)     |                                    |   |
| ས་བཅད་ཀྱི་དབྱེ་གཞི།            | outline node                 | (Q*........)    |                                    |   |
| ས་བཅད་ཀྱི་ནང་གསེས།           | outline branches             | (Q**........)   |                                    |   |
| ངོས་འཛིན་བྱ།                 | what is identified           | (R.........)    |                                    |   |
| ངོས་འཛིན་བྱེད།                | identification               | (R*.........)   |                                    |   |
| རྩ་བ།                      | root text                    | (M.........)    |                                    |   |
| འགྲེལ་བ།                    | commentary                   | (M*.........)   |                                    |   |



# Word Segmentation
Human correction of the segmentation of the SOAS corpus. 

## མིང་ཚིག་གཅོད་མཚམས་ཀྱི་རྣམ་གཞག

- **ཐ་སྙད་སོར་འཇོག** དཔེར་ན། མེ་ཏོག་སེར་ཆེན་ལྟ་བུའི་ཚིག་ཡོངས་གྲགས་ཀྱི་ཐ་སྙད་རིགས་སོར་འཇོག་བྱས་ཡོད། 
- **ཐ་སྙད་རིང་ཐུང་།** ཡོངས་གྲགས་ཀྱི་ཐ་སྙད་ཡིན་ཀྱང་ཚེག་བར་ལྔ་ལས་མང་ན་ང་ཚོས་འདིར་དུམ་བུར་གཏུབ་ཡོད། རྒྱུ་མཚན། ཀླད་ཁམས་ཚན་རིག་གི་དཔྱད་འབྲས་ལྟར། ཀློག་པ་པོར་ཀློག་བདེ་བ་དང་ཡིད་ལ་འཛིན་བདེ་བ་སོགས་ཀྱི་ཆེད། དཔེར་ན། བྱང་ཆུབ་སེམས་དཔའ་སེམས་དཔའ་ཆེན་པོ་ལྟ་བུ།
- **དགག་ཚིག** སྤྱིར་དགག་ཚིག་དང་ཚིག་གྲོགས་རིགས་མཉམ་དུ་ཡོད་ཚེ་གཏུབ་དགོས་མོད། ཡོངས་གྲགས་ཀྱི་ཐ་སྙད་རིགས་ཡིན་ཚེ་མཉམ་འཇོག་བྱ་དགོས། དཔེར་ན། མི་རྟག་པ། མི་མཐུན་ཕྱོགས། འདུས་མ་བྱས། མ་རིག་པ། མ་བྱིན་ལེན། མི་ཚངས་སྤྱོད། དཔག་མེད། དཔག་ཏུ་མེད། མ་འོངས་པ། ལྟ་བུའོ།།
- **བསྡུས་ཚིག** དཔེར་ན། ལྟ་སྤྱོད་ལྟ་བུའི་བསྡུས་ཚིག་རིགས་ཐ་སྙད་དམ་མིང་ཚིག་རང་སྐྱ་འཕེལ་བར་བརྩིས་ནས་གཏུབ་མེད།
- **འབྲེལ་སྒྲ།** སློབ་གྲྭ་ཆེན་མོའི་དགེ་རྒན
- **མིའི་མིང་།** དཔེར་ན། མི་འཇིགས་དབྱངས་ཅན་དགའ་བའི་བློ་གྲོས་ལྟ་བུའི་རིགས་གཅིག་གྱུར་གྱིས་ཁ་གཏོར་ཏེ་བཞག་ཡོད།
- **ས་ཆའི་མིང་།** དགའ་ལྡན་དགོན་ལྟ་བུའི་རིགས་ཀྱང་ཁ་གཏོར་ཏེ་དགའ་ལྡན་དང་དགོན་ལྟ་བུར་བཞག་ཡོད།


## གཏན་འབེབ་བྱ་ཐབས།

### གཤམ་དུ་ཨིན་ཡིག་All ཞེས་པ་དེ་ཚང་མ་མཉམ་དུ་བསྒྱུར་བཞག་པའི་དོན་ཡིན།

- **k** མིང་ཚིག་གང་ཞིག་རང་གི་ཆ་ཤས་ཀྱི་གོ་བ་མིན་པའི་གོ་བ་འཕར་མ་ལེན་རྒྱུ་ཡོད་ཚེ་་་་

### [རྣམ་པར་]དང་[རྣམ་པ][ར་]དབྱེ་བ་འབྱེད་སྟངས།
**རྣམ་པར་** ཞེས་པའི་ཚབ་ལ་ **ཡོངས་སུ་** ལྟ་བུ་འགྲོ་མིན་བརྟག་དགོས། དཔེར་ན། **རྣམ་པར་དག་པ་** ཞེས་པའི་ཚབ་ལ་ **ཡོངས་སུ་དག་པ་** ཞེས་འབྲི་ཆོག་པས་ **རྣམ་པར་** **པ** དང་རྗེས་འཇུག་ **ར་** གཉིས་ཁ་གཏོར་མི་དགོས། གཞན་ **ཕྱིའི་རྣམ་པར་བལྟ་** ཞེས་པའི་ཚབ་ལ་ **ཕྱིའི་ཡོངས་སུ་བལྟ་** ཞེས་མི་འགྲོ་བས་ཁ་གཏོར་དགོས།

**རྣམ་པར་** ཞེས་པའི་ཚབ་ལ་ **རྣམ་པ་ལ** འགྲོ་མིན་བརྟག་དགོས། དཔེར་ན། **རྣམ་པར་དག་པ་** ཞེས་པའི་ཚབ་ལ་ **རྣམ་པ་ལ་དག་པ་** ཞེས་མི་འགྲོ་བས་ **རྣམ་པར་** ཁ་གཏོར་མི་དགོས། **ཕྱིའི་རྣམ་པར་བལྟ་** ཞེས་པའི་ཚབ་ལ་ **ཕྱིའི་ཡོངས་སུ་བལྟ་** ཞེས་མི་འགྲོ་བས་ཁ་གཏོར་དགོས།


## དཀའ་ཁག་རིགས།

- སངས་རྒྱས་པ། འཚང་རྒྱ་བ། སངས་རྒྱ་བ། སངས་རྒྱས། གཏུབ་དགོས་སམ། ?ཁྱིམ་མཛེས་ནི་ཁྱིམ་མཚེས་ཀྱི་དོན།
- དགག་ཚིག་རིགས་གཅིག་མིང་ཚིག་འགྱུར་ཚར་་་་ དཔེར་ན་ མི་རྟག་པ། ཞེས་པ་ལྟ་བུ།
- [རྣམ་པར་སངས་ རྒྱས་]
- [སངས་][རྒྱས་]
- བུ་སྟོན།  5118 [མི་སློབ་ལམ] མི་སློབ་ལམ་
- བུ་སྟོན།  5296 (པཎྜི་ཏ་སུ་ནྱ་ཤྲཱི) གཏུབ་སྟངས་མ་ཤེས་སྟབས་་་་་་་རང་སོར་བཞག་ཡོད།
- བུ་སྟོན། 8287 (མ་བྱིན་ལེན་) གཏུབ་མེད།
- བུ་སྟོན། 8486 (ཕྱིན་ཅི་མ་ལོག་པ།) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 9380 (མ་ལུས་པ་)  མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 8637 (བསམ་གྱིས་མི་ཁྱབ་) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། All (མི་དགེ་བ་)
- བུ་སྟོན། all (དགེ་སློང་མ་)
- བུ་སྟོན། all (དགེ་བསྙེན་མ་)
- བུ་སྟོན། all (བླ་ན་མེད་པ་)
- བུ་སྟོན། all (ཁ་ན་མ་ཐོ་)
- མཛངསབླུན། 1749 (གདོན་མི་ཟ་བ་)
- མཛངསབླུན། (ཕྱིར་མི་ལྡོག་པ་)
- མཛངསབླུན། (ཕྱིར་མི་འོང་བ་)
- བུ་སྟོན། all (བརྗོད་དུ་མེད་པ)
- མི་ལ་རས་པ། all (མི་མ་ཡིན་)
- མི་ལ་རས་པ། all (ཕྱིན་ཅི་མ་ལོག་པ་)
- བུ་སྟོན། all (བདག་མེད་)
- བུ་སྟོན། all (ཕྱིན་ཅི་མ་ལོག་པ)
- བུ་སྟོན། all (ལུང་མ་བསྟན་)
- བུ་སྟོན། all (དངོས་མེད་)
- བུ་སྟོན། all (ཁ་ན་མ་ཐོ་བ)
- བུ་སྟོན། all
- བུ་སྟོན། all
- བུ་སྟོན། all
- བུ་སྟོན། all


- བུ་སྟོན། 9223 (དོན་རྟོགས་པ) མཉམ་དུ་བཞག་ཡོད།


- བུ་སྟོན། 8617 (རྨད་དུ་བྱུང་བ) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 9160 (བརྟེན་ནས་) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 9574 (གཏན་ལ་འབེབས་པ)
- བུ་སྟོན། 9577 (ཟིལ་གྱིས་གནོན་པ)
- མཛངས་བླུན། 113,249(མྱ་ངན་ལས་འདའ, མྱ་ངན་ལས་འདས་)
- མཛངས་བླུན། 415 (འཛམ་བུའི་གླིང་)
- མཛངསབླུན། 3125 (ཉོན་མོངས་པ་)
- བུ་སྟོན། (རྟགས་ཙམ་འཛིན་པ་)
- བུ་སྟོོན། 11111 (ཇི་ལྟ་བ་)
- བུ་སྟོན། 10995 (ཁ་ཅིག་)
- བུ་སྟོན། 10808 (འདི་དག་)
- བུ་སྟོན། 10410 (ཀུན་ཏུ་)
- བུ་སྟོན། 10077 (རབ་ཏུ་)
- བུ་སྟོན། 10107 (ཁྱད་པར་)
- བུ་སྟོན། 9328 (མདོར་ན་) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 9462 (དེ་འདྲ་)
- བུ་སྟོན། 9799 (དེས་ན་)
- བུ་སྟོན། 9542 (ཡང་ཡང་)
- བུ་སྟོན། 9044 (ལ་སོགས་པ) མཉམ་དུ་བཞག་ཡོད།
- བུ་སྟོན། 9596 (ཇི་སྙེད་པ་)
- བུ་སྟོན། 11435 (ཡང་དག་པ་)
- བུ་སྟོན། 11912 (དེ་ལྟ་ན་)
- བུ་སྟོན། 11920 (གལ་ཏེ་)
- བུ་སྟོན། 12707 (ཇི་སྐད་དུ་)
- བུ་སྟོན། 12819 (དཔེར་ན།)
- བུ་སྟོན། 12822 (ཆེད་དུ་)
- བུ་སྟོན། 12919 (དེ་ནས་)
- བུ་སྟོན། 13076 (དེ་ལ་)
- བུ་སྟོན། 13764 (དེ་ཁོ་ན་)
- བུ་སྟོན། 14302 (དེ་དག་)
- བུ་སྟོན། all (ངེས་པར་)
- བུ་སྟོན། all (དེའི་ཕྱིར་)
- བུ་སྟོན། all (དེ་བཞིན་)
- བུ་སྟོན། all (ཅི་ཡང་)
- བུ་སྟོན། all (དེ་ལྟར་)
- བུ་སྟོན། all (ཇི་ལྟར་)
- བུ་སྟོན། all (ཇི་སྐད་དུ)
- བུ་སྟོན། all (དེ་ཉིད་)
- བུ་སྟོན། all (དེ་ཡང་)
- བུ་སྟོན། all (ཅིའི་ཕྱིར་)
- བུ་སྟོན། all (ཅི་ཞིག་)
- བུ་སྟོན། all (རྟག་ཏུ་)
- བུ་སྟོན། all (ནམ་ཡང་)
- བུ་སྟོན all (ཡང་ན་)
- བུ་སྟོན all (གཞན་ཡང་)
- བུ་སྟོན all (དེ་ལྟ་བུ་)
- བུ་སྟོན all (འདི་ལྟར་)
- བུ་སྟོན all (ཤིན་ཏུ་)
- བུ་སྟོན all (གང་དག་)
- བུ་སྟོན all (མི་རུང་)
- བུ་སྟོན all (འདི་ནི་)
- བུ་སྟོན all (འོན་ཀྱང་)
- བུ་སྟོན all (འོ་ན་)
- བུ་སྟོན all (ཡང་དག་པ)
- བུ་སྟོན all (དེ་སྙེད་)
- བུ་སྟོན all (ལྷན་ཅིག་)
- བུ་སྟོན all (དོན་དུ་)
- བུ་སྟོན all (འདི་ལྟ་སྟེ་)
- བུ་སྟོན all (ཅིའི་སླད་)
- བུ་སྟོན all (གང་ཕྱིར་)
- བུ་སྟོན all (སླར་ཡང་)
- བུ་སྟོན all (བར་དུ་)
- མར་པ། all (ཅིས་ཀྱང་)
- མར་པ། all (ཅི་ནས་ཀྱང་)
- མར་པ། all (ད་ལན་)
- མར་པ all (ད་རེས་)
- མར་པ། all (དྲུང་དུ་)
- མར་པ། all (འདི་དག་)
- མར་པ། all (ད་གཟོད་)
- མར་པ། all (ཇི་བཞིན་)
- མར་པ། all (ཚུལ་བཞིན་)
- མར་པ། all (ལྟ་ཅི་)
- མི་ལ་རས་པ། all (ཅི་ཕན་)
- མི་ལ་རས་པ། all (ཅི་ལྕོགས་)
- མི་ལ་རས་པ། all (ཅི་དྲག་)
- མི་ལ་རས་པ། all (གང་དྲག་)
- མི་ལ་རས་པ། all (དང་དུ་ལེན་)
- མི་ལ་རས་པ། all (གང་ཞེ་ན)
- མི་ལ་རས་པ། all (དེ་ལྟ་བས་ན་)
- བུ་སྟོན། all  (དེ་ལྟ་མོད་ཀྱི་)
- བུ་སྟོན། all (མོད་ཀྱི་)
- བུ་སྟོན།། all (དེ་བས་ན་)
- མི་ལ་རས་པ། all (ཅི་སྟེ་)
- མི་ལ་རས་པ། all (དེ་ནི་)
- མི་ལ་རས་པ། all (རེ་ཞིག་)
- མི་ལ་རས་པ། all (ཅི་མ་རུང་)
- མི་ལ་རས་པ། all (ད་ནི་)
- མི་ལ་རས་པ། all ()
- མི་ལ་རས་པ། all ()
- མི་ལ་རས་པ། all ()
- མི་ལ་རས་པ། all ()
- མི་ལ་རས་པ། all ()
- མི་ལ་རས་པ། all ()
- མཛངས་བླུན། 987 (འདི་ལྟ་བུ་)
- མཛངས་བླུན། 1050 (ཇི་ཙམ་)
- མཛངས་བླུན། 1196 (ཡོངས་སུ་)
- མཛངས་བླུན། 1416 (དེ་སྐད་)
- མཛངས་བླུན། 415 (འདི་ཉིད་)
- མཛངསབླུན། 951 (བཞིན་དུ་)
- མཛངསབླུན། 1511 (འདི་ཙམ་)
- མཛངསབླུན། 1692 (ཅི་ཙམ་)
- མཛངསབླུན། 2335 (མ་ཐག་)
- མཛངསབླུན། 2535 (མདོ་སྡེ་)
- མཛངསབླུན། 3374 (ཕྱིར་)
- མཛངསབླུན། 126 (དེའི་ཚེ་ན་)
- མཛངསབླུན། (སླད་དུ)
- མཛངསབླུན། (མྱུར་དུ་)
- མཛངསབླུན། (རླུང་ནད་)
- མཛངསབླུན། (འབའ་ཞིག་)
- མཛངསབླུན། (ཆོས་ཉིད་)
- མཛངསབླུན། (ཆེ་གེ་མོ་)
- མཛངསབླུན། (བྲེལ་ཕོངས་)
- མཛངསབླུན། (ཡིད་བཞིན་)
- མཛངསབླུན། (རྨ་ཁ་)
- མཛངསབླུན། (འོན་ཏེ་)
- མཛངསབླུན། (ཐབས་ཅིག་)
- མཛངསབླུན། (ལམ་ཀ་)
- མཛངསབླུན། (སྲང་ལམ་)
- མཛངསབླུན། (མ་རུངས་པ་)
- མཛངསབླུན། (རྡུལ་ཕྲ་མོ་)
- མཛངསབླུན། (ཟླ་མེད་པ་)
- མཛངསབླུན། (སྒོ་ང་)
- མཛངསབླུན། ()
- མཛངསབླུན། ()
- མཛངསབླུན། ()


- མཛངསབླུན། (ད་ལྟ ར)
- མཛངསབླུན། (ཞེ་སྡང་ ཁྲོ་བ)
- མཛངསབླུན། (མགོན་མེད་ ཟས་སྦྱིན་)
- མཛངསབླུན། (ཀུན་དགའ་ ར་བ་)
- མཛངསབླུན། (ར་བ་ བསྲུང་བ་)
- མཛངསབླུན། (རི་རབ་ ལྷུན་པོ་)
- མཛངསབླུན། (ཉིལ་ རྡོ་རྗེ་)
- མཛངསབླུན། (དུ་ མ་)
- མཛངསབླུན། (ཕྱུག་པ་ ནོར་དབྱུག་)
- མཛངསབླུན། (དཔྱིད་ ས་བོན་)
- མཛངསབླུན། (རྐྱེན་ སྨན་)
- མཛངསབླུན། (བཙོན་ར་ བ ས་ ཀྱང་)
- མཛངསབླུན། (མུ་སྟེགས་ཅན་ ཀུན་ཏུ་རྒྱུ་)
- མཛངསབླུན། (བང་མཛོད་ སྲུང་མི་)
- མཛངསབླུན། (འབྲོག་ ས་སྟོང་)
- མཛངསབླུན། (མཆོག་ གཙོ་བོ ར་)
- མཛངསབླུན། (རིམ་གྲོ་ བསྙེན་བཀུར་)
- མཛངསབླུན། (ཕོ་བྲང་ སླས་)
- མཛངསབླུན། (དབྱར་ དགུན་ སྟོན་ དཔྱིད་)
- མཛངསབླུན། (གནམ་ མཐའ་འོག་)
- མཛངསབླུན། (བ་གླང་ རྫིའུ་)
- མཛངསབླུན། (དགེ་སློང་ མ་)
- མཛངསབླུན། (རི་ དྲང་སྲོང་ལྷགས་)
- མཛངསབླུན། (སློབ་དཔོན་ བྲམ་ཟེ་)




## ནོར་བཅོས།
- མཛངས་བླུན། 250 མེ་ཏོག་དམ་,མེ་ཏོག་དམ་པ་
- མཛངས་བླུན། 761 ངལ་ས་,ང་ལས་ 
- མཛངས་བླུན། 925 ཐངས་པ་,ཐིངས་པ་
- མཛངས་བླུན། 1133 མྲད,རྨད་
- མཛངས་བླུན། 1498 ད་ཙམ,དེ་ཙམ་
- མཛངས་བླུན། 6558 ཁསམ་,ཁམས་
- མཛངས་བླུན། 6814 ཆེ་བཅན,ཆེ་བ་ཅན་
- མཛངས་བླུན། 9196 ཟས་གཏང་མ་,ཟས་གཙང་མ་
- མཛངས་བླུན། 9196 ཤེས་པ་ཞིག(བསྐྱར་ཟློས། སུབ་ཡོད།)
- མཛངས་བླུན། 9196 རྒྱ་མཚོར་ཞུགས་སོ,(བསྐྱར་ཟློས། སུབ་ཡོད།)
- མཛངསབླུན། 43706 འཐུབ་,འཐུང་
- མཛངསབླུན། 43764 ཚབས་,ཚ་ བ ས་
- མཛངསབླུན། 44141 སྤྱོད་བ་,སྤྱོད་པ་
- མཛངསབླུན། 44908 ལྟ་,ལྟར་
- མཛངསབླུན། 46085 ཕྲ་,བྱ་
- མཛངསབླུན། 46455 དྲག་པོ་,དྲང་པོ་
- མཛངསབླུན། 46290 རིག་བ་,རིང་ པོ ར་ ཐོགས་
- མཛངསབླུན། 47581 གསོལ་ང་,གསོལ་བ་
- མཛངསབླུན། 47781 མ་ལ་,མལ་
- མཛངསབླུན། 48219 ཞལ་ཅེ་བ་,ཞལ་ཆེ་བ་
- མཛངསབླུན། 49379 མཚང་བ་,མ་ ཚང་བ་
- མཛངསབླུན། 49950 ཚེ ར་,ཚེ་
- མཛངསབླུན། 50843 ནད་,ན་ ད་
- མཛངསབླུན། 51001 འགྲོ་,འོག་
- མཛངསབླུན། 54350 ས་བདག་,བདག་
- མཛངསབླུན། 58622 ཡི་དགས་,ཡི་དྭགས་
- མཛངསབླུན། 62371 ཡི་ དམ་ རངས་ ཏེ་,ཡིད་ མ་ རངས་ ཏེ་
- མཛངསབླུན། 72419 ཅི་སྙེད་,ཅི་སྙེད་
- མཛངསབླུན། 35746 རིང་བཞིན་,རང་བཞིན་
- མཛངསབླུན། ()
- མཛངསབླུན། ()
- མཛངསབླུན། ()
- མཛངསབླུན། ()
- མཛངསབླུན། ()


