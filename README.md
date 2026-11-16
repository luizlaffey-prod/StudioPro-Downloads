# StudioPro — Downloads

Instaladores e atualizações da Luiz Laffey Productions. Este repositório contém apenas arquivos de distribuição, assinaturas públicas, checksums e catálogos; o código-fonte permanece privado.

## Downloads

Use a [página de versões](https://github.com/luizlaffey-prod/StudioPro-Downloads/releases) e escolha o pacote da sua plataforma.

- **Windows x64:** instalador `x64-setup.exe`. O arquivo `x64-setup.nsis.zip` é destinado ao atualizador integrado.
- **Mac Apple Silicon:** arquivo `aarch64.app.zip`. O arquivo `aarch64.app.tar.gz` é destinado ao atualizador integrado.

Cada versão inclui `LEIA-ME.txt`, `ROLLBACK.txt` e `SHA256SUMS.txt`. As assinaturas `.sig` verificam os pacotes pelo atualizador StudioPro; são diferentes da certificação de aplicativos pelo sistema operacional.

## Atualizações e compatibilidade

Os catálogos em `feeds/` servem ao atualizador integrado. Durante a transição, os canais existentes do Google Drive são preservados. Configurações, vozes, fotos, presets e rascunhos ficam nos diretórios de dados dos aplicativos.

Uma publicação não comprova instalação na sua estação. Leia as notas da versão e faça a validação adequada antes de adotá-la em produção. O rollback da versão instalada é manual e deve preservar seus dados.
