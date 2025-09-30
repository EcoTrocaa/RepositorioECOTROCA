# ECOTROCA

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
Eco Troca

1.3. Propósito do Sistema
----------------------------------------------------------
Este documento apresenta os requisitos dos usuários a serem desenvolvidos pela EcoTroca, fornecendo aos desenvolvedores as informações necessárias para o projeto e implementação, assim como para a realização dos testes e homologação do sistema.

Incentivar o publico e donos de empresas a realizar reciclagem de forma consciente, com o uso de um sistema de troca de recompensas pelas embalagens recicladas em pontos de coleta específicos

1.2. Público Alvo
------------------------------------------------------------
Público geral, principalmente os mais envolvidos em questões ecológicas, e empresas com ideais ecológicos.

1.3. Descrição dos usuários
------------------------------------------------------------
<Descrever quais os usuários finais do sistema (quem vai utilizar o sistema). Neste espaço vocês vão traçar um perfil de usuário, bem como as personas e análide de tarefas>

Personas:

<Imagem, arquivo (PDF), link com as Personas.>

Análise da situação atual: antes da introdução de sua solução

1. O que as pessoas fazem? 2. Quais os artefatos envolvidos? 3. O que elas precisam saber?

Análise das tarefas depois: como serão executadas as suas tarefas com sua solução:

1. O que as pessoas fazem? 2. Quais os artefatos envolvidos? 3. O que elas precisam saber?

Cenário: Antes

<Preencher com o cenário idealizado antes da aplicação do seu sistema.>

Cenário: Depois

<Preencher com o cenário idealizado depois da aplicação do seu sistema.>

2. Documentos gerais no repositório (Aula 19/09/25)

**2.1. Requisitos Funcionais**
------------------------------------------------------------
| Identificador | Descrição                                                                                               | Categoria             | Escopo     | Prioridade |
|---------------|---------------------------------------------------------------------------------------------------------|-----------------------|------------|------------|
| RF01          | O sistema deve permitir criar conta com nome, e-mail e senha ou login social (Google/Facebook).         | Cadastro/Autenticação | Sistema    | Alta       |
| RF02          | O usuário deve visualizar no mapa pontos de coleta próximos, com endereço, horário e materiais aceitos. | Mapa/Localização      | Sistema    | Alta       |
| RF03          | O sistema deve permitir registrar entrega de materiais em pontos de coleta para gerar créditos.         | Créditos              | Sistema    | Alta       |
| RF04          | O sistema deve calcular automaticamente créditos gerados pelo tipo e quantidade de material.            | Créditos              | Sistema    | Alta       |
| RF05          | O usuário deve acompanhar o saldo de créditos em tempo real.                                            | Créditos              | Sistema    | Alta       |
| RF06          | O sistema deve permitir a troca de créditos por recompensas, como vouchers ou doações.                  | Recompensas           | Sistema    | Alta       |
| RF07          | O sistema deve enviar notificações push sobre pontos de coleta próximos ou promoções.                   | Notificações          | Sistema    | Média      |
| RF08          | Administradores devem cadastrar e atualizar pontos de coleta, com endereço, horários e materiais.       | Administração         | Backoffice | Alta       |
| RF09          | O sistema deve exibir um histórico de entregas e trocas de créditos.                                    | Histórico             | Sistema    | Alta       |
| RF10          | O sistema deve integrar com parceiros para validar créditos ou emitir vouchers.                         | Integração            | Sistema    | Alta       |


***2.2. Requisitos Não Funcionais***
------------------------------------------------------------
| Identificador | Descrição                                                                                      | Categoria     | Escopo  | Prioridade |
|---------------|------------------------------------------------------------------------------------------------|---------------|---------|------------|
| RNF01         | O sistema deve estar disponível 99,5% do tempo                                                 | Confiabilidade| Sistema | Alta       |
| RNF02         | O sistema deve ser compatível com Android e iOS                                                | Portabilidade | Sistema | Alta       |
| RNF03         | O app deve ajustar-se automaticamente a diferentes tamanhos de tela                            | Portabilidade | Sistema | Média      |
| RNF04         | O sistema deve responder as requisições do usuário em até 2s em 95% das operações              | Eficiência    | Sistema | Alta       |
| RNF05         | Notificações devem ser enviadas até 1 minuto após algum evento relevante                       | Eficiência    | Sistema | Média      |
| RNF06         | O carregamento dos mapas de pontos de coleta deve ocorrer em até 10s                           | Eficiência    | Sistema | Alta       |
| RNF07         | O sistema deve suportar ao menos 10 mil usuários simultâneos                                   | Escalabilidade| Sistema | Alta       |
| RNF08         | Todo tráfego de dados deve ser criptografado usando HTTPS                                      | Segurança     | Sistema | Alta       |
| RNF09         | Autenticação deve suportar login por redes sociais como Gmail, Facebook                        | Segurança     | Sistema | Alta       |
| RNF10         | A interface deve ser intuitiva, permitindo localizar um ponto de coleta em no máximo 4 cliques | Usabilidade   | Sistema | Alta       |


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
