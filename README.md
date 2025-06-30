# Projeto TecnoMala: Plataforma de Compartilhamento de Malas Inteligentes

## Visão Geral do Projeto

Este repositório contém os artefatos desenvolvidos como parte da atividade prática da disciplina de Modelos de Negócio e Atividade de Inovação. Nosso foco foi a **Plataforma de Compartilhamento de Malas Inteligentes**, um modelo de negócio inovador que visa otimizar a logística de empresas através da reutilização, rastreabilidade e segurança proporcionadas por malas equipadas com tecnologias como sensores, geolocalização e blockchain.

O projeto aborda os desafios logísticos atuais, oferecendo uma solução colaborativa e sustentável para o transporte de produtos.

## A Mala Retornável Inteligente

A base do nosso modelo de negócio é a mala retornável inteligente, um produto tecnológico equipado com:
* **Sensores:** Para monitoramento de condições como temperatura, umidade, tempo de trajeto e impactos.
* **Geolocalização:** Para rastreamento em tempo real do trajeto da mala.
* **Módulos de Comunicação:** Permitem a troca de informações.
* **Sistema de Segurança baseado em Blockchain:** Garante a integridade, rastreabilidade e imutabilidade dos registros de uso e movimentação da mala.

## Como Funciona a Plataforma de Compartilhamento

A plataforma permite que empresas que enviam produtos regularmente compartilhem malas inteligentes dentro de uma rede cooperativa. O uso é controlado por um sistema de créditos, e todas as trocas são registradas automaticamente por smart contracts.

As principais etapas do funcionamento são:

1.  **Consultar e Reservar Mala:**
    * As empresas acessam a plataforma de compartilhamento.
    * Consultam a disponibilidade de malas inteligentes próximas à sua localidade, com informações como tipo, distância e tempo estimado de entrega.
    * Escolhem e fazem a reserva da mala desejada.
    * A plataforma registra o compromisso e envia a solicitação ao operador logístico.

2.  **Recebimento e Preparação do Envio:**
    * A mala é recebida da equipe de logística.
    * O produto é preparado e colocado dentro da mala.
    * O lacre eletrônico é ativado para segurança.

3.  **Envio e Transferência:**
    * O envio é iniciado e monitorado continuamente por sensores e geolocalização.
    * Ao final do uso, a empresa tem a opção de devolver a mala para o centro de distribuição da rede ou repassá-la diretamente para outro participante que tenha feito uma nova reserva.
    * Este modelo cria um ciclo contínuo de compartilhamento, onde as malas circulam de forma eficiente e rastreada.

4.  **Acompanhar Gestão de Saldo:**
    * Cada movimentação da mala é registrada automaticamente via blockchain com smart contracts.
    * O sistema calcula quantas vezes cada empresa usou ou cedeu malas, consolidando registros de uso.
    * Empresas que disponibilizaram mais malas acumulam créditos, e as que mais utilizaram acumulam débitos.
    * O saldo pode ser compensado financeiramente ou convertido em vantagens futuras na rede.

## Estrutura do Repositório

* `TECNOMALA/Especificação/Atividade_Prática___GPN.pdf`: O documento original que descreve o contexto do projeto, os modelos de negócio e as instruções da atividade prática.
* `TECNOMALA/Especificação/Gestão/Gestão do Projeto TecnoMala.pdf`: Documento com o planejamento e gestão do projeto, incluindo etapas, responsáveis e entregáveis.
* `TECNOMALA/BPMN/`: Pasta contendo os diagramas BPMN modelados para cada etapa do processo da Plataforma de Compartilhamento de Malas Inteligentes. (Você precisará criar esta pasta e adicionar seus arquivos `.bpmn` ou imagens aqui)
* `TECNOMALA/Interfaces/`: Pasta com os esboços das interfaces gráficas (telas de aplicativo ou sistema desktop) propostas para as tarefas de usuário final. (Você precisará criar esta pasta e adicionar seus arquivos de imagem ou protótipo aqui)
* `Relatório_Final_TecnoMala.pdf`: O relatório completo da atividade, detalhando o modelo de negócio, processos modelados, justificativas, interfaces e estratégias de validação. (Você precisará adicionar este arquivo aqui)

## Estratégias de Validação

Os modelos BPMN desenvolvidos foram validados utilizando as seguintes estratégias:
* **Caminhamento de casos de uso:** Percorremos cenários realistas passo a passo para identificar a completude e lógica do modelo.
* **Validação por pares:** Troca e análise mútua do modelo com outro grupo para checar coerência e aderência ao problema.
* **Simulação dramatizada (role-playing):** Representação do processo em equipe para identificar lacunas ou ambiguidades.
* **Comparação com a descrição textual:** Verificação da fidelidade do modelo BPMN à descrição informal do processo.

## Apresentação do Projeto

Uma apresentação em vídeo detalhando o projeto, os processos modelados e as interfaces propostas está disponível no YouTube.

* [Link para o vídeo da apresentação no YouTube](**colocar link aqui qnd gravarmos**)

## Contribuições

Este projeto foi desenvolvido por:
| Aluno | GitHub | LinkedIn |
|-------|--------|----------|
| Alice lourenço dos Reis | [![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)]) | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin)]() |
| Davi Campos Sutil | [![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)]) | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin)]() |
| Gustavo Saraiva Mariano | [![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)](https://github.com/saraivagustavo) | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/gustavo-saraiva-mariano/) |
| Karyna Martins Carbas | [![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)](https://github.com/Carbas-k) | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/karyna-carbas-4b8753240/) |
| Pedro Henrique Albani Nunes | [![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)](https://github.com/PedroAlbaniNunes) | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/pedro-henrique-albani-nunes-33a729270/) |



## Licença

Este projeto está licenciado sob a MIT License. Consulte o arquivo `LICENSE` para mais detalhes.
