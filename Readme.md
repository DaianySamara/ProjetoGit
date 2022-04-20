Ola, esse projeto para usar o git.

	criar um repositório na máquina:
git init  ( criar um repositório) e vai se torna master
git add README.md (add criado dentro da área steid)
git commit -m "first commit"( para criar um primeiro commit)
git branch -M main (para mudar o nome da branch de master para main)
git remote add origin https://github.com/DaianySamara/ProjetoGit.git ( conectar com github)
git push -u origin main(mandar todos os arquivos para o github) 

-------------------------------------------------------------------------
sempre que fizer alterações e subir para git hub
git add . (para add todo arquivo alterados para a steid)
git status (vai mostrar o que foi adicionado e modificado )
git commit -m “criação do projeto" ( novo commid com uma nova msg)
git push origin main ( esta subindo para o github)

-----------------------------------------------------------------
nova branch
git checkout -b “novo-botao” (sai da main para ir para novo-botao)

git add . (para add todo arquivo alterados para a steid)
git status (vai mostrar o que foi adicionado e modificado)
git commit -m novo botao ( novo commid com uma nova msg)
git push origin novo-botao ( esta subindo para o github)


agora irar aparecer compare & pull request (onde não fica junto e baixa o arquivo. Ver as comparações e desejar migrar na banch principal ->
--------------------------------------------------------------------


voltar para a brach main

git checkout main ( para voltar para a novo-botao so substituir o nome)


---------------------------------------------------------------
merge – pegar a branch ex novo-botao e juntar com a principal main

git merge novo-botao ( para juntar as branch)
Git push origin main


------------------------------------------------------------------------------------------------------------------

puxar do github para a maquina

vai no repositório, vai em code link https e copia, cria uma pasta na maquina terminal bash
Git clone https://github.com/rafaballerini/GitTutorial.git

** salvar as alterações feita no github para o projeto na maquina
Vai na pasta abri no terminal

git pull

