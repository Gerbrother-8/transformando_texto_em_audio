# Conversor de Texto em Áudio com Python e gTTS 🎙️

Este projeto foi desenvolvido como parte do módulo **"Os Pilares Formais da IA: do Machine Learning à IA Generativa"** do bootcamp **Bradesco - GenAI & Dados** na plataforma DIO. O objetivo é demonstrar a aplicação prática de bibliotecas de síntese de voz (Text-to-Speech) de forma simples e eficiente.

## Sobre o Projeto
O script utiliza a biblioteca `gTTS` (Google Text-to-Speech) para converter entradas de texto em português em arquivos de áudio (.mp3). O projeto foi estruturado para ser executado no ambiente **Google Colab**, facilitando a instalação de dependências e a reprodução imediata do áudio.

## Tecnologias Utilizadas
* **Python 3**
* **gTTS:** Biblioteca para interface com a API de conversão de texto em fala do Google.
* **IPython.display:** Utilizada para renderizar o player de áudio diretamente no notebook.
* **Google Colab:** Ambiente de desenvolvimento em nuvem.

## Como Executar
1.  Abra o arquivo `.ipynb` no Google Colab.
2.  Execute a primeira célula para instalar as bibliotecas necessárias e configurar o ambiente.
3.  Execute a segunda célula.
4.  Quando solicitado, digite o texto que deseja converter.
5.  O sistema gerará o arquivo `audio_gerado.mp3` e abrirá um player para reprodução do áudio.

## Estrutura de Arquivos
* `script_gtts.ipynb`: Notebook com o código-fonte.
* `audio_gerado.mp3`: Saída gerada pelo script.

## Autor
Desenvolvido por Germano P. Valentini.
