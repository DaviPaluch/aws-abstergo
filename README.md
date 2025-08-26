<div class="relatorio">
  <h1>Relatório Técnico – Adoção de Serviços AWS</h1>

  <p>
    <strong>Data:</strong> 25/07/2025<br>
    <strong>Empresa:</strong> Abstergo Industries<br>
    <strong>Responsável:</strong> Davi Paluch
  </p>

  <hr>

  <h2>1. Contextualização</h2>
  <p>
    Com o objetivo de reduzir custos imediatos e modernizar a infraestrutura de TI, a Abstergo Industries iniciou um projeto de migração parcial para serviços em nuvem da Amazon Web Services (AWS). O estudo e a execução foram conduzidos por Davi Paluch, com foco na escolha de três soluções estratégicas capazes de substituir recursos locais de alto custo e otimizar processos internos.
  </p>

  <hr>

  <h2>2. Estrutura do Projeto</h2>
  <p>
    A implementação foi organizada em <strong>três fases</strong>, cada uma direcionada a um desafio específico da empresa. A seguir, descrevem-se as soluções aplicadas:
  </p>

  <h3>Fase 1 – Armazenamento de Arquivos com Amazon S3</h3>
  <ul>
    <li><strong>Objetivo:</strong> substituir servidores físicos destinados a backups e arquivos internos.</li>
    <li><strong>Situação anterior:</strong> a empresa mantinha infraestrutura própria de armazenamento, o que implicava gastos elevados com energia, manutenção e expansão de capacidade.</li>
    <li><strong>Solução adotada:</strong> migração de todo o repositório para o <strong>Amazon S3</strong>, aproveitando sua escalabilidade, durabilidade e modelo de pagamento por uso.</li>
    <li>
      <strong>Resultados obtidos:</strong>
      <ul>
        <li><strong>Economia:</strong> eliminação da infraestrutura local dedicada a armazenamento.</li>
        <li><strong>Benefício adicional:</strong> acesso seguro e versionamento automático, além de replicação entre regiões para maior resiliência.</li>
      </ul>
    </li>
  </ul>

  <hr>

  <h3>Fase 2 – Automação de Processos com AWS Lambda</h3>
  <ul>
    <li><strong>Objetivo:</strong> reduzir desperdício de recursos computacionais em tarefas rotineiras.</li>
    <li><strong>Situação anterior:</strong> atividades como geração de relatórios e processamento de dados eram executadas em servidores que permaneciam ociosos na maior parte do tempo.</li>
    <li><strong>Solução adotada:</strong> migração dessas rotinas para o <strong>AWS Lambda</strong>, permitindo a execução de código apenas quando necessário, sem dependência de servidores ativos.</li>
    <li>
      <strong>Resultados obtidos:</strong>
      <ul>
        <li><strong>Economia:</strong> cobrança restrita ao tempo de execução das funções, evitando custos com infraestrutura inativa.</li>
        <li><strong>Benefício adicional:</strong> escalabilidade automática e maior velocidade na implementação de melhorias.</li>
      </ul>
    </li>
  </ul>

  <hr>

  <h3>Fase 3 – Escalabilidade Dinâmica com Auto Scaling (Amazon EC2)</h3>
  <ul>
    <li><strong>Objetivo:</strong> otimizar o uso de instâncias de computação em momentos de variação de tráfego.</li>
    <li><strong>Situação anterior:</strong> para evitar falhas durante picos de acesso, a empresa mantinha várias instâncias EC2 ativas, mesmo quando a demanda era baixa.</li>
    <li><strong>Solução adotada:</strong> implementação de <strong>Auto Scaling</strong>, permitindo o ajuste automático da quantidade de instâncias conforme a carga de trabalho.</li>
    <li>
      <strong>Resultados obtidos:</strong>
      <ul>
        <li><strong>Economia:</strong> redução no número de instâncias em períodos de baixa utilização.</li>
        <li><strong>Benefício adicional:</strong> garantia de alta disponibilidade com custos proporcionais à demanda real.</li>
      </ul>
    </li>
  </ul>

  <hr>

  <h2>3. Considerações Finais</h2>
  <p>
    A introdução dos serviços <strong>Amazon S3</strong>, <strong>AWS Lambda</strong> e <strong>Auto Scaling</strong> trouxe ganhos imediatos para a Abstergo Industries, tanto em redução de custos quanto em melhoria da eficiência operacional. A empresa passou a contar com um ambiente mais flexível, seguro e preparado para escalar conforme suas necessidades.
  </p>
  <p>
    Recomenda-se a continuidade da exploração de soluções AWS e a análise periódica de novos serviços que possam potencializar ainda mais a competitividade da empresa.
  </p>

  <hr>

  <h2>4. Documentos Complementares</h2>
  <ul>
    <li>Procedimento de migração para Amazon S3</li>
    <li>Funções otimizadas para AWS Lambda</li>
    <li>Estratégia configurada de Auto Scaling</li>
  </ul>

  <hr>

  <p>
    <strong>Assinatura do Responsável:</strong><br>
    Davi Paluch
  </p>
</div>