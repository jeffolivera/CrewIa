# 🤖 Projeto de Estudos com CrewAI

Este repositório contém experimentações e estudos utilizando a ferramenta **[CrewAI](https://docs.crewai.com/)**, voltada para orquestração de agentes autônomos com LLMs. O objetivo é explorar e compreender as capacidades da ferramenta, criando fluxos inteligentes e colaborativos entre múltiplos agentes.

---

## 📚 Sobre o Projeto

Este projeto tem caráter educacional e explora:

- Criação e configuração de agentes com objetivos distintos;
- Colaboração entre agentes para execução de tarefas complexas;
- Integração com LLMs e ferramentas externas;
- Simulação de fluxos autônomos multiagente.

Todos os testes foram feitos com foco em aprendizado prático, visando futuras aplicações em automações, atendimento inteligente e soluções baseadas em IA.

---

## 🧠 Tecnologias Utilizadas

- **Python 3.10+**
- **CrewAI** – Framework de agentes colaborativos
- **LangChain** – Para integração com LLMs
- **OpenAI API** (ou outra LLM de sua escolha)
- **Docker** (opcional, para isolamento do ambiente)

---

## 🧪 Estrutura do Projeto

```bash
📁 Multi-agents planejamento de viagens/
├── agents.ipynb         # Definições de agentes, tasks e execução
├── requirements.txt     # Dependências do projeto
└── README.md            # Este documento
```
## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/jeffolivera/CrewIa.git
cd Multi-agents planejamento de viagens
```
2. Rode o comando: criação do ambiente virtual (certifique-se de ter o python instalado)
```bash
python3 -m venv .venv
```

3. Rode o comando: entrar no abiente virtual
```bash
./.venv/bin/activate
```

- No meu caso é:
```bash
source ./.venv/bin/activate (eu uso Ubuntu)
```

4. Verifique se dentro do ambiente virtual o pip setuptools está na lista com o comando: (certifique-se de ter o pip instalado)
```bash
pip list
```

5. Caso o setuptools esteja instalado, siga para o proximo passo. Caso não estiver instalado, rode o comando:
```bash
pip install setuptools
```

6. Rode o comando: (comando para instalar o dotenv)
```bash
pip install dotenv
```

7. Instale as dependências:
```bash
pip install -r requirements.txt
```
8. Configure suas credenciais (por exemplo, OpenAI API Key) em um .env:
```bash
OPENAI_API_KEY=your_api_key_here
```
9. Executar o projeto

## 📌 Objetivos de Aprendizado

- Entender o funcionamento básico do CrewAI
- Criar múltiplos agentes com especializações distintas
- Implementar ferramentas personalizadas
- Testar fluxos colaborativos com sucesso

## ✍️ Autor
Jeferson Oliveira
Desenvolvedor | Entusiasta em IA
**[LinkedIn](https://www.linkedin.com/in/jeferson-oliveira-dev/)
