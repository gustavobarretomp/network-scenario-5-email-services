# Cenário 5 — Rede com RIPv2, DNS, HTTP e E-mail

Projeto acadêmico desenvolvido em grupo para a disciplina de **Sistemas de Comunicação e Redes**.

O cenário representa uma infraestrutura com cinco roteadores, cinco redes locais, dois servidores DNS, dois servidores de e-mail, um servidor web e quatro máquinas clientes.

A topologia foi simulada no Cisco Packet Tracer e implementada em ambiente virtualizado com Ubuntu Server.

## Topologia

<p align="center">
  <img src="docs/assets/topologia-cenario-5-publico.png" alt="Topologia do Cenário 5" width="100%">
</p>

## Tecnologias utilizadas

- Cisco Packet Tracer
- Oracle VirtualBox
- Ubuntu Server
- FRRouting e RIPv2
- BIND9
- Apache2
- Postfix e Dovecot
- TCPDump e Wireshark
- Netplan e Linux

## Serviços implementados

- Roteamento dinâmico entre as cinco redes.
- Resolução DNS com registros A e MX.
- Servidor web com Apache2.
- Envio de mensagens com SMTP.
- Recebimento de mensagens com POP3.
- Comunicação entre dois domínios de e-mail.

## Testes realizados

Durante o projeto foram realizados testes de:

- conectividade entre as redes;
- convergência do RIPv2;
- resolução de nomes;
- consulta de registros MX;
- acesso ao servidor web;
- envio e recebimento de e-mails;
- captura e análise de pacotes.

## Site e roteiro de estudo

Fui responsável pela criação do site do projeto.

O site foi desenvolvido para transformar o Cenário 5 em um roteiro de estudo sobre virtualização e infraestrutura de redes.

Utilizei inteligência artificial como ferramenta de apoio para organizar as etapas de aprendizagem e reunir vídeos do YouTube relacionados à criação das máquinas virtuais, configuração das redes e implementação dos serviços.

[🌐 Acessar o site e o roteiro de estudo](https://gustavobarretomp.github.io/network-scenario-5-email-services/)

## Arquivos do projeto

- [Simulação no Cisco Packet Tracer](packet-tracer/)
- [Relatório técnico](docs/relatorio-cenario-5.pdf)
- [Site do projeto](https://gustavobarretomp.github.io/network-scenario-5-email-services/)

## Minha participação

Projeto desenvolvido em grupo. Minha participação incluiu:

- atuação como Scrum Master;
- organização das atividades;
- apoio nas configurações e testes;
- participação na documentação;
- criação do site;
- organização do roteiro de estudo;
- publicação do projeto no GitHub.

## Responsável pelo repositório e pelo site

**Gustavo Barreto**

Projeto voltado ao estudo de redes, virtualização, Linux e segurança da informação.
