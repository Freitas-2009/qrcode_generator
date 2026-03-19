# 🔗 QR Code Generator

Gerador de QR Code simples feito em Python. Informe um texto ou URL, escolha o nome do arquivo e o QR Code é salvo automaticamente em uma pasta dedicada.

---

## 📋 Pré-requisitos

- Python 3.x
- pip

## 📦 Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
pip install qrcode pillow
```

## 🚀 Como usar

Execute o script:

```bash
python gerar_qrcode.py
```

O programa vai pedir duas informações:

```
Coloque o texto ou URL: https://www.twitch.tv/exemplo
Nome do arquivo (sem extensão): meu-qrcode
```

O QR Code será salvo na pasta `img/` com o nome que você escolheu.

> 💡 A pasta `img` é criada automaticamente caso não exista.

## 📁 Estrutura

```
📂 qrcode_generator
 ┣ 📂 img/            ← QR Codes gerados ficam aqui
 ┗ 📄 generator.py
```

## 🛠️ Tecnologias

- [qrcode](https://pypi.org/project/qrcode/) — geração do QR Code
- [Pillow](https://pypi.org/project/Pillow/) — exportação da imagem

## 📄 Licença

Este projeto está sob a licença MIT.
