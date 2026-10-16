# Mesa de Análise

Analisador de vídeo quadro a quadro que roda direto no navegador. Feito para destrinchar trailers, gameplays e clipes de live.

Os vídeos **não são enviados para nenhum servidor**: tudo acontece no seu computador.

## Recursos

- Lista de clipes: importe vários vídeos ou uma pasta inteira, ou arraste para a tela
- Avanço quadro a quadro, FPS ajustável e velocidade de 0,1× a 2×
- Zoom com a roda do mouse e arrastar para mover
- Desenho por cima do vídeo: caneta, seta, retângulo e círculo, em 4 cores
- Régua com calibração (meça algo de tamanho conhecido e as medidas saem em metros)
- Marcadores com notas, visíveis na timeline
- Volume com barra deslizante (a roda do mouse sobre a barra também ajusta) e botão de mudo
- Tela cheia imersiva: os painéis somem e voltam quando você mexe o mouse; encoste o mouse na borda esquerda para abrir a lista de clipes
- Modo Apresentar, que esconde os painéis (bom para live)
- Exportar marcadores em texto ou a análise completa em JSON, e importar de volta

As marcações ficam salvas no navegador, ligadas ao nome do arquivo de vídeo.

## Atalhos

| Tecla | Ação |
|---|---|
| Espaço | Reproduzir / pausar |
| ← → | 1 quadro (Shift: 10 quadros) |
| ↑ ↓ | Clipe anterior / próximo |
| M | Marcar momento |
| [ ] | Marcador anterior / próximo |
| V D A B O R | Mover, caneta, seta, retângulo, círculo, régua |
| 1–4 | Cor |
| Z ou Ctrl+Z | Desfazer |
| Delete | Apagar desenhos do quadro |
| Roda do mouse | Zoom |
| Alt + arrastar | Mover a imagem |
| 0 | Ajustar à tela |
| P | Modo apresentar |
| K | Mudo |
| F | Tela cheia |

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo, `mesa-de-analise`).
2. Envie os arquivos desta pasta (`index.html`, `README.md` e `.nojekyll`) para a raiz do repositório.
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`. Salve.
5. Em um ou dois minutos o site fica disponível em `https://SEU-USUARIO.github.io/mesa-de-analise/`.

## Usar sem internet

Basta abrir o `index.html` com dois cliques. Sem internet ele funciona normalmente, só usa as fontes padrão do sistema.

## Formatos de vídeo

Abre o que o seu navegador suportar: MP4 (H.264), WebM e, na maioria dos casos, MOV. Arquivos MKV dependem do codec. Se um vídeo não abrir, converta para MP4.
