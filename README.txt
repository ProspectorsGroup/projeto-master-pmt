PROJETO MASTER PMT — FASE 1 / MÓDULO 2 — ATUALIZAÇÃO V4 — LAYOUT APROVADO

O QUE FOI CONSOLIDADO NESTA ATUALIZAÇÃO
1. Linguagem visual alinhada ao site: azul-marinho, branco e dourado, estrutura limpa e institucional.
2. Cabeçalho: PROSPECTORS GROUP à esquerda e Corretores Associados à direita.
3. CANTOS 100% RETOS em todo o anúncio. Nenhum componente usa cantos arredondados.
4. Miolo reorganizado para os campos definidos: Nome do Projeto, Construtora, Endereço, Entrega, Metragens, Tipologias e Vagas.
5. Destaques do Projeto: texto livre + oito campos editáveis, sem ícones de piscina/academia/salão etc.
6. Apenas um botão de mapa e um botão de vídeo.
7. Área do corretor sem repetição da marca PROSPECTORS abaixo do nome.
8. Rodapé final com WhatsApp e e-mail do corretor.
9. Todos os campos de texto do anúncio são editáveis na Ficha-Mestre e também diretamente no Anúncio Premium.
10. Imagem principal, duas fotos complementares e foto do corretor podem ser trocadas.

QR CODE DINÂMICO
- O QR Code NÃO é mais um arquivo fixo.
- O sistema monta o link do WhatsApp com o número e a mensagem cadastrados na Ficha-Mestre.
- Ao mudar o telefone ou a mensagem, o botão WhatsApp e o QR Code passam automaticamente a usar os novos dados.
- A imagem do QR é gerada online pelo serviço QuickChart quando a página é aberta; portanto, a geração do QR exige conexão com a internet.

MENSAGEM PADRÃO
“Olá, vim pelo QR CODE e gostaria de mais informações. Aguardo seu retorno!”

COMO USAR
1. Abra ficha-mestre.html.
2. Preencha os dados e troque as imagens desejadas.
3. Informe vídeo e Google Maps.
4. Informe WhatsApp, e-mail e mensagem padrão.
5. Clique “SALVAR E ABRIR ANÚNCIO PREMIUM”.
6. No anúncio, confira o botão WhatsApp e escaneie o QR Code.
7. Use “IMPRIMIR / PDF” quando desejar gerar uma versão para impressão/PDF.

OBSERVAÇÃO SOBRE MÍDIAS
O Anúncio Premium é responsivo e serve como peça-mestre para Web, Google Sites e visualização em celular/desktop. Instagram, Facebook e Google Ads exigem proporções específicas; as adaptações desses formatos devem preservar a mesma identidade visual, mas serão saídas derivadas do Master, não uma simples redução do anúncio completo.

ARQUIVO DE REFERÊNCIA
assets/layout-referencia-aprovado.png = imagem visual aprovada que orientou esta atualização.


ATUALIZAÇÃO V4.1 — PREÇO / MAPA
- Mantido o layout V4 aprovado.
- Botão VER NO MAPA deslocado para a esquerda, imediatamente abaixo da foto principal.
- No antigo espaço do mapa foi inserido PREÇO A PARTIR DE, editável pela Ficha-Mestre e diretamente no anúncio.
- Demais elementos preservados.

ATUALIZAÇÃO V4.1 FINAL APROVADA — 11/09/2026
- Layout final do Anúncio Premium congelado conforme aprovação do usuário.
- Cantos 100% retos.
- Caixa de descrição do produto alinhada verticalmente ao início da caixa do corretor.
- Duas fotos acessórias no rodapé esquerdo.
- Vídeo e Localização em caixas brancas na lateral direita.
- Dados do corretor com maior legibilidade.
- WhatsApp, link e QR Code sincronizados automaticamente: ao alterar telefone ou mensagem na Ficha-Mestre, o QR é regenerado.
- Arquivo de referência visual: assets/layout-final-v4-1-aprovado.png.

V4.1.1 — AJUSTE TIPOGRÁFICO DO CABEÇALHO
- PROSPECTORS GROUP: Arial/Helvetica, peso 700 e espaçamento 0,6px, seguindo o padrão da primeira página do Módulo 1.
- Nenhum outro elemento de layout foi alterado.

V4.2 — INTEGRAÇÃO MULTICANAL / PUBLICAÇÃO
- Base: V4.1.2 aprovada; layout visual preservado.
- Adicionado Modo Publicação via index.html?public=1, sem barra de edição.
- Adicionada exportação/importação da Ficha-Mestre em JSON para transferir dados entre navegadores/dispositivos.
- Validação dos links de vídeo e Google Maps antes da abertura.
- Mantida sincronização automática WhatsApp -> link -> QR Code.
- Preparação técnica para hospedagem HTTPS e incorporação no Google Sites.

V4.2.2: botão do anúncio abre diretamente o aplicativo WhatsApp via protocolo whatsapp://; QR Code permanece em wa.me.


V4.2.3 - Ajuste funcional do botão WhatsApp:
- Em PC, o botão abre https://web.whatsapp.com/send diretamente para o telefone cadastrado.
- Em celular, usa wa.me para abrir o WhatsApp.
- O QR Code continua usando wa.me.
- A autenticação do WhatsApp Web depende da sessão já conectada no navegador.

V4.2.4 - Correção do botão WhatsApp:
- O botão passa a usar exclusivamente o link oficial https://wa.me/NUMERO?text=MENSAGEM em PC e celular.
- A conversa deve abrir com o destinatário cadastrado e a mensagem preenchida; o envio final permanece sob ação do usuário no WhatsApp.
- QR Code e layout visual permanecem inalterados.


V4.2.6 - DIAGNÓSTICO WHATSAPP
- O botão mostra antes do redirecionamento o telefone normalizado, a mensagem e o link oficial wa.me gerado.
- Ao confirmar, abre exatamente esse link oficial.
- Objetivo: separar definitivamente erro de montagem do link de redirecionamento/autenticação do WhatsApp.


V4.2.8 — WhatsApp Web: botão convertido para link HTML direto, sem JavaScript de redirecionamento, usando web.whatsapp.com/send com phone, text, type=phone_number e app_absent=0. O QR Code permanece em wa.me.


V4.2.8 - Correção WhatsApp: botão passa a usar diretamente o link oficial https://wa.me/<numero>?text=<mensagem>, sem web.whatsapp.com/send intermediário.
