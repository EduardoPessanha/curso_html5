    <!DOCTYPE html> => tag de configuração inicial -> Informa ao navegador que é um site em HTML5 

    <html lang="pt-br"" => Informando a linguagem do documento HTML5

    <head" => Área de cabeçalho  do documento HTML5 - faz as configurações comportamentais da página

    <meta charset="UTF-8"> <!-- Define o padrão UTF-8 para os caracteres, para resolver o problema de acentuação-->
    <title>Tudo sobre Google Glass</title> <!-- Define o título da página -->

    <!-- Formatação de texto:
     
        
    A partir da versão 5, o HTML parou de "prestar atenção" na formatação e passou a focar na SEMÂNTICA, que é o significado das coisas.
    E a CSS que é uma outra tecnologia, vai se focar na formatação e estílo da página.
    tag de formatação do HTML5 :
    "<b>" => negrito
    "<i>" => itálico - indica para o navegador que simplismente você quer a letra inclinada.
    "<em>" => enfase - além da letra inclinada informa aos navegadores que se quer enfatizar determinado termo / expressão.
    "<del>" => riscado - indica um texto que foi deletado

    "<sup> texto...</sup>" => gera um resultado sobrescrito
    "<sub> texto...</sub>" => gera um resultado subscrito
    
    "<pre>=>  tag para representar pré-formatação (todos os "espaços, tabulações e enter" serão considerados)
    "<code></code>" => tag para formatar códigos
    </pre>" 

    "<span>" => tag utilizada para formatar pequenos trechos de texto, utilizada para inserir códigos CSS:
        Exemplo:
        <span style="text-decoration: underline;"> texto... </span> => texto sublinhado
        <span style="text-decoration: overline;"> texto... </span> => linha acima do texto
        <span style="text-decoration: line-though;"> texto... </span> => texto riscado
        <span style="font-weight: bold;"> texto... </span> => texto em negrito
            Os valores para esse parâmetro são:
            normal => texto sem formatação
            bold => texto em negrito
            bolder => texto em negrito mais intenso
            valores na faixa de 100 a 1000 => define a intensidade do negrito

    Alinhamento:

        <h1 style="text-align: center;"> => alinha ao centro
        <h1 style="text-align: right;"> => alinha a direita
        <h1 style="text-align: left;"> => alinha a esquerda
        <p style="text-align: justify;"> => alinha justificado
        <p style="text-ident: valor;"> => faz a identação de um paragrafo de acordo com o valor especificado


    tag depreciada no HTML5:
    "<u>" => sublinhado
    "<s>" => riscado

    -->
    
    <style>
    p {
        text-align: justify; 
        text-indent: 50px;        
    }
    </style>

    </head>

    <body> => Área do corpo do documento HTML5 
    
    <!-- As tag <div> criam áreas de divisão: -->
    
    <div id="interface">

        <header id="cabecalho"> <!-- a tag "<header>" é uma tag para criar / delimitar a área de cabeçalhos -->

            <hgroup> <!-- a tag "<hgroup>" serve para agrupa os titulos -->

                <h1>Google Glass</h1>
                <h2>A revolução do Google está chegando</h2>

            </hgroup>

            <img src="_imagens/glass-oculos-preto-peq.png" alt=""> <!-- [AQUI ENTRA UMA FOTO] A tag "<img>" é para "image" ou imagens.  O parâmetro principal dessa tag é o "src" que significa "source" ou origem-->
            

            Menu Principal
            - Home
            - Especificações
            - Fotos
            - Multimídia
            - Fale conosco

        </header>

        <hgroup>
            
            <h3>Tecnologia > Inovações</h3>
            <h1>Saiba tudo sobre o Google Glass</h1>
            <h2>por Gustavo Guanabara</h2>
            <h3>Atualizado em 23/Abril/2013</h3>

        </hgroup>
    <!-- 
        <span style="font-weight: 400;"> texto com "font-weight" com valor de 400... </span><br/>
        <span style="font-weight: 600;"> texto com "font-weight" com valor de 600... </span><br>
        <span style="font-weight: 1000;"> texto com "font-weight" com valor de 1000... </span> -->

        <!--No HTML o ENTER e vários espaçõs são ignorados pelo navegador.
        Para quebrar linhas usa-se a tag "<br/>" (break roll) e para gerar espaços: "&nbsp;" (non-breaking space ou espaço sem quebra).  Organizando os parágrafos: -->
        
        <!--- No HTML% podemos fazer a ifenização ou quebra de palavras forçada, usando a tag "<wbr>" (Word Breaker ou quebra de palavras), para criar os hífens devemos usar "&shy;" (short Hyphen) ao invéz do "<wbr>"-->

        <h2>O que é</h2>

        <p>O <b><i>Google Glass</i></b> é um <span style="font-weight: 1000;">acessório em forma de óculos que possibilita a interação dos usuários</span> com diversos conteúdos em realidade aumentada. Também chamado de <i>Project Glass</i>, o eletrônico é capaz de tirar fotos a partir de comandos de voz, enviar mensagens instantâneas e realizar vídeo&shy;con&shy;ferên&shy;cias. Seu lançamento está previsto para 2014, e seu preço deve ser de US$ 1,5 mil. Atualmente o <em>Google Glass</em> encontra-se em fase de testes e já possui um vídeo totalmente gravado com o dispositivo. Além disso, a companhia de buscas registrou novas patentes anti-furto e de desbloqueio de tela para o acessório.</p>

        [AQUI ENTRA UMA FOTO]

        <h1>Data de lançamento</h1>

        <p>Não há uma data específica e oficial para o dispositivo ser lançado, ainda. Pode ser que ele esteja disponível em demonstrações a partir de 2013, mas seu lançamento para as lojas fica para, pelo menos, 2014.</p>

        <h1>Especificações Técnicas</h1>

        Tabela Técnica do Google Glass Mar/2013

        Tela:Resolução equivalente a tela de 25"
        Camera: 5MP para fotos / 720p para vídeos
        Conectividade: Wi-Fi/ Bluetooth
        Memória Interna: 12GB

        <h1>Como funciona</h1>

        <p>De acordo com fontes próximas do Google, os óculos vão contar com uma pequena tela de LCD ou AMOLED na parte
        superior e em frente aos olhos do usuário. Com o uso de uma câmera e GPS, você pode se situar, assim como
        selecionar opções com o movimento da cabeça</p>
        
        <h1>O que você pode fazer com o Google Glasses</h1>

        <p>O vídeo de divulgação do Google mostra que você pode se transformar em uma espécie de “super-<wbr/>humano”, já que o aparelho pode indicar a quantos metros você está de seu destino, se o metrô está aberto ou fechado, mostrar o clima, agenda e até mesmo permitir que você marque encontros apenas com comandos de voz.</p>

        [AQUI ENTRA UM VÍDEO]

        <h1>Outras Notícias</h1>
        <h2>Vídeo mais recente</h2>

        [AQUI ENTRA UM VÍDEO]

        <h2>Novidades no Glass</h2>

        <p>O Google enfim revelou as especificações completas do Google Glass, e com ele uma surpresa ainda inédita no
        mercado: a gigante das buscas usará um sistema de áudio baseado na transdução por condução. Através das hastes
        dos óculos, o som será transmitido para o ouvido do usuário por meio de microvibrações em determinados ossos de
        sua cabeça, sem usar nenhum tipo de alto-falante.</p>

        <p>Além da surpresa do áudio, a tela montada a frente do olho do usuário também chamou atenção. Serão 640 x 360
        pixels de resolução que, em proporção, equivaleria a um monitor de 25 polegadas de alta definição colocado a 2,5
        metros de distância do espectador.</p>

        <p>&copy; Copyright 2013 - by Gustavo Guanabara
        Facebook | Twitter</p>

    </div>

    </body>

    </html>