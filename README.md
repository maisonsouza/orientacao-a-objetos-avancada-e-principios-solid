# Curso de SOLID com Java: Orientação a Objetos com Java
```
Pré-requisitos: Tecnologia em Orientação a objetos
                Conhecimentos de Alguma Linguagem Orientada a Objetos
```

## SOLID
> Acrônimo, conjunto de 5 boas práticas em Orientação a Objetos. Cada letra fala de uma boa prática em particular
```
*S*ingleReponsibilityPrinciple (Príncipio da Responsabilidade Única) - Coesão
*O*penClosedprinciple (Príncipio do Aberto e fechado) - Desaclopada e estável
*L*iskovSubstitutivePrinciple (Príncipio de Substituição de Liskov) - Herança e Composição
*I*nterfaceSegregationPrinciple (Príncipio de Segregação de Interface) - Interfaces
*D*ependencyInversionPrinciples (Principio de Inversão de Dependência) - Abstração
```

### Coesão e o Single Responsibility Principle
* Tenha classes que são muito coesas e pouco acopladas.
* Classes não coesas são dificéis de manter, complexas, sucetíveis a bug, dificéis de testar.
* Classes coesas são pequenas e bem definidas.

### Acoplamento e estabilidade
* O problema do acoplamento é tornar as classes fragéis a mudanças.
* Devemos usar acoplamento com classes e interfaces estavéis que mudem menos.
* Acoplamento eferente(Classe depende outras) x Acoplamento aferente(Quem depende de mim)
* Programe voltado a interface

### Classes abertas, Open Closed Principle e o Dependence Inversion Principle
* **Abertas** para extensão, **fechadas** para alteração.
* DIP - Pensar primeiro na abstração depois na implementação

### Entendendo o encapsulamento
* Mostrar o que o método faz e esconder como ele faz.
* Pensar na propagação de mudanças.
* As classes clientes não devem conhecer a implementação.
* Lei de Demeter - Ganhar encapsulamento.

### Herança, COmposição e Liskov Substitute Principle
* Principio de Substituição de Liskov
* Pré condições das classes filhas não podem ser muito restritas.
* Pós condições das classes filhas não podem ser muito irrestritas.
* O Uso de herança é complexo.
* Favoreça a composição ao invés da herança.

