# TINA - Assistente virtual

<p align="left">
  <img src="https://img.shields.io/static/v1?label=&message=Python&color=blue&style=for-the-badge&logo=python"/>
  <img src="https://img.shields.io/static/v1?label=&message=gTTS&color=blue&style=for-the-badge&logo=gtts"/>
  <img src="https://img.shields.io/static/v1?label=&message=speech_recognition&color=blue&style=for-the-badge&logo=speech_recognition"/>
  <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
</p>


Este Projeto foi realizado por Maurício André de Almeida como trabalho no curso de Processamento de Linguagem Natural na DIO.ME


# Projeto Criando um sistema de assistência virtual do zero. 

Neste projeto deve ser desenvolvido um sistema de assistência virtual, utilizando PLN (Processamento de Linguagem Natural), com base nas bibliotecas apresentadas durante o curso. O sistema deve obedecer aos seguintes requisitos: 
	
Um módulo para transformação de texto em áudio (text to speech); 
 	
	
Um módulo para transformação de fala (linguagem natural humana) em texto (speech to text); 
 	
	
O módulo 2, deve acionar por comando de voz algumas funções automatizadas, como por exemplo: abrir uma pesquisa no Wikipedia, abrir o Youtube, apresentar a localização da farmácia mais próxima. 
 	
Para realizar este projeto, podem ser utilizada todas as bibliotecas apresentadas no curso, principalmente a biblioteca Speech recognition em Python.  

### <b>Implementação:</b>

Neste projeto utilizei as bibliotecas speech_recognition, pyaudio, pygame, gtts, webbrowser e subprocess

Realizei os seguintes passos para cumprir o desafio:

<ul>
<li>Carregar as bibliotecas necessárias</li>
<li>Criar a função para falar um texto</li>
<li>Criar as strings do nome da assistente, mensagens padrão e traduções para tempo e clima</li>
<li>Função para remover verbos dos comandos</li>
<li>Função para pesquisar a previsão do tempo</li>
<li>Função para processar os comandos e executar as ações</li>
<ul>
  <li>Pesquisar na internet</li>
  <li>Pesquisar na Wikipedia</li>
  <li>Pesquisar no Youtube</li>
  <li>Falar a data</li>
  <li>Falar a hora</li>
  <li>Falar a previsão do tempo</li>
</ul>
<li>Função para ouvir o microfone</li>
<li>Programa principal que escuta a palavra de ativação e manda executar os comandos até ouvir a palavra "Sair"</li>
</ul>
