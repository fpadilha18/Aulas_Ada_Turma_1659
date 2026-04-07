# Aulas_Ada_Turma_1659
Aulas ADA modulo 2

*** teste de insercao de dados (nuvem - pc)

* para alterar diretorio, no cmd ou bash:

cd "/c/Users/Fábio Padilha/Aulas_Ada_Turma_1659"

C:\Users\Fábio Padilha\Aulas_Ada_Turma_1659
	C:\Users\Fábio Padilha\Aulas_Ada_Turma_1659>git status
	On branch main
	Your branch is up to date with 'origin/main'.
	nothing to commit, working tree clean

** para "puxar" da nuvem para o PC

C:\Users\Fábio Padilha\Aulas_Ada_Turma_1659>git pull origin main

	remote: Enumerating objects: 5, done.
	remote: Counting objects: 100% (5/5), done.
	remote: Compressing objects: 100% (2/2), done.
	remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
	Unpacking objects: 100% (3/3), 950 bytes | 12.00 KiB/s, done.
	From https://github.com/fpadilha18/Aulas_Ada_Turma_1659
	 * branch            main       -> FETCH_HEAD
	   ca14021..4dd80ff  main       -> origin/main
	Updating ca14021..4dd80ff
	Fast-forward
	 README.md | 2 ++
	 1 file changed, 2 insertions(+)


*** novo teste de insercao de dados (pc - nuvem)

salva o arquivo .txt, se não ele não identifica mudanças para enviar

git commit -m "Minha alteração no README via pc, passando pra nuvem"
	On branch main
	Your branch is up to date with 'origin/main'.

	Changes not staged for commit:
	  (use "git add <file>..." to update what will be committed)
	  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

	no changes added to commit (use "git add" and/or "git commit -a")

git add README.md
	git commit -m "Atualizando o README pelo computador"
	[main b78f005] Atualizando o README pelo computador
	 1 file changed, 31 insertions(+), 1 deletion(-)

Fábio Padilha@DeathStar MINGW64 ~/Aulas_Ada_Turma_1659 (main)
$ git push origin main
	Enumerating objects: 5, done.
	Counting objects: 100% (5/5), done.
	Delta compression using up to 4 threads
	Compressing objects: 100% (2/2), done.
	Writing objects: 100% (3/3), 773 bytes | 773.00 KiB/s, done.
	Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
	To https://github.com/fpadilha18/Aulas_Ada_Turma_1659.git
	   4dd80ff..b78f005  main -> main




