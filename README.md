# luavenv

Gerenciador de ambientes virtuais isolados para Lua, inspirado no `venv` do Python.

## Recursos
* Cria ambientes isolados com binários do Lua e LuaRocks.
* Não exige compiladores C locais na máquina do usuário.
* Funciona no Linux, macOS e Windows.

## Instalação

Baixe o executável pré-compilado para o seu sistema na aba [Releases](https://github.com/SEU_USUARIO/luavenv/releases).

## Como Usar

### 1. Criar um ambiente virtual
```bash
luavenv meu_ambiente --lua:5.3.6
```
### 2. Ativar o ambiente:

```bash
# linux/macOs:
source my_venv/bin/activate
```
```dos
rem Windows:
my_venv\bin\activate.bat
```
### 3. Instalar pacotes com LuaRocks:
```bash
luarocks install luavenv
```

Licença
Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.txt) para mais detalhes.
