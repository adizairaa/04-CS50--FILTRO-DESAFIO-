# Filtro de Imagem BMP

Este repositório contém a implementação de um programa em C que aplica diferentes filtros a imagens no formato BMP de 24 bits. O programa permite converter imagens para escala de cinza, refletir, desfocar e detectar bordas usando o operador Sobel.

## Funcionalidades

O programa oferece quatro filtros principais:

1. **Escala de Cinza** - Converte a imagem em preto e branco, mantendo os níveis de brilho.
2. **Reflexão** - Espelha a imagem horizontalmente.
3. **Desfoque (Blur)** - Aplica o efeito "box blur", suavizando a imagem.
4. **Detecção de Bordas** - Utiliza o operador Sobel para destacar contornos na imagem.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `bmp.h` - Define estruturas e tipos utilizados para manipular arquivos BMP.
- `filter.c` - Contém a função `main` que gerencia a execução do programa.
- `helpers.h` - Cabeçalho com a definição das funções auxiliares.
- `helpers.c` - Implementa os filtros mencionados.
- `Makefile` - Arquivo para compilar o programa.
- `images/` - Contém imagens BMP de amostra para teste.

## Instalação e Uso

### Passo 1: Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/filter-bmp.git
cd filter-bmp
```

### Passo 2: Compilar o Programa
```sh
make filter
```

### Passo 3: Executar o Programa
O programa pode ser executado com a seguinte sintaxe:
```sh
./filter [opção] imagem_entrada.bmp imagem_saida.bmp
```

Onde `[opção]` pode ser:
- `-g` para escala de cinza
- `-r` para reflexão
- `-b` para desfoque
- `-e` para detecção de bordas

Exemplo de uso:
```sh
./filter -r imagem.bmp refletida.bmp
```



## Contribuição
Contribuições são bem-vindas! Para contribuir:
1. Fork este repositório.
2. Crie uma branch (`git checkout -b minha-feature`).
3. Implemente sua melhoria.
4. Envie um pull request.

## Licença
Este projeto é licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Desenvolvido como parte do curso CS50 da Universidade de Harvard.

