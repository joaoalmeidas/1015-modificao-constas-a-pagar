# 1015-modificao-constas-a-pagar
Neste exercício, modificamos o aplicativo de contas a pagar das figuras 10.11 a 10.15 a fim
de incluir a funcionalidade completa do aplicativo de folha de pagamento das figuras 10.4 a 10.9. O aplicativo ainda deve processar dois
objetos Invoice, mas agora deve processar um objeto de cada uma das quatro subclasses Employee. Se o objeto atualmente processado
for uma BasePlusCommissionEmployee, o aplicativo deverá aumentar o salário-base de BasePlusCommissionEmployee em
10%. Por fim, o aplicativo deve gerar a saída da quantia de pagamento para cada objeto. Complete os seguintes passos para criar o novo
aplicativo:
a) Modifique as classes HourlyEmployee (Figura 10.6) e CommissionEmployee (Figura 10.7) para colocá-las na hierarquia
Payable como subclasses da versão de Employee (Figura 10.13) que implementa Payable. [Dica: altere o nome do método
earnings para getPaymentAmount em cada subclasse, de modo que a classe satisfaça seu contrato herdado com a interface
Payable.]
b) Modifique a classe BasePlusCommissionEmployee (Figura 10.8) para que ela estenda a versão da classe CommissionEmployee
criada na parte (a).
c) Modifique PayableInterfaceTest (Figura 10.15) para processar polimorficamente duas Invoice, uma SalariedEmployee,
uma HourlyEmployee, uma CommissionEmployee e uma BasePlusCommissionEmployee. Primeiro gere uma representa-
ção String de cada objeto Payable. Em seguida, se um objeto for uma BasePlusCommissionEmployee, aumente seu salário-
-base em 10%. Por fim, gere a saída da quantia de pagamento para cada objeto Payable.
