# Git e Github - Entendendo como o Git funciona por baixo dos panos. 

- **SHA1:**
sigla **SHA** significa secure hash algorithm (algoritmo de hash seguro), é um conjunto de funções hash criptográficas projetas pela **NSA**.

**A encriptação gera conjunto de caracteres identificador de 40 dígitos.** 

*forma curta de representar um arquivo.* 


- **Objetos fundamentais**
- **Sistema distribuído** 
- **Segurança**

## Git e Github - Objetos internos do Git

**Objetos:**
**BLOBS:**
"**O que é blob em Git?**
Cada arquivo no Git é armazenado como um objeto blob, por exemplo, a partir do conteúdo do arquivo logo.png ele gera um hash que será armazenado em algum lugar endereçável como aa1b2fb696a831c89c53f787e03d863691d2b671 . O mesmo ocorre com o arquivo app.css"

**TREES**
As Trees armazenam blobs, responsável por montar a estrutura de onde estão localizados os arquivos. 

**COMMITS**
objeto mais importante, junta tudo.

O comando git commit captura um instantâneo das mudanças preparadas do projeto no momento. Os instantâneos com commit podem ser considerados versões "seguras" de um projeto, o Git nunca os altera, a menos que você peça a ele.

**Chave SSH:**
é uma forma de estabelecer uma conexão segura e encriptada entre duas maquinas.
(com duas chaves: publica e privada, entre o github e o computador atual)

**Tracked ->** arquivo que o git tem ciência deles
**Untracked ->** arquivos que o git não tem ciência deles.

**Unmodified > Modified > Staged**

Git compara os **SHA1** para ver que o arquivo teve alguma modificação.

ao digitar o comando git add -> o arquivo muda seu status pra **stage (aguardando)**

**Commit retorna pra unmodified.**

**dois Ambientes:**

**Servidor -> Remote Repository (GitHub)**

**Ambiente de Desenvolvimento (minha maquina)**

**Working Directory > Staging Area > Local Repository** 

**Adiciona arquivo que era Untracked > dar Git Add > se move pra Staging Area**

**Arquivos se transitando por Working Directory e Staging Area** 

**Git Commit > Move arquivos na area Staging Area pro Local Repository.**