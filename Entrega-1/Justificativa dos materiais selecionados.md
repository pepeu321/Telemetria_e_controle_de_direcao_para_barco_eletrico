1. ACS758 – Sensor de Corrente

O ACS758 é um sensor de corrente baseado em efeito Hall. Ele permite a medição de corrente sem contato elétrico direto, oferecendo segurança e precisão.
Justificativa:

Permite monitorar a corrente consumida pelo motor do leme ou pelo sistema elétrico do barco.

Fornece proteção indireta ao sistema, permitindo detectar sobrecargas ou falhas de corrente.

Integração fácil com microcontroladores via saída analógica proporcional à corrente medida.

2. AS5600 – Sensor de Ângulo Magnético

O AS5600 é um sensor de posição angular sem contato magnético, com resolução de até 12 bits.
Justificativa:

Permite medir com precisão o ângulo do leme sem desgaste mecânico, garantindo durabilidade.

Fornece feedback essencial para o controle do motor e manutenção da direção desejada.

Suporta comunicação via I²C, facilitando integração com microcontroladores como o ESP32.

3. BTN8982TA – Driver de Motor (Ponte H)

O BTN8982TA é um driver automotivo de ponte H com proteções integradas contra sobrecorrente, sobretensão, sobretemperatura e diagnóstico de falhas.
Justificativa:

Controla o motor do leme com segurança e eficiência.

Permite operação bidirecional do motor e controle preciso do PWM.

Reduz risco de danos ao motor e ao sistema de potência do barco, aumentando a confiabilidade.

4. ESP32-S3 – Microcontrolador

O ESP32-S3 é um microcontrolador avançado com conectividade Wi-Fi e Bluetooth, suporte a PWM, ADC, I²C, SPI e CAN (via transceptor externo).
Justificativa:

Centraliza o controle do leme, leitura de sensores e processamento de telemetria.

Permite comunicação remota via MQTT e integração com outros sistemas do barco.

Suporta interfaces múltiplas necessárias para ACS758, AS5600, LV25P, MCP2515 e GYNEO6MV2.

5. LV25P – Sensor de Tensão

O LV25P é um sensor de tensão isolado, projetado para monitoramento seguro de tensões DC ou AC.
Justificativa:

Permite medir a tensão de alimentação do motor ou do sistema elétrico com isolamento elétrico.

Protege o microcontrolador de picos de tensão, garantindo segurança do sistema.

Auxilia na coleta de dados de telemetria, como consumo de energia e eficiência.

6. MCP2515 – Controlador CAN

O MCP2515 é um controlador CAN SPI que permite a comunicação com redes CAN, padrão usado em automóveis e embarcações.
Justificativa:

Permite integrar o barco com sistemas que utilizam protocolo CAN, como sensores, baterias e módulos de potência.

Facilita escalabilidade futura do projeto, adicionando outros módulos inteligentes.

Funciona como interface entre o ESP32-S3 e a rede CAN.

7. GYNEO6MV2 – Módulo GPS + Acelerômetro/Giroscópio

O GYNEO6MV2 combina GPS com sensores inerciais, permitindo rastreamento de posição e orientação.
Justificativa:

Fornece geolocalização e velocidade do barco em tempo real.

Permite registro de rotas, navegação autônoma e telemetria avançada.

Integração fácil via UART com microcontroladores, essencial para sistemas inteligentes de direção.
