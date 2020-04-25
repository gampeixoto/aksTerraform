# **Montando ambiente integrado com Azure**
 1. **Instalando o Chocolatey**
    - Siga as instruções do [Chocolatey](https://chocolatey.org/install#individual), é fácil e rápido de instalar. 
    
    - *"Chocolatey entra na categoria de gerenciador de pacotes, mais precisamente para sistemas Windows", assim como o npm.* fonte: [Medium](https://medium.com/@fabiojanio/chocolatey-um-poderoso-gerenciador-de-pacotes-para-windows-a87be4372257)
 
 2. **Instalando o Azure CLI** 
    - Com o chocolatey instalado, é so rodar o comando `choco install azure-cli` para instar o CLI.
 
 3. **Instalando o [Terraforms](https://www.terraform.io/)**
    -   Usando Chocolatey, vamos rodar o seguinte comando para instalar o terraforms `choco install terraform`.

# **Usando**

Abrar o powershell no mesmo diretorio onde contra-se o template que desea usar.

Após isso, vamos conectar o terminal à sua conta na Azure, rodando o comando `az login`

Agora vamos execultar o comando `terraform plan` para execultar o teste do nosso script e verificar o que vai ser aplicado no ambiente.

Dando tudo certo, vamos execultar o comando `terraform apply` onde será aplicado direto no azure.

Obs.: **Sempre ulitize o powershell**