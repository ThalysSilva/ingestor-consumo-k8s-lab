# Course workspace

Esta pasta guarda o material produzido ao longo do curso de Kubernetes.

## Princípio de uso do projeto

O repositório preserva a aplicação completa como sistema-base real. O curso,
porém, não precisa colocar toda a arquitetura em cena desde o início.

A progressão será feita por recortes:

1. começar com apenas os componentes necessários ao conceito atual;
2. adicionar novas peças quando elas ajudarem a ensinar o próximo tópico;
3. chegar gradualmente ao sistema completo.

Isso evita duas armadilhas:

- simplificar artificialmente o projeto e perder valor didático futuro;
- tentar migrar toda a arquitetura cedo demais e aumentar a carga cognitiva.

## Estrutura

- `notes/`: anotações e sínteses das aulas;
- `labs/`: exercícios, checkpoints e experimentos guiados;
- `manifests/`: manifests Kubernetes criados progressivamente.

As subpastas específicas de módulos devem ser criadas conforme a trilha avançar,
não antecipadamente.
