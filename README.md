# Ecommerce-Django
Ecommerce Feito com Django HTML CSS JS e BOOTSTRAP4
Esta é a documentação do projeto "gobuds", um projeto de comércio eletrônico desenvolvido usando o framework Django.

Descrição dos Diretórios e Arquivos Principais

    projeto: Pasta raiz do projeto.

    gobuds: Pasta principal do aplicativo Django "gobuds".

        asgi.py: Arquivo de configuração para a interface ASGI (Asynchronous Server Gateway Interface).

        settings.py: Arquivo de configuração principal do projeto Django, onde são definidas as configurações globais.

        urls.py: Arquivo de configuração de URLs do projeto, onde são definidos os padrões de URL e suas correspondentes views.

        wsgi.py: Arquivo de configuração para a interface WSGI (Web Server Gateway Interface).

    media: Pasta onde os arquivos de mídia são armazenados, como imagens enviadas pelos usuários.
        produto_imagens: Subpasta onde as imagens dos produtos são armazenadas. As imagens são organizadas por ano e mês.

    produto: Aplicativo "produto".

        templatetags: Pasta que contém as tags de template personalizadas para o aplicativo "produto".
            omfilters.py: Arquivo que contém as tags de template personalizadas para o aplicativo "produto".

        templates: Pasta que contém os templates HTML relacionados ao aplicativo "produto".
            produto: Subpasta específica do aplicativo "produto" que contém os templates HTML relacionados aos produtos.

        models.py: Arquivo que contém as definições de modelos (classes) do aplicativo "produto".

        views.py: Arquivo que contém as views (funções ou classes) do aplicativo "produto".

        urls.py: Arquivo de configuração de URLs específico do aplicativo "produto".

        admin.py: Arquivo de configuração do Django Admin para o aplicativo "produto".

        forms.py: Arquivo que contém as definições de formulários do aplicativo "produto".

        apps.py: Arquivo de configuração do aplicativo "produto".

    perfil: Aplicativo "perfil".

        templates: Pasta que contém os templates HTML relacionados ao aplicativo "perfil".
            perfil: Subpasta específica do aplicativo "perfil" que contém os templates HTML relacionados aos perfis.

        models.py: Arquivo que contém as definições de modelos (classes) do aplicativo "perfil".

        views.py: Arquivo que contém as views (funções ou classes) do aplicativo "perfil".

        urls.py: Arquivo de configuração de URLs específico do aplicativo "perfil".

        admin.py: Arquivo de configuração do Django Admin para o aplicativo "perfil".

        forms.py: Arquivo que contém as definições de formulários do aplicativo "perfil".

        apps.py: Arquivo de configuração do aplicativo "perfil".

    pedido: Aplicativo "pedido".

        templatetags: Pasta que contém as tags de template personalizadas para o aplicativo "pedido".
            omfilters.py: Arquivo que contém as tags de template personalizadas para o aplicativo "pedido".

        templates: Pasta que contém os templates HTML relacionados ao aplicativo "pedido".
            pedido: Subpasta específica do aplicativo "pedido" que contém os templates HTML relacionados aos pedidos.

        models.py: Arquivo que contém as definições de modelos (classes) do aplicativo "pedido".

        views.py: Arquivo que contém as views (funções ou classes) do aplicativo "pedido".

        urls.py: Arquivo de configuração de URLs específico do aplicativo "pedido".

        admin.py: Arquivo de configuração do Django Admin para o aplicativo "pedido".

    template: Pasta que contém os templates e arquivos estáticos compartilhados entre os aplicativos.

        parciais: Pasta que contém os templates HTML parciais (reutilizáveis) do projeto.

        static: Pasta que contém os arquivos estáticos (CSS, JavaScript, etc.) do projeto.

            assets: Pasta que contém os recursos estáticos, como bibliotecas de terceiros (Bootstrap, Font Awesome, etc.).

            logo: Subpasta que contém o logotipo do projeto.

        base.html: Arquivo HTML base que serve como o layout principal para outros templates.

        404.html: Arquivo HTML para a página de erro 404 (página não encontrada).

    utils: Pasta que contém arquivos de utilidade para o projeto.

        utils.py: Arquivo que contém funções utilitárias para o projeto.

        validacpf.py: Arquivo que contém uma função para validação de CPF.

    manage.py: Arquivo de gerenciamento do projeto Django.

Esta documentação oferece uma visão geral da estrutura e organização do projeto "gobuds" e de seus principais diretórios e arquivos. Utilize-a como referência para navegar e entender a estrutura do projeto.
