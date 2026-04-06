📚 Trabalho P1 – Estrutura de Dados
Sistema de Gerenciamento de Fila de Atendimento
👨‍🏫 Objetivo

Desenvolver um sistema simples que simule uma fila de atendimento, utilizando obrigatoriamente o conceito de lista encadeada *.

O objetivo do trabalho é avaliar a compreensão de estruturas de dados dinâmicas e sua adaptação a diferentes linguagens de programação.
🧩 Contexto do Problema

Você deverá implementar um sistema que simula uma fila de atendimento, como por exemplo:

    Atendimento em banco
    Fila de hospital
    Atendimento em suporte técnico
    Restaurante ou fila de pedidos

⚙️ Funcionalidades obrigatórias

O sistema deve permitir:

    Inserir pessoa na fila
    Atender próxima pessoa (remoção do início)
    Exibir fila atual
    Buscar pessoa na fila
    Contar quantidade de elementos

🧠 Requisito Obrigatório

A estrutura de dados DEVE ser implementada manualmente como lista encadeada.

❌ Não é permitido (mas haverão exceções a depender da linguagem):

    Arrays
    Listas prontas da linguagem (List, Vec, ArrayList, etc.)

✔ Deve existir:

    Estrutura de nó (Node)
    Referência para o próximo elemento
    Controle da lista (head)

🖥️ Interface

Você pode escolher:

    Interface via terminal (CLI) - mais fácil
    Interface web simples - mais complexa tem pontuação extra

👨‍💻 Linguagens por aluno

Cada aluno deverá implementar o sistema na linguagem escolhida:

    Mahgid → Elixir
    Samuel → Rust
    Robert → Crystal
    João → Java
    Rafael → Nim
    Alberto → Julia
    Caio → Lean

🧠 Sobre ponteiros e referências

Nem todas as linguagens utilizam ponteiros da mesma forma.

Você deve implementar a lista encadeada respeitando o paradigma da linguagem:
Linguagem 	Modelo
Rust 	Ponteiros seguros (Box, Option)
Java 	Referências de objetos
Crystal 	Referências
Elixir 	Estrutura recursiva imutável
Nim 	Ponteiros ou referências (ref)
Julia 	Estruturas mutáveis com referência
Lean 	Tipo indutivo recursivo
📦 Entrega
🔹 Estrutura

Será utilizado um modelo com repositórios:

    1 repositório principal
    1 repositório por aluno

🔹 Repositório principal

Deve conter:

    Este enunciado
    Lista de links para os repositórios dos alunos
    Passo-a-passo de como instalar // rodar a sua aplicação localmente para critérios de correção.

Exemplo:

## Repositórios dos alunos

- Mahgid (Elixir): https://github.com/usuario/edc-p1-2026-projeto-elixir  
- Samuel (Rust): https://github.com/usuario/edc-p1-2026-projeto-rust  
- Robert (Crystal): https://github.com/usuario/edc-p1-2026-projeto-crystal  
- João (Java): https://github.com/usuario/edc-p1-2026-projeto-java  
- Rafael (Nim): https://github.com/usuario/edc-p1-2026-projeto-nim  
- Alberto (Julia): https://github.com/usuario/edc-p1-2026-projeto-julia  
- Caio (Lean): https://github.com/usuario/edc-p1-2026-projeto-lean  

🔹 Gravação da execução e lista de ferramentas

    Será necessário também que o aluno grave a sua própria tela durante o processo de codificação do projeto.
    Embora o uso de IA // LLMs seja permitido para auxiliar a implementação do projeto, é expressamente proibido copiar-e-colar código pronto gerado por qualquer outra ferramenta.
    Também será necessário listar exatamente quais ferramentas foram utilizadas para implementação do projeto.

Material de auxilio

Nesse mesmo repositório, há um arquivo langs.md com dicas de como criar listas encadeadas em cada uma das linguagens a serem utilizadas. deverá ser utilizado os exemplos como base para implementação do enunciado.

📋 Sistema de Fila - Trabalho 1 (Nim) 🚀

📥 Instalação do Nim (Guia Completo)
🖥️ 1. Requisitos do sistema

Antes de instalar, a máquina precisa ter:

✅ Requisitos mínimos:
Sistema operacional:
Windows 10 ou superior
Linux (Ubuntu, Debian, etc.)
macOS
Pelo menos 500 MB de espaço livre
Conexão com a internet (para baixar dependências)
⚠️ Importante:

O Nim depende de um compilador C para funcionar.
No Windows, vamos instalar isso automaticamente com uma ferramenta.

💻 2. Instalação no Windows (PASSO A PASSO COMPLETO)
🔽 Passo 1 — Baixar o instalador
Acesse o site oficial:
👉 https://nim-lang.org/install.html
Clique na opção:
“Windows” → “Install with choosenim”
⚙️ Passo 2 — Baixar o choosenim
Baixe o arquivo:
choosenim-*-windows_amd64.exe
Após baixar:
Clique duas vezes no arquivo
🧠 Passo 3 — Executar instalação
Vai abrir um terminal (prompt)
Pressione Enter para confirmar instalação padrão

👉 O instalador vai automaticamente:

Instalar o Nim
Configurar variáveis de ambiente
Instalar o gerenciador de pacotes (nimble)
Baixar o compilador necessário
🔁 Passo 4 — Reiniciar o terminal

Depois da instalação:

Feche o terminal
Abra novamente o Prompt de Comando ou PowerShell
✅ Passo 5 — Testar instalação

Digite:

nim --version

👉 Se aparecer a versão do Nim, está funcionando.

▶️ 3. Rodando seu primeiro programa
📄 Passo 1 — Criar arquivo

Crie um arquivo chamado:

main.nim
✍️ Passo 2 — Escrever código
echo "Olá, mundo!"
▶️ Passo 3 — Executar

No terminal, vá até a pasta do arquivo e rode:

nim c -r main.nim

👉 Isso faz duas coisas:

c → compila o código
-r → executa automaticamente
📦 4. Gerenciador de pacotes (Nimble)

O Nim já instala o nimble, que funciona como gerenciador de pacotes.

🔍 Testar:
nimble --version
📥 Exemplo de uso:
nimble install jester

👉 Isso instala bibliotecas externas (opcional)

🧰 5. Estrutura recomendada do projeto
/meu-projeto
 ├── main.nim
 ├── README.md
⚠️ 6. Problemas comuns (e solução)
❌ “nim não é reconhecido como comando”

✔️ Solução:

Reiniciar o computador
Ou reabrir o terminal
❌ Erro de compilação

✔️ Verifique:

Se digitou o comando correto:
nim c -r main.nim
❌ Antivírus bloqueando

✔️ Permita o programa (às vezes acontece no Windows)

VÍDEO DO DESENVOLVIMENTO:

https://www.youtube.com/watch?v=V-gpFIVDUGA
