<div align="center">
<img width="135" height="97" alt="image" src="https://github.com/user-attachments/assets/284735f3-35f8-4f64-9e44-a06839ee3c49"/>

![ODS 8](https://img.shields.io/badge/ODS%208-Trabalho%20Decente%20e%20Crescimento%20Econômico-006400)
![ODS 9](https://img.shields.io/badge/ODS%209-Indústria%2C%20Inovação%20e%20Infraestrutura-006400)
![ODS 11](https://img.shields.io/badge/ODS%2011-Cidades%20e%20Comunidades%20Sustentáveis-006400)
![ODS 12](https://img.shields.io/badge/ODS%2012-Consumo%20e%20Produção%20Responsáveis-006400)
![ODS 13](https://img.shields.io/badge/ODS%2013-Ação%20Contra%20a%20Mudança%20Global%20do%20Clima-006400)


> Projeto Disciplina: Requisitos de Software
> UTFPR - Campus Cornélio Procópio.

[Link do Padlet](https://padlet.com/liviaalmeidarosa20/kanban-3fcf29ccs6wdwniw)

</div>

***1. Introdução***

---

**Time EcoTroca**
[`Livia Almeida Rosa`](https://github.com/LiviaRosaa) 
[`Maria Vitoria Mendes Storel`](https://github.com/m4riavit0ria) 
[`Patricia Lacerda Golfete`](https://github.com/patriciagolfete) 

---

**1.2. Nome do Sistema**
♻️EcoTroca

---
**1.3. Propósito do Sistema**

📌Incentivar o publico e donos de empresas a realizar reciclagem de forma consciente, com o uso de um sistema de troca de recompensas pelas embalagens recicladas em pontos de coleta especificos

---
**1.2. Público Alvo**

👉Público geral, principalmente os mais envolvidos em questões ecológicas, e empresas com ideais ecológicos

---
**1.3. Descrição dos usuários**

-Cidadão (Reciclador):
Este é o usuário final primário, a pessoa física que realiza a separação de seu lixo reciclável e o transporta até um Ponto de Coleta credenciado. Sua principal motivação é ganhar recompensas.

-Parceiro (Estabelecimento de Troca):
Este grupo é composto por comércios, lojas, ou organizações não governamentais (ONGs) que participam da rede de recompensas. O papel do Parceiro é aceitar e validar os créditos acumulados pelo Cidadão em troca de seus produtos, serviços ou doações. 

---

**Personas**  


<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/325d7802-f831-48d4-9c6d-333ae651daad" />



👉1. Luciana - A Cidadã Consciente
Ana Lúcia tem 35 anos e é Analista Administrativa. Mora em uma área urbana e busca ativamente maneiras de reciclar seu lixo, mas enfrenta a dificuldade de encontrar pontos de coleta com horários convenientes. Seu principal objetivo no EcoTroca é encontrar o ponto mais próximo de forma rápida (RF02/RNF06) e acumular créditos para trocar por vouchers em supermercados (RF06). Para ela, é crucial que a interface seja intuitiva e que a localização exija no máximo quatro cliques (RNF10).

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/e7c55685-f6ee-4cd6-88bb-dffe7edd8d8c" />


👉 2. João Silva - O Empresário Sustentável
João Silva, 48 anos, é dono de uma padaria e representa o usuário Parceiro. Ele busca iniciativas sustentáveis para diferenciar seu negócio. Seu objetivo é integrar o sistema de validação de pontos (RF10) no caixa de sua loja de forma segura e eficiente. Ele exige que o processo de validação de créditos seja instantâneo (RNF04) e que a comunicação do sistema com o Parceiro seja totalmente criptografada (RNF08) para evitar qualquer tipo de fraude e garantir a confiança na parceria.

---

**Análise da situação atual (antes da solução):**  

✔️ O que as pessoas fazem?  
Atualmente, muitas pessoas até têm o hábito de separar materiais recicláveis, mas encontram dificuldade em localizar pontos de coleta adequados ou em horários acessíveis.
Além disso, falta incentivo direto para manter o hábito de reciclar, o que faz com que parte dos resíduos recicláveis acabe sendo descartada de forma incorreta.

✔️ Quais os artefatos envolvidos?  
- sacolas, caixas e lixeiras de reciclagem doméstica.
- Locais físicos de coleta (pontos verdes, cooperativas, ecopontos).

✔️ O que elas precisam saber?  
As pessoas precisam entender como e onde descartar corretamente seus resíduos, além de quais tipos de materiais são aceitos em cada ponto de coleta.
Empresas precisam compreender os benefícios ambientais e de imagem ao participar de programas de reciclagem, e como se engajar de forma prática e segura.

---

**Análise das tarefas (depois da solução):**  

✔️ O que as pessoas fazem?  
Após a implantação do EcoTroca, a vida dos usuários se torna mais prática, recompensadora e sustentável.
O cidadão agora consegue reciclar com propósito: ele separa seus resíduos, leva até um ponto de coleta credenciado e, em poucos cliques no aplicativo, acumula créditos que podem ser trocados por descontos, produtos ou doações.
A reciclagem deixa de ser apenas um dever ambiental e se transforma em um hábito incentivado e recompensado.

✔️ Quais os artefatos envolvidos? 
- Aplicativo ou sistema web EcoTroca.
- Sistema de pontuação e recompensas digitais.
- Mapas interativos para localizar pontos de coleta.
  
✔️ O que elas precisam saber?
Os cidadãos aprendem que reciclar pode gerar benefícios reais, tanto para o meio ambiente quanto para seu próprio dia a dia.
Eles entendem como cadastrar-se, registrar entregas e usar seus créditos de forma simples e segura.
Já os parceiros passam a compreender como a sustentabilidade pode gerar valor ao negócio, aprendendo a gerenciar trocas e acompanhar o impacto ecológico das suas ações.

---

📖 **Cenário: Antes**  
👉 Antes da criação do EcoTroca, a reciclagem acontecia de forma desorganizada e pouco incentivada.
Muitas pessoas até separavam seus resíduos, mas não sabiam onde descartar corretamente ou não encontravam pontos de coleta próximos.
Sem recompensas ou informações acessíveis, o interesse em reciclar acabava diminuindo.

🏭 As empresas que desejavam adotar práticas sustentáveis não possuíam um sistema que conectasse seus negócios à comunidade recicladora, tornando difícil participar de iniciativas ecológicas.

💭 O resultado era um cenário com baixo engajamento, pouca visibilidade dos pontos de coleta e pouca valorização de quem realmente se preocupa com o meio ambiente.

📖 **Cenário: Depois**  
👉Com o EcoTroca, tudo muda!
Agora, os cidadãos podem localizar pontos de coleta facilmente pelo aplicativo, registrar suas entregas e acumular créditos que podem ser trocados por recompensas ou doações.

💚 A reciclagem se torna simples, digital e recompensadora, transformando um hábito ecológico em uma experiência positiva e motivadora.

🏪 Já os parceiros (empresas e comércios) validam os créditos em tempo real, ganham visibilidade e fortalecem sua imagem sustentável.

🌎 O EcoTroca cria uma rede colaborativa entre pessoas e negócios, onde reciclar gera valor, impacto e consciência ambiental.

---


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
| RF07          | O sistema deve enviar notificações/promoções sobre pontos de coleta próximos da sua localização atual   | Notificações          | Sistema    | S          | Media        | RNF05        |
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

---

**2.3. Perguntas** ❓
> Você costuma separar lixo reciclável em casa ou no trabalho?

> Com que frequência você recicla?

> Você já utilizou algum app ou plataforma relacionada à reciclagem?

> Você conhece pontos de coleta seletiva próximos da sua casa ou trabalho?

> Você sente falta de informações sobre onde descartar corretamente os materiais recicláveis?

> O que você acharia de um app que mostra pontos de coleta próximos a você?

> Que tipo de recompensa você acharia interessante? (Ex: vouchers, produtos ecológicos, doações a ONGs, etc.)

> Você estaria disposto a compartilhar sua localização com o app para encontrar pontos de coleta próximos?

> De que forma sua empresa acredita que o EcoTroca pode fortalecer a imagem sustentável do seu negócio e atrair novos clientes conscientes?

> Como você vê o impacto do EcoTroca na sua comunidade e na conscientização ambiental dos seus clientes?

---

**2.4. Entrevista**

[Entrevista com futuro usuário](https://drive.google.com/drive/folders/1mqItdtni9iOf3Lpj6ZLofCko6Jzsonzc)

---
**2.5. Histórias do Usuário**

1. Como uma pessoa interessada em usar o sistema, eu quero me cadastrar usando nome, e-mail e senha ou via login social (Google/Facebook), para que eu possa acessar a plataforma de forma segura e personalizada.

2. Como um usuário logado, eu quero visualizar no mapa os pontos de coleta próximos com endereço, horário e materiais aceitos, para que eu possa planejar onde entregar meus materiais recicláveis.

3. Como um usuário, eu quero registrar a entrega de materiais recicláveis em um ponto de coleta, para que eu possa acumular créditos pela minha contribuição.

4. Como um usuário, eu quero que o sistema calcule automaticamente os créditos com base no tipo e quantidade de material entregue, para que eu receba uma recompensa justa.

5. Como um usuário, eu quero ver meu saldo de créditos atualizado em tempo real, para que eu saiba quanto já acumulei e quantos posso trocar.

6. Como um usuário, eu quero trocar meus créditos por recompensas como vouchers ou doações, para que eu possa usufruir dos benefícios das minhas ações sustentáveis.

7. Como um usuário, eu quero receber notificações sobre promoções ou novos pontos de coleta próximos da minha localização, para que eu aproveite oportunidades próximas de mim.

8. Como um administrador, eu quero cadastrar e atualizar pontos de coleta com endereço, horário e materiais aceitos, para que os usuários sempre tenham acesso a informações corretas.

9. Como um usuário, eu quero visualizar um histórico com minhas entregas e trocas de créditos, para que eu possa acompanhar meu impacto e minhas atividades no sistema.

10. Como um usuário, eu quero que o sistema valide meus créditos com parceiros e emita vouchers automaticamente, para que eu possa utilizar minhas recompensas com facilidade e segurança.

---
**2.6. Diagramas de Caso de Uso e Especificações**

[Descrição dos principais Casos de Uso](https://docs.google.com/document/d/1CdKKk2AichYENsTETzKRR9Cs9792hcFVkVJLKDEpzZw/edit?usp=sharing)

<img width="400" height="400" alt="Diagrama em branco" src="https://github.com/user-attachments/assets/b3bb7c03-89c4-4dd9-b273-c896bc137480" />

---
**2.7. Diagramas de Atividades**

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/e99ddb87-1e41-46ca-86cc-0061b8f28fd4" />


---
**2.7. Diagramas de Classe**


<img width="400" height="400" alt="Untitled diagram-2025-11-04-010234" src="https://github.com/user-attachments/assets/5d4eec7c-0e8c-4fe8-9fc3-257635b99399" />



---
**2.8. Protótipos**
[Protótipos de tela](https://ninjamock.com/s/JCQ4QZx)

---
**Referências**

<Esta seção é destinada à descrição das referências utilizadas pelo documento, como por exemplo, URLs e livros. Ver exemplo a seguir:>

[1] “Glossário da USina”, <id_doc glossário>, Versão <versão>. Localização: <localização>.
