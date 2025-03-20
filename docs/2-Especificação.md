# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="01-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

1. Maria Fernandes – Aposentada Consciente
	•	Idade: 64 anos
	•	Profissão: Professora aposentada
	•	Estilo de vida: Gosta de passar o tempo em casa, lendo e cuidando do jardim. Tem preocupação com os gastos domésticos e busca maneiras de economizar.
	•	Motivação para usar o sistema: Quer reduzir sua conta de energia, mas não entende muito de tecnologia e precisa de informações simples e diretas.
	•	Desafios: Não sabe exatamente quais aparelhos consomem mais energia em sua casa. Gostaria de um sistema fácil de usar, com explicações didáticas.
	•	Objetivos: Encontrar formas de economizar energia sem precisar investir em novos equipamentos caros.

⸻

2. João Carlos – Jovem Sustentável
	•	Idade: 27 anos
	•	Profissão: Analista de marketing digital
	•	Estilo de vida: Mora sozinho em um apartamento alugado e se preocupa com o impacto ambiental de suas ações. Procura formas sustentáveis de viver.
	•	Motivação para usar o sistema: Quer otimizar seu consumo de energia para reduzir seu impacto ambiental e os custos da conta de luz.
	•	Desafios: Precisa de recomendações sobre quais equipamentos trocar ou como usá-los de forma mais eficiente.
	•	Objetivos: Aprender novas práticas sustentáveis e interagir com outras pessoas no fórum para trocar experiências sobre economia de energia.

⸻

3. Juliana Lopes – Mãe e Gestora do Lar
	•	Idade: 39 anos
	•	Profissão: Empresária e mãe de dois filhos
	•	Estilo de vida: Administra o orçamento doméstico e está sempre buscando formas de reduzir gastos sem comprometer o conforto da família.
	•	Motivação para usar o sistema: Quer controlar melhor o consumo energético da casa, já que os filhos utilizam muitos aparelhos eletrônicos.
	•	Desafios: Precisa de sugestões acessíveis e viáveis para economizar sem precisar trocar todos os eletrodomésticos de uma vez.
	•	Objetivos: Melhorar a eficiência do consumo de energia da casa e ensinar hábitos mais sustentáveis para os filhos.

⸻

4. Rafael Martins – Pequeno Empreendedor
	•	Idade: 33 anos
	•	Profissão: Dono de uma cafeteria
	•	Estilo de vida: Preocupado com os custos do seu negócio e com a sustentabilidade. Quer adotar medidas ecológicas que também sejam financeiramente vantajosas.
	•	Motivação para usar o sistema: Além da conta de luz da sua casa, precisa entender como otimizar o consumo energético do seu estabelecimento.
	•	Desafios: Encontra dificuldades em saber quais equipamentos possuem melhor eficiência energética e como adaptar hábitos de consumo.
	•	Objetivos: Aprender a reduzir o consumo de energia no seu dia a dia e levar esse conhecimento para sua empresa, tornando-a mais sustentável.

⸻

5. Diego Souza – Estudante Universitário
	•	Idade: 21 anos
	•	Profissão: Estudante de Engenharia Ambiental
	•	Estilo de vida: Mora em república com amigos, interessado em tecnologia e sustentabilidade. Usa muitos eletrônicos para estudo e lazer.
	•	Motivação para usar o sistema: Quer aprender mais sobre consumo energético e compartilhar conhecimento no fórum com outras pessoas interessadas em sustentabilidade.
	•	Desafios: Precisa de informações detalhadas e embasadas sobre o impacto dos aparelhos elétricos no consumo geral.
	•	Objetivos: Aplicar o conhecimento adquirido na faculdade para melhorar a eficiência energética em sua casa e influenciar amigos a adotarem práticas sustentáveis.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir que o usuário realize cadastro e login (e-mail e senha). | ALTA | 
|RF-002| O sistema deve permitir que o usuário pesquise eletrodomésticos por nome, categoria ou eficiência energética. | ALTA |
|RF-003| Permitir que o usuário crie posts/tópicos no fórum. | ALTA |
|RF-004| Permitir que o usuário comente em posts existentes no fórum. | BAIXA |
|RF-005| O sistema deve exibir uma tela detalhada do eletrodoméstico com dados de consumo, comparação com modelos eficientes e dicas de economia. | ALTA |
|RF-006| Desenvolver a tela de histórico de visualizações dos eletrodomésticos pesquisados. | BAIXA |
|RF-007| O sistema deve permitir que moderadores apaguem ou editem posts/comentários inapropriados. | BAIXA |
|RF-008| O sistema deve permitir que administradores cadastrem/atualizem dados de eletrodomésticos no banco de dados. | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|RNF-003| O sistema deve garantir criptografia de dados (HTTPS e hash para senhas). |  BAIXA | 



## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |




