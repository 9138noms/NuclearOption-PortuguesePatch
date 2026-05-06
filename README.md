# Nuclear Option – Patch em Português (Localization Patch)

Mod de tradução para o português para o Nuclear Option. Funciona como plugin do BepInEx e traduz a interface, enciclopédia, dicas e descrições — no total **1.886 entradas**.

## Requisitos

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Acesso Antecipado 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Instalação

1. Instale o **BepInEx 5.x** na pasta do jogo.
   ```
   Exemplo: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Inicie o jogo **uma vez** e feche-o. (Isto cria a estrutura de pastas do BepInEx.)

3. Copie todos os arquivos deste repositório para:
   ```
   [Pasta do jogo]\BepInEx\plugins\LocalizationPatch\
   ```
   > Se a pasta `LocalizationPatch` não existir, crie-a manualmente.

4. Inicie o jogo — **a tradução em português será aplicada automaticamente**.

### Instalador automático (alternativa)

https://github.com/9138noms/NuclearOption-LocalizationInstaller/releases/latest

## Atalhos no jogo

| Tecla | Função |
|-------|--------|
| `F10` | Mostrar/ocultar overlay de depuração |
| `Ctrl+F10` | Recarregar dados de tradução (hot-reload) |

## Notas

- Nomes de facções (PALA, BDF, BOSCALI, PRIMEVA, FFL, LMA) e codinomes de aeronaves / armamentos (Compass, Alkyon AB-4, FGA-57 Anvil, IRM-S2, etc.) permanecem em inglês.
- Em caso de problemas, especifique o idioma manualmente em `BepInEx\config\com.noms.localizationpatch.cfg`, definindo `Language = pt`.

## Tradução

- Tradução automática inicial via Google Translate — correções da comunidade são bem-vindas via PR ou Issue.
- Plugin / framework: https://github.com/9138noms/NuclearOption-TranslationToolkit
