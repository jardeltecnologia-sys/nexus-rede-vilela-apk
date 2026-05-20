# Auditoria — correção do APK Nexus

## Erro anterior

A versão anterior misturava:

- Portal/motor da Rede Vilela em `www.redevilela.com.br`
- Assistente virtual Nexus em `www.redevilela.com`

## Correção aplicada

Esta versão usa somente:

```text
https://www.redevilela.com/
```

## Interface nativa

A barra inferior foi simplificada:

- Assistente
- Microfone
- Recarregar

## Permissões

- INTERNET
- ACCESS_NETWORK_STATE
- RECORD_AUDIO
- MODIFY_AUDIO_SETTINGS

A permissão de microfone é mantida porque o site do assistente informa recurso de microfone/voz.

## GitHub

O script continua usando o repositório fixo:

```text
https://github.com/jardeltecnologia-sys/nexus-rede-vilela-apk.git
```
