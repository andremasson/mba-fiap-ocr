# mba-fiap-ocr

## Pre-requisitos:

```
matplotlib
opencv-python
pytesseract
```
### Também instalar:
```
tesseract-ocr: https://tesseract-ocr.github.io/tessdoc/Home.html#binaries
```

## Como executar:

O script irá buscar por todos os arquvivos PNG e JPG no diretório "arquivos". 
Para cada arquivo será criado um TXT com o mesmo nome contendo as informações obtidas na OCR.
As informações coletadas são: Nome do estabelecimento, CNPJ, Data da compra e Valor total.
