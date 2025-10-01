# Fase 1 — Estabelecer Requisitos de Avaliação

<div style="text-align: center;">
  <img src="../assets/images/sougov.png" alt="SouGov.br" style="max-width: 100%; height: auto;">
</div>
<div style="text-align: center; margin: 0; font-size: 14px;">
  Imagem 1: Logo SouGov
</div>

<details>
  <summary>Versão SouGov Desktop</summary>
  Versão X.X — Versão desktop utilizada ao longo desta avaliação.
</details>

<details>
  <summary>Versão SouGov Mobile</summary>
  Versão X.X — Versão mobile utilizada ao longo desta avaliação.
</details>

## 1. Objetivo
O objetivo desta fase é **definir os requisitos de avaliação de qualidade** do sistema **SouGov.br**, com ênfase nas características de **Adequação Funcional** e **Confiabilidade**.  
Este documento apresenta o escopo da avaliação, identifica as partes interessadas e descreve o modelo de qualidade que orientará as próximas etapas da análise.


## 2. Requisitante e Partes Interessadas
- **Requisitante/Gestor:** Ministério da Gestão e Inovação em Serviços Públicos (MGI).  
- **Fornecedor/Desenvolvedor:** Serviço Federal de Processamento de Dados (Serpro).  
- **Usuários finais:** Servidores públicos federais ativos, aposentados, pensionistas e anistiados.  
- **Operadores:** Órgãos de gestão de pessoas da Administração Pública Federal.  
- **Outras partes interessadas:** Órgãos de controle (CGU, TCU), gestores públicos e cidadãos que utilizam os serviços indiretos da plataforma.  


## 3. Descrição do Software
O **SouGov.br** é um aplicativo móvel e uma plataforma web que centralizam funcionalidades de **gestão de pessoas do setor público federal**.  
Entre os principais serviços oferecidos estão:  

- Consulta de contracheque;  
- Solicitação e acompanhamento de benefícios;  
- Atualização cadastral de dados pessoais e funcionais;  
- Prova de vida digital;  
- Gestão de consignações e dependentes;  
- Serviços relacionados à saúde e licenças.  


## 4. Classificação do Tipo de Produto

- **De acordo com a IEEE 1062:**  
  O SouGov.br enquadra-se na categoria **COTS (Commercial Off-The-Shelf Software)**, por ser disponibilizado de forma padronizada a todos os usuários. Nesse contexto, o “fabricante” é o próprio governo, que provê o software como serviço público.  

- **De acordo com Pressman:**  
  Apesar de não ter finalidade comercial direta, o sistema aproxima-se da definição de **Software Comercial**, considerando que busca **automatizar processos sociais e integrar serviços governamentais**, beneficiando grande número de usuários.  


## 5. Propósito da Avaliação e Uso Pretendido
A avaliação tem como propósito verificar se o software atende às necessidades de seus usuários em termos de **adequação funcional** e **confiabilidade**, considerando sua relevância para a gestão pública.  

Os resultados da avaliação visam:  
1. Identificar lacunas funcionais e riscos associados à confiabilidade;  
2. Apoiar o planejamento de evolução e manutenção do sistema;  
3. Contribuir para decisões de melhoria contínua;  
4. Sustentar a transparência e a confiança nos serviços digitais oferecidos pelo governo.  


## 6. Modelo de Qualidade

### 6.1 Adequação Funcional
- **Completude funcional:** verificação da presença de todas as funções necessárias;  
- **Correção funcional:** avaliação da precisão dos resultados produzidos;  
- **Adequação à tarefa:** análise da contribuição das funções para o alcance dos objetivos do usuário.  

### 6.2 Confiabilidade
- **Maturidade:** estabilidade do sistema durante a operação;  
- **Disponibilidade:** capacidade de estar operacional quando necessário;  
- **Tolerância a falhas:** continuidade do funcionamento mesmo diante de falhas parciais;  
- **Recuperabilidade:** capacidade de retornar ao estado operacional após falhas.  


## 7. Critérios de Priorização
- A **adequação funcional** possui prioridade máxima, visto que assegura que as necessidades dos usuários sejam plenamente atendidas.  
- A **confiabilidade** assume papel essencial, considerando o tratamento de **dados pessoais sensíveis** e a execução de **processos críticos** para a administração pública.  


## 8. Escopo, Profundidade e Objetos de Avaliação
- **Escopo:** Aplicativo SouGov (Android/iOS) e versão web.  

- **Profundidade:** Análise funcional e não funcional com foco nas características de adequação funcional e confiabilidade. 

- **Objetos de avaliação:**  
    - Consulta de contracheque;  
    - Atualização cadastral;  
    - Prova de vida digital;  
    - Posse digital;  
    - Notificações.  


## 9. Relação com os Objetivos de Desenvolvimento Sustentável (ODS)

- **ODS 16 — Paz, Justiça e Instituições Eficazes**  
  O SouGov.br contribui para a **transparência**, o **fortalecimento institucional** e a **eficiência** da gestão pública ao digitalizar processos administrativos.  

- **ODS 9 — Indústria, Inovação e Infraestrutura**  
  O sistema promove a **inovação tecnológica no setor público**, ao disponibilizar uma infraestrutura digital acessível e confiável para milhões de cidadãos.  

**Justificativa:** A plataforma representa um avanço na modernização da infraestrutura digital da administração pública, aumentando a eficiência institucional e fortalecendo a confiança social nos serviços governamentais.  

## 10. Conclusão
Esta página da dcumentação apresenta a **Fase 1 da avaliação de qualidade do SouGov.br**, estabelecendo o escopo, as partes interessadas e o modelo de qualidade com foco em **adequação funcional** e **confiabilidade**.  

As etapas subsequentes consistirão em:  
- Definir métricas específicas de avaliação;  
- Selecionar métodos de mensuração;  
- Elaborar planos de teste para validação prática.  

Essas ações possibilitarão a análise aprofundada das características avaliadas e subsidiarão a melhoria contínua do sistema.

---------------------


## Bibliografia

> PRESSMAN, R. S.; MAXIM, B. R. *Engenharia de Software: uma abordagem profissional*. 8. ed. McGraw Hill, 2016.

> SOMMERVILLE, I. *Engenharia de Software*. 10. ed. Pearson, 2019.

> KITCHENHAM, B. *Software Quality: The elusive target*. IEEE Software.

> ORGANIZAÇÃO DAS NAÇÕES UNIDAS (ONU). *Transformando Nosso Mundo: A Agenda 2030 para o Desenvolvimento Sustentável*. ONU, 2015.

> ONU Brasil. *Objetivo 9: Indústria, inovação e infraestrutura*. Disponível em: <https://brasil.un.org/pt-br/sdgs/9>. Acesso em: 27 setembro 2025.

> ONU Brasil. *Objetivo 16: Paz, justiça e instituições eficazes*. Disponível em: <https://brasil.un.org/pt-br/sdgs/16>. Acesso em: 27 setembro 2025.

> Ministério da Gestão e da Inovação em Serviços Públicos (MGI). *SouGov – Aplicativo oficial de serviços do servidor público federal*. Disponível em: <https://www.gov.br/servidor/pt-br/sou-gov>. Acesso em: 27 setembro 2025.

> Governo Federal. *Plataforma Gov.br – Serviços digitais para o cidadão*. Disponível em: <https://www.gov.br>. Acesso em: 27 setembro 2025.

-----------------


## Histórico de versão

<div style="text-align: center; margin: 0; font-size: 14px;">
  Tabela 3: Tabela de Versionamento
</div>

| Versão | Data       | Descrição                             | Autor(a) |
| ------ | ---------- | ------------------------------------- | -------- |
| 1.0    | 28/09/2025 | Versão inicial e incompleta da fase 1 | [Carlos Edurado](https://github.com/CarlosEduardoMendesdeMesquita)   |
| 2.0    | 28/09/2025 | Versão completa da fase 1 | [Laryssa Felix](https://github.com/felixlaryssa) e  [Matheus do Vale](https://github.com/delvale412)  |
| 3.0    | 29/09/2025 | Versão aprimorada da fase 1 | [Laryssa Felix](https://github.com/felixlaryssa)  |

<div style="text-align: center; margin: 0; font-size: small;">
Fonte: 
<a href="https://github.com/AnaBeatrizMassuh">Ana Beatriz Massuh</a>, 
<a href="https://github.com/CarlosEduardoMendesdeMesquita">Carlos Eduardo Mendes</a>, 
<a href="https://github.com/gih7915">Giovana Ferreira</a>, 
<a href="https://github.com/felixlaryssa">Laryssa Felix</a>, 
<a href="https://github.com/vevetin">Laís Soares</a> e 
<a href="https://github.com/delvale412">Matheus Do Vale</a>.
</div>