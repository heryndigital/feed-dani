# Feed da Dani · Estilo com Alma

Planejamento de conteúdo da Dani Merighe: posts, calendário, prévia do feed e destaques.

- Quem abre o link sem login: só visualiza.
- Com login (botão "Entrar para editar"): edita tudo, e as mudanças aparecem ao vivo para quem estiver com o app aberto.

## Como funciona

- `index.html`: o app inteiro.
- `media/`: artes e vídeo dos primeiros posts.
- `seed.json`: dados iniciais (posts, bio e destaques). No primeiro login, o app oferece o botão "Importar dados iniciais".
- `firestore.rules`: regras do banco (leitura aberta, edição só para o e-mail autorizado).

Dados ficam no Firebase (Firestore, plano gratuito Spark). Imagens enviadas pelo app são comprimidas e guardadas no próprio Firestore. Vídeos ficam no Google Drive: cole o link no campo "Original no Google Drive" do post.
