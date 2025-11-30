# Projeto de Portfólio: Robô Remoto de Vigilância e Interação (Full-Stack e IoT)

Este projeto demonstra a capacidade de desenvolver uma solução completa de Internet das Coisas (IoT) e Full-Stack, integrando hardware, software, controlo remoto via web, processamento de dados e comandos de voz.

## O Desafio

O objetivo principal foi conceber e construir um **Robô Remoto de Vigilância e Interação** de baixo custo, capaz de ser controlado a partir de qualquer lugar através de uma interface web intuitiva. O desafio técnico residiu na integração de múltiplos sistemas: a comunicação em tempo real entre o hardware (Raspberry Pi e motores) e o frontend web, e a implementação de funcionalidades avançadas como o controlo por voz e a monitorização do sistema.

## Solução e Funcionalidades Chave

O projeto resultou num sistema robusto com as seguintes funcionalidades de alto impacto:

1.  **Controlo Remoto Full-Stack:** Interface web responsiva para controlo total dos movimentos do robô (WASD), garantindo uma experiência de utilizador fluida e imediata.
2.  **Streaming de Vídeo e Captura em Tempo Real:** Utilização de uma câmara USB e processamento de vídeo para transmitir imagens em tempo real para a interface web, com capacidade de capturar e armazenar fotos e vídeos numa galeria acessível.
3.  **Controlo por Comandos de Voz:** Implementação de um sistema de reconhecimento de voz que traduz comandos verbais ("frente", "esquerda", etc.) em ações do robô, demonstrando proficiência em processamento de linguagem natural (NLP) e integração de APIs.
4.  **Monitorização de Sistema em Tempo Real:** Recolha e apresentação contínua de métricas vitais da Raspberry Pi (temperatura da CPU, uso de RAM, *uptime* e dados de rede) diretamente na interface web, crucial para a manutenção e diagnóstico do sistema.
5.  **Integração de APIs Externas:** Utilização de APIs de meteorologia (OpenWeatherMap) e de rede para fornecer informações contextuais (clima e localização) ao utilizador.

## Tecnologias Utilizadas

Este projeto exigiu o domínio de um vasto leque de tecnologias, demonstrando versatilidade em todo o *stack* de desenvolvimento:

| Componente | Tecnologias Chave |
| :--- | :--- |
| **Hardware/Sistema** | Raspberry Pi (RPi), Motores DC, Controlador L298N, Câmara USB. |
| **Backend/Lógica** | **Python** (para controlo de hardware, processamento de vídeo e lógica de sistema), **Flask** (Framework Web), **SpeechRecognition** (para comandos de voz). |
| **Frontend/Interface** | **HTML5, CSS3, JavaScript** (para a interface web e controlo via teclado), **WebSockets** (para comunicação em tempo real). |
| **Base de Dados** | **MySQL** (para armazenamento de dados como imagens e logs). |
| **Servidor** | **Apache** (para hospedar a interface web). |

---

**Conclusão:** Este projeto é um excelente exemplo de como as competências em **programação web (full-stack)**, **bases de dados (SQL)** e **sistemas embarcados (Python/RPI)** podem ser combinadas para criar soluções inovadoras e funcionais. É um ativo de portfólio ideal para atrair clientes que procuram desenvolvimento de IoT, sistemas de monitorização ou soluções de controlo remoto.
