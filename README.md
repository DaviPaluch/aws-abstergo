<div class="flex w-full flex-col gap-1 empty:hidden first:pt-[3px]"><div class="markdown prose dark:prose-invert w-full break-words dark markdown-new-styling">

<h1 data-start="228" data-end="274">Relatório Técnico – Adoção de Serviços AWS</h1>
<p data-start="276" data-end="364"><strong data-start="276" data-end="285">Data:</strong> 25/07/2025<br data-start="296" data-end="299">
<strong data-start="299" data-end="311">Empresa:</strong> Abstergo Industries<br data-start="331" data-end="334">
<strong data-start="334" data-end="350">Responsável:</strong> Davi Paluch</p>
<hr data-start="366" data-end="369">
<h2 data-start="371" data-end="395">1. Contextualização</h2>
<p data-start="397" data-end="781">Com o objetivo de reduzir custos imediatos e modernizar a infraestrutura de TI, a Abstergo Industries iniciou um projeto de migração parcial para serviços em nuvem da Amazon Web Services (AWS). O estudo e a execução foram conduzidos por Davi Paluch, com foco na escolha de três soluções estratégicas capazes de substituir recursos locais de alto custo e otimizar processos internos.</p>
<hr data-start="783" data-end="786">
<h2 data-start="788" data-end="816">2. Estrutura do Projeto</h2>
<p data-start="818" data-end="972">A implementação foi organizada em <strong data-start="852" data-end="866">três fases</strong>, cada uma direcionada a um desafio específico da empresa. A seguir, descrevem-se as soluções aplicadas:</p>
<h3 data-start="974" data-end="1032"><strong data-start="978" data-end="1030">Fase 1 – Armazenamento de Arquivos com Amazon S3</strong></h3>
<ul data-start="1033" data-end="1691">
<li data-start="1033" data-end="1122">
<p data-start="1035" data-end="1122"><strong data-start="1035" data-end="1048">Objetivo:</strong> substituir servidores físicos destinados a backups e arquivos internos.</p>
</li>
<li data-start="1123" data-end="1291">
<p data-start="1125" data-end="1291"><strong data-start="1125" data-end="1147">Situação anterior:</strong> a empresa mantinha infraestrutura própria de armazenamento, o que implicava gastos elevados com energia, manutenção e expansão de capacidade.</p>
</li>
<li data-start="1292" data-end="1446">
<p data-start="1294" data-end="1446"><strong data-start="1294" data-end="1314">Solução adotada:</strong> migração de todo o repositório para o <strong data-start="1353" data-end="1366">Amazon S3</strong>, aproveitando sua escalabilidade, durabilidade e modelo de pagamento por uso.</p>
</li>
<li data-start="1447" data-end="1691">
<p data-start="1449" data-end="1474"><strong data-start="1449" data-end="1472">Resultados obtidos:</strong></p>
<ul data-start="1477" data-end="1691">
<li data-start="1477" data-end="1558">
<p data-start="1479" data-end="1558"><strong data-start="1482" data-end="1495">Economia:</strong> eliminação da infraestrutura local dedicada a armazenamento.</p>
</li>
<li data-start="1561" data-end="1691">
<p data-start="1563" data-end="1691"><strong data-start="1566" data-end="1590">Benefício adicional:</strong> acesso seguro e versionamento automático, além de replicação entre regiões para maior resiliência.</p>
</li>
</ul>
</li>
</ul>
<hr data-start="1693" data-end="1696">
<h3 data-start="1698" data-end="1754"><strong data-start="1702" data-end="1752">Fase 2 – Automação de Processos com AWS Lambda</strong></h3>
<ul data-start="1755" data-end="2436">
<li data-start="1755" data-end="1842">
<p data-start="1757" data-end="1842"><strong data-start="1757" data-end="1770">Objetivo:</strong> reduzir desperdício de recursos computacionais em tarefas rotineiras.</p>
</li>
<li data-start="1843" data-end="2011">
<p data-start="1845" data-end="2011"><strong data-start="1845" data-end="1867">Situação anterior:</strong> atividades como geração de relatórios e processamento de dados eram executadas em servidores que permaneciam ociosos na maior parte do tempo.</p>
</li>
<li data-start="2012" data-end="2179">
<p data-start="2014" data-end="2179"><strong data-start="2014" data-end="2034">Solução adotada:</strong> migração dessas rotinas para o <strong data-start="2066" data-end="2080">AWS Lambda</strong>, permitindo a execução de código apenas quando necessário, sem dependência de servidores ativos.</p>
</li>
<li data-start="2180" data-end="2436">
<p data-start="2182" data-end="2207"><strong data-start="2182" data-end="2205">Resultados obtidos:</strong></p>
<ul data-start="2210" data-end="2436">
<li data-start="2210" data-end="2326">
<p data-start="2212" data-end="2326"><strong data-start="2215" data-end="2228">Economia:</strong> cobrança restrita ao tempo de execução das funções, evitando custos com infraestrutura inativa.</p>
</li>
<li data-start="2329" data-end="2436">
<p data-start="2331" data-end="2436"><strong data-start="2334" data-end="2358">Benefício adicional:</strong> escalabilidade automática e maior velocidade na implementação de melhorias.</p>
</li>
</ul>
</li>
</ul>
<hr data-start="2438" data-end="2441">
<h3 data-start="2443" data-end="2515"><strong data-start="2447" data-end="2513">Fase 3 – Escalabilidade Dinâmica com Auto Scaling (Amazon EC2)</strong></h3>
<ul data-start="2516" data-end="3139">
<li data-start="2516" data-end="2612">
<p data-start="2518" data-end="2612"><strong data-start="2518" data-end="2531">Objetivo:</strong> otimizar o uso de instâncias de computação em momentos de variação de tráfego.</p>
</li>
<li data-start="2613" data-end="2766">
<p data-start="2615" data-end="2766"><strong data-start="2615" data-end="2637">Situação anterior:</strong> para evitar falhas durante picos de acesso, a empresa mantinha várias instâncias EC2 ativas, mesmo quando a demanda era baixa.</p>
</li>
<li data-start="2767" data-end="2915">
<p data-start="2769" data-end="2915"><strong data-start="2769" data-end="2789">Solução adotada:</strong> implementação de <strong data-start="2807" data-end="2823">Auto Scaling</strong>, permitindo o ajuste automático da quantidade de instâncias conforme a carga de trabalho.</p>
</li>
<li data-start="2916" data-end="3139">
<p data-start="2918" data-end="2943"><strong data-start="2918" data-end="2941">Resultados obtidos:</strong></p>
<ul data-start="2946" data-end="3139">
<li data-start="2946" data-end="3031">
<p data-start="2948" data-end="3031"><strong data-start="2951" data-end="2964">Economia:</strong> redução no número de instâncias em períodos de baixa utilização.</p>
</li>
<li data-start="3034" data-end="3139">
<p data-start="3036" data-end="3139"><strong data-start="3039" data-end="3063">Benefício adicional:</strong> garantia de alta disponibilidade com custos proporcionais à demanda real.</p>
</li>
</ul>
</li>
</ul>
<hr data-start="3141" data-end="3144">
<h2 data-start="3146" data-end="3174">3. Considerações Finais</h2>
<p data-start="3176" data-end="3494">A introdução dos serviços <strong data-start="3202" data-end="3215">Amazon S3</strong>, <strong data-start="3217" data-end="3231">AWS Lambda</strong> e <strong data-start="3234" data-end="3250">Auto Scaling</strong> trouxe ganhos imediatos para a Abstergo Industries, tanto em redução de custos quanto em melhoria da eficiência operacional. A empresa passou a contar com um ambiente mais flexível, seguro e preparado para escalar conforme suas necessidades.</p>
<p data-start="3496" data-end="3661">Recomenda-se a continuidade da exploração de soluções AWS e a análise periódica de novos serviços que possam potencializar ainda mais a competitividade da empresa.</p>
<hr data-start="3663" data-end="3666">
<h2 data-start="3668" data-end="3701">4. Documentos Complementares</h2>
<ul data-start="3703" data-end="3828">
<li data-start="3703" data-end="3746">
<p data-start="3705" data-end="3746">Procedimento de migração para Amazon S3</p>
</li>
<li data-start="3747" data-end="3785">
<p data-start="3749" data-end="3785">Funções otimizadas para AWS Lambda</p>
</li>
<li data-start="3786" data-end="3828">
<p data-start="3788" data-end="3828">Estratégia configurada de Auto Scaling</p>
</li>
</ul>
<hr data-start="3830" data-end="3833">
<p data-start="3835" data-end="3881"><strong data-start="3835" data-end="3865">Assinatura do Responsável:</strong><br data-start="3865" data-end="3868">
Davi Paluch</p>
</div></div>