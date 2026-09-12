<h1 align="center">LemBar</h1>

<p align="center">
  <strong>Your Mac, right at the top.</strong><br>
  Uma central compacta para música, sistema, calendário e ações rápidas integrada à região superior do macOS.
</p>

<p align="center">
  <a href="https://github.com/PaladinoCH/LemBar/releases/latest">
    <img src="https://img.shields.io/github/v/release/PaladinoCH/LemBar?label=release" alt="Latest Release">
  </a>
  <img src="https://img.shields.io/badge/macOS-26.5%2B-black?logo=apple" alt="macOS 26.5+">
  <img src="https://img.shields.io/badge/Universal-arm64%20%7C%20x86__64-blue" alt="Universal">
  <a href="https://github.com/PaladinoCH/LemBar/releases">
    <img src="https://img.shields.io/github/downloads/PaladinoCH/LemBar/total?label=downloads" alt="Downloads">
  </a>
</p>

<p align="center">
  <a href="https://github.com/PaladinoCH/LemBar/releases/latest"><strong>Download LemBar</strong></a>
  ·
  <a href="https://github.com/PaladinoCH/LemBar/releases">Releases</a>
</p>

---

LemBar transforma a região superior do seu Mac em uma central rápida de informações e controles.

Música, informações do sistema, calendário e ações rápidas ficam disponíveis em uma interface compacta projetada para permanecer acessível sem interromper seu fluxo de trabalho.

## Quick Start

1. Acesse a [release mais recente](https://github.com/PaladinoCH/LemBar/releases/latest).
2. Baixe `LemBar-1.0.1-universal.dmg`.
3. Abra o DMG.
4. Arraste `LemBar.app` para `Applications`.
5. Abra o LemBar.

> A versão atual utiliza assinatura ad-hoc e ainda não possui notarização Apple. Consulte [Gatekeeper](#gatekeeper) caso o macOS bloqueie a primeira abertura.

## Recursos

- **Controles de música** — faixa atual, artista, capa, play/pause, próxima/anterior, progresso e volume.
- **Monitoramento do sistema** — CPU, memória, bateria e informações rápidas do Mac.
- **Calendário** — acesso aos calendários configurados no macOS, incluindo iCloud, Google e Microsoft.
- **Ações rápidas** — atalhos para funções úteis do macOS.
- **Múltiplos monitores** — integração com diferentes telas.
- **Temas** — Automático, Claro e Escuro.
- **Inicialização automática** — opção para iniciar junto com o macOS.
- **Interface compacta** — integrada à região superior do sistema.

## Música

A integração atual com o Spotify disponibiliza:

- título e artista;
- capa do álbum;
- estado de reprodução;
- play e pause;
- próxima faixa e faixa anterior;
- progresso da música;
- controle de volume.

## Sistema

O LemBar oferece uma visão rápida de:

- uso de CPU;
- uso de memória;
- bateria;
- informações gerais do sistema.

## Calendário

O LemBar integra os calendários disponíveis no macOS. Eventos de fontes como iCloud, Google, Microsoft e outros calendários configurados no sistema ficam acessíveis diretamente pela interface compacta.

## Compatibilidade

- macOS 26.5 ou superior
- Apple Silicon (`arm64`)
- Intel (`x86_64`)

A distribuição oficial é Universal e o mesmo DMG/ZIP funciona nas duas arquiteturas.

## Download

Versão estável atual: **LemBar v1.0.1**

- `LemBar-1.0.1-universal.dmg`
- `LemBar-1.0.1-universal.zip`

[**Baixar a versão mais recente →**](https://github.com/PaladinoCH/LemBar/releases/latest)

## Instalação

### DMG

1. Baixe `LemBar-1.0.1-universal.dmg`.
2. Abra o arquivo.
3. Arraste `LemBar.app` para `Applications`.
4. Abra o aplicativo pela pasta Aplicativos.

### ZIP

1. Baixe `LemBar-1.0.1-universal.zip`.
2. Extraia o arquivo.
3. Mova `LemBar.app` para `Applications`.
4. Abra o aplicativo.

## Gatekeeper

A versão `v1.0.1` utiliza assinatura ad-hoc e ainda não possui Apple Developer ID ou notarização.

Se o macOS bloquear a primeira abertura:

1. clique com o botão direito em `LemBar.app`;
2. escolha **Abrir**;
3. confirme a execução.

Se necessário, use **Ajustes do Sistema → Privacidade e Segurança → Abrir Mesmo Assim**.

Não é necessário desativar o Gatekeeper.

## Integridade

### DMG

```text
139680a95e80411cca5362e13b50082d3d836e283fff1ef7141cb80b12b287b7
```

### ZIP

```text
4e7f22a55cbd1f3a0a3d80746add9df5860bf7ee6870905efc213d3c184052b0
```

Para verificar no macOS:

```bash
shasum -a 256 LemBar-1.0.1-universal.dmg
shasum -a 256 LemBar-1.0.1-universal.zip
```

## Código-fonte

Este repositório público é utilizado para documentação e distribuição oficial das versões do LemBar.

O código-fonte do aplicativo não é publicado neste repositório.

## Autor

**Henrique Lemos**

---

<p align="center">
  <strong>LemBar</strong><br>
  Your Mac, right at the top.
</p>
