# Aplicativo escolhido

## <a>Histórico de Versão</a>

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
| :----------: |:----------:| :------: | :-----------: | :---------: |:---------: |
|20/11/2022|21/11/2022|1.0|Criação do Documento| [Pedro Lucas](https://github.com/PedroLSF)|[Ana Luiza](https://github.com/AnHoff)
|20/11/2022|21/11/2022|1.1|Ajustes gerais e complementações| [Ana Luiza](https://github.com/AnHoff)|[Pedro Lucas](https://github.com/PedroLSF)
|29/11/2022|30/11/2022|1.2|Correção no Historico de Versão| [Thiago Oliveira](https://github.com/Thiab394)|[João Lucas](https://github.com/HacKairos)
|19/01/2023|20/01/2023|1.3|Correções com base na verificação| [Ana Luiza](https://github.com/AnHoff)|[Eduardo](https://github.com/edudsan)

## <a>Introdução</a>
Existe um documento que comenta um pouco sobre cada um dos aplicativos analisados e que poderiam ser utilizados para o desenvolvimento desse projeto é recomendado ler tal documento e entender o que é o MEI.

O presente documento foca em apresentar o MEI, com suas principais funcionalidades e motivos de escolha, seguido pelos problemas encontrados.

## <a>Motivos de escolha</a>
O MEI é um aplicativo ligado ao Portal do Empreendedor, sendo um dos motivos mais relevantes para a escolha desse aplicativo a existência de uma ampla amostra de usuários. Tal público alvo abundante pode ser facilmente encontrado para auxiliar no desenvolvimento do projeto em questão, fator extremamente relevante para um bom andamento do mesmo. As funcionalidades do aplicativo serão apresentadas em seguida.

### <a>Emitir DAS</a>
#### <a>O que é o DAS?</a>
O DAS é o Documento de Arrecadação do Simples Nacional, ou seja, é como o empresário vai recolher os impostos e através dessa função você pode selecionar o mês e gerar um boleto para pagamento. Os impostos para o MEI são especiais pois, além de ter um valor baixo, ele é fixo. Em resumo, você pode colocar no seu controle de gastos e não terá surpresas ao final do mês.
<br>
Outro ponto notável é a possibilidade de obter o QrCode do boleto.

### <a>Consultar CNPJ</a>
Você pode consultar seu CNPJ. Para isso, siga as seguintes instruções:
<br>

1. Clique em "Consultar CNPJ";
2. Passe pela etapa de segurança;
3. Pronto!

Essa função permite o acesso aos seguintes dados:
<br>

* Situação Cadastral;
* Nome Fantasia;
* Natureza Jurídica;
* CNAE;
* Capital Social;
* Endereço;
* Telefone;
* E-mail.

### <a>Consultar SIMEI</a>
#### <a>O que é o SIMEI?</a>
SIMEI é o sistema de recolhimento dos tributos abrangidos pelo Simples Nacional em valores fixos mensais, devidos pelo Microempreendedor Individual, conforme previsto no artigo 18-A da Lei Complementar nº 123, de 14 de dezembro de 2006. Nesta Tela, você poderá obter informações relativas à situação atual e períodos de opção no Simples Nacional, bem como consultar o valor fixo mensal devido pelo MEI, no ano corrente, que correponde à soma dos seguintes tributos:
<br>

* Contribuição previdenciária relativa à pessoa do empresário na qualidade de contribuinte individual, no valor de 12% ou 5% do limite máximo mensal do salário de contribuição;
* R$ 1,00, a título de ISS, caso seja contribuinte desse imposto;
* R$ 5,00, a título de ISS, caso seja contribuinte desse imposto.

As informações presentes na tela são:
<br>

* Situação Atual;
* Períodos de Opção;
* Informação Importante.

### <a>Período de Restituição</a>
#### <a>O que é?</a>
A restituição do Imposto de Renda é a devolução do valor pago a mais para a Receita Federal durante o ano anterior. Por isso, se na entrega da declaração for indicada uma diferença positiva, significa que o contribuinte — isto é, o usuário — deve pagar o restante do tributo. Nesta etapa o usuário precisará informar um período para a restituição.

### <a>Fazer a declaração</a>
#### <a>O que é e devo declarar?</a>
O Imposto de Renda é um tributo obrigatório para muitos dos contribuintes. Não declarar, ou seja, sonegar o imposto, pode trazer consequências como cair na malha fina (declarar menos do que de fato o contribuinte recebeu e pagou), pagar multas elevadas e entrar na dívida ativa do governo.
<br>
Essa é uma função que consta como nova, através dessa opção o usuário é redirecionado para o site da Receita para que possa informar os dados e declarar o imposto de renda.

### <a>Perguntas e Resposta</a>
#### <a>O que é?</a>
Essa é uma etapa que redireciona para um PDF, que proporciona ao usuário acesso a situações de dúvidas comuns.
<br>
Essa tela também permite acesso ao FAQ para retirar dúvidas e auxílio com o aplicativo. [1]

## <a>Problemas Encontrados</a>
O aplicativo tem baixa segurança, visto que a forma de login exige apenas o CNPJ do usuário e, portanto, qualquer um consegue acessar a conta de outros usuários sem passar por qualquer tipo de validação ou impedimento. Seria importante melhorar ou criar outras formas de autenticação de usuário.

Outro problema é o excesso de simplicidade do aplicativo, que faz com que seja necessário ir a diversas páginas externas, na internet, para realizar várias de suas atividades propostas. O design é minimalista, porém não agradável, e faltam legendas para entender certos tópicos que podem ser estranhos para um novo usuário.

## <a>Bibliografia</a>

[1] MEI, Ministério da Economia, acesso em: https://www.gov.br/pt-br/apps/mei
