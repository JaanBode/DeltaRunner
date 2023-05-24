<div align="center">
  <a href="README-pt.md">Português</a>
  ·
  <a href="README.md">English</a>
</div>
  
<p align="center">
  <a href="#about">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#live-server">Jogo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#dependencies">Dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#execute">Como Rodar</a>
</p>

<a id="about"></a>
**DeltaRunner**  é um runner-style com mecânicas aprimoradas e belos visuais. Vença seu próprio score ao enfrentar monstros que vem de encontro ao seu caminho.
        
<a id="live-server"></a>

## Game
- [DeltaRunnerWindowx](https://github.com/JacanaFSilva/DeltaRunner/archive/refs/heads/windowsBuild.zip) - windows build - download direto.
- [DeltaRunnerLinux](https://github.com/JacanaFSilva/DeltaRunner/archive/refs/heads/linuxBuild.zip) - linux build - download direto.
- [DeltaRunner](https://github.com/JacanaFSilva/DeltaRunner/archive/refs/heads/main.zip) - jogo pré-compilad - download direto.

<a id="dependencies"></a>

## Dependências

- [Python](https://www.python.org/) - código principal.
- [Pygame](https://www.pygame.org/news) - biblioteca para desenvolvimento de jogos em python.
- [PyInstaller](https://pypi.org/project/pyinstaller/) - biblioteca para compilação em executável de um arquivo python.

<a id="execute"></a>

## Rodando em sua máquina

<h2><strong>Pre-requirements</strong></h2>

- **requisito para usuários linux** **[WineHq](https://wiki.winehq.org/Download)** - para executar o arquivo.
- Abra o runner.exe e o jogo irá iniciar automaticamente.
- Se você quiser compilar por si próprio, então:

## 1: Clone o repositório para sua máquina:

Abra o Windows PowerShell, e digite as seguintes instruções:

```sh
  cd *roty_directory/
```
e:
```sh
  https://github.com/JacanaFSilva/DeltaRunner.git
```

## 2: Depois de instalar as dependências, execute:

```sh
 cd *roty_directory/DetalRunner/Runner-preCompiledBuild
 pyinstaller runner.py
```

## 3: O arquivo runner.py irá compilar num executável e você poderá rodar o game.

*root_directory: by default "C:\Program Files"
<!--<h1 align="center">
  <img alt="Runner" src="public/images/logo.svg" height="100px" />
    <br>Runner, faster than sanic<br/>
</h1>
-->
