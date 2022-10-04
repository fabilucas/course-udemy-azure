# course-udemy-azure
Engineering Project Building from scratch including designing, architecting, implementing solution and overall testing.

Project 1 - Connected Vehicles

1) Na AWS, utilizando o serviço S3, criei o bucket "iotbucket-udemy"
2) No bucket criado, criamos a estrutura de diretorio YYYY > MM > DD
3) Dentro do diretorio de dia carrego o arquivo de exemplo fornecido pelo curso

Azure DataLake Storage Account

1)  Selecionei o serviço de storage accounts.
    Ao criar a storage account, foi necessário escolher a subscription* e criar um novo resource group

2) Ao criar a storage account, selecione a opção de data lake storage gen2*

3) Em data lake storage, criei um container com o nome input, e dentro criei o diretorio "landing"


*Azure subscription: azure account
*Storage Gen2: 


Azure Data Factory


1) Selecionei o serviço Data Factories, e criei uma conta ADF


Key Vault

1) Entrei no serviço de key vault e criei uma key vault
2) Voltando na AWS, no painel de IAM, criei um usuário, dei permissao de acesso na S3, e gerei uma access key e secret key
3) Após, no resource key vault criado, gerei 2 secrets: 1 para o acces key id criado na AWS, e outro para a secret access key gerada na aws

Access Policy

1) Na azure, na key vault, fui em access policies
2) Coloquei pra criar uma access policy, usando o template: key secret & certificate management
3) Selecionei a minha conta criada como principal e criei
4) Agora a key vault pode ser acessada pelo meu usuario e pela application correspondente a minha ADF account

Criando o pipeline para movimentar o arquivo da S3 para a landing 



