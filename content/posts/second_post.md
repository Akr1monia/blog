---
title: Deep seek, l’IA cinese contro gli oligarchi tecnologici americani
date: 2025-01-31
description: Deep seek r1, un nuovo llm che sbaraglia i benchmark attuali
summary: Il rilascio di deep seek all'indomani dell'accordo stargate fa vacillare le certezze degli oligarchi tecnologici.
toc: true
---

Il 26 gennaio è stato rilasciato **DeepSeek-R1**, successore di V3, di proprietà dell’omonima azienda cinese. Questo a pochi giorni dopo l’annuncio **del piano Stargate**, un investimento da 500 miliardi di dollari per accelerare lo sviluppo dell’AGI. Il piano, sostenuto da **colossi tecnologici come Meta, Amazon, Google e OpenAI**, include la costruzione di nuovi data center nei prossimi quattro anni e segue la revoca di **Trump** di alcune restrizioni imposte dall’amministrazione Biden sull’uso dell’IA nella governance pubblica. Gli attori coinvolti sono OpenAi di Sam Altman , Oracle - azienda colosso del cloud, Soft Bank e  un fondo di investimenti emiratino.

### La balena blu
L’uscita di DeepSeek-R1 ha scosso il settore, causando tra le altre il **crollo delle azioni Nvidia**, la cui tecnologia è fondamentale per l’addestramento dei modelli di OpenAI.

{{< figure src="posts/img/nvidia.png"  width="auto" >}}


Il modello sembra una copia carbone di chat-gpt, sia nell'interfaccia web che nelle funzionalità. Due però sono gli aspetti che destano maggiore allarme.
1. DeepSeek-R1 si è rivelato più performante di GPT-4o nei benchmark, **eccellendo nella comprensione del linguaggio** naturale e nelle operazioni logico-matematiche. 
2. R1 è oltre **20 volte più economico** rispetto ai competitor ed è disponibile in una versione **Open Source**, cioè scaricabile e utilizzabile con infrastrutture relativamente economiche.

{{< figure src="posts/img/benchmark.png"  width="auto" >}}

### Un pessimo bugiardo
Tuttavia, il modello presenta limitazioni e criticità. DeepSeek-R1 **applica filtri severi** su argomenti sensibili per il governo cinese, **censurando** qualsiasi informazione su repressioni o violazioni dei diritti umani. Questo sistema si basa su una guardrail che rileva e blocca alcuni argomenti discussi da umano e IA. Non è difficile però aggirare i controlli giocando un po' con il chatbot. In questo caso abbiamo provato a chiedere di sostituire alcune lettere con dei numeri

{{< figure src="posts/img/chat.png"  width="auto" >}}

Inoltre è dubbia la vera natura del modello. Come già accennato questo è disponibile OpenSource, ed è quindi scaricabile e visionabile nella sua architettura. Manca però l'algoritmo di addestramento. Dettaglio fondamentale senza il quale è impossibile ricreare il modello da zero dal proprio computer. Sulla base di questa mancanza OpenAI accusa l'azienda cinese di aver costruito R1 distillandolo da gpt. Il processo di distillazione prevederebbe , a grandi linee, di usare gli output del modello forte per migliorare e addestrare il modello debole. La pratica di per sé non ha nulla di sbagliato ma in questo caso i termini di utilizzo di OpenAi la impediscono chiaramente. R1 in tutto questo appare confuso, spesso dichiara di essere ChatGpt, cancella le sue risposte a metà, chiede di parlare di altro, insomma un pessimo bugiardo.

### Il segreto di pulcinella
Debole anche l'infrastruttura. Il 29 gennaio, la società di sicurezza Wiz ha scoperto una **vulnerabilità nei database** di DeepSeek che esponevano pubblicamente log, chat e dati degli utenti. Il problema è stato risolto rapidamente, ma ha sollevato **dubbi sulla sicurezza** dell’infrastruttura e sulla gestione dei **dati sensibili** da parte dell’azienda cinese.

{{< figure src="posts/img/wiz2.png"  width="auto" >}}

### Defensor privacy
Sul fronte privacy, il 28 gennaio il **Garante italiano** ha annunciato l’apertura di un’istruttoria su DeepSeek, evidenziando preoccupazioni legate alla normativa cinese sulla protezione dei dati, molto diversa da quella europea. L’app è stata **rimossa dagli store** di Google e Apple in Italia, ma resta accessibile via desktop. Il modello cinese raccoglie una quantità di dati superiore a quella di qualsiasi altro chatbot e come indicato nella sua informativa **applica la legislazione cinese** senza chiaro riferimento alle **normative europee**.

### Cambio degli equilibri
L’industria cinese cerca di recuperare la gara sull’intelligenza artificiale, l’America sente il fiato sul collo. All’indomani del’insediamento di Trump il conflitto geostrategico con la Cina ritorna in primo piano. Stargate è nato sotto una cattiva stella e in quella che assume tutte le caratterstiche di una corsa allo spazio gli USA vivono un secondo “momento sputnik” vedendo dissolversi la loro certezza di una superiorità tecnologica.