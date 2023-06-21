![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
# Terraform
Repositório dedicado ao armazenamento de um tutorial detalhado e passo a passo para a instalação do Terraform.

1. Fazer o download do arquivo (Terraform.exe")\
2. Direcionar/criar variavel de ambiente **Meu computador > propriedades > Configurações avançadas do sistema >
Variáveis de ambiente > Variáveis do sistema > Path > Novo > copiar o path de onde está o arquivo terraform.exe **\
3. Fazer o download e instalação do AWS Cli\
4. Execute no power shell > msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi (pode atualizar)
5. Verifique se instalou > C:\> aws --version
   ```Saída exxemplo: aws-cli/2.10.0 Python/3.11.2 Windows/10 exe/AMD64 prompt/off```
6. Crie o usuario que será utilizado para conectar o terraform, exemplo "terraform-user"
7. Abra o usuario criado, vá em Security credentials > Crie o Access Key
8. Salve as credenciais de acesso, access key e private acess key
9. No powershell navegue até a pasta com os arquivos > digite: aws configure > passe as credenciais
10. Digite no power shell> aws s3 ls
11. Verifique se há algum erro na saída
12. Crie o arquivo main.tf onde achar > https://registry.terraform.io/providers/hashicorp/aws/latest/docs
13. Com o arquivo main.tf criado > execute o "terraform init" no power shell no diretorio correto
14. Instale a extensao HashiCorp Terraform no visual studio code
