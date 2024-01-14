# 1.0 Noções fundamentais
  Conclusão

# 1.1 Objetivos

Este documento tem como propósito definir e organizar os seguintes aspectos sobre o desenvolvimento da solução do IFPI- campus Angical.

# 1.2 Proposito
Este projeto tem como finalidade suprir a necessidade de controle e coordenação da diretoria referente a vida acadêmica dos alunos do IFPI- campus Angical

busca uma melhor solução em software para substituir um sistema precedentemente implementado, sendo que, deve possuir como característica necessária a confiabilidade total.

O software, a ser implementado, deve monitorar a presença e atividades escolares dos alunos mantendo os responsáveis informados.

# Panoramas gerais

| Visões  |
| --------------|
| Bruno pega as chaves diariamente |
| A Autorização é obrigatória para acessar chaves de laboratórios específicos |
| Necessidade de solicitar permissão para pegar a chave |
| Restrição de permanência em apenas um laboratório |
| Designação de monitores individuais para cada professor |
| Restrição de levar chaves para casa, tanto para professores quanto para alunos |
| Monitoramento e responsabilidade dos monitores |
| Implementação de sistemas para facilitar a distribuição de chaves aos alunos, mediante autorização do professor |

# 2.Estrutura
# 2.1 Oportunidade de negócios
Atualmente, a maneira como as escolas públicas gerenciam a vida acadêmica dos professores é antiquada e ineficiente. O controle é rudimentar, causando problemas na precisão e atualização dos dados, o que dificulta a comunicação eficiente com os responsáveis. Isso prejudica o processo acadêmico como um todo. Nosso projeto propõe uma solução moderna e eficaz, utilizando a informatização para identificar alunos e notificar os pais, melhorando significativamente a gestão escolar.

# 2.2 Principais desafios Identificados
| Desafios |
| --------------|
|Falta de um sistema eficiente para facilitar a entrega de chaves aos alunos com autorização do professor|
|Prática recorrente de professores e alunos levando as chaves para casa|
|Risco de perda das chaves|
|Necessidade de arrebentar a porta em caso de perda da chave, impactando negativamente as atividades acadêmicas|
|Possibilidade de perder tanto a chave principal quanto a reserva, aumentando a complexidade do problema|
|Dificuldade em rastrear responsabilidades, especialmente quando outros servidores possuem cópias das chaves, o que pode resultar em situações de falta ou danos em salas sem identificação do responsáve|

# Descrições da Parte Interessada e do Usuário

# 3.1 Perfil Resumido da Parte Interessada
Nome	Descrição	Responsabilidade
Equipe de Desenvolvimento	Estudantes da Universidade de Brasília na disciplina de MDS.	Desenvolver e Implementar o software.
Equipe de Gestão de Projeto	Estudantes da Universidade de Brasília na disciplina de GPP.	Gerir o desenvolvimento do produto, identificando problemas e propondo soluções.
Clientes	Centro de Ensino Médio 01 do Gama.	Fornecer informações sobre os alunos.

# 3.2 Principais Necessidades da Parte Interessada
Necessidades	Prioridade	Interesses	Solução Atual	Solução Proposta
Gerenciar a vida acadêmica dos alunos.	Alta	Manter controle diário de entrada/saída e atividades acadêmicas dos alunos.	Método manual e ineficiente, usando também o aplicativo Acadêmicos Total Pais e Filhos.	Implementar um software mais confiável para gerenciar eficientemente a vida acadêmica dos alunos.
Notificar os responsáveis.	Alta	Informar os responsáveis sobre entrada/saída e vida acadêmica dos alunos.	Responsáveis recebem SMS sobre entrada dos alunos, mas não têm acesso digital ao histórico escolar.	Enviar SMS aos responsáveis sobre entrada/saída do aluno e disponibilizar uma plataforma web para acesso ao histórico escolar do estudante.
Acompanhar o desenvolvimento acadêmico dos alunos.	Média	Ter uma visão abrangente e atualizada do desempenho dos alunos.	Relatórios periódicos e reuniões presenciais.	Desenvolver um sistema que permita o acompanhamento contínuo e detalhado do desempenho acadêmico dos alunos.
Facilitar a comunicação entre escola e responsáveis.	Alta	Estabelecer uma comunicação eficaz para questões acadêmicas e administrativas.	Comunicação principalmente por telefone e reuniões presenciais.	Implementar uma plataforma de comunicação integrada que permita a troca de informações de maneira eficiente entre a escola e os responsáveis.

# 4 Visão Geral do Produto
# 4.1 Perspectiva do Produto
A visão do produto centra-se na introdução de um sistema informatizado e eficiente para monitorar o acesso dos alunos, utilizando o leitor de códigos de barra já existente na instituição de ensino. Este leitor realizará a identificação de cada aluno por meio da carteirinha, permitindo que os responsáveis recebam notificações por SMS sobre os horários de entrada e saída dos alunos.

Além disso, cada responsável terá acesso a um histórico escolar abrangente do aluno. Este histórico incluirá informações cruciais, como o número de faltas, desempenho acadêmico no boletim escolar e registros de advertências ou suspensões. Dessa forma, a proposta vai além do simples controle de acesso, oferecendo uma solução abrangente para que os responsáveis possam acompanhar de perto o desenvolvimento acadêmico e comportamental de seus filhos. Essa abordagem visa fornecer uma experiência mais completa e transparente no envolvimento dos responsáveis na vida escolar dos alunos. 

# Membros
| Nome | Dever |  E- mail | 
| :---         |     :---:      |          ---: |
| Felipe Justo | listar visões gerais (escopo)     | caang.2022119isinf10@aluno.ifpi.edu.br   | 
| Felipe Ribeiro | Listar problemas/ soluções  | caang.2022119isinf11@aluno.ifpi.edu.br     | 
