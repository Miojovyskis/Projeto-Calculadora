# 🧮 Calculadora Simples em Bash

Projeto simples criado para praticar comandos básicos do Linux, criação de scripts Bash e permissões de arquivos.

---

# 📋 Objetivo

Este script realiza operações matemáticas simples utilizando o Bash:

* Soma
* Subtração
* Multiplicação
* Divisão

Foi desenvolvido como exercício para aprender:

* Criação de arquivos no Linux
* Edição de arquivos com Nano
* Permissões com chmod
* Execução de scripts Bash

---

# 📂 Criando o Arquivo

Crie o arquivo usando o Nano:

```bash
nano calculadora.sh
```

---

# 💻 Código

```bash
#!/bin/bash

echo "10 + 5 = $((10 + 5))"
echo "10 - 5 = $((10 - 5))"
echo "10 * 5 = $((10 * 5))"
echo "10 / 5 = $((10 / 5))"
```

---

# 🔐 Permissões

Permita a execução do script:

```bash
chmod +x calculadora.sh
```

Ou defina permissões específicas:

```bash
chmod 744 calculadora.sh
```

### Significado do 744

| Número | Permissão                   |
| ------ | --------------------------- |
| 7      | Leitura, escrita e execução |
| 4      | Somente leitura             |
| 4      | Somente leitura             |

---

# ▶️ Executando

Execute o script com:

```bash
./calculadora.sh
```

---

# 📸 Saída Esperada

```text
10 + 5 = 15
10 - 5 = 5
10 * 5 = 50
10 / 5 = 2
```

---

# 🚀 Tecnologias Utilizadas

* Linux
* Bash Script
* Nano
* Terminal

---

# 📚 Conhecimentos Praticados

* Navegação no Linux
* Criação de arquivos
* Edição de arquivos
* Permissões de execução
* Operações matemáticas em Bash

---

# 👨‍💻 Autor

Projeto desenvolvido por Luiz Fellipe durante os estudos de Linux e programação.

