# Parte 2 - Prova Módulo 4

## Semáforo Inteligente com ESP32

### 1. Estado Inicial
- **Descrição**: Todos os LEDs estão apagados. O sistema está pronto para começar a monitorar a luminosidade e responder às interações do botão.
- **Comportamento esperado**: 
  - LED verde: apagado
  - LED amarelo: apagado
  - LED vermelho: apagado
- **Print**:
  ![estado inicial](https://github.com/user-attachments/assets/ad1d6e8d-96ba-4bab-b2fe-81ddebdd68ed)

  

### 2. Modo Noturno
- **Descrição**: Quando a luminosidade detectada pelo sensor LDR está abaixo do limiar, o sistema entra no modo noturno.
- **Comportamento esperado**: 
  - LED amarelo: piscando a cada 1 segundo
  - LED verde: apagado
  - LED vermelho: apagado
- **Print**:
  ![modo noturno](https://github.com/user-attachments/assets/a8c847fa-6e74-4035-ab2a-60a3acb0f79c)

  

### 3. Modo Convencional
- **Descrição**: Quando a luminosidade detectada pelo sensor LDR está acima do limiar, o sistema entra no modo convencional.
- **Comportamento esperado**:
  - LEDs alternam nas seguintes sequências:
    1. **LED verde**: aceso por 3 segundos
    2. **LED amarelo**: aceso por 2 segundos
    3. **LED vermelho**: aceso por 5 segundos
- **Print**:
![vermelho](https://github.com/user-attachments/assets/ef2e1512-8fb7-4cfe-85ff-ad43bc1fa3a6)
![verde](https://github.com/user-attachments/assets/3736ef46-b452-471e-a4e5-fb680d5842e3)
![amarelo](https://github.com/user-attachments/assets/3b9e049f-9c25-4acb-afb7-2077288d903e)


### 4. Botão Pressionado no LED Vermelho
- **Descrição**: Quando o sistema está no modo convencional e o LED vermelho está aceso, pressionar o botão fará com que o sistema mude para o LED verde após 1 segundo.
- **Comportamento esperado**: 
  - LED vermelho: aceso
  - Após pressionar o botão: LED verde aceso após 1 segundo
- **Print**:
![verde](https://github.com/user-attachments/assets/2eb92183-8636-4d1b-ba97-b9e178578493)
