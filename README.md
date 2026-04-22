# 📋 Guia de Commits

---

## Tipos de commit

| Tipo | Para que serve | Quando usar | Exemplo |
|------|---------------|-------------|---------|
| ![feat](https://img.shields.io/badge/feat-0C447C?style=flat-square&labelColor=E6F1FB&color=E6F1FB&logoColor=0C447C) | Nova funcionalidade para o usuário | Adicionou algo novo que o usuário vai usar ou sentir | `feat: adicionar login com Google` |
| ![fix](https://img.shields.io/badge/fix-791F1F?style=flat-square&labelColor=FCEBEB&color=FCEBEB) | Correção de bug | Resolveu um comportamento errado ou inesperado | `fix: corrigir cálculo de desconto no carrinho` |
| ![docs](https://img.shields.io/badge/docs-3C3489?style=flat-square&labelColor=EEEDFE&color=EEEDFE) | Alterações em documentação | Mudou README, JSDoc, comentários ou wikis | `docs: atualizar guia de instalação` |
| ![style](https://img.shields.io/badge/style-72243E?style=flat-square&labelColor=FBEAF0&color=FBEAF0) | Formatação sem mudar lógica | Espaços, ponto-vírgula, indentação — sem afetar funcionamento | `style: formatar arquivos com prettier` |
| ![refactor](https://img.shields.io/badge/refactor-27500A?style=flat-square&labelColor=EAF3DE&color=EAF3DE) | Reestruturação de código | Melhorou a estrutura sem corrigir bug nem adicionar feature | `refactor: extrair lógica de pagamento` |
| ![perf](https://img.shields.io/badge/perf-085041?style=flat-square&labelColor=E1F5EE&color=E1F5EE) | Melhoria de performance | Otimizou velocidade, memória ou uso de recursos | `perf: usar índice no campo email do banco` |
| ![test](https://img.shields.io/badge/test-633806?style=flat-square&labelColor=FAEEDA&color=FAEEDA) | Adição ou correção de testes | Criou, ajustou ou removeu testes — sem mexer em código de produção | `test: cobrir cenário de senha inválida` |
| ![build](https://img.shields.io/badge/build-412402?style=flat-square&labelColor=FAC775&color=FAC775) | Sistema de build e dependências | Alterou npm, webpack, tsconfig, Dockerfile ou dependências | `build: atualizar node para v22` |
| ![ci](https://img.shields.io/badge/ci-712B13?style=flat-square&labelColor=FAECE7&color=FAECE7) | Configuração de CI/CD | Mudou GitHub Actions, pipelines, scripts de deploy ou lint | `ci: adicionar step de testes no PR` |
| ![chore](https://img.shields.io/badge/chore-444441?style=flat-square&labelColor=F1EFE8&color=F1EFE8) | Tarefas de manutenção | Tudo que não se encaixa nos outros — bumps de versão, .gitignore, configs | `chore: adicionar .env.example` |

---

## Dicas rápidas

- Use o **imperativo** na descrição: `adicionar`, `corrigir`, `remover` — não `adicionado` ou `adicionando`
- Mantenha a descrição com **menos de 50/72 caracteres**
- Em dúvida entre `fix` e `refactor`: se estava *errado*, é `fix`; se funcionava mas você melhorou, é `refactor`
- Quebre commits grandes em commits menores e focados
