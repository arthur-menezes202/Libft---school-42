# 📚 Libft - Biblioteca de Funções C Padrão (42 School)

[](https://github.com/arthur-menezes202/Libft---school-42)
[](https://en.wikipedia.org/wiki/C_\(programming_language\))
[](https://www.42sp.org.br/)

## 📝 Visão Geral do Projeto

**Libft** é o primeiro projeto fundamental do currículo da **42 School**. Ele exige a criação de uma biblioteca de funções em linguagem C que recria e expande diversas funcionalidades da biblioteca padrão do C (`<string.h>`, `<stdlib.h>`, `<ctype.h>`, etc.).

Este projeto serve como uma prova de proficiência no uso da linguagem C e na compreensão de estruturas de dados e ponteiros, além de estabelecer a base essencial de funções que serão utilizadas em todos os projetos futuros da 42.

## 🎯 Objetivo de Aprendizagem

O desenvolvimento da Libft permitiu aprofundar o conhecimento nos seguintes conceitos:

  * **Manipulação de Ponteiros e Alocação de Memória:** Implementação segura e eficiente de funções que lidam com alocação dinâmica (`malloc`, `free`) e manipulação direta de memória (`memcpy`, `memset`).
  * **Compreensão da Biblioteca Padrão:** Desconstrução e recriação das funções essenciais do C, fornecendo uma visão profunda de seu funcionamento interno.
  * **Boas Práticas de Código:** Cumprimento de um rigoroso padrão de codificação (norminette) e regras de desenvolvimento que garantem código limpo, legível e robusto.

## 🛠️ Funções Implementadas

O projeto está dividido em três categorias de funções:

### Parte 1: Funções da Biblioteca Padrão

Recriação de funções essenciais da biblioteca C padrão (ex: `<ctype.h>`, `<string.h>`, `<stdlib.h>`).

| Função | Descrição |
| :--- | :--- |
| `ft_isalpha` | Verifica se um caractere é alfabético. |
| `ft_strlen` | Calcula o comprimento de uma *string*. |
| `ft_bzero` | Preenche um bloco de memória com zeros. |
| `ft_memcpy` | Copia um bloco de memória para outro. |
| `ft_atoi` | Converte *string* para inteiro. |
| *e mais...* | |

### Parte 2: Funções Adicionais da Libft

Funções que não existem na biblioteca C padrão e são cruciais para a continuação do currículo da 42.

| Função | Descrição |
| :--- | :--- |
| `ft_substr` | Retorna uma *substring* a partir de uma *string* original. |
| `ft_strjoin` | Concatena duas *strings* em uma nova alocada dinamicamente. |
| `ft_split` | Divide uma *string* usando um caractere delimitador. |
| `ft_itoa` | Converte um inteiro em sua representação em *string*. |
| *e mais...* | |

### Parte Bônus: Manipulação de Listas Ligadas

Funções essenciais para trabalhar com estruturas de dados de **lista ligada simples** (`t_list`).

| Função | Descrição |
| :--- | :--- |
| `ft_lstnew` | Cria um novo nó. |
| `ft_lstadd_front` | Adiciona um nó no início da lista. |
| `ft_lstsize` | Conta o número de elementos na lista. |
| `ft_lstclear` | Remove e libera a memória de todos os nós. |
| *e mais...* | |

## ⚙️ Instalação e Uso

### Compilação

Para compilar a biblioteca (`libft.a`), clone o repositório e execute o `make` no diretório raiz:

```bash
git clone https://github.com/arthur-menezes202/Libft---school-42.git
cd Libft---school-42
make
```

O comando `make` irá gerar o arquivo **`libft.a`**.

### Incluindo em um Projeto

Para usar a `Libft` em seu próprio projeto C, você deve:

1.  Incluir o arquivo de cabeçalho (`header`): `#include "libft.h"`
2.  Compilar seu projeto C (`main.c`) junto com a biblioteca (`libft.a`).

**Exemplo de Comando de Compilação:**

```bash
gcc -Wall -Wextra -Werror main.c libft.a -o meu_programa
```

## 🧑‍💻 Autor

| [](https://www.google.com/search?q=https://github.com/arthur-menezes202) | **Arthur Menezes** |
| :---: | :--- |
| | **Perfil GitHub:** [@arthur-menezes202](https://www.google.com/search?q=https://github.com/arthur-menezes202) |
| | **School 42:** armeneze |
