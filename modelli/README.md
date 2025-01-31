# Modelli

In questa pagina raccogliamo una lista di modelli computazionali per la lingua italiana.

## Testo

Modelli *pretrained*: si tratta di modelli generici che e' possibile specializzare a seconda del caso specifico.

- [BART-IT](https://github.com/MorenoLaQuatra/bart-it) 🖊️ E' un modello di analisi e generazione testuale in lingua italiana. Può essere utilizzato in vari contesti tipo [sintesi automatica](https://huggingface.co/morenolq/bart-it-ilpost), transferimento dello stile (da informale a formale), etc.
- [Fauno](https://github.com/RSTLess-research/Fauno-Italian-LLM) Un conversational LLM italiano che può essere utilizzato per una ampia gamma di tasks. Questo è possibile grazie alle sue doti di in-context learning o attraverso il fine-tuning dei pesi LoRA.
- [IT5](https://github.com/gsarti/it5) Versione italiana di T5, un modello di generazione testuale per task sequence-to-sequence disponibile in 4 dimensioni (small, base, large, small-efficient). 50+ checkpoints di IT5 con fine-tuning su vari task di generazione (summarization, style transfer, headline generation) sono [disponibili sull'Huggingface Hub](https://huggingface.co/it5) 
- [Camoscio](https://github.com/teelinsan/camoscio) Versione italiana di Stanford Alpaca. E' un modello generativo addestrato a seguire le istruzioni in linguaggio naturale in italiano.
- [Stambecco](https://github.com/mchl-labs/stambecco) Versione italiana di Stanford Alpaca (GPT-4-LLM). E' un modello generativo addestrato a seguire le istruzioni in linguaggio naturale in italiano, addestrato su un dataset di istruzioni generato con GPT-4


Modelli *fine-tuned*: si tratta di modelli gia' specializzati ad un caso specifico

- [HATE-ITA](https://github.com/MilaNLProc/hate-ita) 🍕 E' un modello per il riconoscimento automatico (binario, si/no) di contenuto d'odio su Twitter. 
- [FEEL-IT](https://github.com/MilaNLProc/feel-it) E' un modello per inferire il "sentiment" (positivo o negativo) e le emozioni da un testo.

## Immagini e Testo

- [CLIP Italian](https://github.com/clip-italian/clip-italian) 🤌 E' un modello multimodale che unisce immagini e testi italiani. Si puo' usare, ad esempio, per cercare, data una descrizione testuale, l'immagine "piu' simile" in una collezione a quel testo. 
