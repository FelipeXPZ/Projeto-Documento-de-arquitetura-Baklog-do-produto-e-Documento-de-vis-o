# 1. Introdução
Bom, agora vamos adentrar nas camadas do diagrama de controle de chaves, revelando oque há por trás da gestão inteligente de acessos e compartilhando saberes e ajudando para que haja a edificação de ambientes mais seguros e mais bem organizados  .
Ao longo desta narrativa, não apenas desvendaremos os aspectos técnicos do diagrama, mas também destacaremos seu impacto tangível em cenários do dia a dia. Seja você um desenvolvedor em busca de perspicácia para implementar um sistema eficiente,ou um gestor dedicado buscando à segurança do local ou um usuário final imerso nas operações diárias, esta jornada busca proporcionar uma melhor compreensão do controle de chaves e sua crescente importância.

# 1.1 Finalidade
Este documento possui como finalidade trazer questões relacionadas à implementação arquiteturial do projeto controle de chaves, mais tambem idealizado na disciplina da Análise e Projeto de Sistemas, que possui como cliente principal a direção da escola IFPI - Campus Angical.Portanto, a importância desse documento reside na sua capacidade de fornecer uma visão clara e conclusiva do sistema de controle de chaves, chegando assim a uma implementação mais eficiente,mais segura e satisfatória para que todas as partes envolvidas tenham um melhor experiência.

# 1.2 Escopo
O diagrama de controle de chaves abaixo oferece uma visão organizada e abrangente do sistema, destacando a eficácia na gestão de acesso e posse de chaves em um ambiente específico. Ele ilustra mecanismos de segurança, como autenticação e autorização, além de evidenciar a integração entre diferentes camadas do sistema. Essa representação proporciona uma melhor compreensão da funcionalidade do sistema e do controle de chaves.

# 2. Visão dos casos de uso
![Imagem 2024-01-12 à(s) 23 33 21_80aa049a](https://github.com/FelipeXPZ/documento-de-visao./assets/144725344/8dd756cd-7007-4754-8adb-683205c5931d)

# 2.1 Atores de Casos de Uso
Ator	Descrição
Adm(Diretor)	O administrador garanti-rá os dados do corpo docente, dos alunos e pode consultar os dados dos alunos.
Aluno	O aluno registra-ra sua entrada e saída e poderá consultar seus dados.
Responsável	O responsável pode-rá examinar os dados do aluno e recebe as informações de entrada e saída do aluno.
Professor	O professor pode consultar dados dos alunos e gerar as informações.
Secretário	O secretário pode registrar as notas e depois consultar os dados dos alunos.

# 2.2 Descrições de Casos de Uso
Caso de Uso	Descrição
UC01 - Manter Alunos	Permite criar, alterar ou apagar um aluno no sistema.
UC02 - Registrar Advertência	Registra uma nova advertência para um aluno.
UC03 - Registrar Suspensões	Registra uma nova suspensão para um aluno.
UC04 - Registrar Notificação	Relata a notificação para aluno.
UC05 - Manter Responsáveis	Permite criar, modificar ou eliminar um responsável de um aluno.
UC06 - Consultar Aluno	Realiza a busca pelo no histórico de um aluno.
UC07 - Visualizar Número de Faltas	Acessa o número de faltas de um determinado aluno.
UC08 - Visualizar Boletim  Acessa o boletim de um determinado aluno.
UC09 - Visualizar Advertências ou Suspensões  Acessa o número de advertências/suspensões de um determinado aluno.
UC10 - Dar Nota	Aderir as notas aos alunos.
UC11 - Registrar Entrada/Saída	Registra a hora de entrada ou saída do aluno.
UC12 - Notificar os Responsáveis	Envia SMS aos responsáveis após a entrada/saída do aluno.
UC13 - Manter Corpo Docente	Permite criar, alterar ou excluir um membro do corpo docente.
UC14 - Fazer Login	Ter acesso as aplicações do sistema, autenticando-se.

# 3.visão

# 3.1 Classe
![Imagem de diagrama 2024-01-13 à(s) 00 48 59_b1a7c709](https://github.com/FelipeXPZ/documento-de-visao./assets/144725344/368d1068-b0dd-489c-8cf4-944ae90bb539)

# 3.2 Colaboração entre Classes
O objetivo deste tópico é apresentar as principais colaborações entre as classes para executar suas funções dentro do sistema.
# 3.1.2 Cartão CRC
![286594612-2d4d9617-0195-4c72-a28e-b07528792c0f](https://github.com/FelipeXPZ/documento-de-visao./assets/144725344/8ecc802d-1b7e-4dd7-b593-865116022409)

# 3.2.2 Lógica das Responsabilidades
1.Responsabilidade: Cadastrar

Colaboradoras:
Usuário
Chave
Autorização
Colaborações:
Consultar Usuário
Consultar Chave
Chave disponível
Autorização da chave

2.Responsabilidade: Em aberto

Colaboradoras:
Usuário
Chave
Colaborações:
Retornar Usuário
Retornar Chave

3.Responsabilidade: Retirar

Colaboradoras:
Usuário
Chave
Colaborações:
Notificar()
Retornar Usuário
Retornar Chave

4.Responsabilidade: Transferir

Colaboradoras:
Usuário
Colaborações:
Consultar Usuário
Retirar()
Cadastrar()

5.Responsabilidade: Pesquisar

Colaboradoras:
Usuário
Chave
Colaborações:
Consultar Chave
Retornar Usuário
Retornar Chave

Na lógica que foi proposta, cada compromisso está associada a um conjunto exato de colaboradoras (atores ou entidade envolvidos) e cooperações (ações ou funções realizadas). Isso ajuda a organizar e manter de maneira clara e objetiva as relações entre diferentes partes do sistema de controle de chaves, tornando mais fácil buscando entender quais entidades estão inclusas em cada uma das tarefas e quais ações são executadas para cumprir um dever específico.

Classe: Posse
Responsabilidade: cadastrar() - Cadastrar a posse de uma chave para um usuário.

* Criar um objeto usuário com os dados repassados.
* Criar um objeto chave com os dados repassados.
* Verificar se o usuário existe ou não
* Verificar se a chave existe ou não
* Verificar se a chave está disponível
* Verificar a autorização do usuário para posse da chave
* Responsabilidade:em Aberto()- Listar






