
# Mocks em Java: conhecendo o Mockito - Leilao - ALURA

# Índice 

* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Conclusão](#conclusão)

# 💻 Descrição do Projeto 💻
Neste aprendemos o que são  mocks e quando são necessários ao escrever testes automatizados. O Mockito, a principal biblioteca de mocks em Java
Escreveremos testes de unidade utilizando o Mockito, simulamos comportamentos de mocks, realizamos validações de mocks e os principais recursos do Mockito

Já sabemos o que são testes automatizados e já sabemos utilizar o JUnit para escrever testes de unidade,por isso vamos aprender a  a usar Mocks.

Em alguns casos, as classes de um projeto dependem de outras classes que executam algum serviço externo, como, por exemplo, acessar um banco de dados. Às vezes, queremos testar apenas a lógica daquela classe de maneira isolada, mas pelo fato de ela depender de outra classe, não é possível isolar essas dependências e testá-la individualmente. Podemos solucionar esse problema fazendo a integração ou usando um Mock, que é o objetivo deste projeto.

Mas o que são Mocks?
De maneira resumida, o Mock é uma classe que simula os comportamentos de outra classe. Ele serve para cenários em que queremos testar as lógicas e os algoritmos de uma classe que tem dependência de outra classe, mas isolando essas dependências.

Com os Mocks, conseguimos escrever um teste de unidade em vez de ter que usar um teste de integração, ou seja, que vai se integrar às dependências.



# Status do Projeto
Finalizado


# PessoasContribuidoras
 Realizei este projeto auxiliado pelas aulas e professores da Alura.
 
 # Tecnologias Utilizadas
- Java
- Mockito
- JUnit
 
# Conclusão

Entendemos a situação em que precisamos utilizar Mock, ou seja, quando queremos testar uma classe. Por exemplo, na nossa classe FinalizarLeilaoService{}, queríamos testar a lógica do finalizarLeiloesExpirados(). Contudo, essa classe tem duas dependências: a LeilaoDao e a EnviadorDeEmails.

Não queríamos fazer um teste de integração. Queríamos um teste de unidade, testando a lógica do finalizarLeiloesExpirados() da classe sem acessar o banco de dados e sem disparar o envio de e-mails. Para fazer essa simulação de acesso do banco de dados e disparada de e-mails, aprendemos que utilizamos Mocks. 

