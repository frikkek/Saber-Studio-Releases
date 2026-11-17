# Saber Studio

Editor de vídeo simples para Windows 10/11: legenda automática (Whisper), cortes na linha do tempo
com os atalhos do FL Studio, velocidade, volume, resolução (até 1080p, vertical ou horizontal) e
exportação pela placa de vídeo (NVIDIA, AMD ou Intel).

## Download

Baixe a versão mais recente em **[Releases](../../releases/latest)**:

| Arquivo | Para quem |
|---|---|
| `SaberStudio-<versão>-Setup.exe` | **Instalador.** Cria atalhos no Menu Iniciar e na Área de Trabalho e um desinstalador. Para atualizar, instale por cima. |
| `SaberStudio-<versão>-Portatil.zip` | **Portátil.** Descompacte e abra `Saber Studio\Saber Studio.exe`. |
| `SHA256SUMS.txt` | Somas para conferir se os arquivos chegaram íntegros. |

O app avisa sozinho quando há versão nova. No portátil, para atualizar, troque a pasta antiga pela nova.
Os atalhos e as preferências ficam salvos no Windows e continuam valendo.

Na primeira legenda automática, o modelo do Whisper é baixado (o "medium" tem uns 1,5 GB).

O Windows SmartScreen pode avisar porque o executável não tem assinatura digital: clique em
**Mais informações → Executar assim mesmo**.

> O Saber Studio se chamava **Legendador** até a versão 0.2.1. As preferências e os atalhos da versão antiga são aproveitados.

Se o app fechar sozinho, mande o arquivo de log do dia: **Ajuda → Abrir pasta de logs** (fica em `%APPDATA%\Saber Studio\logs`).
