# elixir_freecodecamp
Curso da linguagem Elixir da FreeCodeCamp (https://www.youtube.com/watch?v=IiIgm_yaoOA)


Instalar:
sudo add-apt-repository ppa:rabbitmq/rabbitmq-erlang
sudo apt update
sudo apt install elixir erlang-dev erlang-xmerl

Verificar:
elixir -v

Executar terminal interativo:
iex


Arquivos com a extnsão .exs são scripts elixir.
Usado para testar alguma lógica ou serem executados diretamente.

Exemplo:
Crie arquivo com nome hello.exs

e cole:
defmodule Hello do
  def world do
    IO.puts("Hello Elixir!")
  end
end

Hello.world()

Para executar:
elixir hello.exs



Dá para compilá-lo, irá gerar um arquivo com a extensão .beam