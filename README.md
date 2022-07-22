```diff
- Obs: O código fonte deste projeto é privado, este repositório é apenas uma demonstração do projeto.
+ Em: log.mrlabs.com.br
```
**Principais habilidades utilizadas**: php, Laravel, Docker (e compose) e Nginx.

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
