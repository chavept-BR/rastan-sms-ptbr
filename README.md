# Rastan — Tradução PT-BR para Master System

**ChaveptBR — Pixels que falam sua língua.**

## Apresentação

Este projeto disponibiliza um patch de tradução de **Rastan**, para **Sega Master System**, para português brasileiro.

A proposta é permitir que jogadores aproveitem os textos do jogo em português, preservando a experiência original.

| Informação | Detalhe |
|---|---|
| Jogo | Rastan |
| Plataforma | Sega Master System |
| Idioma da tradução | Português brasileiro |
| Identificação do patch | `Rastan-sms-ptBR-v1` |
| Projeto | ChaveptBR |

## Compatibilidade

Aplique o patch somente à ROM original cujo **MD5** corresponda exatamente a:

```text
5b3a785de403c311db7f17eae27caae6
```

O nome do arquivo da ROM não garante compatibilidade. Confirme o hash antes de aplicar o patch. Uma ROM de outra revisão ou já modificada pode apresentar erros ou não aceitar a aplicação.

Se o arquivo estiver em ZIP ou outro formato compactado, extraia a ROM e calcule o MD5 do arquivo do jogo, não do pacote compactado.

### Como conferir o MD5

**Windows — PowerShell:**

```powershell
Get-FileHash -Algorithm MD5 -LiteralPath "C:\Jogos\Rastan.sms"
```

**Linux:**

```bash
md5sum "Rastan.sms"
```

**macOS:**

```bash
md5 "Rastan.sms"
```

Substitua o caminho ou o nome do arquivo pelo da sua ROM. Letras maiúsculas ou minúsculas no hash não alteram o resultado da comparação.

## Download

Baixe o pacote do patch na seção **Releases** deste repositório. Procure o arquivo anexado identificado como `Rastan-sms-ptBR-v1`.

Os arquivos automáticos **Source code (zip)** e **Source code (tar.gz)** não substituem o pacote do patch anexado à Release.

## Instruções de aplicação

1. Tenha uma cópia do jogo original e mantenha um backup da ROM sem alterações.
2. Confira se o MD5 da ROM corresponde ao valor indicado na seção **Compatibilidade**.
3. Baixe o pacote na seção **Releases** e extraia os arquivos, caso esteja compactado.
4. Se o pacote incluir um instalador ou instruções específicas, siga as orientações que o acompanham. Para aplicação manual, abra uma ferramenta compatível com o formato do patch fornecido.
5. Selecione a ROM original como arquivo de entrada e o patch `Rastan-sms-ptBR-v1` como arquivo de tradução. Caso a ferramenta solicite, informe um novo nome para a ROM de saída, por exemplo: `Rastan-PTBR.sms`.
6. Conclua a aplicação e abra a ROM traduzida em um emulador ou dispositivo compatível com Sega Master System.

**Não aplique o patch sobre uma ROM já traduzida.** Para reaplicar a tradução ou instalar uma atualização, utilize novamente uma cópia da ROM original compatível.

O MD5 informado neste documento é o da **ROM original**, antes da aplicação. É esperado que a ROM traduzida tenha um hash diferente.

## Problemas e sugestões

Se encontrar erros de texto, caracteres incorretos ou problemas de aplicação, entre em contato e informe:

- Identificação do patch utilizado.
- MD5 da ROM original.
- Ferramenta usada para aplicar o patch.
- Emulador ou dispositivo utilizado.
- Descrição do problema e, se possível, uma captura de tela.

Não envie ROMs ou arquivos do jogo junto ao relato.

## Créditos

- **Tradução para português brasileiro e adaptação dos textos:** ChaveptBR.
- **Jogo original, personagens e marcas:** seus respectivos titulares.

Este é um projeto de tradução de fãs, sem vínculo oficial com os titulares do jogo.

## Contato

- **E-mail:** [contato@chaveptbr.com](mailto:contato@chaveptbr.com)
- **Site:** [chaveptbr.com](https://chaveptbr.com)

---

O ChaveptBR disponibiliza apenas patches de tradução. Não distribuímos jogos completos, ROMs, ISOs ou imagens de disco. Para utilizar as traduções, é necessário possuir o jogo original. Apoie os desenvolvedores: adquira o jogo nas lojas oficiais da sua plataforma, quando disponível.
