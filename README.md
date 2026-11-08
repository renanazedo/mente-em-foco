# 🎬 Mente em Foco - Automação de Conteúdo

Este repositório serve como a página oficial e repositório de verificação de domínio para o aplicativo **Mente em Foco**. 

O **Mente em Foco** é uma ferramenta local de automação projetada para criadores de conteúdo de desenvolvimento pessoal. Ele automatiza o fluxo de criação de vídeos curtos (Shorts/Reels/TikTok) e os envia diretamente para a caixa de entrada (rascunhos) do criador no TikTok.

## 🚀 O que o robô faz?

O script Python roda localmente no computador do usuário e executa o seguinte fluxo:
1. **Geração de Roteiro:** Utiliza a API do Google Gemini para criar um roteiro focado em temas de desenvolvimento pessoal, baseando-se em referências literárias renomadas.
2. **Locução Neural:** Converte o texto em áudio MP3 gratuito e de alta qualidade usando o `edge-tts`.
3. **Busca de Mídia:** Baixa vídeos de fundo gratuitos e sem direitos autorais do Coverr.
4. **Montagem e Legendas:** Utiliza o `MoviePy` e o `pycaps` para juntar o áudio e o vídeo, gerando uma legenda dinâmica e profissional.
5. **Envio para o TikTok:** Usa a API oficial do TikTok (Content Posting API) para enviar o vídeo finalizado para a caixa de entrada (Rascunhos) da conta do usuário.

## 🛡️ Privacidade e Segurança

- **Processamento 100% Local:** Nenhum vídeo ou dado pessoal é enviado para servidores externos (exceto as chamadas para as APIs necessárias).
- **Sem Coleta de Dados:** O aplicativo não coleta, armazena ou compartilha dados de usuários do TikTok.
- **Controle Editorial:** O aplicativo **não publica vídeos automaticamente**. Ele apenas envia o vídeo para o rascunho, garantindo que o criador revise e publique o conteúdo manualmente.
- **Tokens de Acesso:** Os tokens OAuth do TikTok são armazenados apenas na máquina local do usuário e nunca são expostos publicamente.

## 🌐 Links Oficiais

- [Política de Privacidade](https://renanazedo.github.io/mente-em-foco/politica_privacidade.html)
- [Termos de Serviço](https://renanazedo.github.io/mente-em-foco/termos_servico.html)

## 🛠️ Tecnologias Utilizadas

- Python 3.12
- Google Gemini API (Geração de texto)
- Edge-TTS (Síntese de voz)
- MoviePy & FFmpeg (Edição de vídeo)
- PyCaps (Legendas animadas)
- Coverr API (Banco de vídeos)
- TikTok Content Posting API

---
*Desenvolvido para otimizar a produção de conteúdo sem comprometer a qualidade ou a segurança da plataforma.*
