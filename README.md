# To-Do List

Um aplicativo de console em Java para gerenciar tarefas, com suporte a adicionar, listar, marcar como concluída, remover e redefinir status.

## Funcionalidades
- Adicionar tarefas com descrição.
- Listar tarefas pendentes e concluídas.
- Marcar tarefas como concluídas ou redefinir status.
- Remover tarefas.
- Menu interativo com opções centralizadas via enum `OpcaoMenu`.
- Tratamento robusto de erros com exceções.

## Como Executar
1. Clone o repositório: `git clone https://github.com/seu-usuario/to-do-list.git` ou baixe o arquivo zip do projeto
2. Navegue até a pasta: `cd to-do-list`
3. Compile o projeto:
- `PowerShell` javac -d xxxx (Get-ChildItem -Recurse -Filter *.java -Path src | ForEach-Object { $_.FullName })
- `Windows CMD` javac -d xxxx src\application\program.java src\model\entities\*.java src\model\enums\*.java src\model\services\*.java
5. Execute: `java -cp xxxx application.Program`

**OBS: xxxx : nome da pasta destino dos aquivos compilados da pasta src

## Estrutura do Projeto
- `src/application/Program.java`: Ponto de entrada com o menu interativo.
- `src/model/entities/Tarefa.java`: Representa uma tarefa.
- `src/model/enums/OpcaoMenu.java`: Enum para opções do menu.
- `src/model/services/GerenciadorTarefas.java`: Gerencia a lista de tarefas.

## Tecnologias
- ![Java](https://img.shields.io/badge/Java-17+-blue)
- Git para controle de versão
- MySQL
- JDBC
- Eclipse

## Contribuições
Sinta-se à vontade para abrir issues ou pull requests!
