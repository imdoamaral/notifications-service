## Conceitos do Nest.js

## 1. MODULES

### Decorator
- Serve para ACOPLAR um "funcionamento" dentro de uma outra classe, função ou variável.
- Utiliza o identificador @

### Controller
- Arquivos que são PONTOS DE ENTRADA da aplicação
- Vão lidar com as chamadas HHTP

## 2. SERVICES
- Classes sem um propósito específico (pode ser qualquer coisa)
- Os controllers servem para definir as rotas da aplicação, e os services: todo o resto.
- Ex: conexão com banco de dados, repositórios, etc.

O Nest também trabalha com um dos princípios do SOLID que é a **Inversão de Dependência**, ou seja, ao invés da classe BUSCAR a funcionalidade, ela estará RECEBENDO a funcionalidade em um construtor.

*Parei em 1:09:33*