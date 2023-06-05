# 3rd-party-service-rating-review-platform-updated-
Enable users of 3rd party services to rate and review the providers of those services, in specific verticals.  The initial use case is enabling job applicants to rate and review job recruiters and hiring firms on their transparency and behavior toward job seekers.

#Problem Description
Enable users of 3rd party services to rate and review the providers of those services, in specific verticals.

The initial use case is enabling job applicants to rate and review job recruiters and hiring firms on their transparency and behavior toward job seekers.

Employment is a two-way market between job applicants and hiring firms. But too often hiring firms treat job applicants as disposable. And too often recruiters, who operate in the middle, behave as if hiring firms are their only customers, and also treat job applicants poorly.

We can change this by creating accountability, via ratings and reviews.

Just as Yelp enables ratings and reviews of restaurants etc., we will enable ratings and reviews of hiring firms and recruiters.

Similar to Yelp or Trustpilot but for targeting of whole site / version to specific verticals, such as the job marketplace, and independent of geography (unike Yelp).

#Acceptance Criteria
Core features required:

Search Employers / Recruiters
A. Input name, search against existing entries w/ predictive text entry
B. Present suggested matches, enable selection as approrpriate

Add New Employer / Recruiter
A. Enter employer / recruiter name

Rate & Review: Once an Employer / Recruiter is selected or added:

A. Rate from 1-5 stars [1 worst, 5 best, required to post]

B. Type in a review [up to 1,000 characters, 50 character minimum required to post]. Prompt:
“Do you feel that your time responding to a job via this organization was well spent? Would you recommend this experience to other people? What could the job poster have done better?”

C. Questions [all optional]:

i. Was the salary or pay range clearly stated at the top of the job description?
a. Yes, right at the top
b. Yes but hard to find
c. Not stated

ii. Did the job poster respond to your application quickly (beyond an auto-reply)?
a. Yes, responded within a week
b. Yes, but response took 1-4 weeks
c. No reply in more than 4 weeks

iii. If you didn’t get the job, did the job poster give you useful feedback?
a. I got the job
b. Didn’t get the job, but got useful feedback
c. Got no useful feedback or no feedback at all.

iv. How streamlined or cumbersome was the application process?
a. Easy: just a few clicks
b. Moderate: took a few hours of custom work
c. PITA: multiple unique questions, exercises etc. that took a day or more in total.

v. Were all the application questions / requirements visible before you decided to apply?
a. Yes, all application requirements were visible from the start.
b. Some were visible up-front, others were hidden and only revealed via advancing through a sequence of prompts.
c. There were hidden questions and I also had to manually enter work history or other info provided in my resume.

vi. Paste the URL of the job post you applied to. [200 char max]

Further requirements:

Responses stored in Google sheets initially with flexibility to switch later to Airtable.

Initially, no registration or login required to post or read, but structured to enable adding an up-front registration requirement later.

Ability for site owner to add additional rating & review boxes, or to move or reorder questions. (Modular like in a Google form).

Flexibility to edit static text (across the site and question prompts).

Flexibility to brand / skin / style / format text later.

Flexibility to add paywall as part of registration requirement later.

Here are some basic mockups on Figma:
https://www.figma.com/file/Pm00osbsPXLIDcahis1xaq/Rater


Descrição do Problema
Permitir que usuários de serviços de terceiros avaliem e façam comentários sobre os provedores desses serviços, em setores específicos.

O caso de uso inicial é permitir que candidatos a emprego avaliem e façam comentários sobre recrutadores e empresas de contratação com base em sua transparência e comportamento em relação aos candidatos.

O emprego é um mercado de duas vias entre os candidatos a emprego e as empresas de contratação. Porém, com frequência, as empresas de contratação tratam os candidatos a emprego como descartáveis. E, com frequência, os recrutadores, que operam no meio, se comportam como se as empresas de contratação fossem seus únicos clientes e também tratam mal os candidatos a emprego.

Podemos mudar isso criando responsabilidade, por meio de avaliações e comentários.

Assim como o Yelp permite avaliações e comentários sobre restaurantes, etc., permitiremos avaliações e comentários sobre empresas de contratação e recrutadores.

Similar ao Yelp ou Trustpilot, mas direcionado a todo o site/versão para setores específicos, como o mercado de emprego, e independente de localização geográfica (ao contrário do Yelp).

Critérios de Aceitação
Recursos principais necessários:

Pesquisar Empregadores / Recrutadores
A. Inserir nome, pesquisar em entradas existentes com entrada de texto preditiva
B. Apresentar correspondências sugeridas, permitir seleção conforme apropriado

Adicionar Novo Empregador / Recrutador
A. Inserir nome do empregador / recrutador

Avaliar e Comentar: Depois de selecionar ou adicionar um Empregador / Recrutador:

A. Avaliar de 1 a 5 estrelas [1 pior, 5 melhor, obrigatório para publicar]

B. Digitar um comentário [até 1.000 caracteres, mínimo de 50 caracteres obrigatório para publicar]. Prompt:
"Você acha que seu tempo respondendo a uma vaga através desta organização foi bem aproveitado? Você recomendaria esta experiência para outras pessoas? O que o anunciante da vaga poderia ter feito melhor?"

C. Perguntas [todas opcionais]:

i. O salário ou faixa salarial foi claramente indicado no topo da descrição da vaga?
a. Sim, bem no topo
b. Sim, mas difícil de encontrar
c. Não foi indicado

ii. O anunciante da vaga respondeu rapidamente à sua candidatura (além de uma resposta automática)?
a. Sim, respondeu em até uma semana
b. Sim, mas a resposta levou de 1 a 4 semanas
c. Nenhuma resposta em mais de 4 semanas

iii. Se você não foi contratado, o anunciante da vaga lhe deu feedback útil?
a. Fui contratado
b. Não fui contratado, mas recebi feedback útil
c. Não recebi feedback útil ou nenhum feedback.

iv. Quão simples ou complexo foi o processo de candidatura?
a. Fácil: apenas alguns cliques
b. Moderado: exigiu algumas horas de trabalho personalizado
c. Difícil: várias perguntas únicas, exercícios, etc., que levaram um dia ou mais no total.

v. Todas as perguntas / requisitos da candidatura eram visíveis antes de você decidir se candidatar?
a. Sim, todos os requisitos da candidatura eram visíveis desde o início.
b. Alguns foram visíveis de imediato, outros estavam ocultos e só foram revelados ao avançar por uma sequência de etapas.
c. Havia perguntas ocultas e também precisei digitar manualmente histórico de trabalho ou outras informações fornecidas em meu currículo.

vi. Cole a URL da vaga à qual você se candidatou. [máximo de 200 caracteres]

Outros requisitos:

Respostas armazenadas inicialmente no Google Sheets com flexibilidade para mudar posteriormente para o Airtable.

Inicialmente, nenhum registro ou login é necessário para publicar ou ler, mas estruturado para permitir a exigência de registro no futuro.

Capacidade para o proprietário do site adicionar caixas adicionais de avaliação e comentário, ou mover ou reordenar as perguntas. (Modular, como em um formulário do Google).

Flexibilidade para editar texto estático (em todo o site e prompts de pergunta).

Flexibilidade para personalizar a marca / aparência / estilo / formato do texto posteriormente.

Flexibilidade para adicionar um paywall como parte da exigência de registro posteriormente.

Aqui estão algumas representações básicas no Figma:
https://www.figma.com/file/Pm00osbsPXLIDcahis1xaq/Rater
