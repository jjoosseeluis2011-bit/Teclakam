# KeyCam Pro Remote

Gravador de vídeo, MIDI e acordes para tecladistas, instalável pelo Chrome (PWA). Código próprio, sem relação com o app KeyCam original.

## Publicar no GitHub Pages
1. Crie um repositório e envie estes arquivos na raiz.
2. Em Settings > Pages, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o endereço `https://SEU-USUARIO.github.io/NOME-DO-REPO/` no Chrome do celular (Android) e toque em **Instalar app**.

## Como usar
- **Modo Estúdio:** celular perto do teclado (MIDI por cabo USB-OTG). Toque em Mover para posicionar o teclado e a cifra, e em Config. para ajustar.
- **Modo Câmera Remota:** no celular do tripé. Toque em Gerar código, cole no Estúdio (Config. > Câmera remota), copie a resposta e cole de volta em Conectar. Funciona na mesma rede Wi-Fi ou hotspot, sem internet.
- Os botões 0,5x, 1x, 2x e 3x controlam a câmera ativa, inclusive a remota.
- A gravação sai em .mp4 (ou .webm, se o Chrome não suportar) na pasta Downloads.

## Limitações atuais
- Foco, exposição, balanço de branco e lanterna dependem do que o celular libera ao navegador; se não aceitar, o app avisa.
- O QR Code não entrou: o código de pareamento é longo demais para um QR legível. Copie e cole pelo WhatsApp ou pelo teclado.
- Ainda faltam: ISO e obturador manuais, galeria com corte, re-renderização do vídeo, presets, playback de backing track e modo tela escura na câmera remota.
- O motor de acordes cobre as famílias mais usadas (tríades, 6ªs, 7ªs, extensões, alterados, slash chords, sem quinta), mas não é exaustivo.
- Ao parar a gravação, o Chrome pode pedir permissão para baixar o .mid junto com o vídeo.
