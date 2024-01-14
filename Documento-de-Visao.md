# 1.0 Noções fundamentais
  Conclusão

# 1.1 Objetivos

Este documento tem como propósito definir e organizar os seguintes aspectos sobre o desenvolvimento da solução do IFPI- campus Angical.

# 1.2 Proposito
Este projeto tem como finalidade suprir a necessidade de controle e coordenação da diretoria referente a vida acadêmica dos alunos do IFPI- campus Angical

busca uma melhor solução em software para substituir um sistema precedentemente implementado, sendo que, deve possuir como atributo necessário a confiabilidade total.

O software, a ser implementado, deve monitorar a presença e atividades escolares dos alunos mantendo os responsáveis sempre informados.

# Panoramas gerais

| Visões  |
| --------------|
| Bruno pega as chaves diariamente |
| A Autorização é obrigatória para acessar chaves de laboratórios específicos |
| Necessidade de solicitar permissão para pegar a chave |
| Restrição de permanência em apenas um laboratório |
| Escolha de monitores individuais para cada professor |
| Restrição de levar chaves para casa, tanto para professores quanto para alunos |
| Monitoramento e responsabilidade dos monitores |
| Implementação de sistemas para facilitar a distribuição de chaves aos alunos, mediante autorização do professor |

# 2.Estrutura
# 2.1 Oportunidade de negócios
Tendo em vista que atualmente, o modo como as escolas públicas gerenciam a vida acadêmica dos professores é antiquada e ineficiente. O controle é rudimentar, podendo causar problemas na precisão e atualização dos dados, o que dificulta a comunicação eficiente com os responsáveis. Isso prejudica o processo acadêmico como um todo.

O nosso projeto tem como principal objetivo propor uma solução compreensivel, utilizando a informatização para identificar alunos e notificar os pais, melhorando consideravelmente a gestão escolar.

# 2.2 Principais desafios Identificados
| Desafios |
|--------------|
|Falta de um sistema eficiente para facilitar a entrega de chaves aos alunos com autorização do professor|
|Prática recorrente de professores e alunos levando as chaves para casa|
|Risco de perda das chaves|
|Necessidade de arrebentar a porta em caso de perda da chave, impactando negativamente as atividades acadêmicas|
|Possibilidade de perder tanto a chave principal quanto a reserva, aumentando a complexidade do problema|
|Dificuldade em rastrear responsabilidades, especialmente quando outros servidores possuem cópias das chaves, o que pode resultar em situações de falta ou danos em salas sem identificação do responsável

# Descrições da parte interessada 
# 3.1 Resumo da parte Interessada 
| Nome | Descrição | Responsibilidade
| --- | --- | --- |
| Equipe de desenvolvimento| Estudantes da Universidade de Brasília da disciplina de MDS.| Desenvolver e Implementar o software.
| Equipe de Gestão de Projeto | Estudantes da Universidade de Brasília da disciplina de GPP. | Gerir o desenvolvimento do produto identificando o problema e apontando caminhos e soluções.
| Clientes | Centro de Ensino Médio 01 do Gama. | Disponibilizar informações sobre os alunos .

# Descrições da parte interessada e do usuário 

# 3.2 Principais necessidades da parte interessada
| Necessidades | Prioridade | Interesses | Solução atual | Solução proposta
| ------------- | ------------- | ------------- | ------------- | -------------
Necessidades Prioridade Interesses	Solução Atual	Solução Proposta
Gerenciar a vida acadêmica dos alunos.|Alta|Manter controle diário de entrada/saída e atividades acadêmicas dos alunos.	Método manual e ineficiente, usando também o aplicativo Acadêmicos Total Pais e Filhos.|Implementar um software mais confiável para gerenciar eficientemente a vida acadêmica dos alunos.
|Notificar os responsáveis.|Alta|Informar os responsáveis sobre entrada/saída e vida acadêmica dos alunos.|Responsáveis recebem SMS sobre entrada dos alunos, mas não têm acesso digital ao histórico escolar.	Enviar SMS aos responsáveis sobre entrada/saída do aluno e disponibilizar uma plataforma web para acesso ao histórico escolar do estudante.
Acompanhar o desenvolvimento acadêmico dos alunos.	Média	Ter uma visão abrangente e atualizada do desempenho dos alunos.	Relatórios periódicos e reuniões presenciais.	Desenvolver um sistema que permita o acompanhamento contínuo e detalhado do desempenho acadêmico dos alunos.
Facilitar a comunicação entre escola e responsáveis.	Alta	Estabelecer uma comunicação eficaz para questões acadêmicas e administrativas.	Comunicação principalmente por telefone e reuniões presenciais.	Implementar uma plataforma de comunicação integrada que permita a troca de informações de maneira eficiente entre a escola e os responsáveis.

# 4 Visão Geral do Produto
# 4.1 Perspectiva do Produto
A visão do produto centra-se na introdução de um sistema informatizado e eficiente para monitorar o acesso dos alunos, utilizando o leitor de códigos de barra já existente na instituição de ensino. Este leitor realizará a identificação de cada aluno por meio da carteirinha, permitindo que os responsáveis recebam notificações por SMS sobre os horários de entrada e saída dos alunos.

Queremos criar uma solução moderna para as escolas públicas, informatizando o sistema de identificação de alunos e comunicação com os pais. Além disso, proporcionaremos aos responsáveis um histórico completo, incluindo frequência, notas e registros disciplinares, para um acompanhamento mais eficaz do desenvolvimento acadêmico e comportamental dos alunos. A ideia é oferecer uma experiência mais completa e transparente, envolvendo os responsáveis de maneira mais ativa na vida escolar de seus filhos. 

# Membros
| Nome | Dever |  E- mail | 
| :---         |     :---:      |          ---: |
| Felipe Justo | listar visões gerais (escopo)     | caang.2022119isinf10@aluno.ifpi.edu.br   | 
| Felipe Ribeiro | Listar problemas/ soluções  | caang.2022119isinf11@aluno.ifpi.edu.br     | 
