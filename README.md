# Curso Full Cycle 3.0 - Módulo Fundamento da Arquitetura de Software

<div>
    <img alt="Criado por Alcir Junior [Caju]" src="https://img.shields.io/badge/criado%20por-Alcir Junior [Caju]-%23f08700">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23f08700">
</div>

---

## Descrição

O Curso Full Cycle é uma formação completa para fazer com que pessoas desenvolvedoras sejam capazes de trabalhar em projetos expressivos sendo capazes de desenvolver aplicações de grande porte utilizando de boas práticas de desenvolvimento.

---

## Repositório Pai
https://github.com/alcir-junior-caju/study-full-cycle-3-0

---

## Visualizar o projeto na IDE:

Para quem quiser visualizar o projeto na IDE clique no teclado a tecla `ponto`, esse recurso do GitHub é bem bacana

---
### Tipos de arquitetura

- Software;
- Solução;
- Tecnológica;
- Corporativa.

#### Arquitetura Tecnológica
- Especialidade em tecnologias específicas de mercado;
- Geração de valor baseado em especialidades;
- Diversidade de profissionais especialistas;
    - Arquiteto Elastic;
    - Arquiteto Java;
    - SQL Server;
    - Oracle;
    - SAP;

#### Arquitetura Corporativa
- Impacta estrategicamente a organização como um todo;
- Avaliação de custos;
- Avaliação de possíveis novas tecnologias;
- Padronização de tecnologias;
- Planejamento de grandes implantações;
    - Sistemas "core";
    - Migrações;

#### Arquitetura de soluções
- Fica entre a área de negócios e software;
- Transformar requesitos de negócio em soluções de software;
- Desenhos arquiteturais da solução de um software para reproduzir como ele irá funcionar;
    - C4;
    - UML;
    - BPMN;
- Analisa os impactos comerciais em relação a uma escolha tecnológica;
- Pode participar do processo comercial de pré-venda e venda;
- Analisa os impactos dos custos para o negócio;

#### Arquitetura de Software
- É uma "disciplina" da Engenharia de Software;
- Diretamente ligada ao processo de desenvolvimento de software;
- Afeta diretamente na estrutura organizacional da empresa;
    - Formação dos times;
    - Estrutura dos componentes do software;
    - "Organizações que desenvolvem sistemas de software tendem a produzir sistemas que são cópia das estruturas de comunicação dessas empresas. (Melvin Conway)"
- É a relação entre os objetivos de ngócio e suas restrições com os componentes a serem criados e suas responsabilidades visando a evolução do software.
- "É a organização fundamental de um sistema e seus componentes, suas relações, seu ambiente, bem como os princípios que guiam seu design e evolução" (IEEE Standart 1471);
-  O processo de arquitetar um software estabelece que o que está sendo desenvolvido faça parte de um conjunto maior;

#### Papel do Arquiteto(a) de Software
- Transformar requisitos de negócio em padrões arquiteturais;
- Orquestrar pessoas desenvolvedoras e experts de domínio;
- Entender de forma profunda conceitos e modelos arquiteturais;
- Auxilia na tomada de decisão nos momentos de crise;
- Reforça boas práticas de desenvolvimento;
- Code reviews;
- Apesar de nem todas as organizações possuírem o cargo de arquiteto de software, normalmente profissionais mais experientes como desenvolvedores seniors e tech leads acabam realizando esse papel baseado em suas esperiencias anteriores;
- Há empresas que apesar de não possuírem o cargo de arquiteto(a) de software, possuem um departamento de arquitetura que auxilia os diversos times da organização com questões arquiteturais;

#### Por que aprender arquitetura de software?
- Poder navegar da visão macro para a visão micro de um ou mais softwares;
- Entender quais são as diversas opções que temos para desenvolver a mesma coisa e escolher a melhor solução para determinado contexto;
- Pensar a longo prazo no projeto e sua sustentabilidade;
- Tomar decisões de forma mais fria e calculada evitando assim ser influenciado(a) por "hypes" de mercado;
- Mergulho em padrões de projeto e de desenvolvimento e suas boas práticas;
- Ter mais clareza do impacto que o software possui na organização como um todo;
- Tomar decisões com mais segurança;

#### Arquitetura vs Design
- Arquitetura: Escopo global ou alto nível;
- Design: Escopo mais local;
- "Atividades relacionadas a arquitetura de software são sempre de design. O objetivo primário da arquitetura de software é garantir que os atributos de qualidade, restrições de alto nível e os objetivos do negócio, sejam atendidos pelo sistema. Qualquer decisão de design que não tenha relação com este objetivo não é arquitetural. Todas as decisões de design para um componente que não sejam 'visíveis' fora dele, geralmente, também não são. (Elemar Junior)"

#### Sustentabilidade
- Desenvolver software é caro;
- Software resolve uma dor;
- Software precisa se pagar ao longo do tempo;
- Acompanhar a evolução do negócio;
- Quanto mais tempo o software fica no ar, mais retorno ele gera;
- A solução precisa ser arquitetada;

#### Pilares da arquitetura de software
- Estruturação;
    - Fácil evolução, componentização para atender os objetivos de negócio;
- Componentização;
- Relacionamento entre sistemas;
- Governança;

#### Requisitos arquiteturais (RAs)
- Performance;
- Armazenamento de dados;
- Escalabilidade;
- Segurança;
- Legal;
- Audit;
- Marketing;

#### Características arquiteturais
- Operacionais;
- Estruturais;
- Cross-Cutting;

#### Características arquiteturais: Operacionais
- Disponibilidade;
- Recuperação de desastres;
- Performance;
- Recuperação (backup);
- Confiabilidade e segurança;
- Robustes;
- Escalabilidade;

#### Características arquiteturais: Estruturais
- Configurável;
- Extensibilidade;
- Fácil instalação;
- Reuso de componentes;
- Internacionalização;
- Fácil manutenção;
- Portabilidade (diversos bancos de dados);
- Fácil suporte (logs, debugging);

#### Características arquiteturais: Cross-Cutting
- Acessibilidade;
- Processo de retenção e recuperação de dados (quanto tempo os dados serão mantidos);
- Autenticação e Autorização;
- Legal;
- Privacidade;
- Segurança;
- Usabilidade;

#### Perspectivas para arquitetar software de qualidade
- Performance;
- Escalabilidade;
- Resiliência;

#### Performance
- É o desempenho que um software possuí para completar um determinado workload;
- As unidades de medida para avaliarmos a performance de um software são:
    - Latência ou "Response time";
    - Throughput;
- Ter um software performártico é diferente de ter um software escalável;

#### Métricas para medir a performance
- Diminuindo a latência;
    - Normalmente medida em milliseconds;
    - É afetada pelo tempo de processamento da aplicação, rede e chamadas externas;
- Aumentando o throughput;
    - Quantidade de requisições;
    - Diretamente ligado com a latência;

#### Principais razões para baixa performance
- Processamento ineficiente;
- Recursos computacionais limitados;
- Trabalhar de forma bloqueante;
- Acesso serial a recursos;

#### Principais formas para aumentar a eficiência
- Escala da capacidade computacional (CPU, Disco, Memória, Rede);
- Lógica por trás do software (Algoritmos, Queries, Overhead de frameworks);
- Concorrência e paralelismo;
- Banco de dados (Tipos de bancos, Schema);
- Caching;

#### Capacidade Computacional: Escala vertical vs horizontal
- Escala vertical seria aumentar a capacidade computacional;
- Escala Horizontal seria aumentar a capacidade de máquinas utilizando load balancer;

#### Concorrência vs Paralelismo
- "Concorrência é sobre lidar com muitas coisas ao mesmo tempo. Paralelismo é fazer muitas coisas ao mesmo tempo. (Rob Pike)";

#### Caching
- Cache na borda / Edge computing;
- Dados estáticos;
- Páginas web;
- Funções internas;
    - Evita reprocessamento de algoritmos pesados;
    - Acesso a banco de dados;
- Objetos;

#### Caching: Exclusivo vs Compartilhado
- Exclusivo;
    - Baixa latência;
    - Duplicado entre os nós;
    - Problemas relacionados a sessões;
- Compartilhado;
    - Maior latência;
    - Não há duplicação;
    - Sessões compartilhadas;
    - Banco de dados externo;
        - MySQL;
        - Redis;
        - Memcache;

#### Caching: Edge computing
- Cache realizado mais próximo ao usuário;
- Evita a requisição chegar até o Cloud Provider / infra;
- Normalmente arquivos estáticos;
- CDN - Content Delivery Network;
- Cloudflare workers;
- Vercel;
- Akamai;

#### Escalabilidade
- Escalabilidade é a capacidade de sistemas suportarem o aumento (ou a redução) dos workloads incrementando (ou reduzindo) o custo em menor ou igual proporção.

#### Escalabilidade vs Performance
- Enquanto performance tem o foco em reduzir a latência e aumentar o throughput, a escalabilidade visa termos a possibilidade de aumentar ou diminuir o throughput adicionando ou removendo a capacidade computacional.

#### Escalando Software: Descentralização
- Disco efêmero;
- Servidor de aplicação vs Servidor de assets;
- Cache centralizado;
- Sessões centralizadas;
- Upload / Gravação de Arquivos;

#### Escala de banco de dados
- Aumentando recursos computacionais;
- Distribuindo responsabilidades (escrita vs leitura);
- Shards de forma horizontal;
- Serverless;

#### Otmização de queries e índices
- Trabalhe com índices de forma consciente;
- APM (Application performance monitoring) nas queries;
- Explain nas queries;
- CQRS (Command Query Responsibility Segregation);

#### Proxy reverso
- Um proxy reverso é um servidor que fica na frente dos servidores web e encaminha as solicitações do cliente (por exemplo, navegador web) para esses servidores web;

#### Soluções populares de Proxy Reverso
- Ngnix;
- HAProxy (HA = High Availability);
- Traefik;
