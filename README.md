# Demo - Demonstração: Linkando um repositório remoto com local

## Descrição
Este projeto tem como objetivo demonstrar como linkar um repositório local ao GitHub, permitindo que você faça o versionamento e colabore com outros desenvolvedores. 

## Como usar

### Passo 1: Criar um repositório no GitHub
1. Acesse o GitHub e crie um novo repositório (ex: `demo-repo`).

### Passo 2: Clonar o repositório
No seu terminal, utilize o seguinte comando para clonar o repositório remoto para o seu ambiente local:
```bash
git clone https://github.com/SEU_USUÁRIO/demo-repo.git

### Passo 3: Navegue até a pasta do repositório clonado e adicione um novo arquivo:
cd demo-repo
echo "Hello World" > hello.txt

### Passo 4:  Fazer commit e enviar para o remoto
Adicione o arquivo e faça um commit:
git add hello.txt
git commit -m "Adiciona arquivo hello.txt"
git push origin main

### Conclusão
Esse projeto é uma demonstração básica de como você pode trabalhar com repositórios remotos e locais utilizando Git. Para mais informações, consulte a documentação do Git.



