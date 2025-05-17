💻 Atividade Vivencial - 17 de Maio
Este repositório é baseado na estrutura do projeto PGCCHIB - Processamento Gráfico, fornecido pela disciplina de Processamento Gráfico.

A atividade vivencial do dia 17 de maio foi implementada no arquivo Ex1Parte2M2.cpp, localizado em src/.

🗂 Estrutura Relevante
plaintext
Copiar
Editar
📂 PGCCHIB/
├── 📂 include/               # Arquivos de cabeçalho (incluir glad manualmente)
│   └── 📂 glad/
├── 📂 common/                # Código compartilhado (glad.c)
├── 📂 src/                   # Código-fonte dos exercícios
│   └── Ex1Parte2M2.cpp      # ✅ Atividade do dia 17 de maio
├── 📄 CMakeLists.txt         # Arquivo de build do CMake
├── 📄 GettingStarted.md      # Tutorial de configuração
└── 📄 README.md              # Documentação principal
📝 Descrição da Atividade (Ex1Parte2M2.cpp)
Neste exercício foram trabalhados os seguintes conceitos:

Configuração básica de um contexto OpenGL.

Utilização de vértices para desenhar primitivas.

Transformações básicas (se aplicável).

Prática com shaders e buffers (dependendo do conteúdo abordado na aula).

⚙️ Como Compilar
Siga os passos do arquivo GettingStarted.md do repositório original para configurar e compilar o projeto usando CMake. Lembre-se de garantir que os arquivos da GLAD estejam no local correto:

include/glad/glad.h

include/glad/KHR/khrplatform.h

common/glad.c

🧩 Dependências
GLAD (gerado manualmente via GLAD Generator)

GLFW

OpenGL 3.3 Core Profile

📌 Observações
Certifique-se de que os arquivos da GLAD estejam posicionados corretamente.

A pasta build/ deve ser criada manualmente e não está incluída no repositório.

Em caso de erro de compilação, verifique os diretórios indicados e o CMakeLists.txt.