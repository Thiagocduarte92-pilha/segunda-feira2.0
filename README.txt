# Segunda-feira — protótipo inicial

Este pacote contém uma interface PWA simples para a assistente pessoal.

## O que já funciona
- Interface adaptada para celular.
- Campo de texto e botão de envio.
- Tentativa de reconhecimento de voz, se o navegador oferecer suporte.
- Leitura em voz alta usando a síntese de voz disponível no aparelho.
- Manifesto e service worker para instalação como PWA.

## O que ainda NÃO funciona
A assistente ainda não está conectada a um modelo de IA. As respostas são demonstrativas. O protótipo não envia mensagens para nenhum servidor.

## Como instalar no iPhone
1. Publique os arquivos em um endereço HTTPS (por exemplo, hospedagem estática gratuita).
2. Abra o endereço no Safari.
3. Toque em Compartilhar > Adicionar à Tela de Início.
4. Abra pelo ícone criado.

## Próxima etapa
Conectar um backend seguro a um modelo de IA com uma opção gratuita. Não coloque chaves privadas de API diretamente no HTML/JavaScript público.
