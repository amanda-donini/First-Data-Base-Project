# First-Data-Base-Project
I created my first data base project
              Projeto de Banco de Dados:
Contexto:
  - Dentro de uma empresa os clientes demandam ao helpdesk algumas ações.
  - Essas ações são convertidas em ordem de serviço
  - Os clientes realizam um pedido
  - O pedido é convertido em ordem de serviço caso possa ser realizado
  - O técnico executa a ordem de serviço. Após sua finalização a mesma é arquivada

Entidades: 
  Cliente, Responsável, Pedido e Ordem de Serviço

Relacionamentos
  Solicita, Analisa, Executa, Arquiva
  
            Projeto de Universidade
            
Narrativa - Alunos:
  - A universidade possui diversos alunos que podem estar matriculados em mais de um curso (graduação).
  - Os alunos podem fazer cursos extras fornecidos externa e internamente (universidade) para contar como horas complementares
  - Não há restrição quanto ao número de matérias puxadas se não houver sobreposição de horário.
  - Os alunos são submetidos a duas provas por semestre para cada disciplina. Eventuais trabalhos devem ser tratados pelo professor para compor a nota da prova.
  
Narrativa - Disciplinas:
  - Cada disciplina é fornecida por um professor. Restrição: apenas por este professor.
  - Algumas disciplinas possuem pré-requisitos. Um mesmo pré-requisito pode ser associado a mais de uma disciplina.
  - As disciplinas podem ser comuns a cursos distintos. Ex: Cálculo 1 para computação e engenharia
  - O ciclo de vida da disciplina é semestral
  
Narrativa - Professores:
  - Os professores que ministram as disciplinas estão associados as coordenações de seus respectivos cursos. Ex: Computação, Física, Engenharia …

            Projeto de E-commerce
            
Narrativa - Produto:
  - Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)
  - Cada produto possui um fornecedor
  - Um ou mais produtos podem compor um pedido
  
Narrativa - Cliente:
  - O cliente pode se cadastrar no site com seu CPF ou CNPJ
  - O Endereço do cliente irá determinar o valor do frete
  - Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto
  
Narrativa – Pedido:
  - O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega
  - Um produto ou mais compoem o pedido
  - O pedido pode ser cancelado






