# Aprendendo-Git
Estudos iniciais sobre git e github  

inicia o git (repositorio) no seu projeto  
git init

verificar alteracoes de pastas e arquivos no projeto  
git status

adiciona/atualiza um arquivo ao stage area  
git add "nome do arquivo"

Exemplo  
git add frases.txt

adiciona/atualiza todos os arquivos e pastas modificados ao stage area  
git add .

remove um arquivo do stage area  
git restore --staged "nome do arquivo"

Exemplo  
git restore --staged frases.txt

restaura o arquivo na versáo anterior do stage area  
git restore "nome do arquivo"

Exemplo
git restore Frases.txt

remove um arquivo do stage area  
git restore --staged "nome do arquivo"

Exemplo  
git restore --staged frases.txt
git restore <file>

cria e descreve um ponto na historia  
git commit -m "escreva aqui"

historico de commits do projeto  
git log

clonar/copiar um repositorios para a sua maquina  
git clone "url do repositorio"

Exemplo  
git clone "https://github.com/gabriellopes-dev/Aprendendo-Git.git"  

selecionar a pasta no terminal  
cd "diretorio da pata"

Exemplo  
cd C:\Users\NomeDoUsuario\Documentos\Projetos\Aprendendo-Git

mostra a pasta atual  
pwd

listar arquivos da pasta  
ls

voltar a pasta no terminal  
cd ..

