Tópicos do Exame

Manipulação de Valores de Data, Hora, Texto, Numérico e Booleano

- Use primitivos e classes wrapper.
- Avalie expressões aritméticas e booleanas, usando a API Math e aplicando regras de precedência, conversões de tipo e casting.
- Manipule texto, incluindo blocos de texto, usando as classes String e StringBuilder.
- Manipule objetos de data, hora, duração, período, instantâneo e fuso horário, incluindo horário de verão, usando a API de data e hora.

Controlando o Fluxo do Programa

- Crie construções de controle de fluxo do programa, incluindo if/else, instruções e expressões switch, loops e instruções break e continue.

Usando Conceitos Orientados a Objetos em Java

- Declare e instancie objetos Java, incluindo objetos de classe aninhada, e explique o ciclo de vida do objeto, incluindo criação, reatribuição de referências e coleta de lixo.
- Crie classes e registros e defina e use campos e métodos de instância e estáticos, construtores e inicializadores de instância e estáticos.
- Implemente métodos sobrecarregados, incluindo métodos var-arg.
- Entenda escopos de variáveis, aplique encapsulamento e crie objetos imutáveis. Use inferência de tipo de variável local.
- Implemente herança, incluindo tipos abstratos e selados, bem como classes de registro. Sobrescreva métodos, incluindo os da classe Object. Implemente polimorfismo e diferencie entre tipo de objeto e tipo de referência. Realize conversão de tipo de referência, identifique tipos de objeto usando o operador instanceof e correspondência de padrão com o operador instanceof e a construção switch.
- Crie e use interfaces, identifique interfaces funcionais e utilize métodos privados, estáticos e padrão da interface.
- Crie e use tipos enum com campos, métodos e construtores.

Tratando Exceções

- Trate exceções usando try/catch/finally, try-with-resources e blocos multi-catch, incluindo exceções personalizadas.

Trabalhando com Arrays e Coleções

- Crie arrays, List, Set, Map e coleções Deque e adicione, remova, atualize, recupere e ordene seus elementos.

Trabalhando com Streams e Expressões Lambda

- Use objetos Java e Streams primitivos, incluindo expressões lambda implementando interfaces funcionais, para criar, filtrar, transformar, processar e ordenar dados.
- Realize decomposição, concatenação e redução, bem como agrupamento e particionamento em streams sequenciais e paralelos.

Empacotando e Implantando Código Java

- Defina módulos e exponha conteúdo do módulo, incluindo por reflexão, e declare dependências do módulo, defina serviços, fornecedores e consumidores.
- Compile código Java, crie jars modulares e não modulares, imagens de tempo de execução e implemente migração para módulos usando módulos não nomeados e automáticos.

Gerenciando a Execução Concorrente de Código

- Crie threads de plataforma e virtuais. Use objetos Runnable e Callable, gerencie o ciclo de vida da thread e use diferentes serviços Executor e API concorrente para executar tarefas.
- Desenvolva código seguro para threads, usando mecanismos de bloqueio e API concorrente.
- Processe coleções Java concorrentemente e utilize streams paralelos.

Usando a API Java I/O

- Leia e escreva dados de console e arquivo usando streams de E/S.
- Serialize e desserialize objetos Java.
- Construa, percorra, crie, leia e escreva objetos Path e suas propriedades usando a API java.nio.file.

Implementando Localização
- Implemente localização usando locales e pacotes de recursos. Analise e formate mensagens, datas, horas e números, incluindo valores de moeda e porcentagem.

Assuma o seguinte:

- Pacotes e instruções de importação ausentes: Se os exemplos de código não incluírem instruções de pacote ou importação, e a pergunta não se referir explicitamente a essas instruções ausentes, então assuma que todo o código de exemplo está no mesmo pacote ou que existem instruções de importação para suportá-lo.
- Nomes de caminhos de arquivo ou diretório para classes: Se uma pergunta não declarar os nomes de arquivo ou locais de diretório das classes, então assuma um dos seguintes, o que permitirá que o código compile e execute:
  - Todas as classes estão em um arquivo
  - Cada classe está contida em um arquivo separado e todos os arquivos estão em um diretório
- Quebras de linha não intencionais: O código de exemplo pode ter quebras de linha não intencionais. Se você vir uma linha de código que parece ter sido embrulhada e isso cria uma situação em que o embrulho é significativo (por exemplo, um literal de cadeia de caracteres entre aspas foi embrulhado), assuma que o embrulho é uma extensão da mesma linha e que a linha não contém um retorno de carro rígido que causaria uma falha de compilação.
- Fragmentos de código: Um fragmento de código é uma pequena seção de código-fonte apresentado sem seu contexto. Assuma que todo o código de suporte necessário existe e que o ambiente de suporte suporta totalmente a compilação e execução corretas do código mostrado e seu ambiente omitido.
- Comentários descritivos: Tome comentários descritivos, como "setter e getters vão aqui", no valor nominal. Assuma que o código correto existe, compila e executa com sucesso para criar o efeito descrito.

Os candidatos também são esperados para:

- Entender os conceitos básicos da API Java Logging.
- Usar anotações como Override, FunctionalInterface, Deprecated, SuppressWarnings e SafeVarargs.
- Usar genéricos, incluindo caracteres curinga.