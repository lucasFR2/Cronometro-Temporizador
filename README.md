# Cronômetro e Temporizador – Aplicação Web

Aplicação simples que combina um **cronômetro** e um **temporizador regressivo**, desenvolvida em **HTML, CSS e JavaScript puro**.
Projeto leve, funcional e fácil de utilizar.

---

## 📌 Funcionalidades

### **Cronômetro**

* Iniciar, pausar e retomar
* Parar (reset)
* Registrar voltas
* Exibição: `HH:MM:SS`
* Lista de voltas com rolagem

### **Temporizador**

* Definição de minutos e segundos
* Iniciar, pausar e retomar
* Parar (reset)
* Alerta sonoro ao finalizar
* Exibição: `MM:SS`

---

## 🧩 Estrutura do Projeto

A aplicação utiliza apenas um arquivo HTML contendo:

### **HTML**

* Seção do cronômetro (display, botões, voltas)
* Seção do temporizador (inputs, display, botões)

### **CSS**

* Tema escuro
* Layout centralizado
* Estilização de cards, botões e inputs

### **JavaScript**

Toda a lógica da aplicação está incluída no arquivo:

#### **Lógica do Cronômetro**

* Controle de horas, minutos e segundos
* Estados: rodando / pausado
* Funções principais:

  * `atualizarCronometro()`
  * `iniciarCronometro()`
  * `pausarOuRetomarCronometro()`
  * `resetarCronometro()`
  * `registrarVolta()`

#### **Lógica do Temporizador**

* Contagem regressiva
* Estados: rodando / pausado
* Funções principais:

  * `atualizarTimer()`
  * `iniciarTimer()`
  * `pausarOuRetomarTimer()`
  * `resetarTimer()`

---

## 🚀 Como Usar

### **Cronômetro**

1. Clique em **Iniciar**
2. Utilize **Pausar / Retomar**
3. Clique em **Volta** para registrar tempos
4. Clique em **Parar** para zerar

### **Temporizador**

1. Informe minutos e segundos
2. Clique em **Iniciar**
3. Utilize **Pausar / Retomar**
4. Ao finalizar, um som será reproduzido

---

## 🔔 Som do temporizador

O temporizador utiliza o seguinte áudio:

```
https://actions.google.com/sounds/v1/alarms/alarm_clock.ogg
```

---

## ✔️ Observações

* Código 100% em HTML, CSS e JavaScript
* Funciona em qualquer navegador moderno
* Ideal para estudos ou uso pessoal

---

