## 🚗 Sistema de Automação de Abastecimento

### <h4>1. 📄 <u>Resumo do Projeto</u></h4>
Este projeto automatiza o processo de inserção de dados de abastecimento de veículos em um sistema web desenvolvido pela **S&S Informática**, que é utilizado para o controle da frota de veículos municipais. O sistema de veículos visa atender às exigências do Tribunal de Contas do Estado (TCE), especialmente no que se refere ao envio de informações através do **Sistema de Informações Municipais (SIM)**.

A automação é construída em **Python** utilizando a biblioteca **Selenium**. A solução lê informações de um arquivo **Excel** e preenche automaticamente os campos de um formulário online de abastecimento de veículos. Com isso, o tempo gasto no preenchimento manual é significativamente reduzido e os erros humanos são eliminados, garantindo conformidade e eficiência no controle da frota.



### 2. 🎯 <u>**Objetivos**</u>
- Automatizar o **registro de abastecimentos** em um sistema de gestão.
- Aumentar a **precisão e eficiência**, minimizando erros manuais.
- Facilitar o **controle e a gestão** dos registros de abastecimento.



### 3. 🚀 <u>**Principais Funcionalidades**</u>
- **Login automático** no sistema de gestão de abastecimento.
- **Preenchimento automático de formulários** com dados como placa, quilometragem, litros e combustível.
- **Integração com arquivos Excel** para leitura e inserção de dados.
- **Validação e finalização dos registros** de abastecimento.
- **Relatório de conclusão** ao término do processo de automação.



### 4. ⚙️ <u>**Processo de Automação**</u>
A automação deste projeto segue um fluxo contínuo de operações, permitindo que grandes volumes de dados sejam processados com rapidez e precisão.

### 🔄 Etapas do Processo:
1. **Leitura de Arquivo Excel**: O sistema lê o arquivo `abastecimento.xlsx` da pasta `datasets/`, extraindo dados como data, hora, quilometragem, litros, placa e contrato.
2. **Interação com o Sistema Web**: Utilizando **Selenium**, o script navega até o sistema de abastecimento, realiza login automático e navega até o formulário de novo abastecimento.
3. **Preenchimento dos Dados**: Os campos do formulário são preenchidos automaticamente com base nos dados extraídos do Excel. Sugestões de "placa" e "contrato" são validadas.
4. **Confirmação e Finalização**: Após inserir os dados, o sistema valida as entradas e finaliza o registro do abastecimento.
5. **Relatório Final**: Exibe um relatório indicando a conclusão do processo de abastecimento para o mês.



### 5. 🛠 <u>**Requisitos**</u>
- **Python 3.12**: Linguagem principal do projeto.
- **Selenium**: Biblioteca para automação de navegador.
- **Pandas**: Biblioteca para leitura e manipulação de dados.
- **ChromeDriver**: Ferramenta necessária para controle do navegador Google Chrome.
- **Arquivo Excel**: O arquivo `abastecimento.xlsx` com os dados de abastecimento, localizado na pasta `datasets/`.



### 6. 📊 <u>**Resultados Esperados**</u>
- **Redução de até 80% no tempo** de registro manual.
- **Precisão de 95%** nos dados inseridos.
- **Aumento da produtividade**, liberando a equipe para tarefas estratégicas.
- **Melhor controle dos registros**, com dados precisos e padronizados.



### 7. 🏆 <u>**Benefícios do Sistema**</u>
- **Eficiência**: Automação rápida e precisa, eliminando o tédio, erros e cansaço do processo manual.
- **Escalabilidade**: Capacidade de lidar com grandes volumes de dados.
- **Controle de Qualidade**: Garantia da integridade dos dados, com planilhas padronizadas e validação automática.



### 8. 📝 <u>**Observações Finais e Melhorias Futuras**</u>

#### 🔒 **Dados Fictícios**
Os dados utilizados nos arquivos deste projeto são totalmente **fictícios**, servindo apenas para fins de desenvolvimento, teste e demonstração. Nenhuma informação real ou sensível foi usada ou armazenada.

#### 💻 **Possíveis Melhorias**
Este projeto representa apenas a fase inicial de uma solução de automação mais robusta e abrangente. Algumas melhorias que podem ser implementadas no futuro incluem:

- **Validações aprimoradas**: Adicionar verificações automáticas de consistência dos dados antes da inserção para garantir maior precisão.
- **Interface gráfica (GUI)**: Desenvolver uma interface gráfica para tornar o processo de automação mais acessível para usuários que não têm experiência com programação.
- **Integração com banco de dados**: Conectar a automação diretamente a um banco de dados para evitar a dependência de arquivos Excel e melhorar o gerenciamento de dados.
- **Relatórios automáticos**: Implementar a geração de relatórios automáticos pós-abastecimento, oferecendo métricas sobre o uso do sistema e o desempenho da frota.
- **Melhorias no código**: Refatorar o código, criando **funções modulares** para organizar melhor a automação. Isso permitirá uma maior reutilização do código, facilitando a manutenção e adicionando novas funcionalidades no futuro.
  - **Funções de login**: Separar o processo de login em uma função específica.
  - **Funções de preenchimento de formulário**: Dividir o preenchimento de dados em funções individuais para cada campo ou grupo de campos.
  - **Tratamento de erros**: Implementar funções de tratamento de exceções (erros), com logs detalhados para facilitar o diagnóstico e correção de problemas.

O projeto ainda pode evoluir muito com base nas necessidades específicas dos usuários.



---

<h4>Contato</h4>

Se você tiver dúvidas, sugestões ou deseja colaborar com este projeto, sinta-se à vontade para entrar em contato:

- 📧 **E-mail**: user.franklinalves@gmail.com
- 🌐 **LinkedIn**: [Franklin Alves de Lima](https://www.linkedin.com/in/franklinalvesdelima/)


Ficarei feliz em conversar e receber feedback sobre o projeto!


