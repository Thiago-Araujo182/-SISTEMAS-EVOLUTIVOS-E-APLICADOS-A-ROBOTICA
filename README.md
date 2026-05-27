# ANALISE_YOLO 
##      
Sobre o projeto 
Este projeto tem como objetivo realizar uma comparação entre diferentes versões 
do modelo YOLO (*You Only Look Once*) aplicadas à detecção de objetos em 
imagens. 
Foram analisadas cinco versões do YOLO utilizando uma imagem obtida da 
internet e o COCO Dataset como base de reconhecimento dos objetos. O estudo 
compara: - Tempo de processamento; - Quantidade de objetos detectados; - Precisão do reconhecimento; - Diferenças entre modelos leves e robustos. --- 
##         
Tecnologias utilizadas - Python - Google Colab - Ultralytics YOLO - OpenCV - Matplotlib --- 
##              
Bibliotecas utilizadas 
Instale as dependências utilizando: 
```bash 
pip install ultralytics opencv-python matplotlib 
``` --- 
##    
Estrutura do projeto 
```bash 
ANALISE_YOLO/ 
│ 
├── imagens/ 
│   └── imagem_teste.jpg 
│ 
├── resultados/ 
│   └── deteccoes/ 
│ 
├── ANALISE_YOLO.ipynb 
│ 
├── requirements.txt 
│ 
└── README.md 
``` 
--- 
##    
Como executar o projeto 
### 1. Clone o repositório 
```bash 
git clone <https://github.com/Thiago-Araujo182/-SISTEMAS-EVOLUTIVOS-E-APLICADOS-A-ROBOTICA)> 
git clone <> 
``` 
### 2. Entre na pasta do projeto 
```bash 
cd ANALISE_YOLO 
``` 
### 3. Instale as dependências 
```bash 
pip install -r requirements.txt 
``` 
### 4. Execute o notebook 
Abra o arquivo: 
```bash 
ANALISE_YOLO.ipynb 
``` 
utilizando o Google Colab ou Jupyter Notebook. --- 
##          
Modelos utilizados 
Os modelos utilizados na comparação foram: - YOLO26n - YOLO26s - YOLO26m - YOLO26l - YOLO26x --- 
##        
Objetivo da comparação 
O projeto busca analisar o comportamento das diferentes versões do YOLO em 
relação à velocidade e precisão na detecção de objetos, permitindo observar 
vantagens e limitações de cada modelo. --- 
##       
Resultados 
Os testes realizados geram: - Imagens com objetos detectados; - Classes identificadas; - Tempo de inferência; - Comparação visual entre os modelos. --- 
##      
Licença 
Projeto desenvolvido para fins acadêmicos e educacionais. 
