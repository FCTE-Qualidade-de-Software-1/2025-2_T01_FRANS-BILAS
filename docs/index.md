# Qualidade de software -  Grupo Fran Bilas Turma 2 (2025.2)

## Sobre o Projeto

Esta página é dedicada à documentação de todos os artefatos criados pelo grupo Fran Bilas no segundo semestre de 2025, na disciplina de Qualidade de Software da Faculdade de Ciências e Tecnologias em Engenharia da Universidade de Brasília (FCTE-UnB).

Frances “Fran” Bilas foi uma das seis mulheres programadoras originais do ENIAC, o primeiro computador eletrônico digital de grande escala do mundo. Nascida em 2 de março de 1922, na Filadélfia, e falecida em 18 de julho de 2012, ela estudou matemática e física no Chestnut Hill College, onde recebeu uma bolsa de estudos. Durante a Segunda Guerra Mundial, Fran foi selecionada para integrar a equipe que programava o ENIAC, responsável por calcular trajetórias balísticas e resolver problemas científicos complexos que antes eram feitos manualmente. Seu trabalho consistia em traduzir cálculos abstratos em operações compreensíveis para o hardware do computador, em uma época em que a contribuição feminina na tecnologia era pouco reconhecida. Apesar da falta de visibilidade durante décadas, Fran Bilas deixou um legado pioneiro na história da computação e hoje é lembrada como uma das primeiras mulheres programadoras do mundo, tendo inclusive sido homenageada com sistemas de computação de alto desempenho que carregam seu nome.

<div style="text-align: center;">
  <img src="assets/images/Frances.png" alt="SouGov.br" style="max-width: 100%; height: auto;">
</div>
<div style="text-align: center; margin: 0; font-size: 14px;">
  Imagem 1: Frances Bilas
</div>

## Sistema Escolhido

O **SouGov.br** é uma plataforma voltada aos servidores públicos federais (ativos, inativos e pensionistas) e oferece informações relacionadas apenas à vida funcional desse público. Com isso, a plataforma objetiva reduzir a burocracia nos processos da vida financeira e trabalhista.
O sistema oferece  algumas funcionalidades como **cadastro, autenticação, envio de documentos, emissão de relatórios, comprovante de rendimentos, consultas e afastamentos, contracheques**, garantindo acessibilidade, transparência e segurança das informações.

A plataforma foi **escolhida pelo grupo Fran Bilas**, após os membros sugerirem diferentes plataformas open-source e realizar-se uma votação em enquete para decidir qual seria a mais adequada para o projeto.

<div style="text-align: center;">
  <img src="assets/images/sougov.png" alt="SouGov.br" style="max-width: 100%; height: auto;">
</div>
<div style="text-align: center; margin: 0; font-size: 14px;">
  Imagem 2: Logo SouGov
</div>

<details>
  <summary>Versão SouGov Desktop</summary>
  Versão X.X — Versão desktop utilizada ao longo desta avaliação.
</details>

<details>
  <summary>Versão SouGov Mobile</summary>
  Versão X.X — Versão mobile utilizada ao longo desta avaliação.
</details>

-------

**Características de Qualidade Analisadas do SouGov.br (ISO/IEC 25010):**

As características de qualidade apresentadas a seguir foram escolhidas pelos membros do grupo **Fran Bilas**, como foco principal para a avaliação do sistema.  
A seleção foi realizada com base na relevância de cada característica para medir o desempenho do SouGov.br em relação às necessidades dos usuários e à confiabilidade do sistema.


<font size="3"><p style="text-align: center">Tabela 1: Características de Qualidade Escolhidas</p></font>

| Característica          | Subcaracterística          | Exemplo no SouGov.br                                                      | Impacto para o Usuário                                               |
|-------------------------|---------------------------|--------------------------------------------------------------------------|----------------------------------------------------------------------|
| Adequação Funcional     | Completude                | Todas as funcionalidades de cadastro, autenticação e envio de documentos estão disponíveis | Usuário consegue realizar todas as tarefas administrativas sem limitações |
|                         | Correção                  | Os relatórios gerados refletem corretamente os dados inseridos pelos usuários | Usuário recebe informações precisas, aumentando confiança no sistema |
|                         | Adequação                 | Formulários e dashboards apresentados de forma intuitiva e organizada    | Usuário realiza tarefas rapidamente, sem esforço excessivo           |
| Confiabilidade          | Maturidade                | Sistema com histórico de baixa ocorrência de erros durante acessos simultâneos | Reduz frustração e interrupções, garantindo continuidade do trabalho |
|                         | Tolerância a Falhas       | Caso haja falha em um módulo, outras funcionalidades continuam operando  | Evita perda de dados e mantém serviços essenciais disponíveis        |
|                         | Recuperabilidade          | Sistema permite restauração rápida de sessões e dados após falhas técnicas | Minimiza impacto de falhas, protegendo o usuário e suas informações  |
|                         | Disponibilidade           | Plataforma disponível 24/7 para acesso de órgãos e cidadãos              | Usuário pode utilizar o sistema quando necessário, aumentando confiança |

<div style="text-align: center; margin: 0; font-size: small;">
Fonte: 
<a href="https://github.com/AnaBeatrizMassuh">Ana Beatriz Massuh</a>, 
<a href="https://github.com/CarlosEduardoMendesdeMesquita">Carlos Eduardo Mendes</a>, 
<a href="https://github.com/gih7915">Giovana Ferreira</a>, 
<a href="https://github.com/felixlaryssa">Laryssa Felix</a>, 
<a href="https://github.com/vevetin">Laís Soares</a> e 
<a href="https://github.com/delvale412">Matheus Do Vale</a>.
</div>


**Objetivos de Desenvolvimento Sustentável (ODS) Escolhidos:**

Os **Objetivos de Desenvolvimento Sustentável (ODS)** foram estabelecidos pela Organização das Nações Unidas (ONU) para orientar ações globais em prol de um futuro mais sustentável, inclusivo e justo.  
Eles abrangem questões sociais, econômicas e ambientais, servindo como referência para projetos que buscam gerar impacto positivo na sociedade.

Para este projeto, o grupo optou pelos seguintes ODS:

* **ODS 9 — Indústria, Inovação e Infraestrutura:** O SouGov promove inovação tecnológica no setor público e cria infraestrutura digital acessível e confiável para milhões de usuários.
.
* **ODS 16 — Paz, Justiça e Instituições Eficazes:**O SouGov fortalece a transparência, a confiança e a eficiência das instituições públicas ao digitalizar processos de gestão de pessoas.

---

## Equipe

<div style="text-align: center; margin: 0; font-size: 14px;">
  Tabela 2: Integrantes do grupo Fran Bilas
</div>

<div style="display: flex; justify-content: center;">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/AnaBeatrizMassuh">
          <img src="https://avatars.githubusercontent.com/u/87723296?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Ana Beatriz Massuh</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/CarlosEduardoMendesdeMesquita">
          <img src="https://avatars.githubusercontent.com/u/58157127?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Carlos Eduardo Mendes</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/gih7915">
          <img src="https://avatars.githubusercontent.com/u/134656592?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Giovana Ferreira</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="http://github.com/felixlaryssa">
          <img src="https://avatars.githubusercontent.com/u/143897458?v=4&size=64" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Laryssa Felix</b></sub>
        </a>
      </td>
    </tr>
    <tr>
      <td></td> 
      <td align="center">
        <a href="http://github.com/vevetin">
          <img src="https://avatars.githubusercontent.com/u/92321749?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Laís Soares</b></sub>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/delvale412">
          <img src="https://avatars.githubusercontent.com/u/87723296?v=4" width="100" height="100" style="border-radius: 50%; object-fit: cover;" alt=""/>
          <br /><sub><b>Matheus Do Vale</b></sub>
        </a>
      </td>
      <td></td> 
    </tr>
  </table>
</div>
<div style="text-align: center; margin: 0; font-size: small;">
Fonte: 
<a href="https://github.com/AnaBeatrizMassuh">Ana Beatriz Massuh</a>, 
<a href="https://github.com/CarlosEduardoMendesdeMesquita">Carlos Eduardo Mendes</a>, 
<a href="https://github.com/gih7915">Giovana Ferreira</a>, 
<a href="https://github.com/felixlaryssa">Laryssa Felix</a>, 
<a href="https://github.com/vevetin">Laís Soares</a> e 
<a href="https://github.com/delvale412">Matheus Do Vale</a>.
</div>


## Histórico de Versões

<div style="text-align: center; margin: 0; font-size: 14px;">
  Tabela 3: Tabela de Versionamento
</div>


| Versão | Data       | Descrição                              | Autor(a) |
| :----: | :--------: | :------------------------------------: | :------: |
| 1.0    | 28/09/2025 | Criação e inclusão do README do projeto | [Laryssa Felix](https://github.com/felixlaryssa) |
| 2.0    | 29/09/2025 | Adição de tabela e imagens | [Laryssa Felix](https://github.com/felixlaryssa) |

<div style="text-align: center; margin: 0; font-size: small;">
Fonte: 
<a href="https://github.com/AnaBeatrizMassuh">Ana Beatriz Massuh</a>, 
<a href="https://github.com/CarlosEduardoMendesdeMesquita">Carlos Eduardo Mendes</a>, 
<a href="https://github.com/gih7915">Giovana Ferreira</a>, 
<a href="https://github.com/felixlaryssa">Laryssa Felix</a>, 
<a href="https://github.com/vevetin">Laís Soares</a> e 
<a href="https://github.com/delvale412">Matheus Do Vale</a>.
</div>



