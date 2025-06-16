# ExternalAPI-Integrations

**Integrações externas desenvolvidas em ADVPL para o ambiente TOTVS Protheus, conectando o ERP a serviços públicos como ViaCEP e OpenWeather.**

## 🔗 Descrição

O **ExternalAPI-Integrations** é um projeto que demonstra o consumo de APIs públicas em ADVPL com foco em enriquecer os dados utilizados dentro do Protheus. A proposta é facilitar rotinas comuns como preenchimento automático de endereços ou exibição da previsão do tempo por localização, com tratamento de erros, fallback de dados e uma interface de testes amigável.

## 🌐 Funcionalidades

- 📍 Integração com a API **ViaCEP** para consulta de endereço por CEP  
- ☀️ Integração com a API **OpenWeather** para previsão do tempo por cidade  
- 🧪 Tela de testes para simulação das chamadas e visualização dos dados  
- 🔁 Cache ou fallback local em caso de falha nas APIs externas  
- 🛡️ Validações robustas e mensagens visuais em caso de erro ou falha de rede  

## 🏗️ Tecnologias

- **ADVPL**  
- **REST Client nativo do Protheus**  
- **JSON Parser**  
- **TOTVS Protheus - Tabela e interface customizadas**

## 📦 Como Executar

> Requisitos mínimos:
> - Protheus 12.1.33+ com suporte a chamadas HTTP  
> - Configuração de acesso à internet pelo Appserver  
> - Tabelas customizadas importadas (para cache e interface)  

**Passos:**

1. Clone este repositório  
2. Compile os arquivos `.PRW` no ambiente do Protheus  
3. Acesse o menu `SIGAAPI` ou conforme configurado  
4. Na tela de testes, insira um CEP ou nome da cidade  
5. Visualize o retorno das APIs diretamente na interface  

## 📸 Demonstrações

*(Sugerido: prints da tela com retorno do endereço, ícones de clima, ou falha com fallback ativado)*

## 📑 Licença

Distribuído sob a [Apache License 2.0](./LICENSE)

## 👨‍💻 Autor

Desenvolvido por [Bruno Lebar](https://github.com/Bruno-Lebar-DEV)

Contribuições, ideias e integrações adicionais são sempre bem-vindas!
