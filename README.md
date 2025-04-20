# 🚀 API e Semantic Kernel Básico  

Bem-vindo ao repositório **API e Semantic Kernel Básico**! Aqui, você encontrará um resumo dos conceitos fundamentais sobre **Azure OpenAI API** e o **Semantic Kernel**, explorando desde chamadas de API até o funcionamento de agentes de IA.  

## 📌 Objetivo  
Este repositório serve como guia para compreender:  
✅ Como realizar chamadas de API para o **Azure OpenAI**.  
✅ A arquitetura e funcionalidades do **Semantic Kernel**.  
✅ O papel dos agentes de IA e como eles podem ser utilizados.  

## 🛠️ Pré-requisitos  
Antes de explorar este conteúdo, é recomendável:  
✔️ Ter acesso ao **Azure OpenAI**.  
✔️ Conhecer o básico de **Large Language Models (LLMs)**.  
✔️ Ter noções de **codificação** para chamadas de API.  

## 📚 O que você vai aprender?  
Aqui estão os principais tópicos abordados:  

### 🔹 Introdução ao Azure OpenAI API  
- Como utilizar os diferentes modos do **Azure OpenAI**:  
  ✅ **Chat**  
  ✅ **Completar**  
  ✅ **Imagens**  
  ✅ **Áudio**  
- Chamadas de API e parâmetros essenciais.  

### 🔹 Como realizar chamadas à API do Azure OpenAI  
- Exemplo de chamada usando **Python**:  
```python
client = AzureOpenAI(
    azure_endpoint = os.getenv("AZURE_OPENAI_ENDPOINT"),
    api_key=os.getenv("AZURE_OPENAI_API_KEY"),
    api_version="2024-02-01"
)

Método POST para enviar um prompt e obter uma resposta do modelo.

Configuração de variáveis importantes:

Model ID

Temperature

Max tokens

Top P

Presence/Frequency penalties

🔹 Explorando o Semantic Kernel
O que é o Semantic Kernel?

Papel como Middleware de IA para funções automatizadas.

Arquitetura básica do Semantic Kernel: ✅ Kernel ✅ Skills ✅ Functions ✅ Memory

🔹 Usando Semantic Kernel na prática
Como integrar API de busca rápida para armazenamento eficiente.

Vector Stores para otimizar a recuperação de dados.

Filtros para refinamento das respostas.

🔹 Segurança e Monitoramento
✔️ Dados seguros no Azure. ✔️ Utilização de Azure Monitor para acompanhamento de logs e métricas.

🔗 Links Úteis
Aqui estão algumas referências para aprofundar seus estudos:

Azure OpenAI API Reference

Monitorando chamadas de API no Azure

Introdução ao Semantic Kernel

🤝 Dúvidas?
Caso tenha dúvidas ou queira trocar conhecimento, acesse os fóruns e artigos da comunidade: 🔗 DIO - Fórum & Artigos
