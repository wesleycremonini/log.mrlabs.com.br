```diff
- Obs: O código fonte deste projeto é privado, este repositório é apenas um overview do projeto.
+ Em: log.mrlabs.com.br
```
 **Principais habilidades utilizadas**: php, Laravel, Docker (e compose) e Nginx. Hospedado em servidor linux na Digital Ocean.

<br/>
<br/>

# Overview sobre o sistema
<h3>_Autenticação<h3/>

##### Login
<img src="/images/login.png" width="700">

##### Registro
<img src="/images/registro.png" width="700">
<br/>

<h3>_Permissões<h3/>

##### Gerenciamento de permissões
###### Uma vez registrado o usuário pode ser encontrado nessa tela e poderá receber as devidas permissões.
<img src="/images/permissoes.png" width="700">
<br/>

<h3>_Upload de arquivos<h3/>

###### Arquivos CSV gerados no Notazz devem ser importados para o sistema, dessa forma as notas são geradas após consultar automaticamente a API da PerfectPay e Shopify. Além disso a API dos Correios é consultada para adicionar os rastros de cada entrega de produto.
<img src="/images/importar.png" width="700">
<br/>


<h3>_Notas Fiscais<h3/>

##### Todas as notas
###### Após o upload dos arquivos as notas fiscais ficam disponíveis dentro do sistema.
  
<img src="/images/notas.png" width="700">
  
##### Dados completos
###### Acessando os dados completos de cada nota e com possibilidade de adicionar observações.
  
<img src="/images/nota1.png" width="700"><img src="/images/nota2.png" width="700">
  
##### Observações
###### Acessando as observações diretamente na listagem de notas.
<img src="/images/observacoes.png" width="700">

<br/>

<h3>_Rastreamento<h3/>

##### Lista com o último rastro de cada pedido
###### Os rastreamentos são atualizados automaticamente pelo sistema através de consulta na API dos Correios ou manulamente se necessário.
<img src="/images/rastreios.png" width="700">

##### Acessando um rastreamento com os dados completos e possibilidade de alterar o código de rastreio caso necessário.
###### Todos os rastros do pedido, além de links externos para consulta em outros sites caso necessário.
<img src="/images/rastreio.png" width="700">

###### Alterando código de rastreio
<img src="/images/trocar_rastreio.png" width="700">


<br/>

<h3>_PLP's<h3/>

###### As PLP's são atualizadas automaticamente pelo sistema através de consulta da API do Notazz. Com possibilidade de impressão da PLP e das etiquetas.
<img src="/images/plps.png" width="700">
<br/>

<h3>_Processamentos<h3/>

###### Acompanhamento dos processamentos que ocorrem dentro do sistema
<img src="/images/processamento.png" width="700">
