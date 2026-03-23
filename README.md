Discord Image Scraper (Self-Bot Study)
Este projeto é um script de automação desenvolvido em Node.js utilizando a biblioteca discord.js-selfbot-v13.

[!WARNING]

Aviso de Isenção de Responsabilidade: Este script foi criado estritamente para fins educacionais e de aprendizado. O uso de self-bots pode violar os Termos de Serviço do Discord. Use por sua conta e risco.

🚀 Como Funciona
O script atua como um "ponte" automatizada entre dois canais:

Conexão: O bot se conecta à conta do usuário através de um Token de autenticação.

Extração: Ele acessa um canal de origem específico (ID configurado) e analisa as últimas mensagens em busca de anexos.

Filtro: O código verifica o contentType de cada anexo para garantir que apenas arquivos de imagem (PNG, JPG, GIF, WebP) sejam processados.

Transferência: Cada imagem encontrada é reenviada para uma DM (Mensagem Direta) de destino, respeitando um intervalo (delay) para evitar limites de taxa (rate limiting) da API.

🛠️ Tecnologias Utilizadas
Runtime: Node.js (v20+)

Biblioteca Principal: discord.js-selfbot-v13

Gerenciamento de Dependências: NPM

📋 Pré-requisitos
Antes de rodar o projeto, você precisará de:

Node.js instalado.

O seu Token de usuário do Discord.

Os IDs do canal de origem e do usuário/canal de destino.
