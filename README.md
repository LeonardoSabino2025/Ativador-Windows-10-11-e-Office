# Ativador-Windows-10-11-e-Office
O seu ficheiro `README.md` esteticamente formatado e estruturado profissionalmente está pronto para ser utilizado no seu repositório.

[file-tag: code-generated-file-0-1783554882689556052]

Abaixo deixo uma pré-visualização do conteúdo que foi gerado no ficheiro para que possa ler diretamente por aqui:

***
# Download Windows 11 LTSC (leve)
https://www.microsoft.com/en-us/evalcenter/download-windows-11-iot-enterprise-ltsc-eval

# 🚀 Microsoft Activation Scripts (MAS) — Guia de Uso e Explicação

Este repositório contém uma explicação detalhada e um guia visual sobre o funcionamento do comando utilizado para ativar o Windows 10, Windows 11 e Microsoft Office utilizando o projeto open-source **MAS (Microsoft Activation Scripts)**.

---

## ⚡ O Comando Oficial

Para iniciar a ferramenta interativa de ativação, abra o **PowerShell como Administrador** no Windows e execute o comando abaixo:

```powershell
irm https://get.activated.win | iex


---

irm https://get.activated.win | iex


---

# 🚀 GUIA COMPLETO: Windows 11 22H2 — Download e Instalação Oficial (ISO via UUP Dump)
**Versão Oficial - Sem Evaluation**

## O QUE VOCÊ VAI PRECISAR

| Item | Requisito |
|------|-----------|
| 💾 Espaço em disco | 30 GB livres no SSD |
| 📀 Pen Drive | 8 GB ou maior |
| 🌐 Internet | Estável (vai baixar ~5 GB) |
| ⏱️ Tempo | 20-40 minutos |

## PASSO 1: UUP DUMP - BAIXAR A ISO OFICIAL

### 1.1 Acesse o site
https://uupdump.net

### 1.2 Selecione a versão
- Clique em "Windows 11"
- Escolha: "Windows 11, version 22H2 (22621.6060) amd64"

### 1.3 Escolha o idioma
- Selecione: "Português (Brasil)"

### 1.4 Selecione a edição
✅ MARQUE APENAS: Windows 11 Pro

❌ NÃO MARQUE:
- Windows 11 Enterprise
- Windows 11 Education
- Qualquer coisa com "Eval"

### 1.5 Configure o download
Na tela de opções finais, escolha:
- **Download method**: "Download and convert to ISO (using aria2)"
- Marque a opção **"Include updates"** para que o UUP Dump já baixe a build mais recente com as atualizações incorporadas
- Clique em **"Create download package"** para gerar um arquivo `.zip`

## PASSO 2: GERAR A ISO A PARTIR DO PACOTE

### 2.1 Extraia o `.zip` baixado
Extraia todo o conteúdo em uma pasta de fácil acesso (ex: `C:\UUP`)

### 2.2 Execute o script como Administrador
- Clique com o botão direito em `uup_download_windows.cmd`
- Selecione **"Executar como administrador"**
- Aguarde o download dos arquivos oficiais da Microsoft e a conversão automática em ISO (o processo é feito localmente pela ferramenta `aria2` + `Windows ADK`, ambos baixados automaticamente pelo script)

### 2.3 Localize a ISO pronta
Ao final, a ISO `.iso` estará na mesma pasta, pronta para uso

## PASSO 3: CRIAR O PEN DRIVE BOOTÁVEL

### 3.1 Baixe o Rufus
https://rufus.ie

### 3.2 Configure o Rufus
- Conecte o pen drive (8 GB ou maior)
- Selecione o dispositivo correto
- Em **"Seleção de arquivo de boot"**, escolha a ISO gerada no Passo 2
- Esquema de partição: **GPT** (para UEFI) ou **MBR** (para BIOS legado)
- Sistema de destino: **UEFI** (recomendado para hardware mais recente)
- Clique em **"Iniciar"** e aguarde a gravação

## PASSO 4: INSTALAR O WINDOWS 11 PRO

### 4.1 Boot pelo pen drive
- Reinicie o PC e acesse o menu de boot (geralmente `F8`, `F11` ou `Del`, dependendo da placa-mãe)
- Selecione o pen drive como dispositivo de boot

### 4.2 Siga o instalador
- Escolha idioma, formato de hora/moeda e teclado
- Clique em **"Instalar agora"**
- Na tela de chave de produto, insira sua chave de licença **Windows 11 Pro** genuína (ou selecione **"Não tenho uma chave de produto"** para ativar depois com uma licença válida)
- Selecione a edição **Windows 11 Pro**
- Escolha **"Personalizada: Instalar somente o Windows"**
- Selecione/formate a partição do SSD e prossiga com a instalação

### 4.3 Finalize a configuração
- Aguarde a instalação e as reinicializações automáticas
- Complete a configuração inicial (conta Microsoft ou local, privacidade, etc.)

> ℹ️ Este guia cobre apenas o download oficial e a instalação limpa do Windows 11 Pro a partir de arquivos originais da Microsoft (via UUP Dump). Para a ativação, utilize uma licença genuína adquirida oficialmente.
---
# 🚀 GUIA COMPLETO: Windows 11 22H2 — Download e Instalação Oficial (ISO via UUP Dump)
**Versão Oficial - Sem Evaluation**

## O QUE VOCÊ VAI PRECISAR

| Item | Requisito |
|------|-----------|
| 💾 Espaço em disco | 30 GB livres no SSD |
| 📀 Pen Drive | 8 GB ou maior |
| 🌐 Internet | Estável (vai baixar ~5 GB) |
| ⏱️ Tempo | 20-40 minutos |

## PASSO 1: UUP DUMP - BAIXAR A ISO OFICIAL

### 1.1 Acesse o site
https://uupdump.net

### 1.2 Selecione a versão
- Clique em "Windows 11"
- Escolha: "Windows 11, version 22H2 (22621.6060) amd64"

### 1.3 Escolha o idioma
- Selecione: "Português (Brasil)"

### 1.4 Selecione a edição
✅ MARQUE APENAS: Windows 11 Pro

❌ NÃO MARQUE:
- Windows 11 Enterprise
- Windows 11 Education
- Qualquer coisa com "Eval"

### 1.5 Configure o download
Na tela de opções finais, escolha:
- **Download method**: "Download and convert to ISO (using aria2)"
- Marque a opção **"Include updates"** para que o UUP Dump já baixe a build mais recente com as atualizações incorporadas
- Clique em **"Create download package"** para gerar um arquivo `.zip`

## PASSO 2: GERAR A ISO A PARTIR DO PACOTE

### 2.1 Extraia o `.zip` baixado
Extraia todo o conteúdo em uma pasta de fácil acesso (ex: `C:\UUP`)

### 2.2 Execute o script como Administrador
- Clique com o botão direito em `uup_download_windows.cmd`
- Selecione **"Executar como administrador"**
- Aguarde o download dos arquivos oficiais da Microsoft e a conversão automática em ISO (o processo é feito localmente pela ferramenta `aria2` + `Windows ADK`, ambos baixados automaticamente pelo script)

### 2.3 Localize a ISO pronta
Ao final, a ISO `.iso` estará na mesma pasta, pronta para uso

## PASSO 3: CRIAR O PEN DRIVE BOOTÁVEL

### 3.1 Baixe o Rufus
https://rufus.ie

### 3.2 Configure o Rufus
- Conecte o pen drive (8 GB ou maior)
- Selecione o dispositivo correto
- Em **"Seleção de arquivo de boot"**, escolha a ISO gerada no Passo 2
- Esquema de partição: **GPT** (para UEFI) ou **MBR** (para BIOS legado)
- Sistema de destino: **UEFI** (recomendado para hardware mais recente)
- Clique em **"Iniciar"** e aguarde a gravação

## PASSO 4: INSTALAR O WINDOWS 11 PRO

### 4.1 Boot pelo pen drive
- Reinicie o PC e acesse o menu de boot (geralmente `F8`, `F11` ou `Del`, dependendo da placa-mãe)
- Selecione o pen drive como dispositivo de boot

### 4.2 Siga o instalador
- Escolha idioma, formato de hora/moeda e teclado
- Clique em **"Instalar agora"**
- Na tela de chave de produto, insira sua chave de licença **Windows 11 Pro** genuína (ou selecione **"Não tenho uma chave de produto"** para ativar depois com uma licença válida)
- Selecione a edição **Windows 11 Pro**
- Escolha **"Personalizada: Instalar somente o Windows"**
- Selecione/formate a partição do SSD e prossiga com a instalação

### 4.3 Finalize a configuração
- Aguarde a instalação e as reinicializações automáticas
- Complete a configuração inicial (conta Microsoft ou local, privacidade, etc.)

> ℹ️ Este guia cobre apenas o download oficial e a instalação limpa do Windows 11 Pro a partir de arquivos originais da Microsoft (via UUP Dump). Para a ativação, utilize uma licença genuína adquirida oficialmente.
