# ⏱️ Cronômetro e Temporizador Web

Aplicação web leve que integra um **cronômetro** e um **temporizador regressivo**, desenvolvida inteiramente em **HTML, CSS e JavaScript** sem frameworks externos.

## 📋 Sumário

- [Visão Geral](#visão-geral)
- [Funcionalidades](#funcionalidades)
- [Estrutura do Código](#estrutura-do-código)
- [Instalação e Uso](#instalação-e-uso)
- [Detalhes do Código](#detalhes-do-código)
- [Sugestões de Melhoria](#sugestões-de-melhoria)
- [Licença](#licença)

---

## 🧐 Visão Geral

Este projeto apresenta uma solução para medição de tempo: um cronômetro que permite voltas e um temporizador com alerta sonoro. Totalmente responsivo, utiliza **tema escuro** e interface amigável.

---

## 🚀 Funcionalidades

### Cronômetro
- Iniciar, pausar, retomar e resetar
- Registrar voltas (laps)
- Exibição do tempo em `HH:MM:SS`
- Histórico de voltas rolável

### Temporizador
- Definição do tempo (minutos/segundos)
- Iniciar, pausar, retomar e resetar
- Alerta sonoro ao terminar (`alarm_clock.ogg`)
- Contagem regressiva exibida em `MM:SS`

---

## 📁 Estrutura do Código

O projeto possui **um único arquivo principal**:

```
index.html
```
- Inclui HTML (estrutura da interface), CSS (visual e layout) e JavaScript (lógica e interações) de forma embutida.

---

## 🛠️ Instalação e Uso

1. **Clone ou baixe o repositório:**
    ```bash
    git clone https://github.com/lucasFR2/Cronometro-Temporizador.git
    ```
2. **Abra o arquivo `index.html` em qualquer navegador moderno.**
3. **Utilize normalmente**. Não requer instalação adicional!

**OBS:** Compatível com Windows, Linux, macOS, smartphones e tablets.

---

## 📑 Detalhes do Código

### Estrutura do HTML
- **Seção do Cronômetro**
  - Visor do tempo
  - Botões: Iniciar, Pausar/Retomar, Volta, Parar
  - Lista de voltas
- **Seção do Temporizador**
  - Inputs para minutos/segundos
  - Visor
  - Botões: Iniciar, Pausar/Retomar, Parar

### Principais Estilos CSS
- Layout centralizado e flexível
- Tema dark elegante
- Botões, inputs e cards personalizados
- Lista de voltas com rolagem

### Funções JavaScript Chave

#### Cronômetro

| Função                          | Papel                                                          |
| --------------------------------| -------------------------------------------------------------- |
| `atualizarCronometro()`         | Atualiza o visor de tempo                                      |
| `iniciarCronometro()`           | Inicia a contagem                                              |
| `pausarOuRetomarCronometro()`   | Pausa/retoma o cronômetro                                      |
| `resetarCronometro()`           | Reseta todos os valores e histórico de voltas                  |
| `registrarVolta()`              | Adiciona o tempo atual na lista de voltas                      |

#### Temporizador

| Função                          | Papel                                                          |
| --------------------------------| -------------------------------------------------------------- |
| `atualizarTimer()`              | Atualiza o visor de contagem regressiva                        |
| `iniciarTimer()`                | Inicia a contagem do temporizador                              |
| `pausarOuRetomarTimer()`        | Pausa/retoma a contagem                                        |
| `resetarTimer()`                | Reseta o contador                                              |

#### Outros Pontos
- Manipulação de eventos via `addEventListener`
- Atualização dos visores via DOM dinâmico
- Geração do alerta sonoro ao terminar o temporizador
- Controle total de estado: rodando / pausado / zerado

---

## 💡 Sugestões de Melhoria

- Adicionar testes automatizados (unitários para funções JS)
- Internacionalização (i18n)
- Temas customizáveis
- Exportação das voltas para CSV
- Adaptação para PWA (instalável no celular)

---

**Dúvidas, sugestões ou problemas? Abra uma [issue](https://github.com/lucasFR2/Cronometro-Temporizador/issues)!**
