# Boas práticas de Git e GitHub

1. **Escreva mensagens de commit claras:** descreva a alteração realizada para
   facilitar a compreensão do histórico do projeto.
2. **Faça commits pequenos e focados:** agrupe mudanças relacionadas para
   facilitar a revisão e a identificação de problemas.
3. **Use branches para novas funcionalidades:** desenvolva em uma branch separada
   e integre as alterações à `main` por meio de um Pull Request.
4. **Revise os Pull Requests antes de mesclar:** confira o diff, verifique os
   arquivos alterados e execute os testes aplicáveis.
5. **Não versione senhas ou tokens:** use variáveis de ambiente e configure o
   `.gitignore` para excluir arquivos locais com informações sensíveis.
6. **Mantenha o repositório local atualizado:** após a integração de mudanças,
   volte à `main` e execute `git pull` para sincronizar com o GitHub.
