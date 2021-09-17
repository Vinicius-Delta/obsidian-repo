
O tópico presente tópico irá aprofundar cada uma das etapas, indicando os procedimentos aplicados, além dos resultados e discussões obtidos.

## 4.1 - Identificação dos sinais
Durante esse primeiro momento, foram realizadas pesquisas teóricas para contextualizar sobre o problema da violência policial e sobre soluções tecnologias emergentes que estão testadas ou poderão ser adotadas no futuro pelas forças policiais. 

### 4.1.1 - Uso da internet
Cada vez mais as tecnologias digitais têm sido integradas ao dia-a-dia da população urbana, sendo utilizadas nos mais diversos aparelhos e com diversas finalidades. Graças a ampliação das redes sem fio, vivemos constantemente conectados, interagindo com pessoas e sistemas através de interfaces físicas e digitais.

[..] mas resta o desafio de garantir o acesso pleno a este serviço – estabelecido em 2015 pela ONU como um dos pontos principais para o atingimento do Objetivo de Desenvolvimento Sustentável número 9 (SDG 9):

		Aumentar significativamente o acesso às tecnologias de informação e comunicação e se empenhar para oferecer acesso universal e a preços acessíveis à internet nos países menos desenvolvidos, até 2020. (Disponível em brasil.un.org)

Segundo a pesquisa "TIC Domicílios 2019", cerca de 77% da população urbana do Brasil possui acesso à Internet. Sendo que este dado tem apresentado em crescimento, tendo em vista a adesão de 5,2 milhões de domicílios a mais, em relação ao ano anterior (2018). (CGI.BR, 2020, p. 23-24).

A adesão da população comum aos dispositivos com acesso à Internet foi facilitada pelo trabalho de comunicação das interfaces gráficas, que realizam a intermediação entre a máquina e o usuário. A princípio, o uso dos computadores era restrito para os pesquisadores da área de computação, pois toda interação era feita através de código. A partir da atuação dos designers, a interação com os sistemas digitais foi repensada, abrindo espaço para novas maneiras de input e output, e assim  originou-se o chamado design de interação. (PINHEIRO, 2007, p. 12-13)

Com a evolução do design de interação, foram criados dispositivos com interfaces mais fáceis de usar e assim, a Internet se tornou acessível para um número maior de usuários. Foi através desse avanço que os sistemas ganharam aparência e se tornaram inteligíveis, como afirma Rafael Cardoso (2012, p. 114):

		A internet jamais teria alcançado sua repercussão atual se não fosse pela elaboração das interfaces gráficas que dão sustentação à world wide web. Para a vasta maioria dos usuários, a rede é a www; e esta é um sistema de documentos interligados, o qual exige que cada documento tome alguma configuração visual e assuma uma aparência inteligível. Em suma, do ponto de vista de sua difusão social, a rede é um fenômeno tanto de design quanto de informática. 

O impacto da evolução desse aparato tecnológico pode ser observado em diversas áreas do comportamento humano, sobretudo nas relações humanas. Graças a capacidade dessa ferramenta de aproximar pessoas e reduzir distâncias, surgiram novas formas de se comunicar com conhecidos e desconhecidos, e que se tornaram fenômenos nacionais. 

É importante apontar que a inclusão digital não ocorreu uniformemente no Brasil, devido às desigualdades socioeconômicas de nosso país. Enquanto as classes A e B se aproximam da universalização do acesso a Web (mais de 95% dos lares), apenas 50% dos lares das classes D e E estão conectados. Além disso, 85% dos pertencentes das classes DE enfrentam um segundo nível de exclusão digital: possuir como único ponto de acesso o aparelho celular. Isso restringe as possibilidades de interação on-line, devido às limitações de sistema, hardware e de franquia de dados dos usuários, comparado aos usuários de PC com banda larga.  (CGI.BR, 2020, p. 13)

Mesmo com essas limitações, as classes populares conseguem utilizar a Internet de forma a contornar diversas adversidades. Para as autoras Paula Melgaço e Bruna Madureira, o uso das redes sociais para essa população constitui uma forma de empoderamento, citando como exemplos o uso de sites e plataformas, como base de conhecimento informal, e a possibilidade de comunicação entre amigos e familiares, mesmo que separados pela falta de transporte público e/ou pela insegurança urbana. (MELGAÇO; MADUREIRA, 2017, p. 18-19)

Dentro desse contexto das realidades das periferias brasileiras, em que a violência e o perigo ocasionados pela polícia e tráfico são constantes, os moradores encontram instrumentos de comunicação através da Internet. Mesmo que de forma limitada, através da rede é possível que eles se conectem com seus pares, expressem seus sentimentos e denunciem injustiças perpetuadas pelas demais camadas da sociedade e pelo Estado. 

Na proxíma seção serpa tratado esse uso específico da internet.


### 4.1.2 - Aplicativos contra violência policial
A partir desse crescente interesse, formou-se uma comunidade estadunidense do Reddit com pessoas interessadas em registrar e expor ocorrências de violências cometidas pelos policiais durante os protestos pacíficos decorrentes do assassinato de Floyd. Esta documentação começou a princípio como posts na comunidade r/2020PoliceBrutality (2020 Violência Policial, tradução nossa), mas devido ao grande volume de contribuições, surgiu a necessidade de organizá-las com ferramentas mais apropriadas. 

Levando em conta essa necessidade, um grupo de usuários trabalhou coletivamente na construção de um banco de dados, para auxiliar jornalistas, políticos, promotores, ativistas e cidadãos a utilizarem as informações em campanhas políticas, cobertura jornalística, educação pública e acusação dos policiais criminosos. Eles utilizaram a plataforma Github, por possibilitar a colaboração direta e disponibilizar o código fonte de maneira transparente.

A construção desse banco de dados motivou a participação de engenheiros de software ao movimento, dando origem a sites e aplicativos que dispõem visualmente os casos de violência policial registradas pela comunidade. Ao todo foram desenvolvidas pelo menos 10 interfaces diferentes, por diferentes autores, com ênfase a diferentes funcionalidades.

**
Referência dessas interfaces
**


Dentre as interfaces possíveis para esse projeto, optamos realizar uma análise mais aprofundada do app "2020PB", criado por Hossain Khan, por ser a único voltado a dispositivos móveis. A proposta desse aplicativo é contextualizar os casos de violência policial, durante os antirracistas nos Estados Unidos. Ele possibilita os usuários acessarem toda a base de dados da comunidade r/2020PoliceBrutality em qualquer lugar, além de oferecer um link de acesso rápido para adicionar novas denúncias através do repositório do projeto. Toda a informação utilizada para essa análise provém da página do *Github*, pois não foram encontradas outras referências que tratasse do mesmo.


#### 4.1.2.1 - Estudo do app “2020PB”



Figura XX - Capturas de tela do aplicativo “2020PB”

![](https://lh3.googleusercontent.com/S24nrES4OnDk9SKMfa36Eg_j5t7w-lyiNpd2DvT79X2_Um9mAtqbiZ3biCdgWVE2ZnHG_pwGqdOqyd41hW9GpJDMQZmXkeMF534nefq4H1CL_KkcTttGqNrxKblmr9bsjUR8LGxz=s0)

Fonte: Hossain Khan [https://github.com/2020PB/police-brutality](https://github.com/2020PB/police-brutality) (acesso em 01 de ago de 2021)

  

As principais funcionalidades que este aplicativo possui são: navegar pelos incidentes reportados, filtrando por data ou estado americano; sincronização automática, possibilitando acessar os casos mais recentes; listagem de links relacionados ao caso selecionado, como por exemplo, vídeos em redes sociais ou localização exata, pelo Google Maps;  informações sobre instituições de caridades notáveis que atuam em auxílio a causa.

A navegação do aplicativo é realizada por seções, cada uma contendo um conjunto de funcionalidades: “Incidentes”, “Reportar”, “Doar”, “Informações”. Cada seção é representada por um ícone e um texto de legenda, na parte interior da tela.

A seção “Incidentes” (figura XX) apresenta a listagem dos estados americanos, cada um deles acompanhado do número de incidentes reportados e a data do último incidente registrado. Além disso, na parte superior da tela, é possível escolher navegar por data e atualizar o aplicativo. Em ambos modos de navegação o resultado é semelhante, os casos são listados em cards, contendo uma descrição breve do caso, data, cidade, link para a localização e  links externos para postagens em redes sociais. Também existe a opção de compartilhar informações sobre o caso, porém esta funcionalidade contém uma grave falha de usabilidade, por se encontrar agrupada a função de localização, sem qualquer indicativo externo.

  
  
  
  
  
  
  
  
  

Figura XX - Análise estrutural da seção “Incidentes” do aplicativo  “2020PB”

Fonte: Hossain Khan ([https://github.com/2020PB/police-brutality](https://github.com/2020PB/police-brutality)), imagem adaptada pelos autores

Na tela “Reportar” (figura XX) é apresentado um curto texto explicativo apresentando o repositório do GitHub, link para o FAQ e um grande botão com o símbolo do Black Lives Matter, além da legenda “Reportar novo incidente”. Esse botão leva o usuário para uma página do GitHub, na qual ele pode escrever informações sobre um caso ainda não listado, para ser submetido à aprovação. Todavia, para realizar a submissão, é necessário uma conta no GitHub, o que pode desencorajar usuários que não sejam familiares com a plataforma.

Figura XX - Análise estrutural da seção “Reportar” do aplicativo  “2020PB”

Fonte: Hossain Khan ([https://github.com/2020PB/police-brutality](https://github.com/2020PB/police-brutality)), imagem adaptada pelos autores

Na seção “Doar” (figura XX) é apresentada uma lista de organizações não governamentais americanas alinhadas com o Movimento Black Lives Matter e/ou contra abusos policiais. É apresentado o logotipo, o nome, uma descrição curta, botões com links para mais informações e para a página de doações da mesma. Na parte superior existe um botão, que ao interagir, exibe um aviso no qual explica que o aplicativo não é filiado a nenhuma das instituições listadas, apenas as cita como comodidade aos usuários.

Figura XX - Análise estrutural da seção “Doar” do aplicativo  “2020PB”

Fonte: Hossain Khan ([https://github.com/2020PB/police-brutality](https://github.com/2020PB/police-brutality)), imagem adaptada pelos autores

Por fim, na seção “Informações” (figura XX), são apresentadas a comunidade r/2020PoliceBrutality, o propósito do aplicativo, links para as redes sociais da mesma, além de uma lista das principais hashtags utilizadas pelos membros para facilitar a localização das postagens. 

Figura XX - Análise estrutural da seção “Informações” do aplicativo  “2020PB”

Fonte: Hossain Khan ([https://github.com/2020PB/police-brutality](https://github.com/2020PB/police-brutality)), imagem adaptada pelos autores

  

O fluxograma do aplicativo pode ser verificado na figura X, construído para representar a organização de suas funcionalidades. Como a listagem dos casos segue o mesmo layout, independente do critério de exibição utilizado, as possibilidades de interação se repetem, tornando desnecessária a sua repetição no gráfico.

  
  
  
  
  

Figura XX - Fluxograma do aplicativo “2020PB”

![](https://lh4.googleusercontent.com/fEhZsJoUvI7krXE-sx0ibL5RwSTKxOzNeN_DwATxBjQzhVbd7CK7L_RqPwuh7cftM8w8XRgRytb06Q-Tl1ShFeBD61jrahHU5jdXSZFAM12Ey_apv1M-scqOVu0RHVWh7FSWKVI6=s0)

Fonte: elaborado pelos autores (2021)**




O compartilhamento e compilação de informações relacionadas aos casos de violência policial pode auxiliar na cobertura midiática dos eventos, denunciar os excessos cometidos para os órgãos de fiscalização, reunir organizações e indivíduos interessados em amparar as vítimas e os impactados, além de munir os próprios moradores das regiões mais afetadas com referências para que estes possam cuidar melhor da própria segurança e da segurança de seus entes queridos.


### 4.1.3 - Tendências para o futuro [pendente]




### 4.1.4 - Construção do mapa mental
A partir das pesquisas realizadas, apresentadas nas seções anteiores, foi criado um mapa mental para auxiliar na visualização da relação dos conceitos e palavras chaves encontrados. Esse mapa mental foi expandido (fig. XX), associando a ele a uma especulação dos próprios autores do projeto, pensando em como as problemáticas encontradas podem evoluir para soluções ou novos problemas. O mapa mental completo pode ser encontrado no apêndice X.

**

Figura XX - Captura de tela do mapa mental construído

![](https://lh4.googleusercontent.com/b0AAVSatj2xdmgWxLjNJoJKDwQdQYEJdHcKRqvnlr-evJEflfCgsJ_zbhegv-PTjubnGW8Pn5N9tVCvtWO8fMd6xpozsKiWCt0Vt2vU1D6F1wSfiEj85WhlShW6ijc4IFBHXmlu3=s0)

Fonte: Dos autores (2021)

**

## 4.2 - Classificação das tendências
### 4.2.1 - Taxinomia dos futuros
**

Inspirado na abordagem da Extrapolation Factory, no projeto 99¢ Futures (fig X), previsões escritas na etapa anterior, foram agrupadas entre as categorias “Tecnológico”, “Ecológico”, “Social”, “Político” e “Econômico”. Isso permitiu uma melhor visualização de cada um dos itens e estabeleceu conexões entre ideias relacionadas.

**
### 4.2.2 - Categorização das tendências

## 4.3 - Construção do futuro
### 4.3.1 - Conexões
### 4.3.2 - Escrita da narrativa

## 4.4 - Criação da experiência
### 4.4.1 - Conceituação
### 4.4.2 - Storyboard 
### 4.4.3 - Wireframes
### 4.4.4 - Fluxo de uso
### 4.4.5 - Elaboração estética