# QUOTE QA — PATCHv3b (EGC 1995 / notes147) — 9-image checkpoint

- Date: 2026-11-09 ~19:00 CST (America/Chicago)
- Scope: 9 Round-2 “C*” crops recovered from the v3 WIP and re-verified. Does NOT touch the 5 PATCHv3a assets (kenobi-final-goodbye, kyp-exar-kun-seduction, luke-steps-off-platform, exar-kun-spirit-defeated, anakin-forgiveness-freed), the sealed EOF, or any earlier patch ZIP.
- Source: native 200 dpi page images extracted (`pdfimages`) from `primary/essential-guides/eg-characters-1995/Essential-Guide-to-Characters-1995.pdf`; PDF page N = scan N; printed folio checked on each page.
- Method: Read the full native source page → recrop the whole passage from that page (numbered stacked PARTS where it runs across columns) → Read the FINAL file and compare line by line with the page Read. Not certified from OCR/bounding boxes alone; OCR was only used to find coordinates and as a typing aid, and each OCR error (e.g. “froops”, “leff”, “fo”) was corrected against the image.
- Two WIP rebuilds were REJECTED at this check and recut: Mara (PART 3 ended mid-sentence “to be seen as the” then skipped ~25 lines) and Evazan (ended mid-sentence “set the thermal”). Their v3b files are new cuts.
- Supersedes the Round-2 “C*” claims for these 9 files.

## `egc1995-p082-mara-emperors-hand.jpg`

- Source: EGC 1995 printed p.82 / scan 091 / PDF page 91
- Prior defect: Round-2 C*/cloud PASS was WRONG: prior crop showed only the right column; the defining left/middle-column passage (incl. “Code-named the ‘Emperor’s Hand’”) was cut off. The earlier v3 WIP 4-part rebuild (sha ccd6eebf…) was also rejected at this check: PART 3 stopped mid-sentence at “But even to be seen as the” and skipped to “It was a discussion”.
- Method: native 200dpi PDF page image (pdfimages, PDF p.91); 3 numbered stacked PARTS: left col (150,1717)-(596,2035); middle col (643,1572)-(1090,2033); right col (1139,272)-(1582,1634); continuous, no skipped lines
- Parts: PART 1/3 left column; PART 2/3 middle column; PART 3/3 right column top through end of paragraph
- Opening words: “Nothing is known about her past.” · Ending words: “her: “You will kill Luke Skywalker.””
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `adb8eeff38c77a38c48a482d276b0fc9e12b92a1d73927a9b670474862cf5f34` → `77ed3bc4f30123f6ed00ab67541ebacedff62c7b0796f1fd01aba114d44095db`

> Nothing is known about her past. It is rumored that Emperor Palpatine took her as a young girl and had her parents killed. He trained Mara as his personal, Force-sensitive assassin, teaching her how to use a lightsaber and how to use rudimentary Force powers. The best of his protectors taught her hand-to-hand combat and marksmanship, and she was trained in spy techniques and political intrigue. Code-named the “Emperor’s Hand,” Mara was dispatched to operations that stormtroopers or other troops couldn’t handle. She helped expose traitors, eliminated or discredited Palpatine’s enemies, and brought down mindless bureaucracies. Most helpful of Mara’s Force talents was her ability to hear the Emperor’s call from anywhere in the galaxy. Few in the upper echelons knew that Mara Jade was the Emperor’s Hand. Those few who noticed her at all generally thought she was just a beautiful trinket in Palpatine’s collection. But even to be seen as the Emperor’s consort brought influence, prestige, and respect. The beautiful red-and-golden-haired woman wasn’t in love with Palpatine or the Empire, by any means; but she was in love with her position and power. One of Palpatine’s more public servants was the Dark Lord of the Sith, Darth Vader. Mara tried to stay out of his way as much as she could, but when Vader lost his son, Luke Skywalker, and captured Han Solo, things began to take a turn for the worse. Knowing that Luke would eventually return to Tatooine to rescue his friend, Han Solo, Palpatine sent Mara Jade to kill him. Using the name Arica, she auditioned and won a job as a dancer in Jabba the Hutt’s palace. While her timing could not have been better, Jade still missed her chance to kill Skywalker when the Hutt took Luke and his friends off to the Great Pit of Carkoon for execution. Mara left Jabba’s palace, bitterly tasting defeat and sensing the mind-touch of the Emperor’s disappointment. They would discuss the consequences after her next mission, on Svivren. It was a discussion that was never to occur. Within days, the Emperor was dead, at Darth Vader’s hand. The second Death Star was destroyed in orbit above the moon of Endor, and the Empire was in disarray as various warlords wrestled for control. And in the process, the unknown Emperor’s Hand lost everything. All Mara Jade had to cling to was the last message the Emperor had sent to her: “You will kill Luke Skywalker.”

## `egc1995-p011-evazan-mind-transfer.jpg`

- Source: EGC 1995 printed p.11 / scan 020 / PDF page 20
- Prior defect: Round-2 C* crop was a column expand of the region; the earlier v3 WIP 2-part rebuild (sha a6c06cdd…) was rejected at this check: PART 2 stopped mid-sentence at “The senator set the thermal”.
- Method: native 200dpi PDF page image (PDF p.20); 2 numbered stacked PARTS: middle col (622,1290)-(1065,2041); right col (1113,277)-(1565,1425) through end of article
- Parts: PART 1/2 middle column from “When a senator visited”; PART 2/2 right column through article end
- Opening words: “When a senator visited to check” · Ending words: “would doubtless be a next time!”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `936a0787eea1c46bdcf6b8f53f8651a0d2d541e1419ea442f50d5bdd17a49d47` → `2f29840e81e812fd9ebf31841df0a596384ccb4728885e1aa18fc91c80bb2d57`

> When a senator visited to check up on the progress, Evazan took him to his laboratory. He had modified an Imperial transmogrify unit normally used for reprogramming droids; now it theoretically could transfer the electronic elements of the mind from body to body, effectively giving the mind immortality. While the senator watched, shocked, Evazan stunned a handsome young human and brought him to the labs. Evazan hoped to transfer his own mind into this new, healthy body, but the transfer machine still needed to be tested, and Ponda wanted to be the subject. If the doctor could put Ponda’s mind into that of the hapless Andoan senator, Baba would get his arm back, and governmental power as well. Strapping the two Aqualish in, Evazan made the transfer. While he waited for the “new” Ponda Baba to regain consciousness, the doctor went to look at the young human body whose mind he would soon replace with his own. He found the stunned “man” was wearing a holoshroud, and that the human in his keep was a bounty hunter named Gurion Silizzar, who had an armed thermal detonator in his hand. Seven members of the hunter’s family had been destroyed by Evazan’s experiments, and he meant to exact his revenge. Gurion took the doctor to the roof, where his mother’s ship was to touch down. Evazan’s pet Meduza attacked the hunter, allowing the doctor to disarm his foe. Gurion fell off the tower to his death, and Evazan barely caught hold of the rooftop edge. Footsteps neared the edge, and Evazan was surprised to see his grudging partner. But the transfer had put the senator into Ponda’s body. The senator set the thermal detonator and walked away. As Gurion’s friends neared in their ship, the top of the castle exploded. Had the Silizzar family stayed, they would have witnessed Dr. Evazan extract himself from a gooey mass. The Meduza had cushioned him as he dropped from the tower just before the explosion. Ponda Baba was missing, but Dr. Evazan was buoyed by hope. His device had worked—after a fashion—and there would doubtless be a next time!

## `egc1995-p022-callista-force.jpg`

- Source: EGC 1995 printed p.22 / scan 031 / PDF page 31
- Prior defect: Round-2 C* crop did not hold the full Force-preservation passage (intro sentence + middle-column paragraph + right-column continuation).
- Method: native 200dpi PDF page image (PDF p.31); 3 numbered stacked PARTS: drop-cap intro (left col); middle col “But through the Force… She existed”; right col top 2 lines
- Parts: PART 1/3 intro sentence; PART 2/3 middle col paragraph start; PART 3/3 right col paragraph end
- Opening words: “Only through the power of the” · Ending words: “thirty years, her memories becoming fainter.”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none (PART 1 and PART 2 are separate paragraphs of the same article; nothing invented between them)
- sha256 old → new: `7695e23f4ea0a84e3473a7425cf736b22b892d44eb98544b9551ed48b0ca9396` → `23447d30ff4a3559b04d90e46b067d73c14a3f87d3741b2f741f9dd610bf7d00`

> [PART 1] Only through the power of the Force was Callista able to keep herself alive . . . within the computer banks of one of the Emperor’s deadly weapons! [PART 2–3] But through the Force, Callista did not allow her spirit to die. Her essence resided in the gunnery computer, preventing anyone else from activating the deadly weaponry, and the project was abandoned. She existed in a dreamlike suspension for nearly thirty years, her memories becoming fainter.

## `egc1995-p093-kenobi-strike-me-down.jpg`

- Source: EGC 1995 printed p.93 / scan 102 / PDF page 102
- Prior defect: Round-2 crop was complete but whole column + art (loose); tightened (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: “Teacher and pupil engaged in a” · Ending words: “disappeared, becoming one with the Force.”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `757ec7600d06daed2394b9c89613a2a3d123ede006a757447a92b244e5c9407c` → `17f9edaff669794ca00360d77df959f6964408b7abedfa1bdb045937785f6ffd`

> Teacher and pupil engaged in a savage but evenly matched lightsaber battle. As Vader taunted him for being weak, Kenobi warned him, “If you strike me down, I shall become more powerful than you can possibly imagine.” Suddenly, Ben glimpsed Luke and Leia making their escape; he had to distract Vader and the Imperial troops, to ensure the future of the Jedi. Ben deactivated his lightsaber, and stood, waiting. Vader swung his own weapon, cleaving through Kenobi’s robes, but the noble Jedi Master himself disappeared, becoming one with the Force.

## `egc1995-p097-kun-embrace-dark.jpg`

- Source: EGC 1995 printed p.97 / scan 106 / PDF page 106
- Prior defect: Round-2 crop was complete but whole column + art (loose); tightened (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: “Nadd offered Kun a way to” · Ending words: “already have,” Nadd’s spirit said, laughing.”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `1e2d97f6efc48cd6eeafbca6eaba0b7552cca7d5a7d580d10dd770110f16aebe` → `2082b593d9c3e97ba7e119af45fc58a663d50b76307d17f0484e83e881943a87`

> Nadd offered Kun a way to live, and to repair his broken body: if he embraced the dark side, he would be healed. The betrayal of light was not an easy one for Kun, but the desire to live was stronger still. He accepted the dark side, his screams reaching out across the galaxy and creating ripples in the Force. Whole again, Kun walked the tombs while Nadd’s spirit told him of the alchemical experiments that an ancient Sith Lord, Naga Sadow, had performed on Yavin Four. The experiments gave flesh to the spirits of the dead. Nadd told Kun to travel there to complete Sadow’s work—and give him a new body. The ex-Jedi assured Nadd he would go to Yavin Four to research, but that he would never give in to the dark side. “Oh, but you already have,” Nadd’s spirit said, laughing.

## `egc1995-p140-scan149-luke-failed-highness-endor.jpg`

- Source: EGC 1995 printed p.140 / scan 149 / PDF page 149
- Prior defect: Round-2 C* crop did not show the full paragraph cleanly; recropped whole paragraph (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: “Turning his back on the crippled” · Ending words: “into oblivion, but Luke stopped him.”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `525c98bcbb2810a3f205ad6c426ba6e09ae4322e6018b86bd07d9b674e002baf` → `2cac48dda836f4fac5373aa2fb7f87a6496c526ccd9f3f3d1ec3d0711aeee1d3`

> Turning his back on the crippled Dark Lord, Luke confronted the Emperor, “You’ve failed, Your Highness. I am a Jedi, like my father before me.” Palpatine attacked Luke with blue Force lightning, knowing that the younger Skywalker would never join him. But as Palpatine prepared to deliver the killing bolts, Vader rose up from behind, lifted his Master into the air, and threw him into the burning shaft of the power core. Vader tried to follow him into oblivion, but Luke stopped him.

## `egc1995-p177-scan186-thrawn-unlike-vader-reckless.jpg`

- Source: EGC 1995 printed p.177 / scan 186 / PDF page 186
- Prior defect: Round-2 C* crop did not show the full paragraph cleanly; recropped whole paragraph (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: “Tall, black, and imposing, Vader became” · Ending words: “their deaths lightly, unlike Lord Vader.””
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `21858fb837c1d45d1ed8e0ce7908039b6d746b7775c810336bed8d512ce02dda` → `784dc4b508df94d0596f6fd4839ca63adcc36954546cfa0801f613566bad3729`

> Tall, black, and imposing, Vader became one of the most visible symbols of the Empire. His severe command structure was legendary, if not horrifying; displease him and the least that would happen was physical unpleasantness; disappoint him, and accept death as punishment. Vader seemed to relish killing his own “incompetent” officers, but it did little to gain him respect—only fear. Even Grand Admiral Thrawn once said, “I am not reckless with my men, and I do not take their deaths lightly, unlike Lord Vader.”

## `egc1995-p178-scan187-vader-kenobi-master-of-evil.jpg`

- Source: EGC 1995 printed p.178 / scan 187 / PDF page 187
- Prior defect: Round-2 C* crop did not show the full passage cleanly; recropped both paragraphs incl. art-wrapped lines (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: ““I am the Master now,” Vader” · Ending words: “disappeared, becoming one with the Force.”
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: minor: art-wrapped ragged lines carry adjacent Vader photo edge at left (unavoidable without masking); text complete
- sha256 old → new: `be0898911ba736ea071d1b9a3d5a6f98f0b622fef0ead00b316be7c0660894c4` → `ab0a8009fbb9466df2b0a8a1f67f6283f1a6beeb1891026ddfa027d83e3bfa08`

> “I am the Master now,” Vader said, igniting his lightsaber. “Only a master of evil, Darth,” Kenobi replied. The battle that followed was fierce, with lightsabers clashing and igniting, no quarter asked or given. And then Kenobi warned him, “If you strike me down, I shall become more powerful than you can possibly imagine.” With that, Obi-Wan deactivated his lightsaber and stood waiting. In a rage, Vader swung his own lightsaber, cleaving Kenobi’s robes into pieces. The noble Jedi Master’s body had disappeared, becoming one with the Force.

## `egc1995-p179-scan188-vader-i-am-your-father.jpg`

- Source: EGC 1995 printed p.179 / scan 188 / PDF page 188
- Prior defect: Round-2 C* crop did not show the full paragraph cleanly; recropped whole paragraph (per earlier v3 worker record; old crop not re-inspected in this run)
- Method: re-extracted native 200dpi PDF page image; OCR line-box locate; recrop full passage; single block
- Parts: single block
- Opening words: “Vader finally drove Luke out onto” · Ending words: “You know it to be true.””
- Final file Read word for word: **yes**; every line start and end present.
- Remaining defect: none
- sha256 old → new: `3b939e3a9da9cd5ed4f6c8153c709d6bba2a5495e4d0e1d0970ce495c57c8ca0` → `1c631bf9ea777fe1330714e39b098b0ec53c232a634542dc889d4c7c02469776`

> Vader finally drove Luke out onto a gantry above a reactor shaft and distracted him long enough to slice off his right hand. Defenseless and in shock, Luke could only scream denials as Vader revealed, “I am your father. Search your feelings. You know it to be true.”

## Not covered by v3b (unchecked remainder)

Round-2 C* items still NOT re-proven from originals (14):

- `egc1995-p028-cbaoth-clone.jpg`
- `egc1995-p031-chewie-life-debt.jpg`
- `egc1995-p036-daala-maw.jpg`
- `egc1995-p046-dodonna-force-with-you.jpg`
- `egc1995-p049-dorsk81-exar-kun.jpg`
- `egc1995-p051-kyp-redemption.jpg`
- `egc1995-p067-gethzerion-death.jpg`
- `egc1995-p070-hethrir-waru-death.jpg`
- `egc1995-p098-kun-dark-lord-title.jpg`
- `egc1995-p099-kun-spirit-destroyed.jpg`
- `egc1995-p128-scan137-arca-pray-never.jpg`
- `egc1995-p129-scan138-ulic-dark-lightning-nomi.jpg`
- `egc1995-p129-scan138-ulic-sith-war-betray-kun.jpg`
- `egc1995-p147-scan156-han-leia-i-know-carbonite.jpg`

Additional old-report concerns, still pending (147):

- Wedge Force crop (likely egc1995-p008-no-force.jpg and/or egc1995-p008-wedge-closing.jpg)
- Ackbar opening sentence (likely egc1995-p001/p002 Ackbar crops)
- Endor lightning continuation (likely egc1995-p125-scan134-luke-failed-jedi-lightning.jpg)

The 34 Round-2 “C” items (and 1 “S” statblock) have not been re-proven in v3 either; their old C claims are not proof.
