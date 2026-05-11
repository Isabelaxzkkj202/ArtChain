# Planejamento de Projeto: Plataforma Artística Web3 (Ecossistema Solana)

Este documento detalha a estrutura e as funcionalidades da aplicação de gerenciamento e marketplace para artistas, integrando educação, exposição e pagamentos via criptomoedas, conforme as diretrizes de Descoberta e Ideação.

---

## 1. Entender o Problema Real & Identificar Dores
O projeto ataca a fragmentação do mercado de arte independente. Atualmente, o artista precisa de várias plataformas distintas para aprender, postar, gerenciar contatos e receber pagamentos, muitas vezes lidando com taxas abusivas e burocracia internacional.

**Principais Dores Identificadas:**
* **Barreiras Financeiras:** Taxas altas de conversão de moeda e demora em recebimentos.
* **Estagnação Técnica:** Falta de feedback e material educativo estruturado dentro do ambiente de venda.
* **Desorganização de Contato:** Dificuldade em centralizar redes sociais e meios de comunicação direta.

## 2. Gerar Ideias e Escolher a Direção
A solução escolhida é uma **Aplicação Integrada de Gerenciamento e Marketplace** que utiliza a rede **Solana** pela sua alta velocidade e baixo custo de transação, ideal para microtransações de arte.

## 3. Público e Proposta de Valor
* **Público:** Artistas digitais e tradicionais (iniciantes e profissionais) e colecionadores de arte que utilizam o ecossistema Web3.
* **Proposta de Valor:** "Profissionalizar a jornada do artista, do aprendizado à venda, através de uma plataforma segura, descentralizada e focada em comunidade."

---

## 4. Estrutura do Sistema (Funcionalidades)

* **Perfil do Administrador (Dono do Site):** Exibição prioritária no início do site com e-mail, telefone e redes sociais para suporte e sugestões de melhoria.
* **Perfil do Usuário/Artista:** Cadastro personalizado com `@nome`, portfólio, integração de redes sociais e e-mail de contato.
* **Módulo Educativo:** Seção dedicada a explicações técnicas para melhoria de performance artística.
* **Ideação:** Ferramenta geradora de ideias e desafios para novos projetos.
* **Marketplace Solana:** Sistema de postagem e venda de artes com transações em cripto.
* **Geolocalização:** Funcionalidade para pagamentos e registros baseados no horário e local do usuário.

---

## 5. Conclusão e Entregáveis Detalhados

Como resultado da fase de **Descoberta e Ideação**, os seguintes entregáveis foram estabelecidos para o projeto:

### A. Documento de Escopo e Proposta de Valor
* **Descrição:** Definição clara do problema (centralização de ferramentas) e como a aplicação resolve isso usando a rede Solana.
* **Status:** Concluído.

### B. Especificação de Perfil e Identidade Visual
* **Descrição:** Layout detalhado da Home Page destacando o perfil do proprietário (contato para melhorias) e a estrutura dos perfis de usuários (@nome, redes sociais, contato).
* **Entregável:** Mapa de campos de dados (E-mail, Telefone, Social Links).

### C. Arquitetura de Pagamentos Web3
* **Descrição:** Plano de integração com carteiras Solana (Phantom/Solflare) e lógica de transação para vendas de artes.
* **Entregável:** Fluxograma de compra e venda via Smart Contracts.

### D. Módulo de Conteúdo e Ideação
* **Descrição:** Estrutura da base de conhecimento (tutoriais para melhoria) e do algoritmo de sugestão de ideias para artes.
* **Entregável:** Lista de categorias de melhoria técnica (Ex: Anatomia, Luz, Perspectiva).

### E. Sistema de Geolocalização Temporal
* **Descrição:** Especificação técnica da função que utiliza a localização do usuário para validar o horário de pagamento e transações.
* **Entregável:** Protocolo de segurança baseado em timestamp geolocalizado.
