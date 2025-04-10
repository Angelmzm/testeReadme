# Documentação do Sistema - Projeto 2025.1
---

## Dados do Cliente

- **Título do Projeto:** Glitter&Glamour: um e-commerce de roupas
- **Cliente:** Andréa Maria Zaule Moreira
- **CNPJ/CPF:** 223.954.118.09
- **Contato:** Andrea Moreira
- **Email do Contato:** andreamariazm@gmail.com

---

## Equipe de Desenvolvimento

| Nome Completo                    | Curso                                  | Disciplina                                 |
|----------------------------------|--------------------------------------- |--------------------------------------------|
| Angelica Maria Zaule Moreira     | Sistemas de Informação                 | Programação Orientada a Objetos em Java    |
| Kelliane Vieira dos Santos       | Analise e desenvolvimento de sistesmas | Programação Orientada a Objetos em Java    |


**Professor Orientador:** Kessede Rodrigues

---

## 1. Introdução

A cliente, proprietária de uma loja física de roupas, identificou a necessidade de expandir suas vendas para o meio digital, em sua cidade. Por ser uma pessoa de mais idade e com pouco domínio de tecnologia, ela precisa de uma solução prática, acessível e de fácil utilização para gerenciar sua loja virtual sem complicações.

Para resolver esse problema, será desenvolvido um sistema de e-commerce completo, com frontend e backend integrados, que permitirá o cadastro de produtos, controle de pedidos e visualização de vendas. A interface será intuitiva, com navegação simplificada, garantindo uma boa experiência tanto para a cliente quanto para os consumidores.

As tecnologias utilizadas no backend incluem Express, TypeORM, PostgreSQL, Bcrypt para criptografia de senhas, JWT para autenticação segura, além de CORS e Dotenv para configuração do ambiente. No frontend, o projeto utilizará React para a construção da interface, com Webpack e Babel para empacotamento e transpilação dos arquivos, além de CSS para estilização avançada. Para o design será utilizado o figma.

Esse sistema irá transformar a operação da loja física em uma plataforma digital acessível e eficiente, ampliando o alcance das vendas e facilitando a gestão da loja pela cliente.

---

## 2. Objetivo

Criar um sistema de e-commerce completo que permita à cliente vender seus produtos pela internet, facilitando o cadastro e visualização de peças, o recebimento de pedidos e o acompanhamento das vendas. A plataforma será desenvolvida com foco em usabilidade, oferecendo uma interface amigável e acessível mesmo para pessoas com pouca experiência digital. O sistema visa proporcionar praticidade no dia a dia da cliente e ampliar o alcance da loja no mercado local.

---

## 3. Escopo

O sistema será composto por um e-commerce completo com foco em facilitar a experiência de venda online da cliente. Os principais requisitos que serão implementados incluem:

1. **Catálogo de Produtos e Compras Online**  
   O sistema permitirá o cadastro e visualização de produtos com fotos, preços, tamanhos e descrições. Os usuários poderão acessar o catálogo, selecionar itens e realizar pedidos por meio de um processo de compra simples.

2. **Painel de Gerenciamento para a Cliente**  
   Será desenvolvido um painel administrativo exclusivo para a cliente, onde ela poderá cadastrar, editar e excluir produtos, além de visualizar os pedidos realizados. A interface será intuitiva, adequada para pessoas com pouca familiaridade com tecnologia.

 **Limites da Implementação**  
   A aplicação será voltada inicialmente apenas para o público da cidade da cliente, sem integração com serviços de entrega externos.  
   O sistema não contará, nesta etapa, com funcionalidades como pagamento online integrado e sistema de estoque detalhado.

---

## 4. Backlogs do Produto

 Principais requisitos definidos com base nas necessidades da cliente e nas discussões realizadas com a equipe de desenvolvimento:

1. **Cadastro de Produtos**  
   A cliente poderá adicionar novos produtos ao sistema, informando nome, descrição, preço, imagem e tamanhos disponíveis.

2. **Listagem de Produtos no Site**  
   Os usuários poderão visualizar todos os produtos cadastrados em uma vitrine virtual, com fotos, descrições e preços.

3. **Página de Detalhes do Produto**  
   Cada produto terá uma página com informações mais detalhadas e opção para o usuário selecionar tamanho e quantidade.

4. **Sistema de Pedidos**  
   O cliente poderá adicionar produtos ao carrinho e realizar um pedido. Os dados do pedido serão armazenados para posterior visualização pela cliente.

5. **Painel Administrativo**  
   A cliente terá acesso a um painel onde poderá visualizar os pedidos realizados e gerenciar os produtos (editar ou excluir).

6. **Autenticação e Segurança**  
   A cliente precisará realizar login para acessar o painel administrativo, com uso de autenticação JWT e criptografia de senha com Bcrypt.

7. **Design Responsivo e Intuitivo**  
   A interface será projetada de forma limpa e simples, adequada para fácil navegação em dispositivos móveis e por pessoas com pouca experiência digital.

Esses são os requisitos iniciais definidos para o projeto. Conforme o desenvolvimento avança, novos itens podem ser adicionados ou ajustados conforme necessidade e viabilidade.

---

## 5. Cronograma

| Sprint | Período              | Atividades Principais                                                                 |
|--------|----------------------|----------------------------------------------------------------------------------------|
| 1      | 01/04 – 14/04        | Levantamento de requisitos, definição do escopo, criação do repositório, modelagem do banco de dados e design no figma. |
| 2      | 15/04 – 28/04        | Desenvolvimento do backend: criação de entidades, rotas, autenticação e conexão com o banco de dados. |
| 3      | 29/04 – 12/05        | Desenvolvimento do frontend: layout com React, páginas de produtos, carrinho e painel administrativo. |
| 4      | 13/05 – 26/05        | Integração entre frontend e backend, testes de funcionalidades e correção de erros.   |
| 5      | 27/05 – 05/06        | Ajustes finais, testes de usabilidade, documentação e entrega do projeto.             |


## 6. Materiais e Métodos

### Modelagem do Sistema
<!-- Inserir pelo menos dois diagramas UML (Casos de Uso, Classes, MER, etc.) -->

### Tecnologias Utilizadas
<!-- Linguagens, frameworks, bibliotecas, ferramentas de modelagem e uma pequena descrição de uso. -->

### Arquitetura do Sistema
<!-- Inserir imagem do fluxo de informações ou arquitetura da aplicação. -->

---

## 7. Resultados

###  Protótipo
<!-- Imagens das telas com descrições das ações do usuário. -->

### Códigos das Principais Funcionalidades
<!-- Cole aqui os trechos de código mais relevantes com comentários explicativos. -->

---

## 8. Conclusão

### Impacto do Sistema
<!-- Como o sistema impactou o processo do cliente. -->

### Melhorias Futuras
<!-- Ao menos uma melhoria futura possível. -->

---

## 9. Homologação do MVP

### Fotos da Homologação

- Foto 1: Time + Cliente com slide de fundo
- Foto 2: Apresentação do MVP
- Foto 3: Participantes assistindo
- Foto 4: Vista geral do local

### Lista de Presença

<!-- Inserir foto da lista com assinaturas. -->

---

## 10. Divulgação

### Perfil no LinkedIn do Projeto

- Print do perfil
- Link: 

### Vídeo da Apresentação (Seminário de Projetos)

- Link público: 

#### Fotos da Apresentação

- Foto 1: Time + Slide
- Foto 2: Apresentação do sistema
- Foto 3: Plano geral da frente
- Foto 4: Plano geral do fundo

### Lista de Presença

<!-- Inserir foto da lista de presença com nome, RA e assinatura. -->

---

## 11. FENETEC

### Apresentação do Projeto

- Link público do vídeo:

#### Fotos do Evento

- Foto 1: Time + Pôster
- Foto 2: Apresentação
- Foto 3: Público assistindo
- Foto 4: Plano geral da FENETEC

### Lista de Visitantes

<!-- Inserir imagem ou link da planilha com nomes e e-mails dos visitantes. -->

---

## 12. Carta de Apresentação

```text
[Texto institucional convidando o cliente a participar do projeto, conforme modelo fornecido]
```

---

## 13. Carta de Autorização

```text
[Texto de autorização formal preenchido pelo cliente, conforme modelo fornecido]
```

---

## 14. Relato Individual do Processo

- **Nome do aluno 1:** 
  - *Relato pessoal sobre o processo.*

- **Nome do aluno 2:** 
  - *Relato pessoal sobre o processo.*

- **Nome do aluno 3:** 
  - *Relato pessoal sobre o processo.*

- **Nome do aluno 4:** 
  - *Relato pessoal sobre o processo.*

- **Nome do aluno 5:** 
  - *Relato pessoal sobre o processo.*

---
