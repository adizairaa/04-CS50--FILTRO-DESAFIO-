# 📷 Recuperador de Imagens JPEG

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![C](https://img.shields.io/badge/Linguagem-C-blue)
![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-green)

## 📝 Descrição

Este programa em C recupera imagens JPEG de um arquivo binário. Ele lê blocos de 512 bytes e detecta assinaturas de arquivos JPEG, extraindo e salvando cada imagem encontrada.

## 🚀 Como Usar

1. Compile o programa:
   ```sh
   gcc -o recover recover.c
   ```

2. Execute o programa passando o arquivo de imagem corrompido como argumento:
   ```sh
   ./recover arquivo.bin
   ```

3. O programa criará arquivos JPEG numerados (`000.jpg`, `001.jpg`, etc.) automaticamente.

## 🖥️ Requisitos

- Compilador GCC
- Ambiente Linux/macOS/Windows com WSL

## ⚙️ Funcionamento

🔹 Abre o arquivo binário de entrada 📂  
🔹 Lê blocos de 512 bytes 🔄  
🔹 Identifica a assinatura de arquivos JPEG 🖼️  
🔹 Cria arquivos `.jpg` separadamente 📝  

## 📌 Exemplo de Uso

```sh
$ ./recover card.raw
```

## 📜 Licença

Este projeto está licenciado sob a licença MIT. 📝



