# Makefile Powershell

## 1. Instalando Makefile no Windows Powershell


1.1 Executar o Powershell no modo: *Administrative shell*

1.2 Instalando o [Chocolatey](https://chocolatey.org/install)
``` powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

1.3 Instalando o makefile
```
choco install make
```

## 2. Arquivo: makefile

2.1 Editar o nome do projeto na linha 1 do arquivo makefile
``` makefile
PROJECT=nome_do_projeto
```

2.2 Executar o makefile compilando o projeto:
``` powershell
make
```

2.3 Abrir arquivos .c e .h para edição no Notepad++:
``` powershell
make notepad
```

2.4 Abrir gravador AVRDUDESS:
``` powershell
make flash
```


