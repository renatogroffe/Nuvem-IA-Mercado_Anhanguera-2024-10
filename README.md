 Conteúdos da apresentação "Nuvem/Cloud Computing em 2024 - Primeiros passos, Azure, Inteligência Artificial, tecnologias, carreira..." realizada em 18/10/2024.

---

# Exemplo de uso do Copilot

O que perguntei:

```
Gere para mim um fluxograma em Mermaid explicando como fica o processo de autenticação multifator (MFA) em um App mobile.
```

Fluxograma:

```mermaid
graph TD
    A[Início] --> B[Usuário abre o App]
    B --> C[Usuário insere credenciais]
    C --> D{Credenciais válidas?}
    D -->|Não| E[Fim]
    D -->|Sim| F[Enviar código MFA]
    F --> G[Usuário insere código MFA]
    G --> H{Código MFA válido?}
    H -->|Não| E[Fim]
    H -->|Sim| I[Acesso concedido]
    I --> J[Fim]
```