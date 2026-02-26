# Estrutura das Branches

main: Branch principal, sempre estável e pronta para entrega.  
feat/<nome-da-feature>: Novas funcionalidades.  
fix/<nome-do-fix>: Correções de bugs.  
hotfix/<nome-do-hotfix>: Correções urgentes diretamente relacionadas à produção.  
refactor/<nome>: Refatorações sem alteração de regra de negócio.  

Regras:

- Nunca commitar diretamente na `main`.
- Após finalizada, a branch deve ser enviada via Pull Request.
- Nome das branches deve ser claro e objetivo, sem espaços e sem acentos.

---

## Prazo para Último Commit e PR

- O último commit da feature deve ocorrer no máximo até 2 dias antes do fechamento da sprint.
- O Pull Request deve ser aberto imediatamente após a finalização da tarefa.
- No último dia da sprint, o código deve estar aprovado e pronto para merge na `main`.

---

## Processo de Pull Request

- O PR deve conter descrição objetiva do que foi feito.
- Deve informar quais tarefas do backlog estão sendo atendidas.
- Deve indicar possíveis impactos ou pontos de atenção.

---

## Checklist obrigatório antes de abrir um PR

- [ ] Código revisado
- [ ] Testes executados
- [ ] Build funcionando
- [ ] Documentação atualizada
- [ ] Nome da branch está no padrão definido
