# 🤖 Teste-Robot-framework

Bem-vindo ao **Teste-Robot-framework**! 🚀 Uma aplicação que utiliza o poder do **Robot Framework** para automação de testes. Este projeto foi criado para demonstrar boas práticas em automação de processos e garantir a qualidade em diferentes cenários de teste.

---

## 🚀 Sobre o Projeto

O **Teste-Robot-framework** é uma automação desenvolvida com o **Robot Framework**, uma ferramenta popular para testes automatizados e RPA (Robotic Process Automation). Ele foi projetado para atender a:

- 🧪 Testes funcionais de aplicações web.
- 🔄 Execução de tarefas repetitivas.
- 🏅 Garantia de qualidade e eficiência em processos de software.

---

## 🛠️ Tecnologias Utilizadas

- **Robot Framework**: Framework principal para escrita e execução dos testes.
- **Python**: Linguagem de programação subjacente ao Robot Framework.
- **SeleniumLibrary**: Biblioteca para interação com navegadores web.
- **pip**: Gerenciador de pacotes do Python para instalar dependências.

---

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter os seguintes itens instalados:

- **Python** (versão 3.7 ou superior) 🐍
- **pip** (gerenciador de pacotes do Python) 📦
- **Git** (para clonar o repositório) 🧑‍💻

---

## 🔧 Instalação

Siga os passos abaixo para configurar o ambiente:

1. Clone este repositório:

```bash
git clone https://github.com/Dev-jrleal/projeto-robot.git
cd projeto-robot
```

2. Crie um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate   # Para Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

---

## ▶️ Como Executar

1. Certifique-se de que todas as dependências estão instaladas.
2. Execute os testes com o seguinte comando:

```bash
robot -d results tests/
```

- `-d results`: Define o diretório onde os relatórios serão salvos.
- `tests/`: Pasta que contém os arquivos de teste.

Após a execução, consulte os relatórios gerados em `results/output.html`.

---

## 📁 Estrutura do Projeto

```plaintext
projeto-robot/
├── tests/                # Arquivos de teste (Robot Framework)
│   ├── login.robot       # Testes relacionados ao login
│   ├── cadastro.robot    # Testes relacionados ao cadastro de usuários
│   └── ...
├── resources/            # Recursos reutilizáveis (keywords, variáveis, etc.)
│   ├── keywords.robot    # Custom keywords
│   ├── variables.robot   # Variáveis globais
│   └── ...
├── results/              # Resultados dos testes
├── requirements.txt      # Dependências do projeto
└── README.md             # Documentação do projeto
```

---

## 📝 Contribuindo

Contribuições são **bem-vindas**! Para contribuir, siga os seguintes passos:

1. Faça um **fork** deste repositório.
2. Crie uma **branch** para sua feature ou correção de bug:

```bash
git checkout -b minha-feature
```

3. Faça suas alterações e envie um **pull request**.

---

Agora o README está com uma estrutura mais dinâmica e visualmente atrativa! 😄


 
