# Estacionamento Inteligente Visite 2024 ETEC FERNSNDO PRESTES

## ETEC Fernando Prestes - Extensão FATEC
**Curso:** Desenvolvimento de Sistemas  
**Local:** Sorocaba - SP  

**Integrantes da Equipe:**
- **Leonardo Martins Brasilio**
- **Jones Henrique Branco Sandrini**
- **Pedro Henrique Menezes Bernardo**

---

## Resumo do Projeto

O projeto **"Estacionamento Inteligente"** tem como objetivo desenvolver um sistema automatizado de gerenciamento de vagas em estacionamentos, projetado para atender a um ambiente de **cinco vagas**. O sistema é capaz de monitorar a ocupação das vagas, controlar a abertura de cancelas e fornecer feedback aos usuários sobre a disponibilidade de espaço. A implementação do projeto busca não apenas a eficiência, mas também a melhoria da experiência do usuário ao procurar uma vaga.

### Objetivos do Projeto

- **Automação:** Reduzir a necessidade de intervenção humana na gestão das vagas.
- **Eficiência:** Melhorar a utilização do espaço disponível no estacionamento.
- **Sinalização:** Oferecer informações claras sobre a ocupação das vagas e controle de acesso.

## Componentes do Sistema

O sistema é composto por diversos elementos eletrônicos e programáticos, que juntos garantem seu funcionamento:

### Hardware

- **Arduino Uno:** Placa microcontroladora responsável pela lógica do sistema e comunicação entre os componentes.
- **Protoboard:** Utilizada para conectar todos os componentes eletrônicos de forma organizada e eficiente.
- **Sensores de Infravermelho (IR):** Utilizados para detectar a presença de veículos em cada vaga, permitindo monitorar a ocupação.
- **Servomotores:** Controlam a abertura e fechamento da cancela, permitindo o acesso ao estacionamento.
- **Display LCD 16x2:** Utilizado para exibir informações sobre a ocupação das vagas e status do estacionamento.

- **Cabos Jumpers:** Utilizados para fazer as conexões entre os componentes na protoboard.

### Software

- **Linguagem:** C++
- **IDE Utilizada:** Arduino IDE
- **Lógica de Programação:** O código desenvolvido monitora a ocupação das vagas, controla os servomotores e gerencia as sinalizações.

## Estrutura do Código

O código está dividido em funções principais:

1. **Monitoramento das Vagas:** Verifica constantemente a presença de veículos nas vagas usando os sensores IR.
2. **Controle da Cancela:** Abre a cancela automaticamente quando um veículo é detectado e fecha após a saída.
3. **Exibição de Informações:** Atualiza o display LCD com a quantidade de vagas disponíveis e mensagens de status.
