# Topologia-de-Rede

Configuração de Topologia de Rede - XSystems

Este repositório documenta o trabalho de configuração lógica da rede da empresa XSystems, que inclui uma matriz no Centro do Rio de Janeiro, um escritório de suporte em Niterói e uma filial na Av. Paulista, em São Paulo. A rede foi projetada utilizando o recurso de subnetting/VLSM a partir da rede 192.168.1.0/24 para evitar o desperdício de endereços IP.

Estrutura do Cenário

A XSystems possui:
. Matriz: Centro do Rio de Janeiro
. Escritório de Suporte: Niterói
. Filial: Av. Paulista, São Paulo
  Cada localidade comporta cerca de 50 hosts, e a rede foi planejada para otimizar o uso de IPs por meio de subnetting.

Roteiro de Configuração
Parte 1: Criação da Topologia no Packet Tracer
  . Configuração da topologia inicial no Packet Tracer.

Parte 2: Plano de Endereçamento
  . Desenvolvimento de um plano de endereçamento baseado na rede 192.168.1.0/24.
  . Documentação das sub-redes criadas utilizando subnetting/VLSM.
Parte 3: Endereçamento para a Topologia
  . Detalhamento do endereçamento para cada dispositivo na topologia.
Parte 4: Configuração dos PCs
  . Nomeação e configuração dos PCs conforme a topologia.
Configuração dos endereços IPs e gateways padrão.
Parte 5: Configuração dos Switches
  . Nomeação e configuração dos switches.
  . Configuração de senhas para o acesso console e vty.
  . Criptografia de todas as senhas.
  . Configuração do IP das VLANs.
Salvamento das configurações.
Parte 6: Configuração dos Roteadores
  . Nomeação e configuração dos roteadores.
  . Configuração de senhas de acesso e criptografia.
  . Definição de um banner de acesso.
  . Configuração das interfaces com os endereços IP apropriados.
  . Salvamento das configurações.
  . Parte 7: Verificação de Conectividade
  . Configuração de rotas estáticas entre Rio de Janeiro e São Paulo.
  . Verificação das tabelas de roteamento.
  . Testes de conectividade utilizando o Packet Tracer.
  . Captura de pacotes de um ping entre os PCs 1 e 4.
Ferramentas Utilizadas
  . Cisco Packet Tracer: Para a simulação e configuração da rede.
Documentação: Inclui capturas de tela das configurações realizadas.
