# <img width="30" height="30" src="https://img.icons8.com/color/48/python--v1.png" alt="python--v1"/> <img width="30" height="35" src="https://img.icons8.com/ios/50/flask.png" alt="flask"/> Projeto Final para Curso Pós Graduação em Desenvolvimento Full Stack - MVP_Fullstack <img width="30" height="30" src="https://img.icons8.com/bubbles/100/api.png" alt="api"/>

<p align="center">
  <a href="#Sobre-o-Projeto">Sobre o Projeto</a> &#xa0; | &#xa0; 
  <a href="#Screenshots">Screenshots</a> &#xa0; | &#xa0;
  <a href="#Requerimentos-e-Instalação">Requerimentos e Instalação</a> &#xa0; | &#xa0;
  <a href="#Iniciando-a-aplicação---Implementação">Rodando a aplicação - Implementação</a> &#xa0; | &#xa0;
  <a href="#Referência-da-API">Referência da API</a> &#xa0; | &#xa0;
  <a href="#Exemplos-de-Métodos-HTTP---Referência-da-API"> Exemplos de Métodos HTTP - Referência da API</a> &#xa0; | &#xa0;
  <a href="#Tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#Live-Vídeo-API-Swagger">Live Vídeo API Swagger</a> &#xa0; | &#xa0;
  <a href="https://github.com/ledelmastro" target="_blank">Autor@</a>
</p>

## <img width="30" height="30" src="https://img.icons8.com/bubbles/100/about.png" alt="about"/> Sobre o Projeto ##

🔸 MVP_Fullstack
Projeto Final de desenvolvimento de uma API Backend (Python + Flask) para o Curso de Desenvolvimento Full Stack - Pós Graduação - PUC RJ

## <img width="30" height="30" src="https://img.icons8.com/bubbles/100/screenshot.png" alt="screenshot"/> Screenshots ## 

![App Screenshot](https://github.com/ledelmastro/MVP_Fullstack_Back_End/blob/main/Screenshot2.png?raw=true)

![App Screenshot](https://github.com/ledelmastro/MVP_Fullstack_Back_End/blob/main/Screenshot1.png?raw=true)

## <img width="30" height="30" src="https://img.icons8.com/parakeet/48/software-installer.png" alt="software-installer"/> Requerimentos e Instalação ##

☑️ 1. Certifique-se de ter instalado a última versão de Python, disponível em https://www.python.org/downloads/; 🌍 

☑️ 2. Com Python instalado em sua estação, clone o repositório deste projeto, disponível no diretório github:

   Caso precise de instruções para clonar o repositório para sua máquina, você pode encontrar um bom tutorial em
   https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository;

Clone o projeto  ↪️
~~~ bash  
  git clone https://github.com/ledelmastro/MVP_Fullstack_Back_End
~~~

Vá para o diretório local onde o projeto foi baixado ↪️

~~~bash  
  cd MVP_Fullstack_Back_End/back_end
~~~

Se estiver usando VsCode, abra o diretório local da aplicação ↪️

        CTRL+K+O -> escolha o diretório onde o projeto foi clonado 

ou utilize a linha de comando:
~~~bash  
   code MVP_Fullstack_Back_End/back_end
~~~

## <img width="30" height="30" src="https://img.icons8.com/external-flaticons-flat-flat-icons/64/external-development-project-management-flaticons-flat-flat-icons-2.png" alt="external-development-project-management-flaticons-flat-flat-icons-2"/> Rodando a aplicação - Implementação

Instale as dependências - requerimentos necessários para rodar a aplicação ↪️

~~~bash  
   pip install -r requirements.txt
~~~

Inicie a aplicação (rode o servidor na porta 5000) ↪️

~~~bash  
   pyhon app.py 
~~~

## <img width="30" height="30" src="https://img.icons8.com/external-soft-fill-juicy-fish/60/external-api-microservices-soft-fill-soft-fill-juicy-fish-4.png" alt="external-api-microservices-soft-fill-soft-fill-juicy-fish-4"/> Referência da API 📦 

☑️ Para conferir a documentação da API e testar suas requisições, abra o endereço http://127.0.0.1:5000/swagger/ em seu navegador de preferência.

## <img width="30" height="30" src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/external-http-internet-marketing-flaticons-lineal-color-flat-icons.png" alt="external-http-internet-marketing-flaticons-lineal-color-flat-icons"/> Exemplos de Métodos HTTP - Referência da API 📬

|        Parameter         | Type    | Description                       |
|--------------------------|---------|-----------------------------------|
|📂 GET - /user/{id_user}  | `string`| **Required "id_user", 200 - "Usuario localizado com sucesso."**      |
|<img width="20" height="20" src="https://img.icons8.com/color/48/mailbox-opened-flag-down.png" alt="mailbox-opened-flag-down"/> POST - /login            | `string`| **Required "login","password", 200 - "Login realizado com sucesso"** |
|<img width="20" height="20" src="https://img.icons8.com/officel/80/change-theme.png" alt="change-theme"/> PUT - /user/{id_user}    | `string`| **Required "id_imovel", 201 - "Imovel alterado com sucesso."**       |
|<img width="20" height="20" src="https://img.icons8.com/plasticine/100/filled-trash.png" alt="filled-trash"/> DELETE - /user/{id_user} | `string`| **Required "id_user", 200 - "Usuario deletado com sucesso."**       |

## <img width="23" height="23" src="https://img.icons8.com/color/48/python--v1.png" alt="python--v1"/> Tecnologias 📦

As seguintes tecnologias foram utilizadas no desenvolvimento deste projeto:

- [Python](https://html.spec.whatwg.org/)
- [Flask](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [SqlAlchemy](https://developer.mozilla.org/en-US/docs/Web/javascript)

## <img width="30" height="30" src="https://img.icons8.com/pulsar-color/48/live-video-on.png" alt="live-video-on"/>  Live Vídeo API Swagger  ##

<a href="https://www.canva.com/design/DAGR6aCaftQ/hb_eYIER9h5xZThns4oEhQ/watch?utm_content=DAGR6aCaftQ&utm_campaign=designshare&utm_medium=link&utm_source=editor" target="_blank" rel="noopener noreferrer">Live Vídeo Swagger</a>

## <img width="30" height="30" src="https://img.icons8.com/external-itim2101-gradient-itim2101/64/external-writer-life-style-avatar-itim2101-gradient-itim2101.png" alt="external-writer-life-style-avatar-itim2101-gradient-itim2101"/> Autor(@) ##

Feito por <a href="https://github.com/ledelmastro" target="_blank">Elena Assis da Silva Del Mastro </a>
&#xa0;

<a href="#top">Back to top</a>
