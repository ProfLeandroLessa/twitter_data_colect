
<h1>Coleta de dados no Twitter</h1>

![](doc_imgs/img_twitter_data_collect.png)

<p align = center> 
<a href = '#description'>Sobre</a> •
<a href = '#tecnologies'>Tecnologias e bibliotecas</a> •
<a href = '#Manual'>Manual</a>
</p>


<h2 id = 'description'> Sobre</h2>

Este projeto tem como objetivo criar um coletor de dados simples utilizando a API do Twitter.  Vamos apresentar os principais passos para realizar essa tarefa e, ao final, vamos exportar os dados coletados para um arquivo estruturado do tipo CSV.<br><br>

Os dados a serem coletados são:<br><br>

• created_at: Data da publicação do tweet <br>
• name: Contém o nome da usuário que postou o tweet <br>
• description: Contém a descrição do usuário do tweet <br>
• location: Localização no qual foi postado o tweet <br>
• text - Conteúdo postado do tweet <br>

<h2 id = 'description'> Motivação</h2>

A motivação desse projeto é apresentar de forma prática e simples os passos necessários para realizar uma coleta de dados utilizando a API do Twitter utilizando a linguagem Python.

<h2 id = 'tecnologies'> Tecnologias e bibliotecas </h2>
<p>Linguagem de programação:<br>
<a href='https://www.python.org'>Python 3.9</a>

Bibliotecas utilizadas:<br> 
1.	<a href='https://www.tweepy.org/'>tweetpy</a> - Biblioteca responsável por acessar os dados da API do Twitter;<br> 
2.	<a href='https://docs.python.org/pt-br/3.7/library/os.html'>os</a> - Responsável por realizar diversas interfaces de sistema operacional; <br>
3.	<a href='https://pandas.pydata.org/docs/index.html'>pandas</a> - Utilizada para realizar manipulação e análise de dados em dataframes e series; <br>
4.	<a href='https://pypi.org/project/python-dotenv/'>python-dotenv</a> - Biblioteca utilizada para realizar leitura de chave e valor de um aquivo .env; <br>


IDE:<br>

Para esse projeto, optamos utilizar o aplicativo web Jupyter notebook.<br>

<a href='https://jupyter.org/'>Jupyter Notebook</a>


<h2 id = 'Manual'> Manual</h2>
Foi desenvolvido um manual de auxilio para criação da conta de desenvolvedor no Twitter e eu acredito que será de grande ajuda para você.<br><br>

OBS: Pode ser que os passos demonstrados no manual estejam diferentes com o site atual do Twitter. Isso é uma situação já esperada visto que pode ocorrer mudanças ou atualizações. Mas fique tranquilo(a), geralmente os passos seguem um padrão.<br>

O manual criado pode ser acessado no link abaixo:<br>
<a href='https://github.com/ProfLeandroLessa/twitter_data_colect/blob/master/manual/cria%C3%A7%C3%A3o_conta_desenvolvedor_Twitter.pdf'>Manual de criação para conta de desenvolvedor do Twitter</a>





