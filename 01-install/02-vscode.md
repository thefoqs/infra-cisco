#Autor: Robson Vaamonde<br>
#Procedimentos em TI: http://procedimentosemti.com.br<br>
#Bora para Prática: http://boraparapratica.com.br<br>
#Robson Vaamonde: http://vaamonde.com.br<br>
#Facebook Procedimentos em TI: https://www.facebook.com/ProcedimentosEmTi<br>
#Facebook Bora para Prática: https://www.facebook.com/BoraParaPratica<br>
#Instagram Procedimentos em TI: https://www.instagram.com/procedimentoem<br>
#YouTUBE Bora Para Prática: https://www.youtube.com/boraparapratica<br>
#Data de criação: 16/09/2024<br>
#Data de atualização: 16/09/2024<br>
#Versão: 0.01<br>
#Testado e homologado no Linux Mint 22 Wilma x64<br>
#Testado e homologado o Cisco Packet Tracer 8.2.x x64<br>
#Testado e homologado o Microsoft Visual Studio Code VSCode no Linux Mint 22 Wilma<br>

Site Oficial do Visual Studio Code: https://code.visualstudio.com/<br>
Site Oficial do Visual Studio Code Web: https://vscode.dev/<br>
Link do Marketplace: https://marketplace.visualstudio.com/VSCode

O QUE É E PARA QUE SERVER O VSCODE: O Visual Studio Code é um editor de código-fonte desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle de versionamento Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código.

#01_ Verificando as Informações do Sistema Operacional Linux Mint<br>
```bash
#atalho para acessar o Terminal
Terminal: Ctrl + Alt + T

#OBSERVAÇÃO IMPORTANTE: Linux Mint 22.x é derivado do Ubuntu Desktop 24.04.x Noble Numbat

#verificando as versões e codinome do sistema operacional
sudo cat /etc/os-release
sudo cat /etc/lsb-release

#modo gráfico para verificar as informações de sistema operacional e hardware
Menu
	Informações do Sistema
```

#02_ Atualização do Sistema Operacional Linux Mint<br>
```bash
#atualizando o sistema operacional via MintUpdate (Recomendado)
_ Atualização do sistema utilizando o MintUpdate;
_ Atualização do sistema utilizando o Apt;

#atualizando o sistema operacional via Terminal
#atalho para acessar o Terminal
Terminal: Ctrl + Alt + T

#recomendo utilizando o comando: apt - o comando: apt-get e considerado obsoleto
sudo apt update
sudo apt upgrade
sudo apt full-upgrade
sudo apt dist-upgrade
sudo apt autoremove
sudo apt autoclean
sudo apt clean
```

#03_ Instalando as Dependências do Microsoft Visual Studio Code VSCode no Linux Mint<br>
```bash
#instalando as dependências do VSCode no Linux Mint 22.x
sudo apt install vim git python3 python3-pip cloc
```

#04_ Baixando o Microsoft Visual Studio Code VSCode para o Linux Mint<br>
```bash
#link de download oficial do VSCode
Link de download: https://code.visualstudio.com/download
  Versão: .deb (Debian, Ubuntu 64 Bits)
    Salvar aquivo
```

#05_ Instalando o Microsoft Visual Studio Code VSCode utilizando o Gdebi-Gtk no Linux Mint<br>
```bash
#instalação em modo gráfico (indicado)
Arquivos
  Download
    code_1.*_amd64
      Instalar Pacote
    <Fechar>
```

#06_ Verificando o novo repositório do Microsoft Visual Studio Code VSCode no MintUpdate<br>
```bash
#verificando o novo repositório no Linux Mint
Menu
	MintUpdate
		Editar
			Fontes de Programas
				(Digite a senha do seu usuário)
					Repositórios Adicionais
						Habilitado: Microsoft / Stable - code
					Chaves de Autenticação
						Microsoft (Release signing)
			<Fechar>
	<Fechar>
```

#07_ Iniciando o Microsoft Visual Studio Code VSCode no Linux Mint<br>
```bash
#iniciando o VSCode no Linux Mint
Menu
  Busca Indexada
    vscode
      Dark Theme
      Notifications: Pacote PT-BR
      Disable: Mostrar página inicial na inicialização
```

#08_ Configurando o Microsoft Visual Studio Code VSCode como Aplicativo de Preferência no Linux Mint<br>
```bash
#configuração básica do VSCode no Linux Mint
Menu
  Busca Indexada
    Aplicativos de Preferencias
      Texto puro: Visual Studio Code
      Código fonte: Visual Studio Code
```

#09_ Instalando e Configurando as Principais Extensões Microsoft Visual Studio Code VSCode<br>
```bash
#Instalação das Extensões Básicas do VSCode
Portuguese (Brazil) Language Pack for Visual Studio Code
	(Sem necessidade de configuração)

#Configuração da Extensão Code Spell Checker
Brazilian Portuguese - Code Spell Checker (Corretor Ortográfico de Código)
Manter selecionado a extensão: Brazilian Portuguese - Code Spell Checker
	Pressionar F1
		Show Spell Checker Configuration Info
			User
				Language
					English (en_us)
					Portuguese (pt_br)
					Portuguese - Brazil (pt-br)
				File Types and Programming Languages
					shellscript, python, markdown, etc...

Code Spell Checker
	(Sem necessidade de configuração)

Cisco IOS Syntax
	(Sem necessidade de configuração)
	(Salvar o arquivo com a extensão: .ios)

Cisco IOS-XR Syntax
	(Sem necessidade de configuração)
	(Salvar o arquivo com a extensão: .xr)

Cisco Config Highlight
	(Sem necessidade de configuração)
```

#10_ Configurações básicas do Microsoft Visual Studio Code VSCode para funcionar perfeitamente no Linux Mint<br>
```bash
#Configurações Básicas de Produtividade do VSCode no Linux Mint
Gerenciar
	Configurações
		Code Spell Checker
			C Spell: Enabled Language Ids: 
				Adicionar Item: shellscript
			C Spell: Language: en,pt,pt-BR
			C Spell: Max Duplicate Problems: 500000
			C Spell: Max Number Of Problems: 500000
		Editor
			Editor: Tab Size: 4
			Editor: Detect Indentation: False (Off)
			Editor: Insert Spaces: False (On)
			Render Whitespace: All
		Files
			Files: Eol: \n (LF)
```