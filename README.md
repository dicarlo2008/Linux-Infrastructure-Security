# 🛡️ Linux Infrastructure & Security

## 📖 Visão Geral

Projeto independente de administração de infraestrutura Linux, hardening e segurança operacional, aplicado a ambientes VPS de produção.

O ambiente contempla a administração e manutenção de duas VPS Linux, com serviços de infraestrutura, proxy reverso, balanceamento de tráfego, bancos de dados, monitoramento e controles defensivos.

O trabalho envolve a operação contínua dos serviços, análise de logs, troubleshooting, aplicação de medidas de hardening e automação de rotinas administrativas, com foco em estabilidade operacional, observabilidade e redução da superfície de ataque.

## 🎯 Escopo Técnico

- Administração e manutenção de servidores Linux em produção
- Gerenciamento de serviços e processos do sistema
- Configuração e manutenção de proxy reverso e balanceamento de tráfego
- Administração de regras de firewall e controles de acesso
- Monitoramento de serviços e análise de eventos operacionais
- Investigação de requisições HTTP suspeitas e padrões de atividade maliciosa
- Aplicação de práticas de hardening e redução da superfície de ataque
- Automação de tarefas operacionais com Bash e Python
- Troubleshooting de serviços, conectividade e infraestrutura
- Manutenção e atualização de componentes do ambiente

## 🧰 Stack Tecnológica

### Sistemas e Infraestrutura

- **Linux:** Debian e Ubuntu
- **Web e tráfego:** Nginx e HAProxy
- **Bancos de dados e armazenamento em memória:** MariaDB e Redis
- **Aplicações:** PHP e WordPress

### Segurança Defensiva

- **Firewall:** nftables
- Hardening de sistemas e serviços Linux
- Controle de acesso e restrição da exposição de serviços
- Análise de logs e investigação de eventos
- Proteção de borda e mitigação de tráfego suspeito
- Pesquisa de CVEs e avaliação de impacto no ambiente

### Automação e Ferramentas

- Bash / Shell Script
- Python aplicado a rotinas operacionais
- Git e GitHub
- Docker e Docker Compose — utilizados no computador pessoal para testes e aprendizado, não nas VPS de produção.

## 🔍 Atividades Operacionais

- Administração de duas VPS Linux utilizadas em ambiente de produção
- Configuração, operação e manutenção de serviços Nginx e HAProxy
- Gerenciamento de regras de filtragem de tráfego utilizando nftables
- Análise de logs de acesso e registros do sistema para troubleshooting e investigação de eventos
- Acompanhamento da disponibilidade e do comportamento operacional dos serviços
- Identificação de padrões associados a brute force, scanning e requisições HTTP suspeitas
- Implementação e manutenção de controles defensivos, incluindo bloqueios de IPs
- Automação de tarefas administrativas e rotinas de segurança
- Aplicação de atualizações e práticas de hardening
- Investigação de problemas operacionais e avaliação de possíveis impactos de vulnerabilidades

## 🔐 Práticas de Segurança

O ambiente utiliza medidas defensivas voltadas a:

- Redução da superfície de ataque
- Restrição de acesso aos serviços administrativos
- Filtragem de tráfego na camada de rede
- Análise de logs e acompanhamento de eventos
- Manutenção de serviços e componentes atualizados
- Automação de controles defensivos
- Separação entre informações públicas do projeto e configurações operacionais sensíveis

## 🔒 Segurança do Repositório

Este repositório apresenta a arquitetura geral, as tecnologias utilizadas e as práticas técnicas aplicadas no ambiente.

Scripts internos, regras detalhadas de segurança, credenciais, endereços sensíveis e configurações operacionais não são publicados quando sua divulgação puder aumentar a exposição da infraestrutura.

## 👨‍💻 Áreas de Atuação e Interesse

- Linux System Administration
- IT Infrastructure Operations
- Infrastructure Monitoring
- NOC Operations
- Network Troubleshooting
- Defensive Security / Blue Team
- Log Analysis
- Infrastructure Hardening
- Security Automation
- Incident Investigation
