# Start Studio

Editor visual de páginas iniciais desenvolvido por **Juliano Oliveira / DATACG**, com Codex.

Organize seus links em coleções, personalize símbolos, emojis, favicons e aparência, e use os HTMLs salvos offline. Interface em português do Brasil, inglês, dinamarquês e italiano. A instalação começa vazia, sem links ou dados pessoais.

## Download para Windows

[Baixar a versão mais recente](https://github.com/datacg/startstudio/releases/latest)

Abra a release e escolha o instalador `Start-Studio-Setup-<versão>-x64.exe`. O aplicativo inclui os componentes necessários; não exige instalar Node.js ou Git. O assistente permite escolher as pastas do programa e das páginas.

**O instalador desta fase não possui assinatura digital. O Windows pode apresentar avisos de segurança.** Cada release informa a versão e inclui um arquivo `.sha256` para conferir a integridade do download.

No PowerShell, compare o resultado deste comando com o checksum da release, substituindo o nome pelo arquivo baixado:

```powershell
Get-FileHash '.\Start-Studio-Setup-<versão>-x64.exe' -Algorithm SHA256
```

### Se o Microsoft Edge mostrar um aviso no download

O Edge pode informar que o instalador **“isn't commonly downloaded”** (não é baixado com frequência). Se você conferiu que o download vem deste repositório e decidiu continuar, siga os passos abaixo. Os nomes dos botões estão em inglês; podem variar conforme o idioma e a versão do navegador.

1. Abra o painel **Downloads** pelo ícone de download do Edge ou pelo atalho **Ctrl+J**.
2. Passe o mouse sobre o aviso ao lado de `Start-Studio-Setup-<versão>-x64.exe`. Clique nos **três pontos (…)** do próprio arquivo e escolha **Keep**.
3. Na janela de confirmação, clique na **seta para baixo (▼) ao lado do botão Delete**. No menu que abrir, escolha **Keep anyway**. Clicar diretamente em **Delete** exclui o download.
4. Aguarde o download terminar. Depois, abra o instalador na pasta Downloads e siga o assistente de instalação.

Em algumas versões do Edge, é necessário clicar em **Show more** antes de aparecer **Keep anyway**. A [documentação da Microsoft](https://learn.microsoft.com/en-us/troubleshoot/microsoft-edge/development/download-failures#check-security-and-smartscreen-settings) descreve esse fluxo. Estas instruções se referem ao aviso de download pouco conhecido; não exigem desativar o SmartScreen ou o antivírus.

## Seus arquivos

As alterações feitas no aplicativo são salvas na pasta de páginas escolhida. Os HTMLs, imagens incorporadas e backups ficam separados da instalação. Use `start.html` como página inicial do navegador. O aplicativo permite mover a pasta de dados, exportar o conjunto e restaurar backups como novas páginas.

Este repositório contém somente informações e arquivos de distribuição. Nenhuma biblioteca pessoal de links é incluída no instalador.

Software gratuito. [DATACG](https://datacg.net/startstudio)
