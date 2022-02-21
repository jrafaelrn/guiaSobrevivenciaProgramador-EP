## Tarefas

- Git
    - [ ] Verifique qual o id do commit em que as páginas do juwupiter weeb foram adicionadas, bem como seu autor e data. Registre essas infos em um arquivo TAREFAS.md
- Metaprogramação
    - [ ] Adicione um script no `package.json` para rodar todos os testes de unidade na pasta `src`
    - [ ] Crie um teste de unidade que você achar interessante, utilize pelo menos um `expect` e uma função de mock (`jest.fn()`, nesse caso).
- Containers e Cloud
    - [ ] Crie um Dockerfile para aplicação
    - [ ] Suba um container utilizando o Dockerfile criado e exponha a porta 3000 do container para a sua porta 8080. Acesse a aplicação no navegador do computador hospedeiro, registrando os passos realizados para tal em um arquivo TAREFAS.md
- Shell
    - [ ] Crie um script em shell para gerar a imagem Docker e subir um container a partir dessa imagem. Esse script deve permitir que o usuário escolha em qual porta do computador hospedeiro a aplicação deve rodar
- Tarefas bônus
    - [ ] Utilizar um dos 3 editores de texto expostos nas aulas ou o comando `sed` para trocar todos as tags `<li>` em uma página por tags `<p>`
    - [ ] Utilizar o GitHub para hospedar o EP e registrar o progresso em commits
    - [ ] Utilizar o recurso de CI/CD do GitHub para verificar bugs e memory leaks no código
    - [ ] Utilize um Volume Docker para permitir que os arquivos da pasta `views` possam ser alterados de fora do container