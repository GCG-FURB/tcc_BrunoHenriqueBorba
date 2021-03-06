# Anotações da reuniões

## 2021-01-21

.. escreveu por e-mail ..  
Boa noite professor, tudo bem?  

Esse semestre começo a primeira parte do meu TCC (TCC I).  

Não tenho exatamente uma ideia formada, mas estou pensando em aproveitar que tenho boa parte dos dispositivos da maçã (Mac, iPhone, Watch, bem fã boy infelizmente) e fazer algo que utilize alguma tecnologia que a própria Apple disponibiliza, seja em linguagem de programação ou em hardware. Andei vendo algumas coisas sobre o Lidar, mas não sei até que ponto pode ser algo proveitoso ou o quanto eu conseguiria explorar desse hardware. Por esse motivo resolvi procurar você.  

Podemos marcar algo para alinhar esses pontos?  

Agradeço desde já!  
Att, Bruno  

## 2021-02-25

Respondi a msg e-mail para conversar sobre orientação de TCC.  

## 2021-03-12

Acho que possou e acabei esquencendo de responder as suas dúvidas anteriores.  
Famosas 4 perguntas (por quê, o que, como e para quem).  
Pode ser destinado aos desenvolvedores de aplicações que usaram o LIDAR.  
O seu estudo pode esclarecer dúvidas, expor limites, etc. da sua real usabilidade.  

Pensei em envolver a questão da mobilidade do sensor por exemplo. O fato de você ter sensores desse tipo vindo em equipamentos móveis como tablets ou smartphones, e focar em algo aplicado mais para os usuários no dia a dia mesmo.  
Sim, é que acho que na época que definimos o título ainda não tinhas certeza queiras conseguir comprar o iPhone com LIDAR. Mas agora podemos trazer a palavra mobilidade para o seu título. E sim, pode aparecer algo, mas não sei se seria no título, talvez nos objetivos com "utilizar ambientes não estruturados" ... algo como ambiente não controlado.  

### Acessibilidade usando LIDAR com atuadores de orientação

Numa pesquisa rápida, achei um vídeo (https://youtu.be/8Au47gnXs0w) onde a pessoa usa o lidar do iPad para auxiliar num deslocamento, totalmente vendado. O sensor faz a detecção do ambiente, e uma espécie de “motor” vibra para indicar
as direções que pessoa deveria seguir. É uma ajuda para a acessibilidade.  
Muito interessante ...  
Já orientei um TCC que tínhamos uma caixa com uma "cela braile" e com motores de eletroimas.  
Eu tenho esta caixa, e tenhos alguns motores aqui.  
Poderíamos pensar em algo deste tipo.  
O TCC: <http://dsc.inf.furb.br/arquivos/tccs/monografias/2019_1_jader-antonio-tomelin_monografia.pdf>  

Esse seria o caminho? Como a gente pode focar em explorar esse sensor?  
Eheh, achei a ideia muito boa.  
Poderias usar como base o TCC acima.  

#### 2021-05-03

### Defesa Pré-projeto

[Anotações de defesa do Pré-projeto](./tcc_BrunoHenriqueBorba_2021-05-03_PreProjeto_Defesa.md)

## 2021-09-13

Estava com dificuldades para entender como usar o Buffer de Profundidade.  
Fiz a figura para tentar entender sua dúvida.  
![VisaoGeral](VisaoGeral.drawio.svg "VisaoGeral")  

## 2021-09-20

Problemas com uso das Threads. Arrumou, alguns processos forma para o 2a plano.  
Colocar no artigo comentar os tipos de vibrações.  
O Apple Watch ... usar como retorno tátil.  
Tentar identificar objetos ... ML para reconhecer objetos.  

## 2021-09-27

Fez o treinamento de objetos.  
Reconheceu a cadeira, e não portas.  

DataSet pronto  

Comentou que um exemplo pronto deixa um label virual no objeto real. Deve usar ancoras do ARKit.  
Disse para usar este ...  

## 2021-10-04

Conseguiu usar o exmeplo pronto de label.  
Já tem como dar um "tempo" de vida para as labels.  
Melhorar o processo atual.  
Fazer rotina para substituir o "clicar na tela".  
Ter o retorno de distância e posição de obejtos.  
Usar as "mesh" de obejtos já reconhecidos pelo Frameowrk.  

## 2021-10-18

Artigo, começar a escrever.  
Trabalhou pouco .. uns testes com Apple Watch.  
Pedi para focar no uso do LiDAR e ARKit Ancora.  

## 2021-10-25

RealyKit x ARKit
ScenView X ARView (LiDAR)
ARView (LiDAR)
ARView <https://developer.apple.com/documentation/arkit>
<https://maxxfrazer.medium.com/realitykit-component-entity-bc59acb60728>

Exemplos:
 - detecção de planos / reconstrução da mesh: <https://developer.apple.com/documentation/arkit/content_anchors/visualizing_and_interacting_with_a_reconstructed_scene>  Tocando num objeto ele tenta identiicar qual objeto é.  
 - tentando ter mais inforamções sobre a BBox do objeto (mas acha que nào usa o LiDAR): <https://developer.apple.com/documentation/arkit/content_anchors/scanning_and_detecting_3d_objects>  

## 2021-11-10

Conseguiu usar os recursos dos Frameworks do ARTKit e SceneKit para usar os recursos do LiDAR.  
Pedi para manter o "modo debug", mostrando informações na tela para ajudar o desenvolvedor.  
Disse que a referência ao objeto real é feita pela âncora virtual, e que as vezes fica "próxima" ao objeto real. No caso a âncora "busca" um plano para se fixar.  
Disse que por ter muitas mensagens pensou em usar o som espacial para tentar orientar o usuário. O som espacial pode ser colocado na âncora, assim o som sairia do objeto real num espaço virtual.  

## 2021-12-13

Defesa do TCC  
[tcc_BrunoHenriqueBorba_2021-12-13_defesa_video.mp4](tcc_BrunoHenriqueBorba_2021-12-13_defesa_video.mp4)  
[tcc_BrunoHenriqueBorba_2021-12-13_defesa_ata.pdf](tcc_BrunoHenriqueBorba_2021-12-13_defesa_ata.pdf)  
[tcc_BrunoHenriqueBorba_2021-12-13_defesa_Aurelio.pdf](tcc_BrunoHenriqueBorba_2021-12-13_defesa_Aurelio.pdf)  
Prof. Miguel não fez anotações no texto do artigo, só as considerações na defesa durante sua fala.  
