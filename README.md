# Computação Distribuida

Computação Distribuida é um modelo de computação em que várias máquinas, também conhecidas como nós ou servidores, trabalham de forma coordenada para resolver um problema ou realizar uma tarefa, compartilhando recursos e dados. Ao invés de depender de um único computador para realizar um processamento, a carga de travalho é dividida entre vários sistemas, o que permite maior capacidade de processamento, escalabilidade e eficiência.

## Características de Computação Distrubuída:

1. Processamento paralelo: As tarefas são divididas e executadas simultaneamente em vários nós.
2. Escabilidade: À medida que a demanda por recursos cresce, é possivel adicionar mais máquinas ao sistema, sem necessidade de reestruturar todo o sistema.
3. Resiliência: Se um nó falhar, outros nós podem continuar a execução, aumentando a disponibilidade e a confiabilidade do sistema.
4. Compartilhamento de recursos: Diferentes nós podem compartilhar dados, memória e outras ferramentas para melhorar o desempenho do sistema.

## Como a Computação Distriuída Ajuda na Engenharia de Dados?

A computação distriuída tem um papel fundamental na engenharia de dados, especialmente quando lidamos com grandes volumes de dados ou a necessidade de processamentos complexos e rápidos.
Ela permite que as tarefas de manipulação de dados sejam divididas e executadas de forma eficiente, resultando em uma análise mais rápida e escalável.

#### 1. Processamento de Grandes Volumes de Dados (Big Data):

A principal vantagem da computação distribuída na engenharia de dados é a capacidade de processar grandes volumes de dados. Quando os dados são grandes demais para serem processados em um único servidor ou máquina, a computação distribuída divide o trabalho entre múltiplos nós, permitindo processar Big Data de forma eficiente.

#### Exemplo:

  - Apache Hadoop e Apache Spark são dois exemplos de frameworks de computação distribuída populares na engenharia de dados, que permitem processar e analisar grandes volumes de dados em clusters distribuídos de máquinas.

#### 2. Escalabilidade:

À medida que os dados aumentam, as soluções de computação distribuída podem ser escaladas facilmente, adicionando mais nós (máquinas) para lidar com a carga adicional. Isso é especialmente importante em ambientes de Big Data e Data Lakes, onde o volume de dados pode crescer rapidamente.

#### Exemplo:

- Se você tem uma grande quantidade de dados de transações financeiras, você pode aumentar o número de nós no cluster para processar essas transações de maneira mais rápida e eficiente.

#### 3. Processamento em Tempo Real (Stream Processing):

A computação distribuída também é essencial para o processamento em tempo real de dados. Ela pode ser usada para processar dados à medida que são gerados, em vez de processá-los em lote.
Isso é importante para aplicações que exigem decisões rápidas com base em dados em tempo real.

#### Exemplo:

 - Apache Kafka e Apache Flink são ferramentas baseadas em computação distribuída para processar dados em tempo real, como fluxos de dados de redes sociais, transações bancárias ou monitoramento de sensores.

#### 4. Tolerância a Falhas:

A computação distribuída melhora a tolerância a falhas, já que os dados e os processos são distribuídos por várias máquinas. Se um nó falhar, o processo pode ser retomado em outro nó, garantindo que o sistema como um todo continue funcionando de forma eficiente, mesmo em caso de falhas parciais.

#### Exemplo:

 - Em um ambiente de Data Warehousing, se um servidor falha durante o carregamento de dados, outro servidor pode assumir e continuar o processo, evitando que o trabalho seja perdido ou interrompido.

#### 5. Maior Desempenho e Eficiência:

Quando tarefas de processamento de dados são divididas entre múltiplos nós, a carga de trabalho é reduzida para cada máquina individual, resultando em menor tempo de processamento e maior eficiência.

#### Exemplo:

 - No processamento de grandes volumes de logs ou dados de sensores, a computação distribuída pode dividir a análise entre múltiplos servidores, o que acelera o tempo necessário para extrair insights e tomar decisões.

## Exemplos de Ferramentas e Tecnologias Usadas em Computação Distribuida para Engenharia de Dados:

- Apache Hadoop: Framework de código aberto que permite o processamento e armazenamento de grandes conjuntos de dados em um cluster de máquinas. Ele usa o conceito de MapReduce para distribuir e processar dados de maneira paralela.

- Apache Spark:  Framework para processamento de dados em grande escala, que pode ser usado tanto para processamento em lote quanto em tempo real.  O Spark é amplamente utilizado para análise de dados distribuída e é mais rápido que o Hadoop para certos tipos de tarefas devido à sua capacidade de manter dados na memória.

- Apache Kafka: Plataforma de streaming distribuído que permite processar fluxos de dados em tempo real.

- Google BigQuery: Data warehouse totalmente gerenciado e escalável da Google que usa computação distribuída para consultar e analisar grandes volumes de dados em segundos.

- Amazon EMR (Elastic MapReduce): Serviço da Amazon que facilita o uso de frameworks de computação distribuída como Hadoop e Spark para processar dados em grande escala.

### Resumo:

A computação distribuida permite que a engenharia de dados lide com desafios de escalabilidade, processamento de grandes volumes de dados, e análise em tempo real, proporcionando sistemas mais rápidos, eficientes e resilientes. Ao distribuir o processamento de dados entre várias máquinas, ela ajuda a trasnformar grandes quantidades de dados em insights valiosos de maneira mais eficiente e confiável.
