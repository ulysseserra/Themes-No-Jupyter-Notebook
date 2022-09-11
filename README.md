# Themes No Jupyter Notebook

Rápida descrição do objetivo de fazer esse projeto

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Themes No Jupyter Notebook*
| :label: Tecnologias | jupyter, python (tecnologias utilizadas)
| :rocket: URL         | https://url-deploy.com.br
| :fire: Desafio     | https://url-do-desafio.com.br

<!-- Inserir imagem com a #vitrinedev ao final do link -->
![](https://assets.website-files.com/6141c89a3874c3702674a1c0/625012c9c0dbf1887c4bf7c7_623d8b3bd384c356fff4d0c8_memgraph-jupyter-notebook-cover.png#vitrinedev)

## Detalhes do projeto

Instalando o pacote JupyterThemes
Dentro do jupyter notebook precisaremos instalar o pacote “jupytherthemes”, utilize o seguinte comando:

!pip install jupyterthemes

Depois da instalação finalizada (leva alguns segundos somente), você pode conferir a versão do pacote após importá-lo. Neste exemplo estou usando a seguinte versão:

<img height="150em" src="https://miro.medium.com/max/348/1*c6jqxJO1-Xb64omt53OE0Q.png"/>


Você deve ter reparado no “as jt” não? Aquilo é um álias, tipo um apelido que damos ao pacote afim de evitar escrever “jupyterthemes” cada vez que usamos a biblioteca.

Verificando os temas disponíveis
Para verificar os temas disponíveis no pacote, podemos usar uma função desta biblioteca chamada “.get_themes()” que retorna o nome de cada tema:

<img height="250em" src="https://miro.medium.com/max/321/1*GhCtSu-Mpq70Ao-1iTulQg.png"/>

Instalando um Tema!
Vamos agora usar a função “.install_theme” para instalar nosso novo tema.
Para esse tutorial escolhi instalar um tema novo: “oceans16”.
Para instalar o tema escolhido faça o seguinte comando:

<img height="50em" src="https://miro.medium.com/max/403/1*29KVooPgu0aFU717z4ia_w.png"/>

Depois de instalado, reinicie a página e o tema escolhido já estará disponível!

<img height="420em" src="https://miro.medium.com/max/700/1*x86hLoYvJx7lomz0wmCd8g.png"/>

Mudando o Estilo dos plots
Instalado o tema, é hora de mudar o estilo dos plots no notebook. Sem essa mudança os gráficos serão plotados no formato padrão (light) e vão ficar destoantes do seu novo “dark” notebook.
Para isso vamos importar a classe “jtplot” para usarmos a função “style”:

<img height="100em" src="https://miro.medium.com/max/423/1*14QGluv9UYlrSOcqgVhT5w.png"/>

Vamos utilizar a biblioteca matplotlib para plotar um gráfico de linha bem simples, somente para visualizar como ficou nosso plot temático.
Para isso criei duas listas com coordenadas em x e y:

<img height="400em" src="https://miro.medium.com/max/542/1*shF7rFegApmMJ1rvcEa26w.png"/>

Podemos ainda editar nosso plot usando outros paramêtros da função “style”:

<img height="50em" src="https://miro.medium.com/max/663/1*0K5aGM3GgRPiiKcfU_Pa8g.png"/>

<img height="250em" src="https://miro.medium.com/max/410/1*pAPYWTKI3fd95l2mYrdxDA.png"/>

Para ter acesso a todos os parâmetros da função “style”, no Jupyter Notebook, dentro da função aperte “tab” e uma lista suspensa com as opções de parâmetros, detalhes de cada um e exemplos de uso será apresentada:

<img height="250em" src="https://miro.medium.com/max/521/1*a5P4QSTiWfuJcW60QhnjNA.png"/>

Espero que tenham gostado pessoal!

