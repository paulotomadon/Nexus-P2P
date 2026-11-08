# ⚡ NEXUS // P2P Terminal

Aplicativo web de comunicação **Peer-to-Peer (P2P)** em arquivo único (`index.html`), focado em privacidade, velocidade e zero dependência de servidores de banco de dados.

🌐 **Acesse agora:** [https://paulotomadon.github.io/Nexus-P2P/](https://paulotomadon.github.io/Nexus-P2P/)

---

## 🚀 Funcionalidades

* **🔗 Conexão Direta (WebRTC):** Mensagens, arquivos, voz e vídeo trafegam diretamente entre os navegadores dos usuários (P2P).
* **🔑 Descoberta por ID Curto (1 Clique):** Conecte-se usando um ID de 8 caracteres (`XXXX-XXXX`). O aperto de mão inicial (*handshake*) é protegido com criptografia **AES-GCM (SHA-256)** via relay público.
* **📡 Modo Offline / Manual (Zero-Server):** Gere convites compactados via `CompressionStream` (`deflate-raw`) para conectar em redes locais ou sem depender de nenhum serviço de sinalização externo.
* **📞 Chamadas de Voz, Vídeo e Tela:** Suporte a chamadas em tempo real com alternância de câmeras (frontal/traseira) e compartilhamento de tela com renegociação *in-band*.
* **📎 Envio de Arquivos e Mensagens de Voz:** Transferência em blocos (*chunking* de 16 KB) com controle de *backpressure*, barra de progresso, pré-visualização de imagens e gravador de áudio integrado.
* **💬 Recursos Completos de Chat:** Respostas citadas, edição e exclusão de mensagens para ambos os lados, reações com duplo toque (❤️), confirmação de leitura (`✓✓`), busca na conversa e temas escuro/claro.
* **💾 Portabilidade de Conta:** Histórico e contatos ficam salvos apenas no seu aparelho (`localStorage`), com opção de exportar e importar backup completo em `.json`.

---

## 🛠️ Como Usar

1. Acesse o [Nexus P2P](https://paulotomadon.github.io/Nexus-P2P/) e escolha seu nome de usuário.
2. Copie o seu **ID** no menu lateral e envie para um amigo (ou peça o ID dele).
3. Digite o ID do seu amigo em **Conectar por ID** e clique em **Conectar**.
4. Assim que o amigo aceitar, o canal direto é estabelecido e ele fica salvo na sua lista de **Contatos** para reconexão rápida com o botão `⚡`.

---

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais informações.
