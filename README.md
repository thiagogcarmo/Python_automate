Organizador de Arquivos por Data
Este script em Python organiza arquivos em um diretório com base na data de modificação de cada arquivo. Ele cria pastas nomeadas de forma intuitiva (ex: "aula do dia 03.12.2025") para agrupar os arquivos por data.

Funcionalidade
Organização Automática: O programa verifica todos os arquivos no diretório fornecido e os organiza em pastas criadas automaticamente.
Pasta por Data: Para cada arquivo, uma pasta será criada com o nome no formato "aula do dia dd.mm.yyyy", usando a data de modificação do arquivo.
Mover Arquivos: Os arquivos serão movidos para suas respectivas pastas.
Requisitos
Python 3.x
Biblioteca shutil (já inclusa no Python padrão)
Biblioteca os (já inclusa no Python padrão)
Biblioteca datetime (já inclusa no Python padrão)
Como Usar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu_usuario/organizador-de-arquivos-por-data.git
Instale as dependências (se houver): Nenhuma dependência externa é necessária, pois o script usa apenas bibliotecas padrão do Python.

Modifique o diretório de origem: No código, altere o valor da variável diretorio_origem para o diretório onde seus arquivos estão localizados:

python
Copiar
Editar
diretorio_origem = "caminho/do/seu/diretorio"
Execute o script: Depois de configurar o diretório de origem, execute o script no terminal:

bash
Copiar
Editar
python organizador_de_arquivos.py
O script irá criar as pastas automaticamente e mover os arquivos para os diretórios com base na data de modificação.

Exemplo de Execução
Se você tem os seguintes arquivos:

Copiar
Editar
documento1.txt
relatorio2.pdf
foto3.jpg
E eles foram modificados em 03/12/2025, 04/12/2025 e 05/12/2025, respectivamente, o script criará as pastas:

arduino
Copiar
Editar
aula do dia 03.12.2025/
aula do dia 04.12.2025/
aula do dia 05.12.2025/
E moverá os arquivos para as pastas correspondentes.

Contribuições
Sinta-se à vontade para fazer contribuições! Se encontrar problemas ou tiver sugestões de melhorias, crie uma issue ou envie um pull request.
