# 🎤 Laboratório: Azure Speech Studio

**Explore recursos de conversão de fala em texto e síntese de voz personalizada.**

## 🎯 Objetivos
- Configurar um recurso de *Speech* no Azure.
- Transcrever áudio para texto em tempo real.
- Criar vozes personalizadas para cenários específicos.

---

## 📝 Passo a Passo

### 1. Configuração Inicial
1. **Crie um recurso no Azure Portal**  
   - Navegue até *Speech Services* e gere uma chave de API.
2. **Acesse o Speech Studio**  
   - Use a chave para autenticar no [Speech Studio](https://speech.microsoft.com).

### 2. Transcrição de Áudio
- **Faça upload de um arquivo de áudio** (formato WAV ou MP3).
- Selecione o idioma do áudio (ex: Português Brasileiro).
- **Resultado**: Texto transcrito com marcação de tempo.

### 3. Síntese de Voz
- **Personalize vozes**:
  - Escolha entre vozes pré-definidas (ex: "Maria" para PT-BR).
  - Ajuste velocidade e tom para aplicações de acessibilidade.

---

## 🔑 Funcionalidades-Chave
| Recurso               | Aplicação                         | 
|-----------------------|-----------------------------------|
| **🎙️ Transcrição em Tempo Real** | Call centers, legendas de vídeo. |
| **📢 Voz Personalizada**         | Assistentes virtuais, audiobooks. |

---

## ⚠️ Desafios Comuns
- **Latência em áudios longos**: Divida arquivos grandes em partes menores.
- **Ruído de fundo**: Use filtros de áudio ou modelos treinados para ambientes específicos.