# Linux Commands

Esse repositorio se reserva a amarzena comandos para se utilizar dentro do linux e auxiliar a atividades de adiministração e condiguração de um servidor ou projetos.


## Navegação:

- **cd** ( _current directory_ ) : use para navegar entre diretorios

    Exemplo: 
        
        cd

        cd <path>

        cd .. (retorna a o diretio anterior)

        cd ~ (te lança para seu diretrio raiz)

- **ls** ( _list directory_) : use para lista arquivos e pastas no diretorio atual

    Exemplos: 
    
        ls 

        ls <path>

        ls -a <path> ( lista todas as pastas e arquivo incluindo os ocultos)

        ls -l <paht> ( lista todos as pastas e arquivos mostrando a permição dos mesmos )

- **pwd** ( _print working directory_): use para mostra seu diretorio atual

    Exemplo:

        pwd


## Gerenciamento de Arquivos e Pasta:

- **mkdir** ( _make directory_ ) : use para criar novos diretórios.

    Exemplo:

        mkdir <folder_name> (cria um diretório com o nome especificado)


- **touch** ( _create file_ ) : use para criar novos arquivos vazios ou atualizar o timestamp de arquivos existentes.

    Exemplo:

        touch <file_name>.<extension> (cria um arquivo vazio)

        touch arquivo1.txt arquivo2.txt (cria múltiplos arquivos)

- **rm** ( _remove_ ) : use para remover arquivos ou diretórios.

    Exemplo:

        rm <nome_do_arquivo> (remove um arquivo)

        rm -r <nome_do_diretorio> (remove um diretório e seu conteúdo recursivamente)

        rm -f <nome_do_arquivo> (remove arquivos forçadamente, sem pedir confirmação)

        rm -rf <nome_do_diretorio> (remove diretórios e seu conteúdo forçadamente, sem pedir confirmação)

- **cp** ( _copy_ ) : use para copiar arquivos ou diretórios.

    Exemplo:

        cp <arquivo_origem> <arquivo_destino> (copia um arquivo para outro local)

        cp -r <diretorio_origem> <diretorio_destino> (copia um diretório e seu conteúdo recursivamente)

        cp -i <arquivo_origem> <arquivo_destino> (copia com confirmação interativa antes de sobrescrever)

- **mv** ( _move_ ) : use para mover ou renomear arquivos e diretórios.

    Exemplo:

        mv <origin_ folder> <destiny_folder>  (move ou renomeia um diretório)

        mv <origin_file> <destiny_file> (move ou renomeia um arquivo)




