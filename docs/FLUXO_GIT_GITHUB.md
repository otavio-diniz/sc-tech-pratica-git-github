# Fluxo Git/GitHub praticado

## Visão geral

O laboratório foi desenhado para validar competências remotas com o menor escopo possível e sem tocar em repositórios reais de trabalho.

```text
repositório local
      ↓ push
repositório remoto
      ↓ clone/fetch
branch de exercício
      ↓ commit + push
Pull Request
      ↓ revisão
merge
      ↓
validação da main
```

## Etapas e evidência gerada

| Etapa | O que demonstra |
|---|---|
| Configurar `origin` | Associação correta entre repositório local e remoto |
| `push` inicial | Capacidade de publicar histórico local no remoto |
| `clone` | Capacidade de reconstruir uma cópia de trabalho a partir do GitHub |
| Branch de exercício | Isolamento de alterações antes da integração |
| Commit sintético | Registro atômico e rastreável de uma mudança |
| Push da branch | Sincronização de uma linha de trabalho independente |
| Pull Request | Revisão e comparação antes do merge |
| Merge | Integração deliberada da alteração |
| Readback da `main` | Confirmação de que o resultado esperado chegou à branch principal |

## Aprendizado principal

Git e GitHub não são apenas mecanismos de armazenamento. O valor do fluxo está em **histórico, isolamento, revisão, rastreabilidade e recuperação**. Mesmo um exercício mínimo permite praticar os mesmos conceitos usados em projetos maiores.
