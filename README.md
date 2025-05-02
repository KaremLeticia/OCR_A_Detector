# OCR_A_Detector

Este mini projeto realiza a leitura de imagens contendo texto e identifica automaticamente se há a presença da letra **"A" maiúscula**, utilizando técnicas de **pré-processamento de imagem com OpenCV** e **OCR com Tesseract**.

## 🔍 Objetivo

Demonstrar uma aplicação prática de **visão computacional** e **extração de texto (OCR)** para tarefas de reconhecimento de padrões simples, como a verificação de caracteres específicos.

## ⚙️ Tecnologias Utilizadas

- Python
- OpenCV
- Pytesseract (OCR)
- Google Colab
- Pandas
- Matplotlib

## 🧠 Conceitos aplicados

- Pré-processamento de imagem (escala de cinza, binarização)
- Extração de texto com OCR
- Análise condicional de caracteres
- Visualização de resultados com Matplotlib
- Leitura de arquivos e manipulação com Pandas

## 📂 Como Executar

1. Execute o notebook no [Google Colab](https://colab.research.google.com/).
2. Faça upload das imagens que deseja analisar.
3. O sistema irá:
   - Exibir a imagem original e a binarizada.
   - Indicar se a letra **"A" maiúscula** foi detectada no texto extraído.
   - Gerar uma tabela final com os resultados.

## 📊 Exemplo de Saída

Para cada imagem enviada, será exibido:

- A imagem original
- A imagem binarizada
- O resultado da análise (com ou sem "A")
- Um DataFrame com todos os resultados consolidados

## 🚀 Possíveis Melhorias

- Adicionar interface gráfica com Streamlit
- Permitir escolha de letras ou palavras personalizadas
- Melhorar o pré-processamento com filtros morfológicos

---

Desenvolvido por Karem ✨
