
# Um blog usando Jekyll

O Jekyll é um gerador de sites estáticos – de fato, ele é o mais popular dentre eles. Um site estático não possui componentes rodando no lado do servidor: ele usa tecnologias web padrão (HTML5, JS, CSS) e não interage com componentes dinâmicos (um banco de dados, por exemplo).

É versátil, podendo ser usado para criar blogs, landing pages, sites institucionais, entre outros. O conteúdo é criado através de simples arquivos de texto no formato MarkDown. Cada vez que você atualiza estes arquivos, estes são compilados (transformados) em um site completo.


## Instalação no Ubuntu

Instale Ruby e outros pré-requisitos.

```bash
  sudo apt-get install ruby-full build-essential zlib1g-dev
```

Evite instalar pacotes RubyGems (chamados de gems) como usuário root. Em vez disso, configure um diretório de instalação do gem para sua conta de usuário. Os seguintes comandos adicionarão variáveis ​​de ambiente ao seu ~/.bashrcarquivo para configurar o caminho de instalação da gem:

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

```

Finalmente, instale Jekyll e Bundler:

```
gem install jekyll bundler
```

É isso! Você está pronto para começar a usar o Jekyll.


## Referência

 - [jekyllrb](https://jekyllrb.com/docs/installation/ubuntu/)