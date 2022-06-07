# Desafio Git & Github - DIO

## Comandos mais usados do git

* **Git config --local user.name "Seu nome aqui"** (para saber o autor das alterações no código)
* **Git config --local user.email "seu@email.aqui"** (para saber o autor das alterações no código)
* **Git config user.name / user.email**
* **Git --verson -> verificar versão do git**
* **Git init** -> inicializar um repositório dentro do diretório onde foi inicado o git bash (cria a pasta .git);
* **Git init --bare** -> indica que o repositorio git só conterá as alterações dos arquivos.
* **Git status** -> verificar o que foi feito (status);
* **Git add .** -> adicionar ao versionamento todos os arquivos dentro da pasta;
* **Git commit -m ""** -> informar mensagem de commit;
* **Git log** - verificar os commits que foram feitos;
* **Git log --oneline**
* **Git log -p**
* **Git remote** - lista os repositorios remotos adicionados;
* **Git remote add |nome do repositorio| |link repositorio|** -> adicionar repositório remoto;
* **Git remote -v** -> mostra além do nome o endereço dele;
* **Git push |nome do servidor| |nome da branch|** - empurrar atualizações 
* **Git pull |nome do servidor| |nome da branch|** - pegar atualizações
* **Git branch |nome da branch|** -> criar branch ou consultar as branchs existentes
* **Git checkout |nome da branch|** -> mudar de branch
* **Git checkout -b |nome da branch|** -> cria e muda de branch
* **Git merge |nome da branch que quer unir com a que você está atualmente|** -> unir branchs
* **Git rebase |nome da branch|** -> unir branchs com o commit
* **Git checkout -- |file|** -> desfazer (ctrlZ) a alteração que foi feita no código antes de fazer git add;
* **Git reset HEAD |file|** -> desfazer (ctrlZ) a alteração que foi feita no código depois de fazer git add;
* **Git revert |hash|** -> desfazer (ctrlZ) a alteração que foi feita no código depois de fazer o commit. Apagará o commit
* **Git stash** -> guarda o que foi feito (antes do add e commit) para retornar depois e terminar depois (sem gerar commits);
* **Git stash list** -> mostra tudo o que foi guardado;
* **Git stash pop** -> tira do stash a ultima alteração que foi colocada (depois continuar editando o arquivo e fazer git add/git commit normalmente);
* **Git stash apply <numero do stash>** -> tira o stash o que foi solicitado;
* **Git checkout |hash|** -> voltar a atuar a partir de um commit specífico (para o commit não ficar perdido é necessário que se crie uma branch);
* **Git diff |hash| .. |hash|** -> o que tem de diferente entre dois commits;

* [Documentação Git](https://git-scm.com/docs/git/pt_BR) 
* [Documentação GitHub](https://docs.github.com/pt)
* [Documentação Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

