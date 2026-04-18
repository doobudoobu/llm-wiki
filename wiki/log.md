# Wiki Log

Append-only chronological record of all wiki operations.

Parse with: `grep "^## \[" wiki/log.md | tail -10`

---

## [2026-04-16] init | Wiki initialized

- Created directory structure: `raw/`, `wiki/`
- Created `CLAUDE.md` with schema and conventions
- Created `wiki/index.md` and `wiki/log.md`
- Created `wiki/overview.md`
- Wiki is empty — ready for first ingest

## [2026-04-16] ingest | Keay, *China: A History* — Chapters 1–3 (pre-history to 210 BC)

- Source: `raw/China_A_History_-_John_Keay.epub` → converted to `.txt` via Calibre
- Chapters covered: 1 ("Rites to Writing," pre-c. 1050 BC), 2 ("Sages and Heroes," c. 1050–250 BC), 3 ("The First Empire," c. 250–210 BC)
- Summary page: [[src-keay-china-ch1-3]]
- Pages created: [[dynasty-xia]], [[dynasty-shang]], [[dynasty-zhou]], [[dynasty-qin]], [[figure-confucius]], [[figure-qin-shi-huangdi]], [[concept-mandate-of-heaven]], [[concept-oracle-bones]]
- Pages updated: [[overview]], [[timeline]], [[index]]
- Most interesting new details:
  - The oracle bones were discovered in 1899 when a scholar noticed archaic writing on "dragon bones" being sold as malaria medicine in a Beijing pharmacy
  - The Mandate of Heaven appears to be a Zhou invention — the Shang's oracle bones barely mention "Heaven" at all; their supreme deity was the personal Di
  - The Tarim Mummies (Xinjiang, ~2000 BC): DNA-certified Caucasoid people in Celtic-weave tartan, politically explosive today as Uighur separatists use them to contest Beijing's historical claim to Xinjiang
  - Sima Qian wrote extensively about the First Emperor's tomb but never mentioned the terracotta army — discovered by well-diggers in 1974
  - The Stone Cattle Road story: Qin tricked the king of Shu into requesting a road (by staging fake gold-dunging stone cows), built it, then used it for invasion

## [2026-04-16] ingest | Keay, *China: A History* — Chapters 4–6 (210 BC – AD 189)

- Source: `raw/China_A_History_-_John_Keay.txt` (lines ~1466–2136)
- Chapters covered: 4 ("The Han Succession," 210–141 BC), 5 ("Of Commanderies and Kingdoms," 141–87 BC), 6 ("Dynastic Decline and Usurpation," 87 BC–AD 189)
- Summary page: [[src-keay-china-ch4-6]]
- Pages created: [[dynasty-han]], [[figure-liu-bang]], [[figure-han-wudi]], [[figure-sima-qian]], [[figure-wang-mang]], [[concept-xiongnu]]
- Pages updated: [[overview]], [[timeline]], [[index]]
- Most interesting new details:
  - Xiang Yu's last night: surrounded at Gaixia, sings a farewell song to his horse and his concubine, then rides into Han lines alone — considered one of the most dramatic exits in Chinese history
  - Lady Dai's mummy (tomb sealed c. 168 BC): flesh still responsive to pressure after 2,100 years; 138 melon seeds in her stomach; finest silk in the ancient world in her burial clothes
  - Sima Qian chose judicial castration over suicide specifically so he could finish the *Shiji* — "though I should suffer a thousand mutilations, what regret should I have?"
  - Zhang Qian's journey west revealed that China was entirely unknown to Bactria and the states beyond — the "Middle Kingdom" was not remotely in the middle of anything
  - Wang Mang's aviator: a man who strapped bird feathers to himself and "flew several hundred double-paces, then fell" — possibly the earliest authenticated account of human flight

## [2026-04-16] ingest | Benn, *Tea in China* — Chapter 2 (early history of tea)

- Source: `raw/teainchina.pdf` (PDF pp. 38–57, book pp. 21–41)
- Summary page: [[src-tea-ch2]]
- Pages created: [[concept-tea-culture]]
- Pages updated: [[index]]
- Most interesting details:
  - The word *cha* (tea) didn't exist until the mid-Tang; before ~800 CE it was called *tu*, *ming*, *jia*, etc. — one stroke removed from the old character
  - Shennong discovering tea is Lu Yu's invention (c. 760 CE); no pre-Tang source connects the two
  - The earliest reliable tea reference: a courtier secretly replacing his emperor's wine with tea at banquets to avoid getting drunk (Three Kingdoms, ~3rd century CE)
  - Pre-Tang anomaly literature around tea is delightfully strange: a 10-foot hairy mountain demon guarding wild tea plants; a ghost who keeps haunting his household asking for tea; an old woman who sells unlimited tea, gives the money to the poor, and flies out of prison using her tea container
  - Tea as a mass cultural phenomenon spread in decades after ~760 CE, pushed by Buddhist monks as an alternative to alcohol

## [2026-04-16] ingest | Li Feng, *Early China* — Chapters 1–4 (Neolithic through Anyang)

- Source: `raw/early_china_li_feng.pdf` (PDF pp. 24–112, book pp. 1–89)
- Chapters covered: 1 (introduction/historiography), 2 (Neolithic complex society), 3 (Erlitou and Erligang), 4 (Anyang and Bronze Age cultures)
- Summary page: [[src-li-feng-ch1-4]]
- Pages created: [[concept-neolithic-china]], [[concept-erlitou]], [[figure-lady-hao]]
- Pages updated: [[dynasty-xia]] (Erlitou debate, Bingong xu), [[dynasty-shang]] (Anyang layout, Huanbei city, Lady Hao numbers, Mother Wu cauldron, industrial scale), [[overview]], [[timeline]], [[index]]
- Most interesting new details:
  - Taosi solar observatory (discovered 2003, c. 2600–2100 BC): one of the oldest confirmed solar observatories in the world; 13 pillars, 12 slits; possibly the context that first demanded a writing system to track calendar sections
  - Erlitou's building orientation (6–10° west of north) vs. Yanshi/Shang (7° east of north): an astronomical shift that almost certainly marks the cosmological break between Erlitou culture and the Shang
  - Huanbei Shang City (discovered 1999, north of Huan River): an entire pre-oracle-bone Shang city hidden on the Anyang periphery, solving the mystery of where the first three Anyang kings' records were; establishes the "Middle Shang" period
  - Lady Hao commanded armies of 10,000+ soldiers; her unlooted tomb (468 bronzes, 755 jades) is the richest excavated at Anyang — and it was not a royal tomb
  - Mother Wu ding-cauldron: 875 kg, 1.33 m high, required 1,000+ simultaneous artisans — the largest bronze vessel in the world
  - Sanxingdui (Sichuan): contemporary with late Shang, completely independent religious system; life-size bronze human statue (172 cm) is the only complete life-size Bronze Age human bronze in China
  - Lajia earthquake site (~4000 BP): oldest noodle in China found under a fallen bowl; mothers died protecting children

## [2026-04-16] ingest | Birrell, *Chinese Mythology* — Chapters 1–3 (Origins, Culture Bearers, Saviors)

- Source: `raw/Anne-Birrell-Chinese-Mythology_-An-Introduction-Johns-Hopkins-University-Press-1993.pdf` (PDF pp. 39–105, book pp. 23–88)
- Chapters covered: 1 ("Origins"), 2 ("Culture Bearers"), 3 ("Saviors")
- Summary page: [[src-birrell-ch1-3]]
- Pages created: [[concept-chinese-mythology]], [[figure-nu-kua]], [[figure-pan-ku]], [[figure-yi-archer]], [[figure-yu-the-great]]
- Pages updated: [[overview]], [[index]]
- Most interesting new details:
  - P'an Ku (China's "canonical" creation myth) only appears in 3rd-century AD texts and is probably borrowed from Central Asia — Nü Kua is six centuries older. The Han era's male-dominant rationalization is what made P'an Ku orthodox.
  - Nü Kua made aristocrats from yellow earth and commoners by dragging a cord through mud — social stratification literally built into creation
  - Master Yen built a functional android (leather, wood, lacquer) that sang, danced, and winked at palace ladies; the king nearly had him executed before he tore it apart to prove it was artificial
  - Yü the Great worked the flood for ten years so totally that his body broke: no nails, no leg hair, one side shriveled, he couldn't lift one leg past the other — the "Yü walk" became a real shamanic ritual dance
  - T'ang the Conqueror (Shang founder) cut his hair and fingernails, purified himself, and lay on a pyre to sacrifice himself to Heaven to end a seven-year drought; rain fell before the fire took
  - The "virgin brides" story: the annual drowning of two virgins as river-god brides may have been a real local custom for disposing of unwanted daughters — families received huge cash compensation

## [2026-04-16] ingest | Wikipedia, *Dynasties of China* — legitimacy disputes + dynasty stubs

- Source: `raw/Dynasties of China.md`
- Pages updated: [[concept-mandate-of-heaven]] (added "The legitimacy wars" section: Three Kingdoms debate, Northern/Southern Dynasties mutual barbarian insults, Qing–Southern Ming split, Japan claiming to be China's true heir)
- Pages created: [[dynasty-three-kingdoms]], [[dynasty-jin]], [[dynasty-northern-southern]], [[dynasty-sui]], [[dynasty-tang]], [[dynasty-five-dynasties]], [[dynasty-song]], [[dynasty-yuan]], [[dynasty-ming]], [[dynasty-qing]] (all stubs — to be expanded with full sources)
- Pages updated: [[index]]
- Most interesting new details:
  - The Northern/Southern Dynasties called each other "island barbarians" and "barbarians with braids" — both sides equally convinced the other was the uncivilized one
  - Japan's Tokugawa shogunate refused to recognize Qing legitimacy and declared itself the rightful heir of Chinese civilization after the Ming fell
  - Ouyang Xiu's elegant solution to the legitimacy problem during fragmented eras: orthodoxy doesn't reside anywhere — it enters "a state of limbo" and waits for reunification

## [2026-04-16] ingest | Li Feng, *Early China* — Chapter 5 (oracle bones and late Shang)

- Source: `raw/early_china_li_feng.pdf` (pp. 90–111, PDF pages 113–135)
- Chapter: 5 — "Cracking the secret bones: literacy and society in late Shang"
- Summary page: [[src-li-feng-ch5]]
- Pages updated: [[concept-oracle-bones]] (major expansion), [[dynasty-shang]] (hegemonic state model, succession section)
- Pages updated (index): [[index]]
- Most interesting new details:
  - Full divination mechanics: four-part inscription structure (preface, charge, prognostication, verification); the crack is produced by a heated metal stick; the king examines the crack, not the diviner; verifications appear in only 1.2% of inscriptions
  - Non-royal oracle bones discovered 1991 at Huayuanzhuang-east, 300m from the palace — belonging to a prince, following entirely different conventions; divination was "a highly secret proceeding" even within Anyang
  - The Shang High God (*di*) may be the celestial Northern Pole — the character *di* derived from the surrounding star formation; two kings eventually took the title themselves (Di Yi, Di Xin)
  - Shang succession rule (brothers before sons) held for ~12 generations then broken by powerful kings; primogeniture established by repeated violation, not decree
  - The Shang was a "hegemonic not legitimate" state — no fixed perimeter, no permanent administration, maintained entirely by the king's continuous military display

## [2026-04-17] ingest | Keay, *China: A History* — Chapters 10–12 (755–1405 CE)

- Source: `raw/China_A_History_-_John_Keay.txt` (lines ~3013–3511)
- Chapters covered: 10 ("Disorder Restored," 755–1005), 11 ("Civilization Gridlock," 1005–1235), 12 ("All Under Yuan," 1235–1405)
- Summary page: [[src-keay-china-ch10-12]]
- Pages updated: [[dynasty-five-dynasties]], [[dynasty-song]], [[dynasty-yuan]], [[timeline]], [[index]]
- Pages created: [[dynasty-xi-xia]], [[concept-neo-confucianism]], [[event-mongol-conquest-song]], [[figure-wang-anshi]]
- Most interesting new details:
  - Huang Chao's final exit in 884: after sacking Chang'an, he had his concubines killed then rode north alone into the dawn with two servants — consciously echoing Xiang Yu at Gaixia a thousand years earlier
  - Feng Dao served nine emperors across all five dynasties (and two Liao emperors) without apparent loss of rank; supervised the first complete printed Confucian classics in 953; later historians condemned him savagely, but his own defense was that he served the people not the emperor
  - Wang Anshi's New Policies: low-interest state loans to cut usurers (who charged 100%), state granaries, corvée commutation — "most ambitious reorganization between the First Emperor and the Communist Party" (Keay); reversed the year after his patron Song Shenzong died; Wang Anshi died the following year
  - Foot-binding: rare before 1086, apparently universal among Han women by 1100; persisted 800 years; non-Han ruling dynasties (Jurchen, Mongol, Manchu) shunned it throughout, using it to distinguish themselves from Han subjects
  - The siege of Xiangfan (1267–73): six years; Colonel Chang's hundred-ship paddle-wheel relief attempt; ultimately broken by Muslim trebuchets imported from Persia, capable of hurling 150 kg stones
  - Lu Xiufu strapped the seven-year-old Song emperor to his back and jumped into the sea at the Battle of Yamen (1279); the 800-ship fleet followed
  - The Xi Xia ("Great State of White and High"): a sophisticated Tangut Buddhist empire controlling the Gansu horse corridor, annihilated by Chinggis so completely that their script was not deciphered until the 20th century

## [2026-04-17] ingest | Keay, *China: A History* — Chapters 13–14 (1405–1760 CE)

- Source: `raw/China_A_History_-_John_Keay.txt` (lines ~3598–4172)
- Chapters covered: 13 ("The Rites of Ming," 1405–1620), 14 ("The Manchu Conquest," 1620–1760)
- Summary page: [[src-keay-china-ch13-14]]
- Pages updated: [[dynasty-ming]], [[dynasty-qing]], [[timeline]], [[index]]
- Pages created: [[src-keay-china-ch13-14]], [[figure-zheng-he]]
- Note: This completes Keay ingestion. Chapters 15–16 (1760–1950) judged outside the wiki's dynastic scope.
- Most interesting new details:
  - Zheng He's treasure ships were over 130m long — five times the length of Columbus's *Santa María*; 27,000 men; reached East Africa 70 years before Vasco da Gama rounded the Cape; abandoned because they were ritual, not commercial, enterprise: "more money, power, and ceremony applied in the same old way was simply bound to fail"
  - The Tumu Incident (1449): the Zhengtong Emperor's 500,000-man army collapses in 28 days of incompetence; the emperor sits on the ground among his dead guards and is found by a Mongol prince who suspected he was "someone special"
  - The last Ming emperor climbed Coal Hill after midnight on 25 April 1644 with only an old eunuch, looked at the fires in the suburbs, and hanged himself from a crossbeam in the Hat and Girdle Department
  - Zheng Chenggong (Coxinga): half-Japanese Ming loyalist who controlled the entire China coast from Guangdong to Zhejiang; expelled the Dutch from Taiwan in 1661; died in his thirties convulsed with grief when news arrived that the last Ming pretender had been strangled; simultaneously worshipped by the KMT, communists, and Japanese
  - The Zunghar genocide: 600,000 Zunghars in Xinjiang — 40% killed by smallpox (deployed as a weapon), 30% by Qing armies, 20% fled; "Zungharia was left as a blank social space"; one authority calls it "the final solution"
  - The Macartney Mission (1793): the Qianlong Emperor's dismissal letter to George III: "we have no need of your manufactures"; Macartney accurately predicted the empire was "an old, crazy, First-rate man-of-war" drifting toward catastrophe

## [2026-04-17] ingest | Keay, *China: A History* — Chapters 7–9 (189–755 CE)

- Source: `raw/China_A_History_-_John_Keay.txt` (lines ~2129–3013)
- Chapters covered: 7 ("Four Hundred Years of Vicissitude," 189–550), 8 ("Sui, Tang and the Second Empire," 550–650), 9 ("High Tang," 650–755)
- Summary page: [[src-keay-china-ch7-9]]
- Pages updated: [[dynasty-three-kingdoms]], [[dynasty-jin]], [[dynasty-northern-southern]], [[dynasty-sui]], [[dynasty-tang]], [[timeline]], [[index]]
- Pages created: [[event-battle-red-cliffs]], [[event-an-lushan-rebellion]], [[figure-wu-zetian]], [[concept-buddhism-china]]
- Most interesting new details:
  - The Nanai Vandak letter (313 CE): a Sogdian merchant's letter home to Samarkand, found 1,600 years later in an abandoned postbag at Dunhuang, saying "Luoyang is no more... these Xiongnu who yesterday had been the Emperor's property!" — one of history's most vivid eyewitness documents of imperial collapse
  - Fotudeng converts Shi Le by conjuring a blue lotus from a begging bowl; Shi Hu later explains his Buddhism with unusual clarity: "Buddha, being a foreign god, is the very one we outsiders should worship" — non-Han rulers found Buddhism genuinely useful for legitimacy
  - The "intercalary dynasty" concept: Keay's framework for understanding the Sui as a necessary, traumatic correction between chaos and Tang glory, consciously parallel to Qin before Han
  - Grand Canal: "one of the grandest navigation systems ever undertaken by a single sovereign in pre-modern history" — 2,500 km, still in use today, 21st-century plans to reroute Yangzi water to Beijing through it
  - Wu Zetian's fall: at 80-something, confronted by ministers after pardoning her favorites one too many times; last act was to address her trembling son "in terms of contempt," then return to bed
  - "A poor Persian" listed as the number-one anomaly in a Tang literary parlor game — Chang'an's Persians financed the silk trade in silver coin preferred to debased copper cash
  - Yang Guifei strangled with silk on the road to Sichuan, the emperor watching powerlessly as his escort mutinied — the origin of one of China's great tragic love stories

## [2026-04-17] ingest | Li Feng, *Early China* — Chapters 6–7 (Western Zhou, 1059–771 BCE)

- Source: `raw/early_china_li_feng.pdf` (pp. 112–160)
- Chapters covered: 6 ("The inscribed history: the Western Zhou state and its bronze vessels"), 7 ("The creation of paradigm: Zhou bureaucracy and social institutions")
- Summary page: [[src-li-feng-ch6-7]]
- Pages created: [[event-zhou-conquest-shang]], [[concept-fengjian]], [[figure-duke-of-zhou]]
- Pages updated: [[dynasty-zhou]], [[concept-mandate-of-heaven]], [[timeline]], [[index]]
- Most interesting new details:
  - The five-planet conjunction of 1059 BCE (confirmed by modern astronomy) was the actual trigger for King Wen's declaration of kingship — the Mandate of Heaven was born in a real astronomical event, not purely political invention
  - Caucasoid bone sculptures with the character *wu* 巫 ("shaman") found at the Zhou capital Zhouyuan; carnelian beads and faience from India and West Asia in Zhou tombs — the Zhou world reached into Central Asia
  - Li Feng's key intervention: *fengjian* is NOT feudalism — it was a kinship-based system, not a contractual one; he published a 2003 *Harvard Journal of Asiatic Studies* article on this
  - Heaven's Mandate was also a source of anxiety for the Zhou themselves: only King Wen was the recipient; subsequent kings could only maintain it; late Western Zhou poetry is haunted by fear of losing it
  - The Bao Si story (smiling concubine / beacon fires) is "essentially fictional" (Li Feng); the real fall was a 777 BCE political split that brought in barbarian proxies
  - The Zhou invented bureaucracy — real administrative offices (Supervisor of Land, Construction, Horses) organized into a Ministry; Shang had no equivalent
  - The "Confucian Classics" (Yijing, Shangshu, Shijing) were created 300 years before Confucius; the earliest Shangshu texts are Duke of Zhou's government documents
  - King Zhao drowned with his entire royal Six Armies in the Han River — no bronze was cast to record it

## [2026-04-17] ingest | Benn, *Tea in China* — Chapters 3–5 (Buddhism, Poetry, Lu Yu)

- Source: `raw/teainchina.pdf` (PDF pp. 56–130, book pp. 42–116)
- Chapters covered: 3 ("Buddhism and Tea in the Tang Dynasty"), 4 ("Tea Poetry in Tang China"), 5 ("The Patron Saint of Tea")
- Summary page: [[src-tea-ch3-5]]
- Pages created: [[figure-lu-yu]]
- Pages updated: [[concept-tea-culture]] (major expansion: Buddhism, *Chajiu lun*, Famen si, Tang tea poetry, Lu Yu and *Chajing*, deification)
- Pages updated (index): [[index]]
- Most interesting new details:
  - Lu Yu was abandoned as a baby, found by a monk among wild geese in late autumn, refused his monastic vows, taught himself to read on cattle with a bamboo stylus, ran away at 13 to join entertainers — then became the God of Tea
  - The *Chajiu lun*: Mr. Tea vs. Mr. Alcohol argue about superiority; neither wins; Mr. Water interrupts and ends the debate
  - The 1987 Famen si discovery: imperial gilt-silver teaware buried with Buddha's finger-bone relic; the "esoteric Buddhist ritual" reading is probably wrong (Benn)
  - Tea is completely absent from pre-Tang poetry — Jiaoran and Lu Tong invented the vocabulary of tea mysticism from nothing in the mid-Tang
  - Bai Juyi wrote about tea without any spiritual framing, showing everyone else's mystical vocabulary was a deliberate choice
  - An Lushan rebellion may have done more to reduce Tang alcohol consumption than any Buddhist temperance movement

## [2026-04-17] ingest | Benn, *Tea in China* — Chapters 6 and 8 (Song and Ming tea)

- Source: `raw/teainchina.pdf` (PDF pp. 131–144, 186–212; book pp. 117–144, 172–197)
- Chapters covered: 6 ("Tea in the Song Dynasty"), 8 ("Religion and Culture in the Tea Economy of Late Imperial China")
- Summary page: [[src-tea-ch6-8]]
- Pages updated: [[concept-tea-culture]] (major expansion: Song cake tea, diancha, "Go drink tea," monastic ceremonies; Ming tea revolution, Yixing ware, five famous teas, Xu Cishu's list, water connoisseurship, Japan split)
- Pages updated (index): [[index]]
- Most interesting new details:
  - Emperor Huizong wrote the finest Song tea manual with expert precision — then was captured by the Jurchen in 1127 and died in captivity. Most knowledgeable tea emperor; worst fate.
  - Ming Taizu's 1391 edict abolishing cake tea accidentally created modern tea: leaf tea, teapots, multiple steepings. A peasant emperor's practical impatience transformed the entire tradition.
  - Xu Cishu's list of appropriate occasions: "as drunken guests disperse," "when the children have left the building," "in light cloud and drizzle" — the most human document in tea literature
  - Yuan Hongdao's servants secretly replaced thirty jars of famous springwater with ordinary mountain water; his friends praised it; he was furious when he found out
  - Monk Dafang invented Songluo tea by transplanting Huqiu monastery's pan-firing technique to a different mountain — monastic knowledge transfer as the engine of tea innovation
  - Japan preserved Song diancha (whisked powdered tea) because Eisai visited in 1168–1191, before the Ming revolution. This is why matcha looks like it does.

## [2026-04-18] ingest | Birrell, *Chinese Mythology* — Chapters 4–5 (Destroyers, Miraculous Birth)
- Summary page: [[src-birrell-ch4-5]]
- New pages: [[figure-kung-kung]], [[figure-yi-yin]]
- Pages updated: [[figure-yi-archer]] (river god, Fu-fei theft, peach-wood death by Feng Meng), [[dynasty-xia]] (King Chieh mythology), [[dynasty-shang]] (founding birth myth, King Kai cattle raid, King Chou's rise and fall)
- Most interesting new details: Kung Kung breaking Pu-chou Mountain is the cosmological explanation for why the sun moves west and rivers flow southeast. Yi Yin's mother turned into a mulberry tree when she looked back at the flood — the greatest minister in Chinese history was born from dead wood. King Chou of the Shang starts as "attractive, intelligent, heroic" in Ssu-ma Ch'ien's telling — the last-bad-ruler myth is more interesting when it's a tragedy, not a caricature. And peach wood became apotropaic because Feng Meng used it to kill the best archer in the world.

## [2026-04-18] ingest | Spinoza, *Ethics* Part I (Concerning God)
- Summary page: [[src-spinoza-ethics-p1]]
- New pages: [[figure-spinoza]]
- Secondary source used: Beth Lord, *Spinoza's Ethics: An Edinburgh Philosophical Guide*
- Pages updated: [[index]]
- Most interesting details: Spinoza uses Descartes' own definitions against him — he accepts the standard definition of "substance" and shows it leads necessarily to ONE substance, not many. The Appendix is a furious attack on teleological thinking: "good," "bad," "beautiful," "ugly," "order," "chaos" are not features of reality but projections of human psychology. The "sanctuary of ignorance" = God's will, where people flee when they run out of causal explanations. Spinoza's God has no personality, no free will, no purposes, no particular concern for humans — it is simply being itself. His contemporaries called him an atheist; Novalis called him "the God-intoxicated man."

## [2026-04-18] restructure | Wiki expanded to multi-domain knowledge base
- CLAUDE.md rewritten: scope expanded from Chinese history to philosophy, religion, anthropology, linguistics
- Added `domain` frontmatter field; added domain-specific ingest guidance for philosophy, religion, anthropology, linguistics
- `wiki/index.md` reorganized with domain sections; new empty sections for Philosophy, Religion, Anthropology, Linguistics
- Spinoza's *Ethics* queued for ingestion as first philosophy source

## [2026-04-18] ingest | Tao Tao Liu, *The Chinese Myths* — Chapters 1–2 (Brief History; Literary Traditions)
- Summary page: [[src-tao-liu-ch1-2]]
- Pages updated: [[concept-chinese-mythology]] (shenhua etymology; Shan Hai Jing as map captions; Sima Qian's admission; mythology in modern China), [[concept-buddhism-china]] (Guanyin's gender transition: Tang moustache → Ming baby-holder), [[index]]
- Most interesting new details: The Chinese word for mythology (*shenhua*) was borrowed from the West via Japan in the 20th century — China had no native concept of "myths" as a category. The *Shan Hai Jing* is map captions: the surviving text annotated a set of geographical maps that are now lost, which explains why it reads like a catalogue. China's Mars rover is named Zhurong (God of Fire); the lunar missions are named Chang'e. Guanyin was visibly male in Tang Dunhuang paintings (moustache) and became unmistakably female by Ming porcelain. The "Epic of Darkness" (*Hei An Zhuan*) — a Tang-dynasty oral epic only performed at funerals — was still alive in manuscript form when an old farmer in Shennongjia gave a copy to a researcher in 1982.

## [2026-04-18] ingest | Birrell, *Chinese Mythology* — Chapter 12 (Love)
- Summary page: [[src-birrell-ch12]]
- Pages updated: [[index]]
- Most interesting new details: The Sky Voyager myth — a man rides a raft to Sky River and meets the Weaver Maid's oxherd, and when he gets home the astronomer Yen Chün-p'ing tells him his arrival registered as "a stranger star trespassing into the Draught Ox constellation." A mortal's trip to heaven left a trace in the stars. Han P'ing's wife deliberately rots her clothes before throwing herself from a tower so the prince's guards can't catch her — they grab the rags and she falls free. Their graves grow two catalpa trees that bend toward each other, roots entwined below, boughs embraced above. The chapter opens with a censorship thesis: Han officials "corrected" the Classic of Mountains and Seas in 6 BC, and there is no Aphrodite, no Eros, and no Zeus in the Chinese tradition as a result.

## [2026-04-18] ingest | Birrell, *Chinese Mythology* — Chapters 9–11 (Goddesses, Immortality, Metamorphoses)
- Summary page: [[src-birrell-ch9-11]]
- New pages: [[concept-queen-mother-west]]
- Pages updated: [[figure-nu-kua]] (Han-era demotion: silent achievement, Karlgren/Schafer, Fu Hsi consort pairing), [[index]]
- Most interesting new details: The original *Classic of Poetry* Weaver Maid poem has zero romantic content — both Weaver Maid and Draught Ox are images of futile, unfinished labor. Six hundred years of romantic elaboration on top of a poem about uselessness. The Queen Mother of the West begins with tiger fangs and panther tail administering divine executions; she ends pouring wine at a garden party. The silkworm myth: a girl breaks a promise to her horse, mocks its dead skin, and gets wrapped in it and transformed — the origin of the entire Chinese silk industry, and "mulberry" (*sang* 桑) puns on "mourning" (*sang* 喪). P'eng-tsu, the Chinese Methuselah, refuses to reveal his secret of 767-year-long life because longevity "has broken my good humor in my guts." He disappears heading west. Last seen seventy years later.

## [2026-04-18] ingest | Spinoza, *Ethics* Part III (On the Origin and Nature of the Emotions)
- Summary page: [[src-spinoza-ethics-p3]]
- Secondary source used: Beth Lord, *Spinoza's Ethics: An Edinburgh Philosophical Guide*
- Pages updated: [[index]]
- Most interesting details: Conatus (P6-7) is the single most important concept — each thing's essence IS its striving to persist; we do not desire things because they are good, we call them good because we desire them. The three primitive affects are joy (transition to greater power), sadness (transition to lesser power), and desire — from these everything follows. Emotional contagion (P27): imagining a similar being feeling an emotion causes us to feel the same; this is the root of compassion, emulation, envy, and competition. Ethnic hatred (P46): a rigorously non-moral explanation of racism as accidental conditioning applied at scale — race and nation are imaginary generalizations with no rational basis. There is no active sadness — sadness is necessarily passivity. The closing image: "like waves on the sea, driven by contrary winds, we toss about, not knowing our outcome and our fate." The P35 scholium on jealousy — written with unmistakable personal experience — is the most affectively raw passage in the Ethics.

## [2026-04-18] ingest | Spinoza, *Ethics* Part II (On the Nature and Origin of the Mind)
- Summary page: [[src-spinoza-ethics-p2]]
- Secondary source used: Beth Lord, *Spinoza's Ethics: An Edinburgh Philosophical Guide*
- Pages updated: [[index]]
- Most interesting details: Parallelism (P7) dissolves the Cartesian mind-body problem by showing mind and body are not two things to begin with — they are one mode expressed through two attributes. Two causal chains (physical things causing physical things; ideas causing ideas) run in perfect parallel and never cross. Everything has a mind — stones, sewing machines, rivers — the difference from human minds is only complexity. Memory is not an archive but a bodily habit: the soldier and the farmer see the same horse-tracks and think completely different things. "Truth is its own standard" — knowing something truly is knowing you know it. The three kinds of knowledge: imagination (habit, experience, hearsay — only source of error), reason (common notions — necessarily true), intuition (grasps essence directly, sub specie aeternitatis — treated fully in Part V). Will and understanding are the same thing — there is no separate faculty of assent standing above the ideas.

## [2026-04-18] ingest | Birrell, *Chinese Mythology* — Chapters 6–8 (Yellow Emperor, Yi Archer cycle, Yü the Great cycle)
- Summary page: [[src-birrell-ch6-8]]
- New pages: [[figure-yellow-emperor]]
- Pages updated: [[figure-yu-the-great]] (warrior aspects: Fang-feng, Hsiang Liu, Wu-chih-ch'i/Sun Wukong; Nine Cauldrons; world measuring), [[figure-yi-archer]] (Wu Kang on the moon; the moon's full cast of immortality-seekers)
- Most interesting new details: Wu-chih-ch'i — the chained ape monster who caused typhoons on the Huai River — is Sun Wukong's direct ancestor, six centuries before Journey to the West. The Yellow Emperor's mythology is a textbook case of progressive domestication: from beast-armies and killed gods to Chuang Tzu's sock puppet who learns wisdom from Taoists. And the moon in Chinese mythology is populated entirely by people who wanted to live forever and got trapped there.

## [2026-04-18] ingest | Spinoza, *Ethics* Parts IV–V (Human Bondage; Human Freedom)
- Summary pages: [[src-spinoza-ethics-p4]], [[src-spinoza-ethics-p5]]
- Secondary source used throughout: Beth Lord, *Spinoza's Ethics: An Edinburgh Philosophical Guide*
- Pages updated: [[figure-spinoza]] (added full See Also section), [[src-spinoza-ethics-p3]] (fixed forward link to P4), [[index]]
- Most interesting details (Part IV): Virtue = power, not piety — D8 is the pivot of Spinoza's entire ethics. "When each man most seeks his own advantage, men are most useful to one another" (P35C2) — the seeming paradox that genuine self-interest and altruism are the same thing. Spinoza's attack on Calvinist despondency: joy is ethically good; laughter, music, theater, and pleasure are a wise person's tools. "A free man thinks of nothing less than of death, and his wisdom is a meditation not of death but of life" (P67) — the direct inversion of Stoic meditatio mortis. Free will is a legal fiction, needed for punishment, but not real. The state is a machine for managing affects through stronger affects (fear).
- Most interesting details (Part V): The method of liberation — separate the affect from the image of its cause; form an adequate idea of the remaining bodily change; the passion dissolves into active joy. Understanding that all things are necessary is the greatest therapeutic tool: it dissolves resentment, envy, blame, and a certain kind of fear. The intellectual love of God (P32C): joy + adequate idea of God as cause, eternal, incapable of frustration, identical with God's love of himself. The final proposition (P42): "Blessedness is not the reward of virtue, but virtue itself" — the entire inversion of Christian moral psychology in one sentence. The last line on the wise person: "he never ceases to be, but always possesses true acquiescence of his spirit."
- Note: This completes the full *Ethics* (Parts I–V). Beth Lord's guide used throughout as secondary commentary.

## [2026-04-18] ingest | Hume, *An Enquiry Concerning the Principles of Morals* (1751)
- Summary page: [[src-hume-epm]]
- New pages: [[figure-hume]]
- Pages updated: [[index]]
- Most interesting details:
  - The "monkish virtues" passage (Section IX) is Hume's most polemical: celibacy, fasting, penance, mortification, and humility are placed explicitly in the *vice* column because they serve no purpose, "stupefy the understanding and harden the heart." A philosophical attack on asceticism framed as a matter of simple observation.
  - The "sensible knave" problem (Section IX Part II): Hume openly admits he cannot fully refute the clever person who violates justice whenever they can do so secretly and profitably. His answer — they sacrifice "inward peace of mind" for "worthless toys and gewgaws" — is incomplete, and he knows it.
  - The vault vs. wall analogy (Appendix III): benevolence builds like a wall (each stone of kindness adds to the total); justice builds like a vault (every stone collapses without the whole). One of the clearest philosophical distinctions in the book.
  - The Oedipus/Nero contrast (Appendix I): both stand in formally similar relations to their victims, but Oedipus's act was a factual mistake, Nero's a moral one. Morality cannot consist in relations; it consists in the sentiment of disapprobation.
  - The "particle of the dove" concession: Hume doesn't need to win the self-love debate. Even a tiny residue of genuine sympathy — "some particle of the dove kneaded into our frame, along with the elements of the wolf and serpent" — is sufficient, because it is common to all and universal in scope.
  - Hume died peacefully in 1776, calmly refusing religious consolation. James Boswell visited hoping to find deathbed panic; found none. Edinburgh clergy were appalled. His death was as philosophically provocative as his writing.

## [2026-04-18] ingest | Hegel, *Phenomenology of Spirit* — Preface and Introduction (§§1–89)
- Summary page: [[src-hegel-phenom-preface-intro]]
- New pages: [[figure-hegel]]
- Secondary source used throughout: Terry Pinkard, *Hegel's Phenomenology: The Sociality of Reason* (Cambridge, 1994)
- Translation: A.V. Miller (Oxford, 1977)
- Pages updated: [[index]]
- Most interesting details:
  - "The night in which all cows are black" (§16) — Hegel's famous attack on Schelling's absolute identity: saying "in the Absolute, everything is one" sounds profound but destroys all determinacy. The paragraph is barely veiled; Schelling never forgave it.
  - "The True is the whole" (§20) — but the whole is *only* the result together with the entire process of becoming; the result alone is "the corpse which has left the guiding tendency behind it."
  - The Bacchanalian revel (§47): "Truth is thus the Bacchanalian revel in which no member is not drunk; yet because each member collapses as soon as he drops out, the revel is just as much transparent and simple repose." One of the most vivid images in all of Hegel.
  - Determinate negation (§79) — the most technically important concept of the Introduction. When a form of consciousness fails, it collapses into the specific nothingness *of that form*, not into nothingness in general. This specificity points toward the next form and drives the dialectic forward.
  - "Behind the back of consciousness" (§87) — the transition to each new form happens necessarily, but consciousness doesn't see it coming; we (the philosophical observers) see the necessity that the consciousness undergoing it does not.
  - Thesis-antithesis-synthesis is NOT Hegel — Hegel himself dismisses this triadic schema as "a lifeless schema." Pinkard confirms it was invented by popularizers (traced to Fichte).
  - Pinkard's key reframe: Spirit (*Geist*) is not a metaphysical entity but a *relation* — the shared social space of reason-giving among persons. The Phenomenology is a dialectical history of European *Geist*, not a map of a pre-existing spiritual reality.
- Note: Text covers §§1–89 (Preface complete, Introduction complete). Next section: A. Consciousness (§§90–165), then B. Self-Consciousness including Master/Slave (§§166–230).
