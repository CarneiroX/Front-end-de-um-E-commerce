# Front-end-de-um-E-commerce
Um projeto front-end de um E-commerce proposto na faculade. O sitem contém elementos HTLM, CSS, e JavaScript


Como Rodar o Projeto:

. SQLITE 3: 
	. Ter o SQLITE 3 Instalado no PC: https://www.sqlite.org/download.html
	. Baixar o "sqlite-tools-win32-x86-3390400.zip" 
	. Extrair a pasta e executar o arquivo "sqlite3"
---------------------------------------------------------------------------------------------------
. CMD:
	- cd C:\Users\alexc\Desktop\A3_WEB (No caso, mudar pro diretório onde baixou o projeto)
	- .\env\Scripts\activate
	- set FLASK_APP=crud.py (Caso dar erro no anterior tentar esse: set FLASK_APP=crud)
	- set FLASK_ENV=development
	- flask run
	- Copiar a porta e abrir no navegador: http://127.0.0.1:5000/
---------------------------------------------------------------------------------------------------
. Site:
	- No site para acessar a tela de Admin, precisa colocar o "/admin" no endereço
			Exemplo: http://127.0.0.1:5000/admin
	- Para visualização da Tela Mobile, ir na pasta "mobile" e abrir o arquivo "usuario.html"
---------------------------------------------------------------------------------------------------
. SQLITE VIEWER: 

	- Site para visualização do Banco de Dados: https://inloop.github.io/sqlite-viewer/
	. Abrir o arquivo "banco.db" no site
	. Há um arquivo de Backup desse Banco de Dados na pasta "Mobile"
	. Caso Necessite rodar ele, só renomear para "banco" e mover para pasta "A3_WEB"
