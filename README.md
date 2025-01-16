# Análise de Logs de Segurança

Este repositório contém um conjunto de scripts Python para automação da análise de logs de segurança em sistemas Linux. O objetivo deste projeto é identificar padrões de tráfego de rede e possíveis atividades suspeitas, fornecendo uma forma rápida de detectar incidentes de segurança.

## Funcionalidades

- **Análise de Logs de Rede**: O script analisa logs de servidores e roteadores, procurando por padrões incomuns de tráfego que podem indicar um ataque.
- **Alertas de Segurança**: Configura alertas para eventos suspeitos encontrados nos logs.
- **Relatórios Detalhados**: Geração de relatórios sobre os eventos identificados, com informações sobre o tipo de ameaça e possíveis ações corretivas.

## Tecnologias Usadas

- **Python**: Linguagem principal para o desenvolvimento dos scripts.
- **Regular Expressions**: Utilizado para análise e extração de padrões dos logs.
- **Linux**: O sistema operacional utilizado para a execução dos scripts (também aplicável em outros sistemas UNIX).

## Como Rodar

### Pré-requisitos

1. Ter Python 3.x instalado. Para verificar a versão do Python, execute:
   ```bash
   python --version
