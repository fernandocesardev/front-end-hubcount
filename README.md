# Parabéns Desenvolvedores!

Se você recebeu este teste é porque você foi um dos selecionados para a fase de conhecimento da vaga de Front-end da HubCount.

Mas vamos para o que importa: O Teste.

## DESAFIO: CALCULADORA DE ENTREGAS

### Descrição

Você deverá desenvolver um mini sistema que irá calcular o frete através do CEP que for informado pelo usuário.

### Descrição do sistema

A tela inicial deverá conter 2 campos e 2 botões, sendo eles:

- Campo 1: Nome do cliente
- Campo 2: CEP do cliente
- Botão 1: Adicionar frete (é possível adicionar mais de 1 frete para cálculo)
- Botão 2: Calcular fretes

Após acionar o botão para adicionar frete (Botão 1), o sistema irá adicionar o cliente e o CEP a tabela de fretes a serem calculados. 

Após acionar o cálculo dos fretes (Botao 2), o sistema irá redirecionar para a última tela, que deverá conter a tabela de informações do cliente (Nome, Dados de endereço fornecidos pela consulta do CEP*) junto do cálculo do frete. Nesta mesma tela deverá ter um botão para voltar e um para imprimir o orçamento calculado.

\* - Rua, Bairro, Cidade, Estado...

OBS: Utilize um serviço de consulta de CEP. Recomendamos o ViaCEP (https://viacep.com.br/)

Wireframe :
![image](https://user-images.githubusercontent.com/3793622/115311979-ebc0dd00-a146-11eb-9886-163f3826fc9e.png)

### Regra de negócio (considerando uma empresa localizada em SP capital)

- Para São Paulo capital o frete e gratis
- Capitais da região sudeste terão frete fixo de R$ 50,00
- Cidades do interior da região sudeste terão frete fixo de R$ 80,00
- Capitais das regiões Sul e Nordeste terão frete fixo de R$ 70,00
- Cidades do interior das regiões sul e nordeste terão frete fixo de R$ 100,00
- Capitais das regiões Centro-oeste e Norte terão frete fixo de R$ 100,00
- Demais cidades terão frete fixo de R$ 150,00

### Regras do teste:

- Desenvolver e entregar em até 1 semana da data da entrevista.
- Devera utilizar algum framework JS (preferencia pelo Angular 2+/AngularJS)
- Devera ter um layout responsivo

### Método de avaliação por prioridade (_da mais para a menos importante_):

1. Data de entrega: não ultrapassar o deadline (7 dias do envio do teste).
2. Funcionalidade: deve funcionar da forma pedida.
3. Ferramentas: deve utilizar as tecnologias obrigatórias.
4. Validações: deve validar os campos e retornar mensagens amigáveis.
5. Código: bem escrito e bem descrito.
6. Plus II*: layout.
7. Plus III*: outras tecnologias utilizadas.

\*: _o importante são os outros pontos, mas esse poderá ser escolhido como ponto de desempate_
