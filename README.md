# 📋 Guia de Commits

---

## Tipos de commit

| Tipo       | Para que serve                        | Quando usar                                                                 | Exemplo                                         |
|------------|---------------------------------------|-----------------------------------------------------------------------------|-------------------------------------------------|
| `feat`     | Nova funcionalidade para o usuário    | Adicionou algo novo que o usuário vai usar ou sentir                        | `feat: adicionar login com Google`              |
| `fix`      | Correção de bug                       | Resolveu um comportamento errado ou inesperado                              | `fix: corrigir cálculo de desconto no carrinho` |
| `docs`     | Alterações em documentação            | Mudou README, JSDoc, comentários explicativos ou wikis                      | `docs: atualizar guia de instalação`            |
| `style`    | Formatação sem mudar lógica           | Espaços, ponto-vírgula, indentação — sem afetar funcionamento               | `style: formatar arquivos com prettier`         |
| `refactor` | Reestruturação de código              | Melhorou a estrutura sem corrigir bug nem adicionar feature                 | `refactor: extrair lógica de pagamento`         |
| `perf`     | Melhoria de performance               | Otimizou velocidade, memória ou uso de recursos                             | `perf: usar índice no campo email do banco`     |
| `test`     | Adição ou correção de testes          | Criou, ajustou ou removeu testes — sem mexer em código de produção          | `test: cobrir cenário de senha inválida`        |
| `build`    | Sistema de build e dependências       | Alterou npm, webpack, tsconfig, Dockerfile ou dependências                  | `build: atualizar node para v22`                |
| `ci`       | Configuração de CI/CD                 | Mudou GitHub Actions, pipelines, scripts de deploy ou lint                  | `ci: adicionar step de testes no PR`            |
| `chore`    | Tarefas de manutenção                 | Tudo que não se encaixa nos outros — bumps de versão, .gitignore, configs   | `chore: adicionar .env.example`                 |

---

## Dicas rápidas

- Use o **imperativo** na descrição: `adicionar`, `corrigir`, `remover` — não `adicionado` ou `adicionando`
- Mantenha a descrição com **menos de 50/72 caracteres**
- Em dúvida entre `fix` e `refactor`: se estava *errado*, é `fix`; se funcionava mas você melhorou, é `refactor`
- Quebre commits grandes em commits menores e focados
