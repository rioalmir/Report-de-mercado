# Automação de Relatório de Fechamento de Mercado

## Descrição
Este projeto tem como objetivo automatizar a geração e o envio de relatórios diários de fechamento de mercado utilizando Python. Ele coleta cotações históricas do Ibovespa e do Dólar, processa os dados e envia automaticamente por e-mail ao final de cada dia útil.

## Funcionalidades

* Coleta automática de cotações históricas: Busca as cotações diárias do Ibovespa e do Dólar através de APIs públicas.</br>
* Processamento de dados: Geração de um relatório com os principais indicadores do dia (fechamento, variação percentual, etc.).</br>
* Envio automático de e-mail: O relatório gerado é enviado automaticamente para destinatários definidos.</br>
* Agendamento diário: O script pode ser configurado para rodar diariamente ao final do pregão da Bolsa de Valores.</br>

## Tecnologias Utilizadas

* Python: Linguagem principal utilizada para automação.</br>
* APIs financeiras: Para a coleta de dados de cotações do Ibovespa e Dólar.</br>
* SMTP (Protocolo de E-mail): Utilizado para o envio automático de e-mails.</br>

## Pré-requisitos

* Python 3.8+</br>
* Biblioteca requests para comunicação com APIs.</br>
* Biblioteca smtplib para envio de e-mails.</br>
* Biblioteca pandas para tratamento de dados.</br>
* Uma conta de e-mail configurada com acesso SMTP.

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias.
