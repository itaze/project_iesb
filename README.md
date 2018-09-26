# Projeto de Seguranças IESB

Firewall de borda, transparente e tratando blocos de endereçamento baseados no IANA.

Firewall implementado no gateway

Planejamento

- Objetivo: Implementar firewall que trate o tráfego a nível de protocolo e aplicação.

- Justificativa: Uma vez que firewall de pacotes não entrega a segurança necessária, é relevante tratar a nível de aplicação. Onde o comportamento da aplicação baseado em assinaturas, promove filtro mais seguro.

-Etapas: Firewall de borda, firewall no gateway, firewall de aplicação.

- Conclusão: Tratamento de firewall com atualizações de regras dinâmicas, regras de boa performance(statless), controles a nível de protocolo de aplicação.
