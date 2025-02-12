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

        ls <path> | grep <input_text> ( use para lista com o filtro de texto )

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


## Vizualização e Edição de arquivos: 

- **cat** ( _concatenate _ ): use para exibir o conteúdo de um arquivo no terminal.

    Exemplo:

        cat <arquivo> (exibe o conteúdo do arquivo)

        cat arquivo1.txt arquivo2.txt (exibe o conteúdo de vários arquivos em sequência)

        cat -n <arquivo> (exibe o conteúdo do arquivo com numeração de linhas)

        cat > novo_arquivo.txt (cria um novo arquivo e permite digitar o conteúdo diretamente no terminal; pressione Ctrl+D para salvar e sair)

- **tail** ( _tail end_ ): use para exibir as últimas linhas de um arquivo.

    Exemplo:

      tail <arquivo> (exibe as últimas 10 linhas do arquivo)

      tail -n 20 <arquivo> (exibe as últimas 20 linhas do arquivo)

      tail -f <arquivo> (exibe as últimas linhas do arquivo em tempo real, útil para monitorar logs)

- **head** ( _head_ ): use para exibir as primeiras linhas de um arquivo.

    Exemplo:

        head <arquivo> (exibe as primeiras 10 linhas do arquivo)

        head -n 15 <arquivo> (exibe as primeiras 15 linhas do arquivo)

- **less** ( _less_ ): use para visualizar arquivos grandes de forma paginada.

    Exemplo:

        less <arquivo> (abre o arquivo para visualização paginada; use as teclas de seta para navegar, e pressione "q" para sair)

        less +F <arquivo> (abre o arquivo e segue novas linhas em tempo real, semelhante ao `tail -f`)

- **more** ( _more_ ): use para visualizar arquivos grandes de forma paginada (similar ao less, mas com menos funcionalidades).

    Exemplo:

        more <arquivo> (abre o arquivo para visualização paginada; pressione "Enter" para avançar e "q" para sair)

- **grep** ( _global regular expression print_ ): use para pesquisar texto dentro de arquivos.

    Exemplo:

      grep "texto" <arquivo> (procura a palavra "texto" no arquivo)

      grep -i "texto" <arquivo> (procura a palavra "texto" ignorando maiúsculas e minúsculas)

      grep -r "texto" <diretorio> (procura a palavra "texto" em todos os arquivos do diretório, recursivamente) 

- **diff** ( _difference _ ): use para comparar dois arquivos e mostrar as diferenças.

    Exemplo:

        diff <arquivo1> <arquivo2> (mostra as diferenças entre os dois arquivos)

        diff -u <arquivo1> <arquivo2> (mostra as diferenças em formato unificado)

- ### Nano:

- ### Vim:

## Controle de Permissão:

## Gerenciamento de Usuarios:

## Execução de Arquivos:

## FireWall:

## SystemCTL:

## Crontab:


curl

wget

