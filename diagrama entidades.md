# Diagrama de entidades

## funcionarios

* id String
* nome String
* email String
* senha String
* celular String
* tecnico Boolean
* status String
* ativo Boolean
* Especialidades

## clientes

* id String
* CNPJ
* nome String
* telefone String
* email String
* endereco String // tabela de endereços

## Ordens de serviço

* id String
* idCliente String
* idFuncionario        // FK null
* endereco String      // depende do cliente
* descricao String
* Situação             // fazer orçamento, em aberto, concluida....  Default: em Aberto
* dtRequisitado String
* dtAtendido String
* dtConcluido String

## Serviços // Tipos de serviços prestados

* id
* nome/descrição
* preçoBase
* 
* 
