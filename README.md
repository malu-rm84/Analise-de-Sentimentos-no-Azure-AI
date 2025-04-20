# 🎤 Laboratório de Fala & Linguagem com Azure

**Explore recursos de IA para análise de texto, síntese de voz e chatbots inteligentes usando Azure Speech Studio e Language Studio.**  
*(Documentação técnica do projeto desenvolvido durante o laboratório prático)*  

---

## 📌 Índice Rápido
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Laboratórios Passo a Passo](#-laboratórios-passo-a-passo)
- [Recursos Úteis](#-recursos-úteis)

---

## 🚀 Funcionalidades Principais

| Recurso                  | Descrição                                                                 |
|--------------------------|---------------------------------------------------------------------------|
| **📊 Análise de Sentimentos** | Detecta emoções em textos (positivo/negativo/neutro) e palavras-chave. |
| **🎙️ Reconhecimento de Fala** | Converte áudio em texto com alta precisão em múltiplos idiomas. |
| **🤖 Chatbots Inteligentes**  | Criação de bots com NLP para atendimento automático em sites e apps. |
| **🌍 Detecção de Idiomas**   | Identifica automaticamente o idioma de textos ou áudios. |

---

## 🔬 Laboratórios Passo a Passo

### 🎤 **Speech Studio Lab**
1. **Configuração de Recursos**  
   - Crie um recurso de *Speech* no Azure Portal e obtenha a chave de API.
2. **Transcrição de Áudio**  
   - Faça upload de arquivos de áudio para gerar transcrições em texto.
3. **Síntese de Voz**  
   - Personalize vozes para aplicações usando modelos pré-treinados ou customizados.

  ```python
     # Exemplo: Converter áudio em texto
     from azure.cognitiveservices.speech import SpeechRecognizer
     recognizer = SpeechRecognizer(subscription_key="SUA_CHAVE")
     result = recognizer.recognize_once()
     print(result.text)
  ```

### 📚 **Language Studio Lab**
1. **Análise de Texto**  
   - Insira textos para extrair sentimentos, entidades (locais, datas) e frases-chave.
2. **Classificação Personalizada**  
   - Treine modelos para categorizar textos conforme regras específicas (ex: feedback de clientes).
  
  ```text
  Exemplo de entrada:
  "Adorei o serviço rápido, mas o preço é alto."
  
  Saída:
  - 😊 Sentimento: 70% positivo
  - 🔑 Palavras-chave: "serviço rápido", "preço alto"
  ```
---

## 🛠️ Recursos Úteis
| Ferramenta                  | Link                                                                 |
|-----------------------------|---------------------------------------------------------------------|
| **Documentação do Speech Studio** | [🔗 Acessar](https://speech.microsoft.com) |
| **Guia do Language Studio** | [🔗 Acessar](https://learn.microsoft.com/pt-bp/azure/language-studio) |
| **Azure Bot Service**       | [🔗 Criar um Bot](https://azure.microsoft.com/pt-bp/services/bot-services/) |

---

Feito por Malu ⭐
