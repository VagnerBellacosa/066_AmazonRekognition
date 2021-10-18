# O que é Amazon Rekognition?

[PDF](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/rekognition-dg.pdf#what-is)

[RSS](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/rekupdates.rss)



O Amazon Rekognition facilita a adição de análises de imagens e vídeos aos seus aplicativos. Basta fornecer uma imagem ou um vídeo à API do Amazon Rekognition, e o serviço poderá identificar objetos, pessoas, texto, cenas e atividades. Ele também pode detectar qualquer conteúdo inadequado. O Amazon Rekognition também fornece recursos altamente precisos de análise, comparação e pesquisa facial. É possível detectar, analisar e comparar faces para uma grande variedade de casos de uso, incluindo verificação de usuários, catalogação, contagem de pessoas e segurança pública.

O Amazon Rekognition é baseado na mesma tecnologia comprovada e altamente escalável de aprendizado profundo desenvolvida pelos cientistas de visão computadorizada da Amazon para analisar diariamente bilhões de imagens e vídeos. Não requer experiência em aprendizado de máquina para usar. O Amazon Rekognition inclui uma API simples e fácil de usar que pode analisar rapidamente qualquer arquivo de vídeo ou imagem armazenado no Amazon S3. O Amazon Rekognition está sempre aprendendo com novos dados, e estamos sempre adicionando novos rótulos e recursos de comparação facial ao serviço. Para obter mais informações, consulte o .[Perguntas frequentes sobre o Amazon Rekognition](http://aws.amazon.com/rekognition/faqs/).

Entre os casos de uso comuns para usar o Amazon Rekognition estão os seguintes:

- **Bibliotecas de imagens e vídeos pesquisáveis**— O Amazon Rekognition torna imagens e vídeos armazenados pesquisáveis, de maneira que você possa descobrir as cenas e os objetos que aparecem neles.

   

- **Verificação de usuário baseada em face**— O Amazon Rekognition permite que os aplicativos confirmem identidades de usuários comparando a imagem ao vivo com uma imagem de referência.

   

- **Detecção de Equipamentos de Proteção Pessoal**

  O Amazon Rekognition detecta equipamentos de proteção individual (EPI), como capas faciais, capas de cabeça e capas de mão em pessoas em imagens. Você pode usar a detecção de EPI onde a segurança é a nossa maior prioridade. Por exemplo, indústrias como construção, manufatura, saúde, processamento de alimentos, logística e varejo. Com a detecção de EPI, você pode detectar automaticamente se uma pessoa está usando um tipo específico de EPI. Você pode usar os resultados da detecção para enviar uma notificação ou para identificar locais onde avisos de segurança ou práticas de treinamento podem ser aprimorados.

   

- **Sentimento e análise demográfica**— O Amazon Rekognition interpreta expressões emocionais, como felicidade, tristeza ou surpresa, além de informações demográficas, como sexo, em imagens faciais. O Amazon Rekognition pode analisar imagens e enviar os atributos de emoção e informações demográficas ao Amazon Redshift para relatórios periódicos sobre tendências, como locais de armazenamento e cenários semelhantes. Observe que uma previsão de uma expressão emocional é baseada apenas na aparência física da face de uma pessoa. Não é indicativo do estado emocional interno de uma pessoa, e o Rekognition não deve ser usado para fazer essa determinação.

   

- **Pesquisa Facial**— Com o Amazon Rekognition, você pode procurar em imagens, vídeos armazenados e streaming de vídeos por faces que correspondem àquelas armazenadas em um contêiner, conhecido como coleção de faces. Coleção de faces é um índice de faces que você detém e gerencia. A pesquisa de pessoas com base nas faces exige duas etapas principais no Amazon Rekognition:

  1. Indexe as faces.
  2. Pesquise as faces.

   

- **Detecção de conteúdo não seguro**— O Amazon Rekognition pode detectar conteúdo adulto e violento em imagens e vídeos armazenados. Os desenvolvedores podem usar os metadados retornados para filtrar conteúdo inadequado com base nas necessidades de negócio. Além de sinalizar uma imagem com base na presença de conteúdo não seguro, a API também retorna uma lista hierárquica de rótulos com pontuações de confiança. Esses rótulos indicam categorias específicas de conteúdo não seguro, o que permite, assim, uma filtragem granular e um gerenciamento de volumes grandes de conteúdo gerado pelo usuário (UGC). Por exemplo, redes sociais e sites de encontros, plataformas de compartilhamento de fotos, blogs e fóruns, aplicativos para crianças, sites de comércio eletrônico, entretenimento e serviços de publicidade online.

   

- **Reconhecimento de celebridades**— O Amazon Rekognition pode reconhecer celebridades em imagens fornecidas e em vídeos. O Amazon Rekognition pode reconhecer milhares de celebridades em várias categorias, como política, esportes, negócios, entretenimento e mídia.

   

- **Detecção de texto**— O Amazon Rekognition Text in Image permite reconhecer e extrair conteúdo textual das imagens. O Text in Image oferece suporte à maioria das fontes, incluindo aquelas altamente estilizadas. Ele detecta texto e números em diferentes orientações, como aqueles geralmente encontrados em banners e pôsteres. Nos aplicativos de redes sociais e de compartilhamento de imagens, você pode usá-lo para habilitar pesquisas visuais com base em um índice de imagens que contêm as mesmas palavras-chave. Em aplicativos de mídia e entretenimento, é possível catalogar vídeos com base no texto relevante na tela, como anúncios, notícias, placares esportivos e legendas. Por fim, em aplicativos de segurança pública, você pode identificar veículos com base nos números das placas deles nas imagens tiradas por câmeras de rua.

   

- **Rótulos personalizados**— Com o Amazon Rekognition Custom Labels, você pode identificar os objetos e as cenas em imagens que são específicos das necessidades dos seus negócios. Por exemplo, você pode encontrar seu logotipo em postagens de mídias sociais, identificar seus produtos nas prateleiras das lojas, diferenciar plantas saudáveis ou infectadas, classificar as peças de máquina em uma linha de montagem ou detectar personagens animados em vídeos. Para obter mais informações, consulte[O que são os rótulos personalizados do Amazon Rekognition?](https://docs.aws.amazon.com/rekognition/latest/customlabels-dg/what-is.html)no*Guia do desenvolvedor de rótulos personalizados do Amazon Rekognition*.

Alguns dos benefícios de usar o Amazon Rekognition incluem:

- **Integração poderosa de análise de imagem e vídeo em seus aplicativos**— Você não precisa de visão computadorizada nem de conhecimentos em aprendizado profundo para usufruir uma análise de imagem e vídeo confiável no Amazon Rekognition. Com a API, é possível integrar com rapidez e facilidade a análise de imagens e vídeos a qualquer aplicativo de dispositivo conectado, da web ou celular.

   

- **Análise de imagem e vídeo baseada em Deep Learning**— O Amazon Rekognition usa tecnologia de aprendizado profundo para analisar imagens de forma precisa, encontrar e comparar faces em imagens, além de detectar objetos e cenas em imagens e vídeos.

   

- **Análise de imagem escalável**— O Amazon Rekognition permite analisar milhões de imagens, de maneira que você possa organizar grandes quantidades de dados visuais.

   

- **Integração com outros serviços da AWS**— O Amazon Rekognition foi projetado para funcionar perfeitamente com outros serviços da AWS, como Amazon S3 eAWS Lambda. Você pode chamar a API do Amazon Rekognition diretamente do Lambda em resposta a eventos do Amazon S3. Como o Amazon S3 e o Lambda são dimensionados automaticamente em resposta à demanda do aplicativo, você pode criar aplicativos de análise de imagem dimensionáveis, acessíveis e confiáveis. Por exemplo, sempre que uma pessoa chega à sua residência, a câmera da porta pode carregar uma foto do visitante no Amazon S3. Isso aciona uma função do Lambda que usa operações da API do Amazon Rekognition para identificar seu convidado. Você pode executar uma análise diretamente em imagens armazenadas no Amazon S3 sem precisar carregar ou mover os dados. Suporte paraAWS Identity and Access ManagementO (IAM) facilita o controle de acesso seguro a operações da API do Amazon Rekognition. Usando o IAM, você pode criar e gerenciar usuários e grupos da AWS para conceder acesso apropriado aos desenvolvedores e usuários finais.

   

- **Baixo custo**— Com o Amazon Rekognition, você paga apenas pelo número de imagens e vídeos que analisa e pelos metadados de face que armazena. Não há tarifas mínimas nem compromissos antecipados. Comece a usar gratuitamente e economize mais à medida que cresce usando o modelo de definição de preços em níveis do Amazon Rekognition.

## Qualificação do Amazon Rekognition e HIPAA

Este é um serviço qualificado da HIPAA. Para obter mais informações sobre a AWS, a Lei de Portabilidade e Responsabilidade de Seguro de Saúde de 1996 dos EUA (HIPAA) e o uso dos serviços da AWS para processar, armazenar e transmitir informações de saúde protegidas (PHI), consulte [Visão geral da HIPAA](http://aws.amazon.com/compliance/hipaa-compliance/).

## Você é um usuário iniciante do Amazon Rekognition?

Caso seja um usuário iniciante do Amazon Rekognition, recomendamos que você leia as seções a seguir em ordem:

1. **[Como funciona a Amazon Rekognition](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/how-it-works.html)**— Esta seção apresenta diversos componentes do Amazon Rekognition com os quais você trabalha para criar uma experiência completa.
2. **[Conceitos básicos do Amazon Rekognition](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/getting-started.html)**— nesta seção, configure sua conta e teste a API do Amazon Rekognition.
3. **[Como trabalhar com imagens](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/images.html)**— Esta seção fornece informações sobre como usar o Amazon Rekognition com imagens armazenadas em buckets do Amazon S3 e imagens carregadas de um sistema de arquivos local.
4. **[Trabalhar com vídeos armazenados](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/video.html)**— Esta seção fornece informações sobre como usar o Amazon Rekognition com vídeos armazenados em um bucket do Amazon S3.
5. **[Trabalhar com streaming de vídeos](https://docs.aws.amazon.com/pt_br/rekognition/latest/dg/streaming-video.html)**— Esta seção fornece informações sobre como usar o Amazon Rekognition com streaming de vídeos.