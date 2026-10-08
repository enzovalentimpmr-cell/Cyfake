# Camera Photo Selector

Projeto inicial Android Studio em Kotlin.

## O que esta versão faz

- Abre a galeria para selecionar uma imagem.
- Mostra a imagem selecionada em uma prévia.
- Solicita permissão para câmera.
- Tenta abrir a câmera frontal.

## Importante

Esta versão NÃO substitui a câmera do sistema em outros aplicativos.

Para fazer algo como:

"Outro aplicativo abre a câmera frontal -> escolher uma foto -> outro aplicativo receber a imagem como entrada de câmera"

será necessário desenvolver uma arquitetura específica para câmera virtual/integração com o sistema. Android não permite que um aplicativo comum simplesmente se registre como uma câmera física universal para todos os demais aplicativos.

## Como abrir

1. Abra esta pasta no Android Studio.
2. Aguarde o Gradle sincronizar.
3. Conecte um aparelho Android ou use um emulador.
4. Execute o módulo `app`.

Recomendado:
- Android Studio recente
- JDK 17
- Android SDK 35
