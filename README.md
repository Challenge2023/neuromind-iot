# Neuromind

## Projeto de Disruptive Architecture - Global Solution

Este repositório contém o código-fonte de um dispositivo baseado em ESP32, projetado para coletar dados de temperatura corporal e pressão arterial. Esses dados são transmitidos para um servidor MQTT hospedado em "mqtt.tago.io" por meio da biblioteca EspMQTTClient. A solução visa preencher a lacuna na assistência aos profissionais de saúde, fornecendo uma ferramenta precisa e eficiente para coleta de dados biométricos.

## Video demostrativo

https://github.com/Challenge2023/neuromind-iot/assets/101189058/2e9a2552-d14d-4feb-9db4-743ecc7bb463

Link youtube : https://youtu.be/TuLy11BiFJo

## Problema Identificado

A ausência de um sistema integrado e inteligente impede os profissionais de saúde de obterem insights rápidos e relevantes para diagnósticos mais precisos durante a avaliação de pacientes. Embora existam ferramentas disponíveis para a coleta de dados, a falta de inteligência por trás dessas ferramentas dificulta a análise eficiente e a interpretação imediata dessas informações críticas.

## Solução com IoT

A solução proposta utiliza o ESP32 para coletar dados vitais diretamente do paciente, eliminando a necessidade de medições manuais demoradas. Além disso, a integração com um servidor MQTT permite a comunicação eficiente entre o dispositivo e sistemas de análise mais avançados, proporcionando insights instantâneos e relevantes para apoiar diagnósticos mais precisos.

## Instruções

### Dependências

- Arduino IDE (ou plataforma de desenvolvimento Arduino equivalente)
- Sensores de temperatura e pressão arterial compatíveis com ESP32
- Módulo de comunicação para envio de dados (Wi-Fi, Bluetooth, etc.)

### Instalação

1. Clone este repositório: git clone [https://github.com/seu-usuario/seu-repo.git](https://github.com/Challenge2023/neuromind-iot)
2. Abra o projeto na Arduino IDE.
3. Configure as credenciais Wi-Fi e MQTT no código-fonte.
4. Carregue o código para o seu ESP32.
5. Conecte os sensores de temperatura e pressão arterial conforme as especificações do fabricante.
6. Configure a comunicação para enviar os dados coletados para o servidor MQTT.

## Equipe

Claudio Roberto - rm95340
David Augusto - rm93429
Lucas Amadeu - rm94539
Rafal Mafort - rm95699
Vitor Mantovani - rm92875

Este projeto representa uma solução inovadora de Disruptive Architecture, centrada na integração de uma inteligência avançada para superar a limitação na obtenção rápida e relevante de insights durante avaliações médicas. O objetivo é proporcionar suporte eficiente aos profissionais de saúde para diagnósticos mais precisos e informados.

