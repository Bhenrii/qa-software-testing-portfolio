TC001 — Investigação de falha na geração de relatório

1. Identificação

* ID: TC001
* Categoria: Teste funcional / Investigação de defeito
* Funcionalidade: Geração de relatório e exportação para Excel
* Tipo de teste: Teste manual
* Status: Reprovado

2. Objetivo

Verificar se a funcionalidade de geração de relatório permite aplicar os filtros disponíveis e gerar um arquivo Excel com os dados correspondentes aos critérios selecionados.

3. Pré-condições

* Acesso autorizado ao ambiente de testes.
* Funcionalidade de relatórios disponível para execução.
* Critérios de consulta definidos para o período de teste.

4. Passos executados

1. Acessar a funcionalidade de geração do relatório.
2. Informar o período de consulta.
3. Selecionar uma empresa para filtrar os resultados.
4. Repetir a consulta utilizando a opção de todas as empresas.
5. Acionar a geração do relatório.
6. Verificar se o arquivo Excel é disponibilizado.
7. Analisar os erros apresentados no console do navegador.
8. Comparar o comportamento observado com o de outras versões disponíveis para teste.

5. Resultado esperado

* A tela deve permitir a seleção dos filtros disponíveis.
* A consulta deve processar os critérios informados.
* O relatório deve ser gerado e disponibilizado para exportação.
* Eventuais erros devem ser investigados para determinar sua relação com a falha.

6. Resultado obtido

Durante a execução, foram observados os seguintes comportamentos:

* O arquivo Excel não foi disponibilizado.
* A tela apresentou comportamento aparentemente estático.
* A seleção de empresa e a interação com os filtros ficaram limitadas.
* O console do navegador apresentou erros de JavaScript, CORS e política de permissões.

O comportamento também foi observado em outras versões consultadas durante a investigação.

7. Análise técnica inicial

Os erros registrados no console indicam possíveis problemas relacionados à execução de JavaScript e à comunicação entre origens diferentes.

Entretanto, não foi confirmada uma relação causal entre esses erros e a falha na geração do relatório.

A ocorrência de comportamento semelhante em outras versões também impede atribuir o problema exclusivamente à atualização técnica investigada.

Conclusão técnica: a falha funcional foi reproduzida, mas a causa raiz permanece indeterminada.

8. Evidências — Cenários executados

Evidência 01 — Consulta com empresa específica

Cenário: Foi informado o período de criação de 24/08/2026 a 23/10/2026 e selecionada uma empresa específica para a consulta.

Resultado observado: A tela apresentou comportamento estático, sem permitir concluir o fluxo de consulta e geração do relatório. O arquivo Excel não foi disponibilizado.

Evidência 02 — Consulta com todas as empresas

Cenário: Os mesmos critérios de período foram utilizados, alterando o filtro de empresa para abranger todas as empresas disponíveis.

Resultado observado: O comportamento permaneceu semelhante ao cenário anterior. Não foi possível concluir a geração do relatório nem obter o arquivo Excel.

Evidência 03 — Análise dos erros técnicos

Cenário: Durante a investigação, foi analisado o console do navegador para identificar possíveis erros associados ao comportamento da funcionalidade.

Resultado observado: Foram identificadas mensagens relacionadas a erro de JavaScript, política de CORS e restrição de permissões do navegador. A relação direta entre essas mensagens e a falha na geração do relatório não foi confirmada.

Evidência 04 — Comparação entre versões

Cenário: O comportamento da funcionalidade foi comparado com o observado em outras versões disponíveis para teste.

Resultado observado: Comportamento semelhante também foi identificado nas versões consultadas. A comparação não permitiu determinar a causa raiz nem atribuir a falha exclusivamente à atualização técnica investigada.

Observação: As evidências são descritas textualmente para documentar os cenários, os resultados observados e as limitações da análise. Não são anexados prints, imagens ou logs internos.

9. Limitações

* A causa raiz não foi confirmada.
* A relação entre os erros do console e a falha funcional não foi comprovada.
* A comparação entre versões não foi suficiente para determinar a origem do problema.

10. Aprendizados

* Diferenciar o comportamento observado de uma hipótese técnica.
* Registrar resultados com base em evidências.
* Investigar erros de console sem assumir causalidade.
* Evitar atribuir uma falha a uma alteração técnica sem confirmação.
