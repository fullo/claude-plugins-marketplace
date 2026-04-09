# Fullo Plugins Marketplace

Marketplace di plugin per Claude Code di Francesco Fullone / Daruma Consulting.

## Plugin disponibili

| Plugin | Descrizione |
|--------|-------------|
| **sustainable-manager** | Sustainability Manager - analisi ESG, studi LCA, compliance CSRD/ESRS, rilevamento greenwashing, reportistica sostenibilita |
| **writing-assistant** | Assistente editoriale per la serie "the Right Way": TOV, grammatica italiana, formato Markua/LeanPub, coerenza narrativa |
| **sustainable-code-skill-setup** | Sviluppo software sostenibile - misurazione SCI, compliance W3C WSG 1.0, audit accessibilita, green coding practices |
| **adversarial-verify** | Verifica adversarial del codice — metodologia Chain-of-Verification (CoV) per code review rigorosa, decomposizione scettica dei claim, e rilevamento bug basato su evidenze |
| **adversarial-thinking** | Compagno di pensiero adversarial — metodo socratico, cognitive forcing, desirable difficulties. Rende il pensiero piu' difficile, non piu' facile. |
| **thinking-habit** | Profilatore cognitivo — scopre come pensi attraverso 5 dimensioni (canale, strategia, direzione, medium, logica), traduce i prompt nel tuo stile, e media la comunicazione tra profili diversi. |

## Aggiungere il marketplace

```bash
claude plugin marketplace add fullo/claude-plugins-marketplace
```

oppure dall'interno di Claude Code:

```
/plugin marketplace add fullo/claude-plugins-marketplace
```

## Installazione plugin

Per installare un plugin da questo marketplace:

```bash
claude plugin install <plugin-name>@fullo-plugins
```

oppure dall'interno di Claude Code:

```
/plugin install <plugin-name>@fullo-plugins
```

## Aggiornare il marketplace

```bash
claude plugin marketplace update fullo-plugins
```
