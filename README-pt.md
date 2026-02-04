# Google Drive Magnet Flow

<!-- Secção de Emblemas -->
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/augusto-mate/google-drive-magnet-flow/blob/main/google_drive_magnet_flow.ipynb)
[![Licença: MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/downloads/)

<!-- Seletor de idioma -->
> *[English](README.md) version available.*

**Google Drive Magnet Flow** é um notebook Google Colab poderoso e focado em privacidade, projetado para otimizar o processo de download de links magnet, criptografar opcionalmente o conteúdo e fazer upload seguro diretamente para o seu Google Drive. Este projeto garante o gerenciamento eficiente dos seus downloads com segurança aprimorada e limpeza automática.

### Funcionalidades:

*   **Download de Links Magnet:** Suporta o download de múltiplos links magnet.
*   **Criptografia Opcional:** Criptografa seu conteúdo baixado usando arquivos ZIP ou 7-Zip protegidos por senha para maior privacidade.
*   **Manuseio Seguro de Senhas:** Implementa `getpass` para entrada de senha oculta e mecanismos de repetição para confirmação.
*   **Upload Direto para o Google Drive:** Faz o upload contínuo de arquivos criptografados (ou downloads brutos) para o seu Google Drive montado usando `shutil`.
*   **Limpeza Local Automatizada:** Garante que todos os arquivos temporários locais e diretórios de download sejam limpos após o processo, independentemente do sucesso do upload.
*   **Sem Dependência do Rclone:** Otimizado para integração direta com o Google Drive, sem a necessidade de configuração do `rclone`.
*   **Arquivamento com Privacidade em Primeiro Lugar:** Arquivos criptografados são nomeados com um timestamp, garantindo que nenhuma palavra descritiva seja publicamente exposta.
*   **Estrutura de Arquivo Limpa:** Arquivos ZIP criptografados não incluem pastas pai (`/content/downloads`), colocando o conteúdo diretamente na raiz do arquivo.

### Como Funciona:

1.  **Inserir Links Magnet:** Forneça um ou mais links magnet.
2.  **Escolher Criptografia (Opcional):** Decida se deseja criptografar seus downloads e selecione entre a compressão ZIP ou 7-Zip.
3.  **Definir Senha de Criptografia:** Insira e confirme uma senha forte (a entrada é oculta).
4.  **Especificar Destino no Google Drive:** Defina a subpasta no seu Google Drive onde os arquivos serão enviados.
5.  **Processamento Automatizado:** O notebook lida com o download, criptografia (se escolhida), upload e limpeza local.

---

## Aviso Legal

Este projeto é fornecido apenas para fins educacionais e de pesquisa. O desenvolvedor não apoia ou endossa qualquer uso ilegal desta ferramenta. Os usuários são inteiramente responsáveis por suas ações e pelo cumprimento de todas as leis e regulamentos aplicáveis em suas respectivas jurisdições. Use esta ferramenta por sua conta e risco.

---

## Autor

*   **Augusto Mate** — *Desenvolvimento Inicial*
*   [@augusto-mate](https://github.com/augusto-mate)

## Licença

Este projeto está licenciado sob a **Licença MIT** — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

### Inspiração

> "E tudo quanto fizerdes, fazei-o de todo o coração, como para o Senhor e não para homens." (Colossenses 3:23)
