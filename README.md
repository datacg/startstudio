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

## Seus arquivos

As alterações feitas no aplicativo são salvas na pasta de páginas escolhida. Os HTMLs, imagens incorporadas e backups ficam separados da instalação. Use `start.html` como página inicial do navegador. O aplicativo permite mover a pasta de dados, exportar o conjunto e restaurar backups como novas páginas.

Este repositório contém somente informações e arquivos de distribuição. Nenhuma biblioteca pessoal de links é incluída no instalador.

Software gratuito. [DATACG](https://datacg.net/startstudio)
