# Challenge Sprint 3 - COMPUTAÇÃO DISTRIBUÍDA & CLOUD COMPUTING

**Título do Challenge:** SPI / METAINDÚSTRIA - SMART ROBOTICS
**Turma:** 4ECS | **Ano:** 2025
**Período para Entrega:** 05/09/2025 - 30/09/2025
**Status:** NOTA: 85
**Cabeçalho Original:** COMPUTAÇÃO DISTRIBUÍDA & CLOUD COMPUTING - Sérgio Ricardo Rota NOTA: 85

## 1. Enunciado e Instruções do Professor

1) (3,0 pontos) A execução de duas transações, Ti e Tj, em um banco de dados, é serializável se produz o mesmo resultado para a execução serial de qualquer intercalação de operações dessas transações (Ti seguida de Tj ou Tj seguida de Ti). O uso de bloqueios (locks) é uma maneira de se garantir que transações concorrentes sejam serializáveis. A tabela abaixo mostra informações relativas a três transações, T1, T2 e T3, que operam sobre dois dados compartilhados, A e B, e utilizam bloqueios para controle de concorrência.

Com relação às transações T1, T2 e T3, considere as afirmações a seguir:

I - O conjunto (T1, T2) não é serializável, e há o perigo de ocorrer deadlock durante a execução concorrente dessas transações.

II - O conjunto (T1, T3) não é serializável, mas não há o perigo de ocorrer deadlock durante a execução concorrente dessas transações.

III - O conjunto (T2, T3) é serializável, e não há o perigo de ocorrer deadlock durante a execução concorrente dessas transações.

Sobre as afirmações acima, assinale a opção correta.

(A) Apenas uma afirmação está correta.

(B) Apenas as afirmações I e II estão corretas.

(C) Apenas as afirmações I e III estão corretas.

(D) Apenas as afirmações II e III estão corretas.

(E) Todos as afirmações estão corretas.

 

2) (2,0 pontos) Uma transação é dita distribuída quando ativa operações em diferentes servidores, físicos ou virtuais. Neste cenário, a técnica de virtualização de hardware consiste em emular um computador no qual a camada de software é executada sem que detalhes do computador físico e de seus componentes sejam expostos. Em um ambiente de computação distribuída, a técnica pode ser útil para que o sistema operacional e os softwares do usuário sejam executados em uma máquina virtual com características permanentes, em conformidade com o que foi projetado, verificado e validado, mesmo que um computador físico diferente seja empregado. Com base nesse contexto, é correto afirmar que:

(A) Adquirir licenças de software do usuário no volume de uma licença para cada computador físico, o que favorece a economia de licenças, pois softwares em máquinas virtuais não correspondem a cópias extras.

(B) Utilizar um computador com capacidade extra de comunicação de dados para favorecer o seu desempenho, pois um sistema distribuído em máquinas virtuais consome mais recursos de rede do que o mesmo sistema distribuído sendo executado em um computador físico.

(C) Utilizar um computador com capacidade extra de memória principal para favorecer o seu desempenho, pois um sistema distribuído em máquinas virtuais requer mais espaço de memória física do que o mesmo sistema distribuído sendo executado em um computador físico.

(D) Adquirir computadores físicos com processadores similares para favorecer a compatibilidade, pois sistemas distribuídos fortemente acoplados compartilham recursos intensamente, funcionando de forma mais eficiente em máquinas virtuais quando os computadores físicos são compatíveis.

(E) Adquirir dispositivos de armazenamento físico com, pelo menos, o dobro da capacidade do dispositivo virtual a ser usado a fim de favorecer a disponibilidade, pois os sistemas operacionais da máquina virtual e da máquina física devem ter espaço equivalente de dados para que exista o mapeamento direto entre o dispositivo virtual e o dispositivo físico.

 

3) (3,0 pontos) A tecnologia blockchain é um sistema transacional distribuído porque organiza e registra transações em uma rede de computadores (nós) que compartilham uma cópia do livro-razão digital de forma descentralizada, tornando-o seguro, transparente e resistente à alteração. Em vez de uma autoridade central, os próprios participantes da rede validam e armazenam os dados, arquitetura em pares (peer-to-peer), que são agrupados em blocos criptograficamente ligados numa cadeia imutável. Por definição, um sistema distribuído é aquele no qual os componentes de hardware ou software, localizados em computadores interligados em rede, comunicam-se e coordenam suas ações apenas enviando mensagens entre si. Com base na definição apresentada e nos conceitos básicos de sistemas distribuídos, assinale a opção correta:

(A) A existência de um relógio físico local sincronizado com um relógio global é o que permite aos usuários de um sistema distribuído trocarem mensagens de forma coordenada.

(B) A falha de um componente em um sistema distribuído peer-to-peer causa a interrupção de todos os demais componentes até o seu retorno.

(C) O compartilhamento dos recursos distribuídos entre computadores interligados por uma rede é possível desde que os dispositivos sejam homogêneos em termos de hardware e software.

(D) A adição de novos dispositivos em um sistema distribuído para atender a uma demanda temporária ou crescente está ligada à característica de escalabilidade do sistema.

(E) A possibilidade de vários clientes acessarem de forma concorrente um mesmo recurso compartilhado em um servidor é resultado do alto nível de transparência do sistema.

 

4) (2,0 pontos) Os sistemas distribuídos consistem em múltiplos componentes de software que se comunicam e que cooperam entre si para realizar tarefas complexas. Um padrão arquitetural comumente utilizado em sistemas transacionais distribuídos é o de microsserviços, o qual divide o sistema em componentes independentes e escaláveis, cada um executando sua própria funcionalidade específica. Essa abordagem facilita a manutenção, o teste e a escalabilidade do sistema como um todo. Em relação a esse tema, qual dos seguintes benefícios é associado à arquitetura de microsserviços em sistemas transacionais distribuídos?

(A) Capacidade de escalabilidade.

(B) Garantia de consistência de dados.

(C) Melhor desempenho de processamento.

(D) Menor consumo de recursos de hardware.

(E) Redução da complexidade de comunicação entre os componentes.

