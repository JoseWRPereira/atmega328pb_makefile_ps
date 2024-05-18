# Makefile Powershell

## Instalando Makefile no Windows Powershell

1. [Installing Chocolatey](https://chocolatey.org/install)

1.1 *Administrative shell*
1.2 `Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))`
1.3 `choco install make`

## Arquivo: makefile

Editar o nome do projeto na linha 1:
> `PROJECT=nome_do_projeto`


Executar o makefile:
> `make`
