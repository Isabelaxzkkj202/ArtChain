# Relatório Consolidado: Projeto ArtChain Web3 - DIA 3 (MVP & Blockchain)

Este documento detalha o planejamento do **Dia 3**, focando na implementação técnica da Blockchain Solana e na definição das prioridades para o **Produto Mínimo Viável (MVP)**.

---

## 🏗️ 1. Onde a Blockchain faz sentido
A integração com a rede **Solana** foi escolhida para resolver gargalos críticos identificados nos dias anteriores:
* **Transparência:** Garantia de que o pagamento chegue diretamente ao artista sem intermediários.
* **Imutabilidade:** Registro permanente da autoria e do timestamp da transação.
* **Escalabilidade:** Aproveitamento das taxas ultra-baixas (menos de $0.01) para viabilizar micro-vendas de artes.

## ⚙️ 2. Definição do Uso de Solana e Recursos
Para o MVP, a arquitetura será focada em:
* **Protocolo de Transferência:** Uso de transações diretas em SOL/USDC.
* **Recurso Web3:** Implementação de metadados on-chain que vinculam a arte ao ID da transação.
* **Segurança:** Integração com a carteira **Phantom** para assinatura de transações.

## ✂️ 3. Definição do MVP (Corte do Não-Essencial)
Para garantir um lançamento rápido e funcional, as seguintes funcionalidades foram priorizadas:
* **Incluso:** Conexão de Wallet, Hub Educativo (Estático), Gerador de Prompts (JS Local) e Marketplace Simples.
* **Removido:** Chats em tempo real, leilões complexos e painéis de analytics avançados.

---

## 🎯 Conclusão e Entregáveis Detalhados - DIA 3

Abaixo estão os entregáveis que encerram o ciclo de planejamento e iniciam a fase de execução técnica:

### 1. Documento de Definição do MVP (MVP Scope)
* **Descrição:** Lista detalhada de funcionalidades "must-have" (obrigatórias) para a primeira versão pública da aplicação.
* **Entregável:** Tabela de prioridades (Sprint Backlog) focada em: Conexão Wallet -> Captura Geo -> Transação Solana.

### 2. Arquitetura de Smart Contract / Transação
* **Descrição:** Mapeamento do fluxo de fundos e metadados na rede Solana.
* **Entregável:** Diagrama de sequência mostrando a interação entre o Frontend, a API de Geolocalização e o Cluster da Solana.

### 3. Especificação de Metadados e Geolocalização
* **Descrição:** Definição de como as coordenadas (Lat/Lng) e o horário local serão anexados à prova de compra.
* **Entregável:** Estrutura de JSON de metadados que será vinculada à transação ou ao NFT gerado.

### 4. Protótipo Técnico Funcional (Skeleton Code)
* **Descrição:** Código base estruturado com as bibliotecas `@solana/web3.js` integradas e o hook de geolocalização ativo.
* **Entregável:** Script inicial pronto para ser versionado no GitHub, garantindo que a base técnica suporte o crescimento do projeto.

---
**Status Final do Projeto:**
- [x] Dia 1: Descoberta & Ideação (Concluído)
- [x] Dia 2: Estruturação da Solução (Concluído)
- [x] Dia 3: Definição de MVP & Blockchain (Concluído)

**Próxima Etapa:** Início do Desenvolvimento (Build Phase).
