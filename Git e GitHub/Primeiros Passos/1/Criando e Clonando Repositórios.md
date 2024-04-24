![[Criando e Clonando Repositórios.png]]

# Comandos

```bash
git init
```
Esse comando inicializa um novo repositório Git no diretório atual.

---

```bash
git clone URL nome-do-diretorio-local
```
Esse comando clona um repositório Git da URL especificada e o salva em uma pasta local com o nome fornecido.

---
```bash
git remote add origin URL
```
Esse comando adiciona um novo repositório remoto chamado "origin" com a URL especificada.

---
```bash
git clone URL --branch feature-1 --single-branch
```
Esse comando clona um repositório Git da URL especificada, mas apenas a partir do ramo (branch) "feature-1" e com um único ramo.