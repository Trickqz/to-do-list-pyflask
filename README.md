# Flask To-Do App

Este é um simples aplicativo de lista de tarefas desenvolvido em Python usando o framework Flask. O aplicativo permite aos usuários adicionar tarefas com título e descrição, bem como remover tarefas existentes conforme necessário.

## Funcionalidades

- **Adicionar Tarefas:** Os usuários podem adicionar novas tarefas inserindo um título e uma descrição.
- **Remover Tarefas:** As tarefas existentes podem ser removidas individualmente.

## Requisitos

Para executar este projeto localmente, você precisa ter Python 3.x instalado em seu sistema, juntamente com os pacotes Flask e openpyxl.

## Utilização

1. Clone este repositório e navegue até o diretório do projeto.
2. Instale as dependências usando `pip install -r requirements.txt`.
3. Execute o aplicativo com `python app.py`.
4. Abra um navegador da web e visite [http://localhost:5000](http://localhost:5000).

## Estrutura do Projeto

- **app.py:** O código principal do aplicativo, contendo a lógica de roteamento e manipulação de tarefas.
- **templates/:** Esta pasta contém os modelos HTML usados para renderizar as páginas web.
- **tasks.xlsx:** Uma planilha Excel usada para armazenar as tarefas adicionadas pelos usuários.