# Automatizar alteração do tipo de instancia EC2 usando Lambda e CloudWatch na AWS

Basicamente este tutorial permite alternar os tipos de instâncias EC2 automaticamente, essas alterações podem ser realizadas em horários ou dias específicos de acordo com sua necessidade. 

Por exemplo: um servidor de produção que utiliza muitos recursos de CPU e Memória em virtude do alto número de acessos de usuários durante o dia. Porém das 18h:00min às 05h:00min, a quantidade de acessos diminui. Neste momento o tipo de instância EC2 pode ser alterado para um tipo que exija menos recursos de CPU e Memória e consequentemente diminuindo o valor cobrado dessa EC2. Este procedimento pode ser feito de forma automatizada e será mostrado abaixo.

Este foi um processo realizado na empresa em que trabalho. Entendo que existem outras formas de fazer e obter o mesmo resultado, porém o que estou compartilhando funcionou perfeitamente e obvite uma redução de custos $$$ considerável mensalmente.
