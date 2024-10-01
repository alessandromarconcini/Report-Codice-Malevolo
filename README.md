# Report-Codice-Malevolo
Un report per il corso di "Codice malevolo" tenuto presso l'università di Verona (Univr).

Esso si riferisce all' analisi statica e dinamica di un malware (Trojan) relativo ad un eseguibile scritto in C++ ma che appare all'utente come un'immagine JPG.
La seconda parte del documento tratta invece dell'analisi condotta su un documento malevolo Microsoft Word che scarica il malware Emotet, Trojan bancario.

**Tool utilizzati:**

- PeStudio, Peid, ExeinfoPe per l'analisi statica di base dell' eseguibile
- Process Monitor, Regshot per l'analisi dinamica di base dell' eseguibile
- Wireshark per l'analisi della rete dell'eseguibile
- IDA e Ghidra per il reverse engineering di alcuni funzioni dell' eseguibile
- Virustotal per la verifica finale dell' eseguibile e del documento malevolo
- exfitool per i metadati del documento malevolo
- yara con le regole per i documenti malevoli per l'analisi del documento malevolo
- strings per lo studio delle stringhe del documento malevolo
- oletimes,oledump,olevba,oletools in generale per l'analisi più approfondita riguardanti le macro contenute nel documento
- Vipermonkey per una simulazione del documento malevolo per individuare ulteriori informazioni sulle macro e deoffuscare
- p2code per l'analisi del pcode (Non era necessario)
- Macchina virtuale Windows 10 + Macchina Remnux

**W A R N I N G / A V V E R T E N Z E**

L' attività di analisi è stata condotta con l'ausilio di due macchine virtuali isolate dal sistema operativo principale, per questioni di sicurezza sul repository NON sono presenti i file malevoli in questione.
Tutelarsi sempre dall'analisi di tali software!
