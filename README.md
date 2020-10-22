# Hackathon-PUCGO 

# Equipe Asgardianos!
Membros: Amanda Kelly Rrodrigues Cândido, Giuilianni dos Santos Oliveira, Grasielle Costa Santos, Wemerson Moura Viana e Willgnner Fereira Santos.

# Título do projeto:
Extensão Tradutor de Libras.

# Público alvo:
Deficientes auditivos.

# Descrição do problema:
Uma das ferramentas mais utilizadas de acessibilidade é a legenda, no YouTube por exemplo existe a legenda automática porém, não está acessível uma fermenta de tradução automática dessa legenda para libras, para entender um vídeo o usuário surdo teria que copiar a transcrição de legendas, editar e depois entrar com esse texto no VLibras por exemplo, que é um tradutor de texto para libras grátis. Uma pesquisa rápida mostra que 70% dos surdos no Brasil não entendem a língua portuguesa, o que dificulta muito mais esse processo, podemos concluir que a integração dessa classe de deficiência é bem baixa nessa rede social e em outras cuja o foco é audiovisual.

# Descrição da proposta de solução:
Uma forma de amenizar esse déficit é a criação de uma extensão do Google Chrome, que faça uma ponte entre a legenda de um vídeo no YouTube com o VLibras automaticamente, descartando dessa forma a necessidade de tradução manual, permitindo que o surdo possa assistir ao vídeo ao mesmo tempo que a tradução de libras é exibida na tela também.

# Descrição do produto:
A extensão usa dois API's, um para pegar a legenda do vídeo e outro para traduzir para Libras, funcionando da seguinte forma:
Extensão (entrada) = id do vídeo; 
API_Legenda (entrada) = vídeo;
API_Legenda (saída) = arquivo de texto com a legenda; 
// é feita a formatação desse texto, retirando tudo que não for para ser traduzido;
API_tradutor (entrada) = arquivo de texto formatado;
API_tradutor(saída) = tradução em forma de animação em um pop-up;
//é exibida a saída;
API_Legenda : Youtube Transcriptor -https://developers.google.com/youtube/v3/docs/captions
API_Tradução: VLibras - https://softwarepublico.gov.br/gitlab/vlibras/vlibras-api

# Linguagem utilizada no projeto:
Javascript e HTML.

# Plataformas usadas:
Visual Studio e Google extension.

# Como utilizar?
1. Vá no google extension (chrome://extensions/);
2. Instale a extensão "Tradutor de Libras 1.0";
3. Abra um vídeo no YouTube (https://www.youtube.com/);
4. Ative a legenda automática;
5. Dê play no vídeo e clique na extensão;
6. Assista à tradução da legenda simultânea a exibição do vídeo.

# Requisitos pré estabelicidos:
Ter extensão "Libras 1.0" instalado.

# Descrição do VLibras:
A Suíte VLibras consiste em um conjunto de ferramentas computacionais de código aberto, responsável por traduzir conteúdos digitais (texto, áudio e vídeo) para a Língua Brasileira de Sinais - LIBRAS, tornando computadores, dispositivos móveis e plataformas Web acessíveis para pessoas surdas.
Fonte: vlibras.gov.br

Como funciona: O VLibras é uma suíte de ferramentas utilizadas na tradução automática do Português para a Língua Brasileira de Sinais. É possível utilizar essas ferramentas tanto no computador Desktop quanto em smartphones e tablets.

O VLibras é uma ferramenta aberta, de distribuição livre, e desenvolvida para melhorar o acesso a informação das pessoas surdas brasileiras.

![image](https://user-images.githubusercontent.com/73254098/96868875-07bc1e00-1445-11eb-8a88-256e8ff6f578.png)

# Imagem ilustrando a extensão sendo utilizada no navegador Google Chrome:

![image](https://user-images.githubusercontent.com/73254098/96866012-13a5e100-1441-11eb-96c1-40e5912bc0c3.png)

# Demonstração da extensão sendo utilizada:

![image](https://user-images.githubusercontent.com/73254098/96866833-44d2e100-1442-11eb-88f0-4de6e283ab6a.png)

![image](https://user-images.githubusercontent.com/73254098/96870364-2fac8100-1447-11eb-8c72-5546ea55c941.png)





























