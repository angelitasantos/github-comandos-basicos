### Digital Innovation One - GitHub Comandos Basicos
#### Aula pratica de Git x Github 01 de junho de 2020
#### Atualizado em 15 de novembro de 2022 (Python/Django)
#### Lista de comandos úteis Git x Github

<header>
    <h1>Git x GitHub</h1>
    <h2>Comandos Básicos</h2>
</header>

<section>
<h3>Configuração</h3>
<ul>
    <li>Setar usuário: git config --global user.name "nome"</li>
    <li>Setar email: git config --global user.email "email"</li>
    <li>Listar configurações: git config --list</li>
</ul>

<h3>Repositório Local</h3>
<ul>
    <li>Criar novo repositório: git init</li>
    <li>Verificar estado dos arquivos/diretórios: git status</li>
    <li>Exibir histórico: git log</li>

<h4>Adicionar arquivo/diretório</h4>
<ul>
    <li>Adicionar um arquivo em específico: git add meu_arquivo.txt</li>
    <li>Adicionar um diretório em específico: git add meu_diretorio</li>
    <li>Adicionar todos os arquivos/diretórios: git add .</li>
    <li>Adicionar um arquivo que esta listado no .gitignore: git add -f arquivo_no_gitignore.txt</li>
</ul>

<h4>Comitar arquivo/diretório</h4>
<ul>
    <li>Comitar um arquivo: git commit meu_arquivo.txt</li>
    <li>Comitar vários arquivos: git commit meu_arquivo.txt meu_outro_arquivo.txt</li>
    <li>Comitar informando mensagem: git commit meuarquivo.txt -m "minha mensagem de commit"</li>
</ul>

<h4>Remover arquivo/diretório</h4>
<ul>
    <li>Remover arquivo: git rm meu_arquivo.txt</li>
    <li>Remover diretório: git rm -r diretorio</li>
</ul>

<h4>Desfazendo operações</h4>
<ul>
    <li>Desfazendo alteração local (working directory): git checkout -- meu_arquivo.txt</li>
    <li>Desfazendo alteração local (staging area): git reset HEAD meu_arquivo.txt</li>
</ul>
</ul>

<h3>Repositório Remoto</h3>
<ul>
    <li>Exibir os repositórios remotos: git remote</li>
    <li>Vincular repositório local com um repositório remoto: git remote add origin "link_do_repositorio"</li>
    <li>Exibir informações dos repositórios remotos: git remote show origin</li>
    <li>Renomear um repositório remoto: git remote rename origin "novo_nome"</li>
    <li>Desvincular um repositório remoto: git remote rm "nome_do_repositorio"</li>
    <li>Enviar arquivos/diretórios para o repositório remoto: git push -u origin main</li>
    <li>Clonar um repositório remoto já existente: git clone "nome_do_repositorio"</li>

<h4>Atualizar repositório local de acordo com o repositório remoto</h4>
<ul>
    <li>Atualizar os arquivos no branch atual: git pull</li>
    <li>Buscar as alterações, mas não aplica-las no branch atual: git fetch</li>
</ul>
<h4>Branches</h4>
<ul>
    <li>Criando um novo branch: git branch novo_branch</li>
    <li>Trocando para um branch existente: git checkout novo_branch</li>
    <li>Criar um novo branch e trocar: git checkout -b novo_branch</li>
    <li>Voltar para o branch principal: git checkout main</li>
    <li>Resolver merge entre os branches: git merge nome_branch</li>
    <li>Apagando um branch: git branch -d nome_branch</li>
    <li>Listar branches: git branch</li>
    <li>Criando branches no repositório remoto: git push origin nome_branch</li>
</ul>
</ul>

<h3>Git e Github - Do clone ao pull request</h3>
<a href="https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/" target="_blank">Clique aqui
    para saber mais</a>
</section>

<footer>
    <h4>Comandos retirados do repositório de: <a href="https://gist.github.com/leocomelli/2545add34e4fec21ec16" target="_blank">Leo Comelli</a></h4>
</footer>