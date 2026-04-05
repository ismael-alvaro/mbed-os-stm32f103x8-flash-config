EN | [PT-BR](#PT-BR)

# STM32F103x8 memory configuration adjustment for mbed-os

This repository contains a small board-specific adjustment for mbed-os on the STM32F103x8.

## What was changed
The flash memory configuration was updated from 64 KB to 128 KB to match the actual device specification.

## Why
Some board definitions may not reflect the correct flash size for this STM32 variant.  
This adjustment helps ensure the firmware build uses the proper memory layout.

## Scope
This is a minimal, single-change repository focused on board configuration.

## Notes
This repository is useful as a reference for embedded firmware configuration on STM32F103-based boards.

---

# PT-BR

[EN](#STM32F103x8-memory-configuration-adjustment-for-mbed-os) | PT-BR

# Ajuste de configuracao de memoria STM32F103x8 para mbed-os

Este repositorio contem um pequeno ajuste especifico de placa para mbed-os no STM32F103x8.

## O que foi alterado
A configuracao de memoria flash foi atualizada de 64 KB para 128 KB para corresponder a especificacao real do dispositivo.

## Por que
Algumas definicoes de placa podem nao refletir o tamanho correto de flash para esta variante STM32.  
Este ajuste ajuda a garantir que a compilacao do firmware use o layout de memoria adequado.

## Escopo
Este e um repositorio minimo, com uma unica alteracao, focado em configuracao de placa.

## Observacoes
Este repositorio e util como referencia para configuracao de firmware embarcado em placas baseadas em STM32F103.
