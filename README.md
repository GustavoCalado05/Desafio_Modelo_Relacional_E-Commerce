# 🛒 Modelo Relacional de Banco de Dados - E-commerce

Este repositório contém a modelagem de banco de dados relacional para uma plataforma de **E-commerce**, desenvolvida utilizando o **MySQL Workbench**.

O objetivo deste projeto é fornecer uma estrutura robusta para gerenciar usuários, produtos, pedidos, pagamentos e logística de entrega.

## 📋 Sobre o Projeto

O arquivo principal `modelo relacional e-commerce.mwb` contém o Diagrama Entidade-Relacionamento (DER) e o esquema físico do banco de dados. A modelagem foi pensada para atender aos requisitos fundamentais de uma loja virtual, garantindo integridade referencial e escalabilidade.

### Principais Entidades Modeladas
* **Clientes:** Gerenciamento de dados pessoais e endereços.
* **Produtos & Categorias:** Catálogo de itens com variações e organização hierárquica.
* **Pedidos (Orders):** Processamento de compras, incluindo itens do pedido e status.
* **Pagamentos:** Registro de transações e métodos de pagamento.
* **Frete/Entrega:** Gestão de envios e rastreamento.
* *(Adicione aqui outras entidades se houver, ex: Estoque, Cupons, Avaliações)*

## 📷 Diagrama Entidade-Relacionamento (DER)

> **Nota:** Para visualizar o diagrama completo, recomenda-se abrir o arquivo `.mwb`. Abaixo está uma prévia da estrutura:

![Diagrama do Banco de Dados](url_da_imagem_aqui.png)
*(Dica: Exporte o diagrama como PNG no MySQL Workbench e substitua este link pela sua imagem, ou coloque a imagem na pasta do projeto)*

## 🛠️ Tecnologias Utilizadas

* **MySQL Workbench:** Para modelagem visual e criação do script SQL.
* **MySQL Server:** Sistema gerenciador de banco de dados (SGBD).

## 🚀 Como Utilizar

Para visualizar e editar o modelo:

1.  Certifique-se de ter o [MySQL Workbench](https://www.mysql.com/products/workbench/) instalado.
2.  Clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repo.git](https://github.com/seu-usuario/nome-do-repo.git)
    ```
3.  Abra o arquivo `modelo relacional e-commerce.mwb` no MySQL Workbench.
4.  Para gerar o script SQL de criação (DDL), vá em: `File > Export > Forward Engineer SQL CREATE Script`.

## 📂 Estrutura do Repositório
