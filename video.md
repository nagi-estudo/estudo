# Resumo de video que vi

## Como AI usa teu computador(Linux)

O terminal é uma interface poderosa para interagir com o sistema operacional, essencial para desenvolvedores, já que ferramentas de IA e servidores (majoritariamente Linux/Unix) operam por meio desses comandos nativos. A manipulação de arquivos e pastas pode ser realizada inteiramente via linha de comando sem necessidade de interface gráfica.

Principais conceitos e comandos:

Navegação e Listagem: O comando pwd identifica o diretório atual de trabalho, ls lista o conteúdo de pastas (o parâmetro -la exibe detalhes e arquivos ocultos), e cd alterna entre diretórios, permitindo navegação absoluta ou relativa.
Gerenciamento de Arquivos e Pastas: mkdir cria diretórios (o parâmetro -p cria subpastas recursivamente), touch cria arquivos vazios, cp copia arquivos e mv move arquivos entre pastas.
Leitura e Escrita: cat exibe o conteúdo de arquivos. O comando echo escreve texto em arquivos, utilizando > para sobrescrever o conteúdo e >> para adicionar (append) ao final.
Permissões e Segurança: chmod ajusta as permissões de leitura, escrita e execução (essencial para rodar scripts como .sh), enquanto sudo permite executar comandos com privilégios de superusuário. O comando rm remove arquivos, e rm -rf força a remoção recursiva de diretórios e seu conteúdo.
Busca e Processamento de Texto: O grep é utilizado para buscar padrões ou termos específicos em arquivos ou diretórios, com suporte a busca recursiva e insensibilidade a maiúsculas/minúsculas. O sed permite a substituição de textos de forma automatizada.
Automação: O operador de pipe (|) conecta o resultado de um comando como entrada para outro, permitindo encadear operações complexas, como listar, filtrar e processar dados em um único fluxo.
O conhecimento desses fundamentos é um diferencial importante para o trabalho diário com infraestrutura, automação de processos e debugging de sistemas.
