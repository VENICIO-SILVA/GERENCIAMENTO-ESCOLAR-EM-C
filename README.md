📚 Sistema de Gerenciamento Escolar em C

Este projeto é um sistema de gerenciamento escolar desenvolvido em linguagem C, com menus interativos para cadastro e consulta de informações de alunos, professores, disciplinas e notas.

 Funcionalidades

Cadastro

Alunos (nome, sobrenome, idade, CPF, matrícula)

Professores (nome, sobrenome, idade, CPF, matrícula)

Disciplinas (nome e professor responsável)

Registro de Notas

Associar notas a alunos em disciplinas específicas

Cálculo automático da média final de cada aluno

Relatórios

Listagem de todos os alunos

Alunos aprovados e reprovados (média ≥ 7 ou < 7)

Consulta detalhada de cada aluno com notas e médias


Linguagem C

Estruturas (struct) para modelagem de dados

Manipulação de arrays fixos com limites máximos (#define)

Funções modulares para organização do código

Controle de entrada/saída com scanf e printf


O sistema roda no terminal (console).

Utiliza system("cls") e system("clear") para limpar a tela (compatível com Windows/Linux).

CPF está implementado como int, mas pode ser ajustado para long long ou string para evitar limitações.
