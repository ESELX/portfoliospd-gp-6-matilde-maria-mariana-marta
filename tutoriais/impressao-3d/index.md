---
title: "Impressão 3D"
icon: lucide/box
tags: galeria
status: Completed
hero_image: attachments/hero.png
hero_title: "Impressão 3D"
hero_subtitle: "Tutorial Bambu Lab A1 mini"
hero_height: 70vh
hero_overlay: 0.3
hero_align: center
published: true
machine_name: "Bambu Lab A1 mini"
---

# Bambu Lab A1 mini

> A impressão 3D confere diferentes métodos adequados a cada projeto e a cada equipamento. O processo FDM/FFF (Modelagem de Deposição Fundida) derrete um filamento termoplástico (PLA, ABS, PETG) e deposita camada por camada. Este processo foi usado para desenvolver os projetos individuais de cada elemento do grupo, com o uso de PETG, recorrendo ao programa Bambu Studio para adaptar/preparar os modelos feitos no Fusion Autodesk e depois imprimir no equipamento.

![](tutoriais/impressao-3d/attachments/hero.png)

**Tutorial 101:**
Modelo: Bambu Lab A1 mini
Data: 13/05/2026
O projeto de exemplo pertence e o tutorial foram desenvolvidos Matilde Pita

## 1. Como desenhar para esta tecnologia?

Para desenhar ou desenvolver um projeto para esta tecnologia é suposto recorrer a programas de construção de figuras tridimensionais como Fusion Autodesk e Blender. Após o desenvolvimento bem sucedido do projeto passamos para o seguinte passo, exportação.

## 2. Como preparar um ficheiro para a máquina

Após modelar o ficheiro no programa Fusion Autodesk ou Blender, deve-se exportar pra um ficheiro compatível com o programa Bambu Studio, esses são:

- **.3MF**: O formato principal e nativo que inclui o projeto completo incluindo a geometria, cores, texturas e definições de impressão.
- **.STL**: O formato clássico de malha 3D que contém apenas a geometria do modelo.
- **.STEP ou .STP**: Formatos CAD de alta precisão, excelentes para manter curvas suaves e dimensões exatas durante a impressão.
- **.OBJ**: Formato de malha comum, que suporta cores e texturas.
- **.SVG** : Compatível para importar logótipos ou imagens 2D para extrusão e personalização direta no modelo.

- Software: Fusion Autodesk, Blender, Bambu Studio
- Formatos de ficheiro: .3MF, .STL, .STEP, .STP, .OBJ, .SVG
- Settings principais: Exportação, Importação

## 3. Antes de Começar

### 3.1. Segurança

Com a maquina de impressão 3D é importante ter em conta que para esta ferramenta funcionar, tanto o bico que expele o filamento, como a placa de formação vão estar em temperaturas altas. Para prevenir queimaduras ou ferimentos é recomendado manter uma distancia segura enquanto a maquina opera e breves momentos após a conclusão da tarefa atribuída.

### 3.2. Que tipo de ficheiros vou usar e onde os posso produzir

Como referido anteriormente, este tutorial é aplicavel a maquinas Bambu e ao seu programa Bambu Lab, que suportam fiicheiros em formato .**3MF**, **.STL**, **.STEP** ou **.STP**, **.OBJ** e **.SVG**.

## 4. Como operar a máquina passo-a-passo

1. Após ligar a maquina, deve-se exportar o projeto, no canto superior direito do programa deve-se clicar em "Open Project" e selecionar o ficheiro exportado anteriormente.
![](Bambulab1.png)

2. Em seguida deve-se fazer os adjustments necessários ao modelo de acordo com as necessidades da impressora e os seus filamentos. 
![](Bambulab2.png)

3. Uma vez pronto, seleciona-se "Slice plate" no canto superior direito, que vai fornecer a informação sobre a quantidade de filamento necessária e a duração de impressão.
![](Slicing.png)

4. Uma vez com o slicing pronto podemos inserir o cartão SD da impressora 3D no computador, clicar em "Print plate" e selecionar "Export plate sliced file" para o cartão SD. Depois disso basta ejetar o cartão SD e inserir na ranhura designada do equipamento de impressão. 
![](Slicing2.png)

5. No ecrã da impressora seleciona-se o projeto a executar e depois é só esperar que a impressora opere! 
![](impressora3D.png)

vídeo da execução do projeto:
![](video3d.mp4)

## 5. Resultado e pós-produção

Após a execução do projeto na impressora, o protótipo está completo e em caso de querer fazer modificações como lixar ou pintar a superfície, basta aplicar um primer para plásticos em spray e deixar secar. 

## 6. Recursos e Ficheiros

- Ficheiros-modelo: `attachments/`

