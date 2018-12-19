# DesafioBackEnd-Secrel

Este arquivo não possui git ignore, logo basta baixa-lo e usar o comando no terminal nodemon

Basta antes criar um banco com o nome de "desafio" e criar as seguintes tabelas

```
CREATE TABLE `tarefas` (
    `id` INT NOT NULL AUTO_INCREMENT,
    `nome` VARCHAR(255) NOT NULL,
    `descricao` VARCHAR(255) NOT NULL,
    `prazo` DATE NOT NULL,
    `prioridade` VARCHAR(100) NOT NULL,
    `concluida` VARCHAR(100) NOT NULL,
    PRIMARY KEY (`id`)
) ENGINE=INNODB;

CREATE TABLE `users` (
    `id` INT NOT NULL AUTO_INCREMENT,
    `username` VARCHAR(20) NOT NULL,
    `password` VARCHAR(20) NOT NULL,
    PRIMARY KEY(`id`)
) ENGINE=INNODB;
```

cmd, digitar comando nodemon e digitar navegador localhost:3000