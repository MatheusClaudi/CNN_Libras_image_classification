# CNN_Libras_image_classification


## Descrição:

    Este repositório contém todos os scripts de pré-processamento de dados e de treinamento utilizados no desenvolvimento de um TCC em formato de notebooks.

## Instruções de uso:
    
    Este trabalho é fruto de meu TCC, caso algum script ou informação presente aqui lhe seja útil, por favor entre em contato comigo e cite meu artigo.

## Email de contato:

    matheus.claudino@ccc.ufcg.edu.br

## Resumo do TCC: 

    Embora a língua de sinais brasileira (Libras) tenha sido reconhecida como uma língua oficial do Brasil em 2002, medidas legais que regularizem e exijam a oferta de ensino de Libras nas escolas em algum grau, apenas foram revertidas em um projeto de lei em 2019. Resultando numa falta de contato de pessoas sem problemas auditivos com Libras, e combinado à constatação da World Federation of the Deaf (WFD) de que cerca de 80% dos surdos do mundo possuem problemas de compreensão nas línguas escritas de seus respectivos países, gera um isolamento social daqueles que dependem do uso de Libras para se comunicar. Neste contexto, existe o campo de reconhecimento de linguagens de sinais (RLS), que se propõe a criar interfaces tecnológicas que possam atuar no problema descrito. Este trabalho utiliza de quadros de vídeos estáticos extraídos do dataset MINDS-Libras para analisar o impacto do uso de métodos de pré-processamento de imagens no treinamento de uma Rede Neural Convolucional (CNN), com o intuito de se obter um modelo capaz de classificar 20 sinais diversos de Libras de forma eficiente. Ao final, o método proposto alcançou acurácia média de 91.08% no conjunto de dados utilizado.

## Descrição da estrutura de pastas:
Pasta finalModels:

    Contém todos os 7 modelos obtidos com o uso de diferentes técnicas de processamento de imagem utilizando o OpenCV. Anexado estão os gráficos de Loss e acurácia do treinamento.

Pasta videoProcessing:
    
    Contém todos os scripts utilizados para redimensionar e cortar os vídeos do dataset original, os armazenando em formato .mp4

Pasta imageProcessing:

    Contém todos os scripts utilizados para realizar transformações de imagem nos dados provenientes de videoProcessing, e de seleção de frames para representar a classe a ser predita.

Pasta customDatasets:

    Contém todos os 7 datasets obtidos das tranformações de imagens resultantes de imageProcessing.

Pasta training CNN:

    Contém todos os scripts de treinamento utilizados para realizar o treinamento dos modelos presentes na pasra finalModels. O treinamento foi feito utilizando Keras e Tensorflow.

## Link para dataset original:

    https://zenodo.org/record/4322984#.YpDY_WjMJEY