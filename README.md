COMO INSTALAR O NIM

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
