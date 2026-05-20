# Auditoria do pacote Nexus Rede Vilela APK

## Arquivos preservados

- docs/nexus-blogger-theme-original.xml
- docs/NEXUS-LOGO-original.png
- docs/nexus-intro-original.mp4

## Build

O workflow usa a estratégia que já funcionou nos projetos anteriores: cria um projeto Android limpo dentro do GitHub Actions e compila com Gradle 8.4 + Android Gradle Plugin 8.2.2.

## Permissões

- INTERNET: necessária para carregar www.redevilela.com.br e www.redevilela.com.
- ACCESS_NETWORK_STATE: diagnóstico de conexão.
- RECORD_AUDIO: necessário para recursos de microfone/voz do Nexus.
- MODIFY_AUDIO_SETTINGS: suporte a mídia/voz.

## Segurança

O APK não coleta dados nativamente. Ele apenas encapsula o portal e o assistant via WebView.
