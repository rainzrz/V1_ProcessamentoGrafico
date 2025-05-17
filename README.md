# PGCCHIB - Processamento Gráfico

Este repositório é baseado na estrutura do projeto PGCCHIB - Processamento Gráfico, fornecido pela disciplina de Processamento Gráfico.

A atividade vivencial do dia 17 de maio foi implementada no arquivo Ex1Parte2M2.cpp, localizado em src/.

## 📂 Estrutura do Repositório
📂 PGCCHIB/
├── 📂 include/               # Arquivos de cabeçalho (incluir glad manualmente)
│   └── 📂 glad/
├── 📂 common/                # Código compartilhado (glad.c)
├── 📂 src/                   # Código-fonte dos exercícios
│   └── Ex1Parte2M2.cpp      # ✅ Atividade do dia 17 de maio
├── 📄 CMakeLists.txt         # Arquivo de build do CMake
├── 📄 GettingStarted.md      # Tutorial de configuração
└── 📄 README.md              # Documentação principal



Siga as instruções detalhadas em [GettingStarted.md](GettingStarted.md) para configurar e compilar o projeto.

## ⚠️ **IMPORTANTE: Baixar a GLAD Manualmente**
Para que o projeto funcione corretamente, é necessário **baixar a GLAD manualmente** utilizando o **GLAD Generator**.

### 🔗 **Acesse o web service do GLAD**:
👉 [GLAD Generator](https://glad.dav1d.de/)

### ⚙️ **Configuração necessária:**
- **API:** OpenGL  
- **Version:** 3.3+ (ou superior compatível com sua máquina)  
- **Profile:** Core  
- **Language:** C/C++  

### 📥 **Baixe e extraia os arquivos:**
Após a geração, extraia os arquivos baixados e coloque-os nos diretórios correspondentes:
- Copie **glad.h** para include/glad/
- Copie **khrplatform.h** para include/glad/KHR/
- Copie **glad.c** para common/

🚨 **Sem esses arquivos, a compilação falhará!** É necessário colocar esses arquivos nos diretórios corretos, conforme a orientação acima.