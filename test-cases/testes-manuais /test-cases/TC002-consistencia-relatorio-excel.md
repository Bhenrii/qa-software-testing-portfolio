CT02 — Validação de Consistência do Gerador de Relatórios

Status: Aprovado — consistência dos dados
Tipo de teste: Teste funcional e validação de dados
Módulo: Gerador de Relatórios

1. Objetivo

Validar se os dados apresentados na tela do Gerador de Relatórios correspondem aos dados exportados para Excel, considerando os mesmos filtros de consulta.

2. Pré-condições

* Ter acesso ao ambiente de testes.
* Possuir dados disponíveis para consulta.
* Ter permissão para utilizar o Gerador de Relatórios.

3. Cenário de teste

CT02.01 — Comparação dos dados exibidos na tela e exportados para Excel

Procedimento:

1. Acessar o módulo Gerador de Relatórios.
2. Selecionar o filtro de Data de Criação.
3. Informar o período de consulta de 01/10/2026 a 23/10/2026.
4. Selecionar o grupo de teste correspondente.
5. Selecionar os campos que serão apresentados no relatório.
6. Gerar o relatório na tela.
7. Exportar o mesmo relatório no formato Excel (.xlsx).
8. Comparar os dados apresentados na tela com os dados exportados.

4. Resultado esperado

Os dados apresentados na tela e os dados exportados para Excel devem corresponder aos mesmos filtros e critérios de consulta, sem divergências nas informações retornadas.

5. Resultado obtido

Foi realizada a comparação entre as informações exibidas na tela e os dados exportados para Excel. As informações verificadas apresentaram correspondência entre os dois formatos.

Resultado: Aprovado para consistência dos dados.

6. Evidências

* Captura de tela dos filtros utilizados.
* Captura do relatório gerado na tela.
* Comparação com os dados exportados para Excel, com informações fictícias ou devidamente anonimizadas.

7. Observações

A aprovação refere-se à consistência dos dados comparados. A abertura do arquivo, a formatação das células e a organização visual da planilha não foram documentadas como verificações independentes neste cenário.
