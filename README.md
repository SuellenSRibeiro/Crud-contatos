# Sistema de Cadastro de Contatos Virtual

Este é um sistema de gerenciamento de contatos desenvolvido em C# com ASP.NET Core. O sistema permite que os usuários criem, visualizem, atualizem e excluam contatos. Além disso, possui recursos de autenticação, controle de acesso e envio de emails.

## Funcionalidades
#### Cadastro de contatos com nome, email e celular.
#### Autenticação de usuários com login e senha.
#### Controle de acesso restrito a determinadas áreas do sistema (admin e usuário padrão).
#### Envio de emails para redefinição de senha.
#### Interface de usuário amigável e responsiva.

## Tecnologias Utilizadas
#### C# (Linguagem de Programação)
#### ASP.NET Core (Framework Web)
#### Entity Framework Core (ORM para Acesso ao Banco de Dados)
#### HTML, CSS e JavaScript (Front-end)
v SQL Server (Banco de Dados Relacional)
#### Visual Studio (IDE de Desenvolvimento)

## Código para funcionar a paginação e a tradução dos componentes de busca

<pre>
  
    $('#table-contatos').DataTable({
        "ordering": true,
        "paging": true,
        "searching": true,
        "oLanguage": {
            "sEmptyTable": "Nenhum registro encontrado na tabela",
            "sInfo": "Mostrar _START_ at&eacute; _END_ de _TOTAL_ registros",
            "sInfoEmpty": "Mostrar 0 at&eacute; 0 de 0 Registros",
            "sInfoFiltered": "(Filtrar de _MAX_ total registros)",
            "sInfoPostFix": "",
            "sInfoThousands": ".",
            "sLengthMenu": "Mostrar _MENU_ registros por pagina",
            "sLoadingRecords": "Carregando...",
            "sProcessing": "Processando...",
            "sZeroRecords": "Nenhum registro encontrado",
            "sSearch": "Pesquisar",
            "oPaginate": {
                "sNext": "Proximo",
                "sPrevious": "Anterior",
                "sFirst": "Primeiro",
                "sLast": "Ultimo"
            },
            "oAria": {
                "sSortAscending": ": Ordenar colunas de forma ascendente",
                "sSortDescending": ": Ordenar colunas de forma descendente"
            }
        }
    });
  
</pre>
