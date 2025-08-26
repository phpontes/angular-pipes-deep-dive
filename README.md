# Angular Pipes Demo

Este projeto foi desenvolvido com o objetivo de **praticar a criação e implementação de Pipes no Angular**.  
Foram criados pipes personalizados para manipulação de listas e conversão de temperaturas.

## 📌 Funcionalidades

- **SortPipe**  
  - Ordena listas de `string[]` ou `number[]`.  
  - Aceita a direção de ordenação (`asc` ou `desc`).  
  - Exemplo de uso:
    ```html
    <li *ngFor="let item of items | sort:'asc'">{{ item }}</li>
    ```

- **TemperaturePipe**  
  - Converte temperaturas entre Celsius (°C) e Fahrenheit (°F).  
  - Aceita valores do tipo `string` ou `number`.  
  - Exemplo de uso:
    ```html
    <p>{{ 25 | temp:'cel':'fah' }}</p> <!-- saída: 77.00 °F -->
    <p>{{ 86 | temp:'fah':'cel' }}</p> <!-- saída: 30.00 °C -->
    ```

## 🚀 Tecnologias Utilizadas

- [Angular](https://angular.io/)  
- TypeScript  
- HTML/CSS

## ▶️ Executando o Projeto

```bash
# Instalar dependências
npm install

# Rodar servidor de desenvolvimento
ng serve

# Acessar no navegador
http://localhost:4200/
```

## 📚 Objetivo

- Este projeto é apenas para estudo e prática de Angular Pipes, sendo uma base simples para compreender:
- Criação de pipes personalizados.
- Uso de pipes em templates.
- Aplicação prática em listas e dados numéricos.
