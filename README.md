# TCC - Identificação de defeitos categorizados em amostras de Abeto

**********

## Atualizações

Arquivos básicos adicionados:
+ Notebooks Jupyter
+ Arquivos .txt dataset
+ Dados.xlsx
+ Dados_csv.csv

Título atualizado, os arquivos serão atualizados e atribuídos conforme a evolução do projeto.


## Lista de Conteúdo

+ [Dataset Info](##dataset-info)
+ [Introdução e Objetivos](##introdução-e-objetivos)
+ [Estrutura dos Diretórios](##estrutura-dos-diretorios)
+ [WD_gather](##wd_gather)
+ [Tratamento_Dados](##tratamento_dados)
+ [Tratamento_Imagens](##tratamento_imagens)
+ [Feature_Detection](##feature_detection)

**********

## Dataset Info

First and foremost I must thank the professionals from the University of Oulu, without whom, this work would not be possible. We will be using the Wood Dataset, wich contains the images of 839 spruce planks. More info can be obtained at:

http://www.ee.oulu.fi/~olli/Projects/Lumber.Grading.html

The Wood Dataset can be found at:

http://www.ee.oulu.fi/research/imag/wood/WOOD/

The suggested references for their work are:

"Kauppinen H. and Silven O.: A Color Vision Approach for Grading Lumber. In Theory & Applications of Image Processing II - Selected papers from the 9th Scandinavian Conference on Image Analysis (ed. G. Borgefors), World Scientific, pp. 367-379 1995."

"Silven O. and Kauppinen H.: Recent Developments in Wood Inspection. International Journal on Pattern Recognition and Artificial Intelligence, IJPRAI, pp. 83-95, 1996."


Olli Silven       olli@ee.oulu.fi  
Hannu Kauppinen    hsk@ee.oulu.fi  

University of Oulu  
Department of Electrical Engineering  
Computer Laboratory  
FIN-90570 OULU  
Finland  

The remaining of the document will be written in Brazilian Portuguese, as an undergrad final papel, it lacks the need for multilingual writing.

Any questions can be sent to <buchner.eng@gmail.com>

**********

## Introdução e Objetivos


**********



## Estrutura dos Diretórios

Os diretórios foram organizados da seguinte maneira:

+ Compactados - Arquivos compactados no formato .gz
+ Imagens_PPM - Extração dos arquivos compactados no formato .ppm
+ Imagens_Originais - Arquivos .pmm convertidos para .jpg
+ Imagens_Recortadas - Imagens seccionadas conforme as coordenadas fornecidas pelo arquivo manlabel.txt
+ Imagens_Tratadas - Imagens gradeadas com os defeitos categorizados conforme o arquivo manlabel.txt
+ Imagens_Sem_Legenda - Imagens recortadas conforme a coordenada total de cada amostra pelo arquivo manlabel.txt
+ Dataframes - Diversos DataFrames gerados no decorrer dos testes.
  + GLCM_ML - Resultados dos modelos de Machine Learning utilizando as características GLCM (Pastas internas para cada modelo).

**********

## WD_Gather

Arquivo base para o projeto, realiza o download dos arquivos do dataset no diretório raiz, move os arquivos para as pastas respetivas e finalmente extrai os arquivos .ppm

**********

## Tratamento_Dados



**********

## Tratamento_Imagens



**********

## Feature_Detection



**********
