** Abertura e fechamento de turno usando apenas o cartão do Motorista **

### Objetivo
~~~~
Validar a abertura e fechamento de turno usando apenas o cartão do Motorista para a operação
~~~~

### Pré-condições
~~~~
N/A
~~~~

### Atores
~~~~
* Operador
* Acesso
~~~~

### Fluxo
~~~~
01. O Operador apresenta o cartão do motorista no Acesso;
02. O Acesso inicia a abertura do turno solicitando ao Operador a configuração da opção [INFORME O TIPO DO TURNO];
03. O Operador apresenta o cartão do motorista no Acesso quando o cursor estiver em [AVAN] para avançar a opção;
04. O Acesso solicita ao Operador a configuração da opção [INFORME O PONTO DE INICIO];
05. O Operador apresenta o cartão do motorista no Acesso quando o cursor estiver em [AVAN] para avançar a opção;
06. O Acesso deve exibir ao Operador a mensagem [AFASTE O CARTAO];
07. O Operador deve afastar o cartão do Acesso;
08. O Acesso deve exibir ao Operador a mensagem [APRESENTE O CARTAO COBRADOR] e o tempo decrescente para concluir a operação;
09. O Operador apresenta e mantem o cartão no Acesso;
10. O Acesso deve exibir ao Operador a mensagem [MANTENHA O CARTAO APROXIMADO PARA TURNO SEM COBRADOR];
11. O Acesso deve exibir ao Operador a mensagem [18 COLETAS RESTANTES AFASTE O CARTAO];
12. O Acesso deve gerar o evento 1 de [ABERTURA DE TURNO];
13. O Acesso deve entrar em estado de turno aberto e exibir a mensagem [APRESENTE O CARTAO E AGUARDE A LUZ VERDE];
14. O Operador deve apresentar e manter o cartão do motorista no Acesso;
15. O Acesso deve exibir ao Operador a mensagem [MANTENNHA O CARTAO APROXIMADO PARA FECHAR O TURNO];
16. O Acesso deve exibir ao Operador a mensagem [18 COLETAS RESTANTES AFASTE O CARTAO];
17. O Acesso deve gerar o evento 19 de [TURNO FECHADO];
~~~~

### Pós-condições
~~~~
N/A
~~~~
