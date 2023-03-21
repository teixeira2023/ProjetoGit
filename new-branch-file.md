criando um commit para a branch criada


******/Documents/GitHub/ProjetoGit (main)
git checkout -b "nova ramificação"
fatal: 'nova ramificação' is not a valid branch name 
***(provavelmente por causa do espaço no nome)***

******/Documents/GitHub/ProjetoGit (main)
git checkout -b "nome-da-branch"
Switched to a new branch 'nome-da-branch'
***(cria a nova branch e alterna para a nova criada)***

******/Documents/GitHub/ProjetoGit (nome-da-branch)
git branch -M "new-branch"
***(mudança de nome da branch)***

******/Documents/GitHub/ProjetoGit (new-branch)
git add .
***(adiciona os novos arquivos)***

******/Documents/GitHub/ProjetoGit (new-branch)
git commit -m "new-branch"
[new-branch 362e408] new-branch
 Committer: Alan 
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 new-branch-file.md
***(novo commit da nova branch)***


******/Documents/GitHub/ProjetoGit (new-branch)
git push origin new-branch
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 370 bytes | 370.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'new-branch' on GitHub by visiting:
remote:      https://github.com/teixeira2023/ProjetoGit/pull/new/new-branch
remote:
To https://github.com/teixeira2023/ProjetoGit.git
 * [new branch]      new-branch -> new-branch
***(envia os arquivos para o Github)***







