 # ♻️🌱🌍 **ECOTROCA** 🌍🌱♻️

> Projeto Disciplina: Requisitos de Software
> UTFPR - Campus Cornélio Procópio.
Link do Padlet: [https://padlet.com/liviaalmeidarosa20/kanban-3fcf29ccs6wdwniw](https://padlet.com/liviaalmeidarosa20/kanban-3fcf29ccs6wdwniw)

***1. Introdução***
---------------------------------------------------------
**Time EcoTroca**
`Livia Almeida Rosa` 
`Maria Vitoria Mendes Storel` 
`Patricia Lacerda Golfete` 

1.2. Nome do Sistema
----------------------------------------------------------
♻️EcoTroca

1.3. Propósito do Sistema
----------------------------------------------------------
📌Incentivar o publico e donos de empresas a realizar reciclagem de forma consciente, com o uso de um sistema de troca de recompensas pelas embalagens recicladas em pontos de coleta especificos

1.2. Público Alvo
------------------------------------------------------------
👉Público geral, principalmente os mais envolvidos em questões ecológicas, e empresas com ideais ecológicos

1.3. Descrição dos usuários
------------------------------------------------------------
-Cidadão (Reciclador):
Este é o usuário final primário, a pessoa física que realiza a separação de seu lixo reciclável e o transporta até um Ponto de Coleta credenciado. Sua principal motivação é ganhar recompensas.

-Parceiro (Estabelecimento de Troca):
Este grupo é composto por comércios, lojas, ou organizações não governamentais (ONGs) que participam da rede de recompensas. O papel do Parceiro é aceitar e validar os créditos acumulados pelo Cidadão em troca de seus produtos, serviços ou doações. 

**Personas**  
👉1. Ana Lúcia - A Cidadã Consciente
Ana Lúcia tem 35 anos e é Analista Administrativa. Mora em uma área urbana e busca ativamente maneiras de reciclar seu lixo, mas enfrenta a dificuldade de encontrar pontos de coleta com horários convenientes. Seu principal objetivo no EcoTroca é encontrar o ponto mais próximo de forma rápida (RF02/RNF06) e acumular créditos para trocar por vouchers em supermercados (RF06). Para ela, é crucial que a interface seja intuitiva e que a localização exija no máximo quatro cliques (RNF10).

👉 2. João Silva - O Empresário Sustentável
João Silva, 48 anos, é dono de uma padaria e representa o usuário Parceiro. Ele busca iniciativas sustentáveis para diferenciar seu negócio. Seu objetivo é integrar o sistema de validação de pontos (RF10) no caixa de sua loja de forma segura e eficiente. Ele exige que o processo de validação de créditos seja instantâneo (RNF04) e que a comunicação do sistema com o Parceiro seja totalmente criptografada (RNF08) para evitar qualquer tipo de fraude e garantir a confiança na parceria.

---

**Análise da situação atual (antes da solução):**  
✔️ O que as pessoas fazem?  
✔️ Quais os artefatos envolvidos?  
✔️ O que elas precisam saber?  

---

**Análise das tarefas (depois da solução):**  
✔️ O que as pessoas fazem?  
✔️ Quais os artefatos envolvidos?  
✔️ O que elas precisam saber?  

---

📖 **Cenário: Antes**  
👉 <Preencher com o cenário idealizado antes da aplicação do seu sistema.>  

📖 **Cenário: Depois**  
👉 <Preencher com o cenário idealizado depois da aplicação do seu sistema.>  


2. Documentos gerais no repositório (Aula 19/09/25)

**2.1. Requisitos Funcionais**
------------------------------------------------------------
| Identificador | Descrição                                                                                               | Categoria             | Escopo     | Prioridade | Prioridade   | Relacional   |
|---------------|---------------------------------------------------------------------------------------------------------|-----------------------|------------|------------|--------------|--------------|
| RF01          | O sistema deve permitir criar conta com nome, e-mail e senha ou login social (Google/Facebook).         | Cadastro/Autenticação | Sistema    | M          | Alta         | RNF09        |
| RF02          | O usuário deve visualizar no mapa pontos de coleta próximos, com endereço, horário e materiais aceitos. | Mapa/Localização      | Sistema    | M          | Alta         | RNF06        |
| RF03          | O sistema deve permitir registrar entrega de materiais em pontos de coleta para gerar créditos.         | Créditos              | Sistema    | M          | Alta         | RNF04        |
| RF04          | O sistema deve calcular automaticamente créditos gerados pelo tipo e quantidade de material.            | Créditos              | Sistema    | M          | Alta         | RNF04        |
| RF05          | O usuário deve acompanhar o saldo de créditos em tempo real.                                            | Créditos              | Sistema    | M          | Alta         | RNF04        |
| RF06          | O sistema deve permitir a troca de créditos por recompensas, como vouchers ou doações.                  | Recompensas           | Sistema    | M          | Alta         | RNF08        |
| RF07          | O sistema deve enviar notificações push sobre pontos de coleta próximos ou promoções.                   | Notificações          | Sistema    | S          | Media        | RNF05        |
| RF08          | Administradores devem cadastrar e atualizar pontos de coleta, com endereço, horários e materiais.       | Administração         | Backoffice | M          | Alta         | RNF08        |
| RF09          | O sistema deve exibir um histórico de entregas e trocas de créditos.                                    | Histórico             | Sistema    | M          | Alta         | RNF04        |
| RF10          | O sistema deve integrar com parceiros para validar créditos ou emitir vouchers.                         | Integração            | Sistema    | M          | Alta         | RNF08        |


***2.2. Requisitos Não Funcionais***
------------------------------------------------------------
| Identificador | Descrição                                                                                      | Categoria     | Escopo  | Prioridade | Prioridade   | Relacional   |  
|---------------|------------------------------------------------------------------------------------------------|---------------|---------|------------|--------------|--------------|
| RNF01         | O sistema deve estar disponível 99,5% do tempo                                                 | Confiabilidade| Sistema | M          |  Alta        | RF04         |
| RNF02         | O sistema deve ser compatível com Android e iOS                                                | Portabilidade | Sistema | M          |  Alta        | RF02         |
| RNF03         | O app deve ajustar-se automaticamente a diferentes tamanhos de tela                            | Portabilidade | Sistema | S          |  media       | RF02         |
| RNF04         | O sistema deve responder as requisições do usuário em até 2s em 95% das operações              | Eficiência    | Sistema | M          |  Alta        | RF03         |
| RNF05         | Notificações devem ser enviadas até 1 minuto após algum evento relevante                       | Eficiência    | Sistema | S          |  Media       | RF07         |
| RNF06         | O carregamento dos mapas de pontos de coleta deve ocorrer em até 10s                           | Eficiência    | Sistema | M          |  Alta        | RF02         |
| RNF07         | O sistema deve suportar ao menos 10 mil usuários simultâneos                                   | Escalabilidade| Sistema | M          |  Alta        | RF03         |
| RNF08         | Todo tráfego de dados deve ser criptografado usando HTTPS                                      | Segurança     | Sistema | M          |  Alta        | RF01         |
| RNF09         | Autenticação deve suportar login por redes sociais como Gmail, Facebook                        | Segurança     | Sistema | M          |  Alta        | RF01         |
| RNF10         | A interface deve ser intuitiva, permitindo localizar um ponto de coleta em no máximo 4 cliques | Usabilidade   | Sistema | M          |  Alta        | RF02         |


**2.3. Perguntas**
------------------------------------------------------------
<Arquivo com as perguntas realizadas na entrevista .>

**2.4. Entrevista**
------------------------------------------------------------
<Arquivo com as respostas do indivíduo entrevistado e link do drive com upload da gravação.>

**2.5. Histórias do Usuário**
------------------------------------------------------------
<Imagem, arquivo (PDF), link com as Histórias de Usuário.>

**2.6. Diagramas de Caso de Uso e Especificações**
------------------------------------------------------------
<Imagem, arquivo (PDF), link com Diagrama de Caso de Uso.>

**2.7. Diagramas de Atividades**
------------------------------------------------------------
<Imagem, arquivo (PDF), link com Diagrama de Atividades.>

**2.8. Protótipos**
------------------------------------------------------------
<Imagem, arquivo (PDF), link com Protótipo.>

**Referências**
------------------------------------------------------------
<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>

[1] “Glossário da USina”, <id_doc glossário>, Versão <versão>. Localização: <localização>.
