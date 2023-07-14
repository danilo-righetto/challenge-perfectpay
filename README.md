# Desafio DEV-PHP da PerfectPay

Esse desafio foi solicitado para a participação do processo seletivo da [PerfectPay](https://perfectpay.com.br/).

## Objetivo

O desafio é desenvolver um sistema de processamento de pagamentos integrado ao ambiente de homologação do **Asaas**, levando em consideração que o cliente deve acessar uma página onde irá selecionar a opção de pagamento entre **Boleto**, **Cartão** ou **Pix**.

### Detalhes do Projeto

Basicamente, o sistema deve ter a opção do pagamento e um formulário com inputs necessários para processar o pagamento e um botão 'finalizar pagamento', e se o pagamento der certo direcionar para uma página de obrigado.


> O sistema deverá suprir as seguintes necessidades:
- O sistema deverá ser desenvolvido utilizando a linguagem PHP no **framework Laravel**.
- Tratar os Dados no Request da requisição para que não aconteça de vir dados faltando ou diferentes do necessário.
- Resposta da solicitação ser padronizada via Resources conforme o necessário.
- Padronização das Requisições das APIs de integração com o Asaas.

> Processamento de pagamentos com boleto, cartão de crédito e pix.
- Se o pagamento for boleto mostrar um botão com o link do boleto na página de obrigado.
- Se o pagamento for Pix exibir o QRCode e o Copia e Cola na página de obrigado.
- Em caso de recusa do cartão ou erro na requisição mostrar uma mensagem amigável no - retorno para facilitar o entendimento do não processamento do pagamento.
- Não é necessário se importar com a qualidade do front, usar um bootstrap bem básico
- Utilize boas práticas de programação
- Utilize boas práticas de git
- Documentar como rodar o projeto

> Opcionais:
- Testes automatizados com informação da cobertura de testes
- Persistência dos dados em banco de dados relacional, de preferência MySql.

## Documentação da API

Link da documentação: https://asaasv3.docs.apiary.io/#

> Credenciais de Sandbox:
Crie uma conta no **Asaas Sandbox**( https://sandbox.asaas.com/ ), na parte de Configuração de Conta->Integrações você irá conseguir a API Key de Sandbox para iniciar a integração.
