# Makefile Powershell

## Instalando Makefile no Windows Powershell


* Executar o Powershell no modo: *Administrative shell*

* Instalando o [Chocolatey](https://chocolatey.org/install)
``` powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

* Instalando o makefile
```
choco install make
```

## Arquivo: makefile

Editar o nome do projeto na linha 1 do arquivo makefile
``` makefile
PROJECT=nome_do_projeto
```


Executar o makefile:
``` powershell
make
```
