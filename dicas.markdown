## Install:
    
### Criando a iso do Sistema Operacional

``` dd if=debian.iso of=/dev/sdb bs=16M oflag=sync status=progress ```
    
   ### Como eu sei o valor do parametro bs?
        Vc pode fazer testes de performance, muito pequeno aumenta o tempo para completar a tarefa.
        Eu fiz alguns testes e cheguei nesse número, mas não sei dizer se é o ideal, mas o tempo é aceitável.
        Obs.: Uma vez esqueci de especificar o bs e ia demorar dez horas para completar o dd hahaha
