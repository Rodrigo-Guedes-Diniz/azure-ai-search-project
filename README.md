# 🔎 Projeto: Azure AI Search – Pesquisa Cognitiva com Inteligência Artificial

## 📌 Objetivo
Demonstrar como configurar e utilizar a **Pesquisa Cognitiva do Azure (Azure AI Search)** para extrair insights avançados de documentos usando IA e tornar os dados pesquisáveis com significado.

---

## 🧭 Passo a passo para configurar uma pesquisa

### 1. Criar um serviço de Azure Cognitive Search
- Acesse o portal do Azure
- Crie um recurso do tipo “**Azure Cognitive Search**”
- Escolha a camada gratuita (F para testes iniciais)

### 2. Preparar os dados
- Faça upload de documentos (PDF, JSON, TXT, etc.) no **Azure Blob Storage**
- Esses documentos serão a fonte dos dados

### 3. Criar um índice de pesquisa
- Vá até seu serviço de Search
- Crie um **Data Source** conectando ao Blob Storage
- Configure um **Skillset** para aplicar técnicas de IA como:
  - Extração de texto
  - Reconhecimento de entidades (nomes, lugares, organizações)
  - Detecção de idioma
  - Análise de sentimentos
- Crie um **Index** com os campos desejados (ex: conteúdo, título, data)

### 4. Explorar o índice (via portal ou API)
- Use a **interface visual no portal do Azure** para fazer buscas
- Exemplo: buscar por termos e ver documentos relevantes com destaque de trechos

---

## 💡 Insights e Aprendizados

- A pesquisa cognitiva **vai além da busca por palavras-chave**. Ela entende contexto e estrutura dos dados.
- O uso de **IA embutida**, como PLN (Processamento de Linguagem Natural), permite análises automáticas em grandes volumes de texto.
- É possível integrar com **aplicativos web, bots, sistemas de CRM e muito mais**.
- Ajuda muito em áreas como **jurídico, financeiro, saúde, atendimento ao cliente e gestão de documentos.**

---

## 🛠️ Ferramentas que podem se beneficiar
- **Intranets corporativas** com busca inteligente
- **Sistemas de atendimento ao cliente**
- **Gerenciadores de conteúdo**
- **Dashboards de Business Intelligence com dados pesquisáveis**
- **Assistentes virtuais empresariais**

---

## ✅ Conclusão

Esse projeto mostra como é possível **combinar IA + pesquisa** para transformar dados não estruturados em **informações úteis e acessíveis**. Ferramentas como o **Azure AI Search** estão democratizando o uso de inteligência artificial, sem a necessidade de código complexo.

---

## 📸 Prints e Resultados

> Inclua aqui imagens do portal Azure com:
> - Criação do índice
> - Resultado das buscas
> - Habilidades aplicadas nos documentos
