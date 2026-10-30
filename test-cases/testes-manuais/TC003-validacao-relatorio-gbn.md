CT03 — Relatório GBN de Bilhetes Não Voado

Status: Aprovado
Tipo de teste: Teste funcional e validação de dados
Módulo: Relatório GBN — Bilhetes Não Voado

1. Objetivo

Validar a geração do Relatório GBN de Bilhetes Não Voado, verificando se as informações apresentadas na tela correspondem aos dados exportados para Excel, conforme os filtros selecionados.

2. Pré-condições

* Possuir acesso ao ambiente de testes.
* Ter dados disponíveis para consulta.
* Possuir permissão para gerar e exportar o relatório.

3. Cenário de teste

CT03.01 — Validação do Relatório GBN de Bilhetes Não Voado

Procedimento

1. Acessar o módulo Relatório GBN.
2. Selecionar o filtro Data de Criação.
3. Informar o período de 01/10/2026 a 23/10/2026.
4. Selecionar a empresa ou grupo de teste correspondente.
5. Selecionar os campos disponíveis de Status de Bilhete e Sistemas de Reserva.
6. Gerar o relatório na tela.
7. Exportar o relatório para Excel (.xlsx).
8. Abrir o arquivo exportado.
9. Comparar os dados da tela com os dados da planilha.

4. Resultado esperado

O relatório deve ser gerado conforme os filtros selecionados, e as informações exportadas para Excel devem corresponder aos dados apresentados na tela.

5. Resultado obtido

A comparação realizada identificou correspondência entre os dados apresentados na tela e os dados exportados para Excel. O arquivo exportado foi aberto normalmente.

Resultado: Aprovado.

6. Evidências

* Captura de tela dos filtros utilizados.
* Captura do relatório gerado na tela.
* Evidência do arquivo Excel exportado.
