# 🚗 Sistema de Automação de Abastecimento

## 1. 📄 **Resumo do Projeto**
Este projeto automatiza o processo de inserção de dados de abastecimento de veículos em um sistema web, utilizando **Python** e **Selenium**. A solução lê informações a partir de um arquivo Excel e preenche automaticamente os campos de um formulário online, com o objetivo de reduzir o tempo de preenchimento manual e eliminar erros humanos.

---

## 2. 🎯 **Objetivos**
- Automatizar o **registro de abastecimentos** em um sistema de gestão.
- Aumentar a **precisão e eficiência**, minimizando erros manuais.
- Facilitar o **controle e a gestão** dos registros de abastecimento.

---

## 3. 🚀 **Principais Funcionalidades**
- **Login automático** no sistema de gestão de abastecimento.
- **Preenchimento automático de formulários** com dados como placa, quilometragem, litros e combustível.
- **Integração com arquivos Excel** para leitura e inserção de dados.
- **Validação e finalização dos registros** de abastecimento.
- **Relatório de conclusão** ao término do processo de automação.

---

## 4. ⚙️ **Processo de Automação**
A automação deste projeto segue um fluxo contínuo de operações, permitindo que grandes volumes de dados sejam processados com rapidez e precisão.

### 🔄 Etapas do Processo:
1. **Leitura de Arquivo Excel**: O sistema lê o arquivo `abastecimento.xlsx` da pasta `datasets/`, extraindo dados como data, hora, quilometragem, litros, placa e contrato.
2. **Interação com o Sistema Web**: Utilizando **Selenium**, o script navega até o sistema de abastecimento, realiza login automático e navega até o formulário de novo abastecimento.
3. **Preenchimento dos Dados**: Os campos do formulário são preenchidos automaticamente com base nos dados extraídos do Excel. Sugestões de "placa" e "contrato" são validadas.
4. **Confirmação e Finalização**: Após inserir os dados, o sistema valida as entradas e finaliza o registro do abastecimento.
5. **Relatório Final**: Exibe um relatório indicando a conclusão do processo de abastecimento para o mês.

---

## 5. 🛠 **Requisitos**
- **Python 3.x**: Linguagem principal do projeto.
- **Selenium**: Biblioteca para automação de navegador.
- **Pandas**: Biblioteca para leitura e manipulação de dados.
- **ChromeDriver**: Ferramenta necessária para controle do navegador Google Chrome.
- **Arquivo Excel**: O arquivo `abastecimento.xlsx` com os dados de abastecimento, localizado na pasta `datasets/`.

---

## 6. 📊 **Resultados Esperados**
- **Redução de até 80% no tempo** de registro manual.
- **Precisão de 95%** nos dados inseridos.
- **Aumento da produtividade**, liberando a equipe para tarefas estratégicas.
- **Melhor controle dos registros**, com dados precisos e padronizados.

---

## 7. 🏆 **Benefícios do Sistema**
- **Eficiência**: Automação rápida e precisa, eliminando o tédio e erros do processo manual.
- **Escalabilidade**: Capacidade de lidar com grandes volumes de dados.
- **Facilidade de Uso**: A interface amigável permite o uso por pessoas com diferentes níveis de habilidade técnica.
- **Controle de Qualidade**: Garantia da integridade dos dados, com planilhas padronizadas e validação automática.

---

## 8. 📬 **Contato**
Caso tenha dúvidas ou sugestões, entre em contato:
- **Nome**: Franklin Alves
- **Email**: franklin.alves.lima@hotmail.com


