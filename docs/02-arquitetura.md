graph TD
    Sub[Nó de Subscrição / Telemetria] -->|Dados Brutos| Core[Núcleo LEVIATHAN]
    Core -->|Processamento de Baixa Latência| Controller[Nó de Controle / Atuação]
    Core -.->|Logs & Monitoramento| Storage[(Armazenamento Local)]
