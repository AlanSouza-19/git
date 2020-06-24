# GIT E GITHUB

## Instalação

<https://git-scm/download>

### SCENES

- [x] Você deseja criar pontos na história da produçao do seu projeto
- [x] Vocẽ deseja verificar mudanças feitas no seu projeto

- [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito
- [x] Você adiociona as novas funcionalidades ao seu projeto em produção
- [x] Você quer apagar o branch da nova funcionalidade, depois de aplicar em seu projeto

- [x] Você quer colocar o seu projeto na nuvem

#### GIT BASH COMMANDS

- `git init` -> Inicializa um novo repositório git vazio
- `git add __nomeDoArquivo__` -> Adiciona o(s) arquivo(s) ao Stage para serem commitados
- `git commit -m "__message__"` -> Adiciona um commit (ponto na história) ao projeto
- `git log` -> Mostra os commits do projeto
- `git status` -> Mostra o estado atual do desenvolvimento do projeto (se existe arquivos não comitados e se tem arquivos não adicionados  linha de tempo do projeto)
- `git show` -> Mostra em detalhes do último commit
- `git show __idDoCommit__` -> Mostra os detalhes de um commit específico a partir de um id
- `git branch` -> Mostra as linhas do tempo existentes do projeto (branch = ramificação)
- `git branch __nomeDaNovaBranch__` -> Cria uma nova branch com o nome especificado
- `git branch -D __NomeDaBranch__` -> Deleta a branch especificada (-D = delete)
- `git chekout __nomeDaBranch__` -> Alterna entre as branchs existentes do projeto
- `git marge __NomeDaBranch__` -> Mescla a linha do tempo de uma branch à branch master

- `git remote add __URLdoRepositório__` -> adciona a url do repositório do GitHub
- `git push -u origin master` -> tranfere os arquivos para o repositório online (quando feito pela prmeira vez no repositório)
- `git push` -> tranfere os arquivos para o repositório online
